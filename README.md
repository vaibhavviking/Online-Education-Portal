<h1>Online Education Portal</h1>

This project aims to solve some of the crucial problems faced in Online Education which stands to be the only solution in this time of COVID-19. Some of the problems faced generally are:
* Different class links for different classes and that too has to be searched from various sources like Mail, Whatsapp etc
* Study Material of all courses scattered everywhere ( Some may be in Google Drive or some may be in MyCloud or some may be in Mails )
* Professors unable to take legit attendance
* Being at home, it becomes difficult to keep everything in mind about classes (like Time-Table)

In total, this project tries to solve some of the problems of this kind to much extent by showing every information at a single place. Moreover, a user sees the information relevant only to him/her. 
* No need to find study materials of a particular course in a long list of mails. 
* No need to mess up with a large time table having all courses for students from all programs and years because this will be done by this project
* No need to find the class links in a long list of mails (especially when you are getting late for class)
* No more proxies or fake names in the class; Only one attendance per student in a class and professor can even see the details of attendance of students

This project can be used by Admin or Student or Professor. 
A student can
* see all his/her details
* see all the courses in which he/she is enrolled
* mark attendance for an ongoing class 
* access the link of ongoing class
* see the Time-Table only for the courses he/she is enrolled in
* access all the study materials of all the courses in which he/she is enrolled in a systematic manner

A professor can
* see all his/her details
* see all the courses which he/she teaches
* check attendance of students for today's class(es) of his/her course
* check attendance of students till today for his/her course
* access the link of class to be taken by him/her
* see the Time-Table only for the courses he/she teaches
* access all the study materials of all the courses which he/she teaches in a systematic manner
* add or remove study material for a course he/she teaches

An Admin can
* see and edit all his/her details
* see, add, remove and edit departments/branches involved in online education
* see, add, remove and edit courses taught in online education
* see, add, remove and edit students' details and the courses that they should take
* see, add, remove and edit professor's details and the courses that they teach
* assign time slots in a week to the courses
* add other admins

We hope that this project solves the general problems faced by Students and Professors atleast to some extent, if not fully. Please refer to 'Execution_Instructions.md' to download, use and edit this project from your local machine.

The website is hosted in Herokuapp and the link for the same is : https://mysterious-beyond-20244.herokuapp.com/

Downloading The Project
For Downloading, using and editing this project from your local machine, we recommend using Visual Studio Code and MySQL Workbench. You should also install Git to clone this project in your local machine. NodeJS is required to run the server of this project.
You can install
Visual Studio Code from : https://code.visualstudio.com/
MySQL and MySQL Workbench: https://www.mysql.com/downloads/
Git:https://git-scm.com/downloads
NodeJS: https://nodejs.org/en/
After installing all above softwares/tools

Open the folder in your local machine where you want to clone this project
Right Click there and select "Open with Code"
Visual Studio Code opens up. Open the terminal in VS Code.
In the terminal, write following commands and press Enter after each command
git init
git clone https://github.com/vaibhavviking/Online-Education-Portal.git ( After this step, all the project files will get stored in your selected location of local machine )
cd o (Then press Tab and then press Enter)
npm init ( You can be prompted to install other modules like md5. In that case type "npm i --save md5" and press Enter )
You also need a 'keys.js' file to get credentials of using the cloud database which is not uploaded in this repository for security reasons. You can mail at any one of the mail ids: cse190001065@iiti.ac.in/ee190002048@iiti.ac.in/cse190001048@iiti.ac.in/cse190001027@iiti.ac.in .
You should also use the same credentials to create MySQL instance and access the database (or) You can create your own cloud database and store the credentials in your 'keys.js' file
node server ( After pressing Enter, you can open 'localhost:5000' in your browser to access the website )
Repository Details
Database folder: All files related to Database ( You can find details inside the folder in Database_Documentation.md )
views folder: All Web pages in .ejs format ( All File names are self explainatory )
views/css folder:All style sheets of the web pages ( All File names are self explainatory )
views/images: All images used in this project
server.js: Node.JS file to run the server
(You may ignore rest other files)

This project is made by
* Komal Kumar (kkomalk)
* Priyanshu Uttam (uttam509)
* Purnadip Chakrabarti (ChakPC)
* Vaibhav Chandra (vaibhavviking)

and is made as a part of evaluation of the course "Database and Information Systems" in Indian Institute of Technology, Indore.
