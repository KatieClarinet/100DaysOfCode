# 100DaysOfCode  
Journal of my 100 days of code  
  
So far I've been tracking my '100 days of code' on twitter, but have decided to do so on here too so that I can delve into more detail!  
I'm already up to day 17 (my favourite number!) so will continue from there onwards...  

**Day 17**  

Today I returned to the hackathon from Day 9 at school of code.  
We used an API to retrieve trivia questions, and create a simple quiz.  
Today I added a container and experimented with CSS to style it.

[Media Trivia Game:](https://github.com/KatieClarinet/Branch-of-fetch-hackathon---Trivia-Game)

**Day 18**

Some of our tasks today included experimenting with CSS variables, and working out how to add a 'night mode' toggle button.  
    
I've made a quick repo here to test my new skills: https://github.com/KatieClarinet/CSSVariables_ToggleDarkMode

**Day 19**

I've had a real 'everything going wrong' kind of day today. I thought I'd worked out how to add some game scores to the Music Trivia game, but my code isn't working - so I shall return to this with a fresh perspective in a day or so.  
  
At SoC today we were introduced to 'Coolors' website, so I have used a premade palette to jazz up the Music Trivia game. A small accomplishment, but hopefully lots of small improvements will add up to big ones soon.  

Here's the link: https://github.com/KatieClarinet/Branch-of-fetch-hackathon---Trivia-Game

**Days 20 and 21**

Yesterday I spent the evening at brum.js meeting some of my fellow SoC bootcampers, so I didn't do any coding after classes but I had a great experience!  
  
Today was the last day of UX/UI week at SoC and we had to design a business landing page. My partner and I opted for a 60s+ dating app and spent the day planning the web content. We went through the  following stages:  
- User stories  
- User personas  
- Research questions  
- Low fidelity wireframe  
- High fidelity wireframe  
- Writing a code plan  
  
This evening I decided to code the page and here's where I've got to:  
  
https://github.com/KatieClarinet/CatchLandingPage  
  
I still need to center the text in the footer boxes and tweak a few things, but it's the best CSS work I've done so far, and acheived in just a few hours so that's progress!  
  
  **Day 22**  
  
*Weekend Soc Tasks*  
The task this weekend is to put our new UX/UI skills into practice and research, design and code a Portfolio page. I used Miro to start a basic plan, then created a survey using Google Forms which I've sent out to as many devs as I can. I'll check how many responces I have tomorrow then continue my planning based on survey responses.  

*Rock Paper Scissors Game*  
It's been really bugging me that I never fixed my RPS game so that it tracks the amount of 'wins/losses/draws'. I watched a JavaScript tutorial on YouTube on how to create the RPS game and followed along. The tutorial doesn't show how to track the score (which I realised once I got to the end of the tutorial!) but, I actually worked out how to do it anyway. So here it is (it's just html and JS, no CSS yet): [Rock Paper Scissors Game](https://github.com/KatieClarinet/RockPaperScissors)  

*Music Trivia Game*  
I went back to my Trivia Game to work on how to track the score and spent a long time playing around with various ways to increment the scores. Eventually I took a piece of paper and drew a map of where I want each function/loop/button to lead, and then drew out a map of what my code was actually doing. I realised that I had all three buttons calling the same function (oops!) and that my code was not in the right order. Happy to say this is now fixed and the game score works!
[Music Trivia Game](https://github.com/KatieClarinet/Branch-of-fetch-hackathon---Trivia-Game)

**Day 23**

I continued with the SoC weekend task. Using the data from my survey I created user stories and personas. I made an inspiration board and had a think about what I liked most: bold colours and minimalist designs! I then created low fi and high fi wireframes (the hi fi is a work in progress).  
  
  **Day 24**  
    
This morning I coded my website, copying my High Fideluty Wireframe [My Website](https://github.com/SchoolOfCode/w3_recap-task-KatieClarinet)  
It's pretty simple at the moment but I will add to it once I have some projects ready.  

  At SoC today we did the W3 tests for HTML, CSS and JavaScript and I scored 77%, 88% and 88% respectively. We then had an introduction to Node and made sure we had it installed. We wrote a few functions using node rather than the browser, which was a new experience!  
  I'm currently a bit confused on how to export/import on node so will return to work on this tomorrow.  

**Day 25**

Today we used node to access the Express package and learned how to write a (very simple!) server. I don't have much to show for today's work, but I know have a much deeper understanding of how APIs work. Hopefully will build something in the next few days that I can link here.  

**Day 26**  

We learned about using Express today, including how to make seperate routers:
- a router that listens for a specific id
- a router that searches by text (we used the includes method for this).  

Notable thing(s) I learned:
- when using 'params' remember these are always a string. So, if you need your data to be treated as a number you will need to use JavaScript 'number' to wrap and convert to a number.  

This evening I read up on RESTful APIs and created a revision board on miro. 
![Revision Board](Revision_Board.png)  

**Day 27**  

This morning we continued our learning of Express and used the GET and POST methods to view/add to our data (an array of books). We used an API called postman rather than our browser.  

In the afternoon we split into groups and researched various aspects of Express. In my group we looked at 'Validating input with Express'. A summary:
- Express-validator provides access to a huge selection of pre-made functions which allow you to (from server side) validate and sanitise the requests of the user/client
- it checks that the input data is in the expected format and type
- it removes unsafe characters from user input
- this provides defense against attacks  

**Day 28**

We had a hackathon today where we created a RESTful API using all CRUD routes. My pair were successful with this but I feel like my knowledge is still pretty shaky so I'm hoping to research these methods/routes a lot more! Our weekend tasks are along the same vein but with some bonus tasks to link up to the front end - so hopefully I can solidify my knowledge with these... stay tuned.  

**Day 29**  

Having a rest day today so I haven't coded anything. In preparation for Kyle Simpson doing a talk at SoC on Monday I have watched his 'Keep Betting on JavaScript' talk from 2019 (which you can find on YouTube). The main takeaway I have is that, although, as a developer, we will work in small chunks, it's important to always keep the bigger picture in mind and think of the future implications of what we are building. There are a bunch of things he mentioned that I need to research (including, but not limited, to: eval, JQuery and strictmode). I really liked his emphasis on 'embracing what people can do' (emphasis on 'can') and his focus on making the web accessible, particularly by making pages work offline. I think I need to look into caching to understand more about how this is achieveable.  

I've been back to my revision board and added a list of things I need to recap from this week: (error handling in express, rate limiting, Using HTTP status codes, Validating input with express, Evolution of HTTP, Cybersecurity, Code formatting: Prettier and ES Lint). These are all topics we split into groups to research on Thursday (my group researched Validating Input with Express) but I think I need to take the time to do some personal research on each as I can tell they are all important! Today I looked into CORS and added a page to my revision board. ![CORS](CORS.png) 

**Day 30**  

Finished off the weekend recap test, which was similar to the Friday hackathon. Created a REST API with CRUD routes (create, read, update and delete) using a nested array of users as data source. Started bonus task, which was to start 'seperation of concerns' by using functions which then get imported into router. Got quite confused with middleware. Hoping to learn more this week!  

**Day 31**  

Returned to the bonus tasks from the weekend recap tasks and successfully implemented all of the model functions! We also had Kyle Simpson's talk today, which centered around 'Imposter Syndrome'.
I learned:
- 'If you wait until you're an expert, you've waited too long'. Meaning, it's better to show your work to others whilst you're on the journey of learning/creating. Their feedback will be handy!
- 'Sometimes doing is the best way to learn'
- 'Don't let lack of experience hold you back'.  

**Day 32**  

After a brief introduction to SQL yesterday, today we started working through the Interactive Tutorial on SQL Bolt and also some (much harder!) questions this afternoon. It's been such a fastpaced day that I need to take time to go back to the questions from this morning and take them at my own pace. I got as far as understanding how to JOIN more than one table together and access data, but everything else is still a mystery to me...  

**Day 33**  

Another jam-packed day of learning!  

Today we covered:
- creating up a Heroku account - we will now use this when setting up databases
- connecting our server to the database
- using pg package 
- using our new PostgreSQL skills to CREATE a new table and UPDATE it using data from our libs/data file 
- reconfigure our functions so that they interact with the database 
- enviroment variables (for telling express which port to listen to and to store our database connection details)
- about Pools and how to use them (still a bit shaky on this)  
  
**Day 34**  

We went into a lot more detail on how to connect our server to the database (using different methods to consolidate this).

**Day 35**  

For the hackathon today we build a REST API using node.js, express and postgreSQL. 
- created a data file with a nested array of our data and used scripts in our package.json to run: one for creating the table in heroku, one for populating the  table in heroku.
- had functioning CRUD routes to manange requests and serve responses.
- used environment variables to store our database credentials
This was our first time putting everything we've learned this week into action and I was surprised at how well we did!  

**Day 36**  

Started the weekend recap work and so far I have:
- set up a database on Heroku
- used SQL querys to create and populate a table (from an array of data)
- set up GET requests to search 'all', 'by id' and 'by query'
- starting linking my routes up to the database rather than the array
- I will continue with this tomorrow  

**Day 37**  

Today I hooked my server up to the data in my postgreSQL database, rather than the array.  

**Day 38**  

Today we started learning about Software Testing. We were introduced to Jest and how to write simple tests for javascript functions including:
- a function that modifies a number
- a function that checks the length of an array
- a function that apends an item to the end of an array (using spread operator)
- a function that adds a key value pair to an object
- a function that throws an error if the number passed to it is even  

**Day 39**  

Today we were introduced to Test Driven Development (TDD) and the three phases:
- RED STAGE Create precise tests - the first one should fail
- GREEN STAGE Correct the code - make the minimal changes needed to correct the code so that it will pass (this )
- Refactor the code - once test runs successfully, check to see if you can optimize performance (but don't change the external behaviour of program)  

We started work on a calculateScrabbleScore function and wrote tests for:
- all alphabet letters entered singularly.  
This was as far as I got in the workshop so I will return to complete the rest of the sections:
- multiple letters
- throwing an error if other characters are entered  

In the afternoon we had a talk and demo session from Cypress (JavaScript tool for end to end testing) 

**Day 40**  

Morning  
We installed Cypress and read through the docs  

Afternoon  
We learned about API endpoint testing using Jest and Supertest.  
We practiced using Jest matchers to write tests checking whether a variable contains an object with a specific structure (each test had a more complex structure)  

**Day 41**  

We have no classes for 4 days now as it's the jubilee weekend.  

Today I returned to the Jest workshop from Day 38 and added in a lot more tests I hadn't thought of - mostly if statements to check 'typeof' data entered.  
  
  **Day 42**

**JEST**
I went back to the TDD workshop from Day 39 and refactored my code for the calculateScrabbleScore function. Initially I had a written that expects a single letter as input and checks the score like this: 
if (word.toLowerCase() === "a") {  
        return 1;  
    }   
    else if (word.toLowerCase() === "d") {  
        return 2;  
    }  
    else if (word.toLowerCase() === "b" || "c" ) {  
        return 3;  
    }     
     However, that was going to be very lengthy so I used regex to refactor it to this:  
     if (arr[i].match(/[aeioulnrst]/ig)) {  
        count += 1;  
    } else if (arr[i].match(/[dg]/ig)) {  
        count += 2;  
    } else if (arr[i].match(/[bcmp]/ig)) {  
        count += 3;    
  
Next I wrote a test for if the function received more than one letter, which failed. So I refactored my code to work with multiple letters or 'strings'. The step after this was the make the function throw an error if a non-alphabet letter was the input. My final code was:
  
export function calculateScrabbleScore(word) {  
    var letters = /^[A-Za-z]+$/;  
if (word.match(letters)) {  
        let arr = Array.from(word);  
       let count = 0;    
    for (let i = 0; i < word.length; i++) {  
    if (arr[i].match(/[aeioulnrst]/ig)) {  
        count += 1;  
    } else if (arr[i].match(/[dg]/ig)) {  
        count += 2;  
    } else if (arr[i].match(/[bcmp]/ig)) {  
        count += 3;  
    } else if (arr[i].match(/[fhvwy]/ig)) {  
        count += 4;  
    } else if (arr[i].match(/[k]/ig)) {  
        count += 5;  
    } else if (arr[i].match(/[jx]/ig)) {  
        count += 8;  
    } else if (arr[i].match(/[qz]/ig)) {  
        count += 10;  
    }  
    }  
return count;  
} else {  
    throw new Error(`Error, ${word} is not alphabet!`);  
}  
}  
calculateScrabbleScore("pet");  
  
and my tests:  
  
describe('calculateScrabbleScore', () => {  
    test.each`  
      word     | expectedResult  
      ${'a'}   | ${1}  
      ${'e'}   | ${1}  
      ${'i'}   | ${1}  
      ${'o'}   | ${1}  
      ${'u'}   | ${1}  
      ${'l'}   | ${1}  
      ${'n'}   | ${1}  
      ${'r'}   | ${1}  
      ${'s'}   | ${1}   
      ${'t'}   | ${1}  
      ${'d'}   | ${2}  
      ${'g'}   | ${2}  
      ${'b'}   | ${3}  
      ${'c'}   | ${3}  
      ${'m'}   | ${3}  
      ${'p'}   | ${3}  
      ${'f'}   | ${4}  
      ${'h'}   | ${4}  
      ${'v'}   | ${4}  
      ${'w'}   | ${4}  
      ${'y'}   | ${4}  
      ${'k'}   | ${5}  
      ${'j'}   | ${8}  
      ${'x'}   | ${8}  
      ${'q'}   | ${10}  
      ${'z'}   | ${10}  
    `('converts $word to $expectedResult', ({ word, expectedResult }) => {  
      expect(calculateScrabbleScore(word)).toBe(expectedResult)  
    })  
  })  
  
  test("Given the string apple calculateScrabbleScore function returns the score",  
function(){  
    const word = "pet";  
    const expected = 5;  
    const actual = calculateScrabbleScore(word);  
    expect(actual).toBe(expected)  
});  
  
test('When given a character not in the alphabet , calculateScrabbleScore returns error', () => {  
    expect(() => {  
      throwErrorIfEven('*&7');  
    }).toThrow();  
  });  

  **CYPRESS**

  Next I went back to the Cypress workshop from Day 40 and wrote some simple tests for an API, using:
  - cy.visit to set the path to the website
  - cy.get to select the CSS selector I wanted .should to check the contents  

**Day 43**  

Went back to Supertest workshop from day 40 and wrote some tests for GET requests.  

Then returned to the Rock, Paper, Scissors project from week 1 - made the game more complex by adding Lizard and Spock. Then made it pretty with CSS.

[Rock Paper Scissors Game](https://github.com/KatieClarinet/RockPaperScissors)  

**Day 44**  

Intro to React. We learned about:
- components
- immutable code
- the virtual DOM
  
**Day 45**  

Intro to Babel (a transpiler (translater) which turns our JSX back to regular JS).  
We learned how to create a button component and a list component.  
Spent some time this evening going through this Tutorial: Intro to React https://reactjs.org/tutorial/tutorial.html  

**Day 46**  

We continued learning how to use React today. I've been reading up on State and Props, to try and understand them better.
State:  
- an updatable structure containing info/data about a dynamic component
- when the data inside component(s) changes, State re-renders the app to reflect the changes
- there are 4 main types of State (local, global, server, URL)  

Props:
- arguments that you pass to React components
- can be used as a method to pass data from one component to another
- passed to the component in the same manner as arguments are passed in a function
- use the same syntax as HTML attributes  

**Day 47**  

We had a mindset session and talks from industry professionals this morning, then spent the afternoon learning about updating immutable objects. The JavaScript methods we used were:
- the split operator
- slice()

I just completed a workshop where I wrote functions that immutably:
- add an item to an array at the beginning or at the end
- insert an item at a specific position/index within an array
- replace an item at a specific position/index within an array
- remove an item at a specific position/index within an array
- update a specific value in an object

**Day 48**  

The hackathon task today was to create a To Do List app using React. In short: my pair didn't have much luck with this. We got so stuck on how to start that we ended up using a tutorial for guidance. In hindsight, this was a bad idea as we ended up following it and just copying the code without understanding it. I want to take the time to really study React and try this again sometime.  

**Day 49**

Spent a few hours today reading the React docs and writing up notes.  

**Day 50**  

I continued studying the React docs today and made a start on weekend recap tasks:
- I created a blog post with the following structure (title, author, datePosted, content, imageUrl)
- I added a hard coded comment section

I then went back to the hackathon from Friday (To Do List) and read up some more on how to approach this. I created an input box and a button but didn't get them linked up yet!  
I need to work out how to get the user input to display on screen

**Day 51**  

First day of our second week learning React. We covered some more complex topics this afternoon:
- useEffect (which I understand is a last resort that should only be used if event handlers aren't appropriate)
- cleanup and when to use it  

This evening I've been studying props in more detail. I've had some issues understanding the relationship between child and parent components and how props are passed so have been studying examples.  

**Day 52**  

Today we learned about useReducer, a hook that can be used in react - it lets you move the state update logic from event handlers into a single function outside of your component.







