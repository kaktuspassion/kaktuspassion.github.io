---
title: "WordWizard"
description: "2023 Fall, Web Application and Language Technology"
pubDate: "January 2024"
heroImage: "/project_wordwizard/main.webp"
badge: "Project documentation"
---

This is the final project of the course "Web Application and Language Technology".

## Overview

**Background.** Digital techniques become more and more popular in teaching environment, and previous traditional paper-based crossword and online crossword games are mainly considered as a game for time leisure. Through our project we want to provide language learners with more personalized crossword to use this game as a learning tool and maybe used in class as an enjoyable game as well as a way of testing learning results.  


**Aim.** The project aims at designing a web-based crossword puzzle that adapts to the user's language category and proficiency, making learning a dynamic and enjoyable experience. Through realizing this project, we want to familiar with an understanding of the web production process and the ability to liaise and work as part of a team.

**Target users.** The aiming users are Foreign Language Learners (L2) who seek to improve their language proficiency in languages including English, Spanish, French, Swedish and Dutch on different CEFR levels: A1, A2, B1, B2, C1. As mentioned above, due to the provided multilingual and CEFR level function, this web can be used not only as a word game for pleasure, but also as a teaching assistant tool for class, even for vocabulary testing and memorizing.  

**Techniques.** In summary, we utilized a combination of HTML, CSS, and JavaScript to craft a user interface, developed with Python and built a database to store users’ information for SQL-based analysis. Through the project we hope to leverage technology to transform traditional linguistics research into an engaging, interactive experience and implement theoretical knowledge from academic coursework into a real-world, functional project. 

## Products research
### Pre-project brainstorming
First of all, together with the course requirements and our personal wishes and majors, we decided to make a language-related game web. On this basis, we needed to determine what language games were available and which ones were within our ability to develope in an innovative and meaningful way. 

Firstly we researched the types of language games:
* Scrabble games (where the player has to spell out words using given letters and place them on the game board to get the highest possible score)
* Crossword puzzles 
* Wordle 
* Word search [https://thewordsearch.com/]
* Pictionary 
* Etc. thewalrus.ca [https://thewalrus.ca/games/]

### Crossword investigation
We chose the more popular crossword puzzles whose algorithms are also relatively well implemented.
![My Local Image](/project_wordwizard/crossword_newspaper.png)
<p align="center" style="font-size: 16px;"><em>Figure 1: Crossword on newspapers</em></p>

### Types
There are 2 main types of crossword puzzles available online: 
* crossword puzzles on news media websites (e.g., Times, Washington Post, etc.)
* online crossword puzzles with sub-themes (e.g., food, animals, etc.)

### Page and function design
1. **Main page**
* Components: navigation bar, main body, footer.
* Navigation bar: logo, name, contact information, back to the main page and other functions.
* Main section: slogan, login, register and start the game in guest mode, with a rotating Rubik's cube on the right side for decoration.
* Footer: Project information and GitLab deployment links.
* Stylistic details: Easy-to-read fonts and sizes; consistent smooth and micro-interactive design such as rounded buttons, hover effects; gradient backgrounds.
2. **Registration and Login Interface**
3. **Game Page**
* Basic Functions: Show All Answers Button, Hint Button, Start Timer Button, Submit Answer Button.
* New Functions: Language Selection Box, Language Level Selection Box, Generate New Crossword Button, Calculate Accuracy Button.
* Accessibility: options to show answers (grid, word, all words) and check answers (grid, word, all words); print function; preferences (e.g. timer, auto-answer matching, highlight relevant clues, etc.).
4. **Personal Centre and Preferences**
* Displays user's game progress and correctness rate, providing a basis for personalised learning.
### Data sources
There are 3 types of data sources for constructing crossword puzzles: 
* the news media's own data
* sub-topic data provided by the websites
* data entered by the users themselves

For our project, the innovation is to produce a multilingual crossword puzzle that supports language and language level selection in response to the increased demand for multilingual learning.

### Target users
We are in an globalized world and language is becoming more and more important as a medium of communication and information flow in all walks of life. Multilingual learning is also becoming more and more common, for example, Duolinguo offers a similar curriculum but for a variety of different languages and levels, and I know for myself that multilingual learning is now very popular among children and parents at home and abroad. As the number of multilingual learners increases globally, so does the user base for language games. This is especially true of crossword game, which was printed in newspapers more than 100 years ago. Our initial intention was to make a fun and innovative crossword game, then after researching, we realized that there are no crossword games on the market specifically for multilingualism, and for different language levels.

Target Users:
- Students/Multilingual students: who want to practize and consolidate their language skills through fun games.
- Teachers: who want to use WordWizard as a teaching aid in the classroom.
- Parents: who want to help their children improve their multilingual skills

### Functions Highlights
- Language and Difficulty Level Selection: Users can select the appropriate difficulty level according to their language level.
- Interactive crossword puzzles: Includes hints, timer, fill-in check, etc.
- Personalised adjustment of the difficulty level of the word bank: improves relevance and learning effect.
- Game progress statistics: Record the correct rate of the user and other data, to provide a basis for personalized learning.



## Schedule

Our goal is to design a crossword game that can be customized according to the user's choice of language and level. As shown in Figure 1, I’m mainly responsible for realizing the crossword generator, modification of HTML and design of CSS of the homepage and crossword game page.

![My Local Image](/project_wordwizard/implementation.png)
<p align="center" style="font-size: 16px;"><em>Figure 2: Implementation of the project</em></p>

At the beginning of the project, I created a plan and updated it as the project progressed. As shown in the workflow figure above, three of us were mainly responsible for the language data, the crossword algorithm, and the user data respectively. Teamwork is a crucial part for the success of the whole project. Corresponding to the course schedule, October-November was the main learning time, where we conceptualized the project and submitted the project description, and December was the main discussion and implementation phase, where we had a detailed deliberation and division of tasks.

**Week 1 - Week 2** Group discussion, topic identification and proposal submission

**Week 3 - Week 5** Page and function design, tasks assignment and data pre-processing

**Week 6 - Week 8** Crossword algorithm development, database setup

**Week9 - Week 10** Group presentation and individual documentation submission


## Results
![My Local Image](/project_wordwizard/summary.png)
<p align="center" style="font-size: 16px;"><em>Figure 3: Summary workflow</em></p>

The overall workflow depicted in Figure 15 for generating a crossword puzzle begins with data preprocessing and ends with the display of the puzzle in an HTML table. 

The project successfully developed a multilingual crossword puzzle game, initially designed as a bilingual English-French application and later expanded to encompass five European languages. This expansion demonstrates the project's scalability and its commitment to catering to a diverse user base. The puzzles are aligned with the Common European Framework of Reference for Languages (CEFR), ensuring they serve as effective tools for language learning across different proficiency levels.

In terms of functionality, the application features an engaging user interface that promotes interactive language learning. Core features like clues in multiple languages, a timer, and accuracy tracking add educational and competitive elements to the game. While the application is fully functional as designed, there is room for enhancements such as real-time tracking and adaptive word frequency adjustments to further personalize the learning experience.

In general, the crossword puzzle generator successfully integrates language learning with technology. It achieved through a well-executed combination of front-end, back-end, and database. The project has laid a foundation for future improvements, with potential enhancements that could elevate its educational value and user engagement.


## Technical details
### Data pre-processing

![My Local Image](/project_wordwizard/data.png)
<p align="center" style="font-size: 16px;"><em>Figure 4: Data for crossword generator</em></p>

Here are the pipeline of data pre-processing, which are all available on Github.

### Web design
#### Homepage
Our web application comprises 4 webpages: the homepage, sign-in, sign-up, and the crossword game page. 
This is a relatively simple and typical main page of a web application that contains navigation bar, main content and footer. The two images below show the preview and structure of the page, respectively.

![My Local Image](/project_wordwizard/homepage_design.png)
<p align="center" style="font-size: 16px;"><em>Figure 5: The homepage design</em></p>

As shown in Figure 4, the navigation bar at the top includes a unique cube logo, a title, and a contact link, creating an intuitive and accessible user interface. The main content area is thoughtfully designed with a left panel containing an engaging slogan, a brief introduction, and action buttons for login, registration, and direct access to the crossword game.

Additionally, the integration of a dynamic 3D cube in the right side demonstrates our commitment to creating an interactive and visually appealing web experience. This cube, rendered using _Three.js_, adds a unique and modern touch to our homepage. The animation is written with the assistant of ChatGPT. The footer provides additional information about the application, emphasizing its educational purpose and origin as a project.

#### Crossword page

![My Local Image](/project_wordwizard/crossword_design.png)
<p align="center" style="font-size: 16px;"><em>Figure 6: The crossword design</em></p>

As in the homepage, the top of the page contains a header section with a distinctive cube logo and the title. There is also a convenient homepage button that allows users to navigate back to the main page easily.

Below the header is the game selection section, which allows users to customize their gameplay experience. This section includes dropdown menus for selecting the puzzle language and the CEFR level, which tailors the difficulty to the user's language proficiency, and many buttons to provide an interactive and supportive environment for learning.

The main feature of this page is the crossword grid where the puzzle will appear. This grid is dynamically generated. Alongside the grid, there are control buttons for starting the game and submitting answers, as well as a timer and an accuracy indicator that provide feedback on the user's performance.

Finally, the clues for the crossword are divided into "Across" and "Down" sections, enhancing the user's ability to solve the puzzle systematically. These clues are also populated by JavaScript.


### Crossword generator algorithm

Using Chatbot to generate a complete crossword code is difficult due to the complexity of the crossword algorithm, especially as it covers a number of special cases that require special attention. As a result, I browsed the web and forums. The crossword code for the web interface is too complex, so I was hoping to find a simple and understandable program that could be implemented into an effective crossword game. And my algrithm is based pn a code snippet from GitHub.
##### **General workflow of crossword**

![My Local Image](/project_wordwizard/workflow_of_crossword.png)
<p align="center" style="font-size: 16px;"><em>Figure 7: General workflow of crossword</em></p>

Figure 9 shows all the process involving Crossword algorithm and its position and role in the whole webapp. The flowchart and code provided illustrate a web application whose primary function is to generate crossword puzzles. Here's a detailed description of the entire process:

**User Input**. Users select a _language_ and a _CEFR level_ on the web application's frontend interface. This selection determines the language and difficulty level of the crossword puzzle.

**Sending Request.** Upon submitting choices, the frontend JavaScript makes an AJAX call to the **Flask backend.** The request is sent to the _/generate_crossword_ endpoint, along with the language and level parameters chosen by the user.

**Backend Processing.** The Flask application receives the request, extracting the language and level parameters. Based on the selected language, an appropriate dataset will be chosen from predefined language data.

**Generating the Crossword.** The backend uses this set of words and clues to call the _generate_crossword()_ function, which creates the crossword puzzle. The generated crossword data is printed to the console and returned to the frontend in JSON format.

**Frontend Display.** The frontend function _generatePuzzle()_ retrieves the crossword data from the backend. Once the data is successfully fetched, it invokes the _displayCrossword()_ function to display the crossword puzzle on the user interface.

Below are codes associated with crossword generator:
a. In _app.py:_
```python
@app.route('/generate_crossword', methods=['GET'])
def generate_crossword_route():
    ……
return jsonify({"puzzle": puzzle})
```
b. in _crossword.js_:
```javascript
// obtain generated puzzle from back-end
    function generatePuzzle() {
        # language and cefr level
        // AJAX call to the Flask backend to generate a new crossword puzzle
        fetch(`/generate_crossword?language=${language}&level=${level}`)
            .then(response => response.json())
            .then(data => {
                crosswordData = data; // Store the returned data
                displayCrossword(data.puzzle); // Call a function to display the crossword
            })
            .catch(error => console.error('Error:', error));
    }
```

Here is the simplified pipeline of the crossword generator algorithm. For more details, I write another blog on that topic to give a detailed illustration. 

## Challenges and reflections
### ## Challenges 
Initially the multilingual dataset is an issue because of the lack of clues, but then we think about using a dictionary API or use the Wordnet to get clues. For crossword there is no alternative, but thankfully we found one example, although not that well-structured, but provided essential insights for algorithm design. 

### Collaboration
The data side and the crossword algorithm side (me and Xiaojing Zhang) need to communicate. I told Xiaojing what information and structure should be included in the data I needed, and she processed the clean data and formed the final data I needed.
When designing the crossword function, it is also important to take into account not only the generated crossword (the grid), but also all the information needed for other function design, for example clues, lists of data used to calculate accuracy, and word bank functions used to provide hints, etc. These data and function will ultimately be used when designing the function button, so my teammates and I discussed in advance what functions we were going to provide and what data we would need so I can define functions for these calculations and return them in the output. 
Besides, daily chats and online meetings were indispensable so that we can adjust the schedule timely. 

### Improvements
These are possible aspects of HTML and CSS that can be improved:
•	The design of the page can always be improved, it can be enriched and more decorative elements can be added to make the overall segmentation consistent and aesthetically pleasing.
•	Automatically adapt pages for mobile phones and tablets.
•	Increase the accessibility of the webpage, and provide some assistance to users with disabilities. For example, how to make crossword puzzles accessible to blind people is also a direction to think about.

And these are possible improvements for crossword game:
•	Automatically update language data from CEFR official online dataset and generate crossword with real-time updated data.
•	Personalize the crossword to the user's learning objective and previous game results. e.g., learners with a learning objective of travelling will be presented with more daily words, and words that have already been answered correctly will be recorded and appear less frequently.
•	Compared to, for example, the Guardian's online crossword, this crossword is significantly simpler because of the different algorithms used in the crossword. The Guardian uses a more complex algorithm that allows for a higher number of words to be filled in, whereas our algorithm is to some extent randomized. So, there is a lot of room for improvement in the algorithm itself.
•	There are also many additional features that can be optimized. For example, the function of checking answers and the function of hints can be accurate to each cell.
There are many other aspects that can be improved, and as this project continues, the issues and improvement directions will become more and more extensive. Here is just a partial list of possible areas of improvement, but the project will generally evolve in a more personalized and playful direction.

## Reference

[1] CEFRLex: Common European Framework of Reference for Languages (CEFR) scale. <cental.uclouvain.be/cefrlex/ >  
[2] WordNet: A Lexical Database for English. <wordnet.princeton.edu/ >  
[3] OMW: Open Multilingual Wordnet. <mwn.org>
[4] https://github.com/jeremy886/crossword_helmig