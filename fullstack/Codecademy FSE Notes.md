## Codecademy
## Fullstack Engineer

# Welcome to the Full-Stack Engineer Path

:: Learning Objectives
After this Path, you will be able to:

- Set up your own dev environment and version control your work with Git/GitHub
- Write client-side and server-side JavaScript code
- Create static, responsive websites with HTML/CSS
- Use the popular React front-end framework, along with Redux
- Build Node/Express back-ends
- Design and build PostgreSQL databases
- Connect a front-end to a back-end for a full-stack PERN application
- Implement best security practices to prevent attacks
- Pass a JavaScript whiteboard interview

:: Syllabus Pages
The Unit Syllabus is your go-to guide to your current Unit. Each Unit is a major topic that we teach using smaller chunks of content, and each Unit Syllabus contains expandable/collapsible lists of all of those lessons, projects, and other content. 

:: Projects
You will demonstrate your knowledge in several Portfolio Projects that exist throughout the Path. Portfolio Projects are projects that you build on your own computer, following a set of requirements. Each one will be unique to your personal vision and set of interests. You can complete the Portfolio Projects either in parallel with or after taking the prerequisite content—it’s up to you!

Certification Exams
We’ve added exams to help you assess your proficiency as you build toward job-ready skills. Here’s how they work:

- You’ll find exams on your Full-Stack career path syllabus page, at the end of each section.
- Each exam assesses your knowledge of the concepts and technologies learned in that section. Exams help verify your proficiency — so you can feel confident in your abilities as you build toward a new career.
- Each exam has 2 parts. The first is multiple choice and fill in the blank, and the second is coding questions, when applicable to the material. Otherwise, you will encounter additional multiple choice and fill in the blank questions.
- Score at least 70% on both parts of the exam to pass.
- If you don’t pass, no worries! You can retake exams once every 24 hours.
- Taking or passing exams is not required to complete the path and exams do not factor into your progress percentage. However, exams must be completed and passed to earn your Codecademy Professional Certification. That means, you can now skip past content you are already familiar with and still earn a Codecademy Professional Certification.

:: Updates
Since we strive to bring you the best and most up-to-date content, we will be periodically updating the materials in this path. For smaller updates we’ll be communicating changes via the Web Development Change Log, which features updates and bug fixes across all Web Development content. For larger changes, we’ll write a blog post detailing the extent of those changes and how they impact the syllabi. If you are enrolled in this path, we’ll send a notification each time there’s been an update, so you know exactly what has changed.







:: Terminology
Inner Loop: Focus zone where are productive, no distractions. Coding zone.


Unit 1:

HREF tags are external resources
SRC tags are resources, put at end of HTML file to increase rendering speed.

:: js function to set random color on button click
:: unit 1, page 11/13
<html>
  <head>
    <link rel="stylesheet" type="text/css" href="style.css">

  </head>

  <body>
      <button onclick="changeColor()">Repaint!</button>
  </body>
  
      <script>
        function getRandomColor(){
          let letters = '0123456789ABCDEF';
          let color = '#';
          for (let i = 0; i < 6; i++) {
            color += letters[Math.floor(Math.random() * 16)];
          }
          return color;
        }
        function changeColor(){
          let newColor = getRandomColor();
          document.body.style.backgroundColor = newColor;
        }
    </script>
  
</html>


:: Programming
1. Closures
2. Partials
3. Hoisting
4. Functional
5. Determined

10x talent, as the label implies, is able to deliver ten times more than is expected, but what makes them so valuable is that they are multidimensional. They are smart, good communicators, and have interests beyond their core specialty. Their curiosity and love of learning drives them to do more and do it better.

What’s your programming personality?
Question Asker

A Lot Like: Dot Connector
Also Like: User Advocate
A Little Like: Problem Solver

Question Asker
Curiosity, communication, and attention to detail are your underlying strengths. You like doing the research and questioning things in order to be the prepared with an answer. You take action by using your insights to formulate a plan, and working with others to see it through. Things you’re into: investigating mysteries, learning constantly, taking a step back, and that “a ha!” moment when you see the big picture.

Career Opportunities
Potential career fields for question askers include User Research, Equity Analysis, Investigative Journalism, Law, and Data Science.

Data Scientists @ Codecademy
Our data science team will analyze how you respond to this survey, keep track of which course you sign up for, and use data to determine how effective that course is at teaching you new skills.

You may excel at Data Science
Data scientists collaborate to unveil patterns in data. Day to day, they organize datasets, dive deep into numbers to track down insights, choose which metrics are best suited to evaluate decisions, and communicate with team members. Data Scientists earn an average salary of $95,996 according to Payscale.

:: Code Review
Bus Factor: If one team member got hit by bus, how would project continue?
Bikeshedding: Focusing on trivial, mundane, low impact issues.

Bikeshedding, also known as Parkinson’s Law of Triviality, is a term coined by C. Northcote Parkinson to describe the tendency for organizations or groups to spend disproportionate amounts of time and energy on trivial or relatively unimportant matters while neglecting more significant issues. The term originates from a fictional scenario where a committee tasked with approving plans for a nuclear power plant spends a significant amount of time discussing the design and color of a simple bikeshed on the plant premises while barely touching upon the complex technical aspects of the nuclear facility. Bikeshedding highlights the human tendency to focus on easily understandable or relatable topics, even if they have minimal impact or relevance to the overall objective. This phenomenon can hinder productivity, waste resources, and lead to misallocation of attention and effort. Understanding and mitigating bikeshedding can improve decision-making and project management in organizations.


