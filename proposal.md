# X-Team 92 Exam Planner Proposal

See https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#code for tips on using *Markdown* tags to format __.md__ files

## Goal

Work as a team to create a project proposal for your X-team to complete together.
The project does not have to be extremely difficult,
but there must be work to do for each member of your team.
You may reference figures using "See figure 1".  
Be sure to submit corresponding image files, i.e. figure1.png (or figure1.jpg) for each figure.

## Grading: To earn full credit, your team's proposal must include:

* (md) documentation: [this file] describing purpose and use of your program

* Description of a program that has:

  ** a main Java program class in a file named Main.java
  
  ** a custom data structure designed and built by your team
  
  ** comprehensive testing of individual units
  
 Caution: You are not being asked to implement this program, at least not yet. 
 We just want your group to make a proposal or pitch for your program.
 
 Tip: Your custom data structure can be composed of or extensions of data structures that you have learned and used in previous programming assignments.  We're looking for decisions about how to build a high-level data structure that will likely have lower-level components.

## Problem Description

College Students have hectic lives with lots of classes and extracirriculars. This leads to students cramming for exams that 
they should have been preparing for in advance.  Our program will keep students accountable by reminding students to study for exams earlier and for a managable amount of time. The program will base the study schedule on the date of exam, student availability, and their level of confidence in the material being tested on. 

## Questions to answer for Exercise #2

1. Name: Give your project proposal a name (and edit the top line of this file)

Exam Planner

2. Output: Describe the output your program will produce.  Include and example format of the output produced.

The output will be how many days in advance you should start studying for the exam based on the comfort level inputted and it will provide the start date of when you should begin preparing. It will also output how many hours each day you should study for that exam.

EX: "For your CS400 exam you should start studying 5 days prior to the exam on October 20th for 3 hours each day."

3. Input: Describe the data that is needed to solve your problem. Include an example format of the input data.
This programs requires several inputs
   1. The respective class in string formal
   1. The comfortability with this particular class as an Integer value
   1. The date of the test of the respective class as an Integer value
   1. The amount of study time you have in a day on average as an Integer value
    
   *Example*
   - CS400
   - 7
   - 121518
   - 5

4. User Interface: Describe a user interface for your program.  Use text menus or a simple graphic user interface. 
The interface would be a simple GUI. It would have a written reminder to study for a specific class that was already possibbly entered.
There is a "Create New Test Plan" button under these reminders and a "Calendar" button above the reminders. The "Calendar 
button would take you to a simple list of dates with the word "Test" on days that were previously entered. The "Create New Test Plan" button would take you to a list of questions for the inputs listed above. There would be an "Implment" button to add the New Test Plan to the calndar.

5. Types List: Break your solution idea down into units that you think can be implemented with a single class.

* calculate how many days needed to study (based on comfort level)
* calculate how many hours to study each of those days (based on comfort level and how much time the user has available to study each day)
* calculate the start date based off of how many days of studying and the exam date
* print out the output for the user

Name each interface or class and briefly describe its function or purpose.


## Edit and Submit this file and any figures referenced by this document.

