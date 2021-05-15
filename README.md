# Questionnaire
The ‘QUESTIONNAIRE’ project was developed to overcome the time-consuming problem of the manual system. Apart from that in the current system, checking the answer sheets after taking a test, waste the examiner's time, so this application will check the correct answer and save the examiner's time and carry the examination effectively. The users which are using this system don’t need high computing knowledge and also the system will inform them while entering invalid data. The aim of this project is to computerized the existing manual system and help the examiners to save their valuable time and important data. Apart from this, data which are exist in this system, will exist for long period of time and will be easy accessible. This project helps the examiners to manage their services in a good way and provide a better service to their users.

<h2 align="center">Questionnaire Demo</h2>

![Questionnaire](https://user-images.githubusercontent.com/54352598/111281347-d85fb500-8662-11eb-8828-ceb7fea66580.gif)
---------------------------------------------------------------------------------------------------------------------------------

<h2 align="center">Project Report</h2>

## Index

* [Introduction](#introduction)
* [Objective](#objective)
* [Overview](#overview)
* [Layout Analysis ](#layout-analysis )
* [Feasibility Study ](#feasibility-study)
* [Existing System](#existing-system)
* [Approach](#approach)
* [Used Case Diagram](#used-case-diagram)
* [Activity Flow Diagram](#activity-flow-diagram)
* [Entity Relationship Diagram](#entity-relationship-diagram)
* [Requirement Analysis](#requirement-analysis)
* [Features of Proposed System](#features-of-proposed-system)
* [Technologies Used](#technologies-used)
* [Module Description](#module-description)
* [Scope of Development](#scope-of-development)
* [Conclusion](#conclusion)


### Introduction

Development of web-based Quiz application is mainly required by students and learners to prepare themselves for different examinations directly through smart phones and tablets in hands. One of the major goal of our project is to facilitate students in learning, gaining and improving their knowledge skills. We designed the application to facilitate the users to be able to take short quizzes using portable devices such as smart phones and tablets. 

What is web development? 
Web development is the building and maintenance of websites; it's the work that happens behind the scenes to make a website look great, work fast and perform well with a seamless user experience. Web developers, or 'devs', do this by using a variety of coding languages. 

About Website 
The ‘QUESTIONNAIRE’ project was developed to overcome the time-consuming problem of the manual system. Apart from that in the current system, checking the answer sheets after taking a test, waste the examiner's time, so this application will check the correct answer and save the examiner's time and carry the examination effectively. The users which are using this system don’t need high computing knowledge and also the system will inform them while entering invalid data. The aim of this project is to computerized the existing manual system and help the examiners to save their valuable time and important data. Apart from this, data which are exist in this system, will exist for long period of time and will be easy accessible. This project helps the examiners to manage their services in a good way and provide a better service to their users.


**[⬆ Back to Index](#index)**


### Objective
The basic objective of this project is to manage the details of students, examinations, marks, courses and papers in a good manner. The performance of the application will be fully control by administrator and administrator can guaranty any one to access. The project will reduce the manual process in managing examinations and all issues regarding that. 

➢Scope -
Scope of this project is very broad in terms of other manually taking exams, few of them are: - <br>
• This can be used in educational institutions as well as in corporate world. <br>
• Can be used anywhere any time as it is a web-based application (user Location doesn’t matter). <br>
• No restriction that examiner has to be present when the candidate takes the test. <br>
<br>
➢Features -<br>
• Secure <br>
• Easy to use <br>
• Reliable and accurate <br>
• No need of examiner <br><br>

➢Functionalities of the project will be as following: <br>
• Able the examiners to punch the MCQ questions online; <br>
• Able the users to solve the questions online; <br>
• Examiners can manage the information regarding exam; <br>
• Correct answer will be evaluated by the system (First it should be determined by examiner) <br>
• Users can see their result after submitting the test. <br>

**[⬆ Back to Index](#index)**

### Overview

To design and implement this project we plan that the project support to different types of users apart from its administrative part. When project is run for the first time it allowed the user to select as who he/she wants to login in the system. Project support login as teacher and login as student. If a user who is student, try to login as teacher system will not allow him and vice versa. User who add as teacher in system will be able to punch test and questions to system and also will be able to observe the result of the student which attempt tests. User who login to system as student will be able to select a particular test and attempt questions depend on this test. After attempting the test and submitting that user will receive a message that you have attempt the test successfully and if the user tries to attempt the same test, system will not allow him/her. Also, a user which login to system as student will be able to observe the result of test, he/she attempt. 

The Questionnaire created for taking online quizzes has following stages- 

➢ Student Portal- <br>
• Login / SignUp <br>
• Test <br>
• Result <br>
• Ranking’s <br>
• Feedback <br>

➢ Quiz Master/Admin Portal- <br>
• Add / Edit Quiz <br>
• Student Information <br>
• Ranking’s <br>
• Feedback Response <br>


**[⬆ Back to Index](#index)**


### Layout Analysis

To conclude introduction, we have used these modules to follow the objectives of our project and each of these modules have logical connections to other modules which they are depend. 

• Index: Which allow users to select their type of login to system; <br>
• Teacher Login: Able the teachers to login to system with a valid user name and password. If a teacher is successfully login to system, he/she will have access to following pages; <br>
• Teacher Home: Which have information about Online MCQ Quiz and issues support by this system for the teachers; <br>
• Punch Test: Which able the teacher to punch a test and after entering the test name and clicking on ‘Submit to Enter Questions’, teacher will be able to add questions to the particular test; <br>
• Students Marks: Which able the teacher to observe the result of all student who have attempt the tests; <br>
• Student Login: Able the students to login to system with a valid user name and password. If student is successfully login to system, he/she will have access to following pages; <br>
• Student Home: Which have information about Online MCQ Quiz and issues support by this system for students; <br>
• Attempt Test: Which able the student to select a particular test for attempting from the existing test in system from drop down list and after clicking on ‘go to Selected test’, the questions of selected test will be displayed for the student to attempt. Then the student will be able to attempt the questions and after submitting, the student will receive a message that the test successfully attempts. 
<br>
➢ Marks: Which able the particular students to have access to the result of the test which he/she attempt. 


**[⬆ Back to Index](#index)**


### Feasibility Study

1) Economic Feasibility - In the system, the organization is most satisfied by economic feasibility. Because if the organisation implements this system, it need not require any additional hardware resources as well as it will be saving lot of time. 

2) Technical Feasibility -This system offers greater levels of user friendliness combined with greater processing speed. Therefore, cost of maintenance can be reduced. Since processing speed is very high and the work is reduced in the maintenance point of view convince that the project is operationally feasible. 

3) Operational Feasibility - The users are expected to be comfortable using the website as it will be self-explanatory and easy to navigate through. Therefore, the project will be operationally feasible. 

4) Schedule Feasibility - With the technologies mentioned previously and the right amount of technical knowledge about them the project can be completed before the deadline. 

5) Behavioural Feasibility - People are inherently resistant to change and computer has been known to facilitate changes. An estimate should be made of how strong the user is likely to move towards the development of computerized system. These are various levels of users in order to ensure proper authentication and authorization and security of sensitive data of the organization. 


**[⬆ Back to Index](#index)**


### Existing System

The whole process of assigning test and evaluating their score after the test, was done manually till date. Processing the test paper i.e. checking and distributing the respective scores used to take time when the software was not installed. 

Disadvantages of Current system: <br>

• The current system very time consuming. <br>
• It is very difficult to analyze the exam manually. <br>
• To take exam of more candidates more invigilators are required but no need of invigilator in case of on-line exam. <br>
• Results are not precise as calculation and evaluations are done manually. <br><br>

Characteristics of the proposed system->  <br>

The project created for taking online quiz has following features: <br>
• In comparison to the present system the proposed system will be less time consuming and is more efficient. <br>
• Analysis will be very easy in proposed system as it is automated. <br>
• Result will be very precise and accurate and will be declared in very short span of time because calculation and evaluations are done by the simulator itself. <br>
• The proposed system is very secure as no chances of leakage of question paper as it is dependent on the administrator only. <br>
• The logs of appeared candidates and their marks are stored and can be backup for future use. <br>


**[⬆ Back to Index](#index)**


### Approach

Modified Waterfall Model 

The modified waterfall model uses the same s as the pure waterfall model. In response to the perceived problems with the pure waterfall model, modified waterfall model have been introduced. This enables the s to overlap when needed. This is selected because our requirements for the projects were clear, it is a small project and hence can be implemented step by step.

<img src="https://user-images.githubusercontent.com/54352598/111307224-24205780-867f-11eb-837e-653bd8aa89e9.png"  align="center" alt="Waterfall Model" width="500" height="400">


**[⬆ Back to Index](#index)**


### Used Case Diagram

<img src="https://user-images.githubusercontent.com/54352598/111307518-92fdb080-867f-11eb-8087-767fc724196f.png" alt="Use Case Diagram" width="500" height="400">

This diagram denotes that user can register, login, view quiz, add quiz, submit quiz, update his details, can check score sheet, and finally logout. 

**[⬆ Back to Index](#index)**


### Activity Flow Diagram

<img src="https://user-images.githubusercontent.com/54352598/111307756-e2dc7780-867f-11eb-8cba-e56501c195a4.png" alt=" Activity Flow Diagram "  width="500" height="400">

•	ADMIN ACTIVITY DIAGRAM

<img src="https://user-images.githubusercontent.com/54352598/111307953-1d461480-8680-11eb-8b84-c4c98eea2744.png" alt=" Activity Flow Diagram "  width="500" height="400">


•	USER ACTIVITY DIAGRAM

<img src="https://user-images.githubusercontent.com/54352598/111308079-436bb480-8680-11eb-87db-69586fa859e7.png" alt=" Activity Flow Diagram "  width="500" height="400">

**[⬆ Back to Index](#index)**


### Entity Relationship Diagram 


<img src="https://user-images.githubusercontent.com/54352598/111308238-701fcc00-8680-11eb-8f76-f699b38b14e0.png" alt=" ER Diagram "  width="500" height="400">

We wish to convey the following Database design:<br>
ADMIN {Login, Update_Details, Password, Quiz_Details, Edit_Quiz}<br>
QUIZ MASTER {Create_Quiz, Start_Quiz}<br>
PARTICIPANTS {Answer, Scores}<br>


**[⬆ Back to Index](#index)**


### Requirement Analysis 

The fundamental idea behind our project is to make a product that would offer new aspects of learning. We wanted to create a tool that fits into modern age, but still stays true to the concepts of studying. During development, we worked out on some points, given as follows: <br>
•	The provided platform should be user-friendly,<br>
•	The platform should be highly interactive,<br>
•	Both user and quiz master could easily get the student ranking and score sheet,<br>
•	A portal should be created where one can his/her feedback for further improvements.<br>

Questionnaire’s main objective is to efficiently evaluate the candidate thoroughly through a fully automated system that not only saves lot of time but also gives fast results.
For students they give papers according to their convenience and time and there is no need of using extra thing like paper, pen etc.

**[⬆ Back to Index](#index)**


### Features of Proposed System 

•	To make the site more enjoyable and to get a measure of the learning achieved we are going to make an interactive quiz for each section. Users of the site can use the quizzes to test the knowledge gained in a section they have worked through.
•	The first thing we need to decide upon is the sort of quiz required and how many answers are required per question. Parsing answers from users could be an extremely difficult process and having to deal with multiple correct answers to questions can also lead to complications. We want the quizzes to be easily understood by our users and also easy to code. This also helps with writing the Project itself as the main purpose of the Project and indeed the site in general is to learn client side disciplines. So to make the quiz as easy as possible we will choose a multiple choice quiz with one correct answer per question.
•	We will use HTML for the structure, CSS for the presentation and JavaScript/query for the behavior. These versions of the aforementioned disciplines work in all modern browsers so we don't have to worry about things not working in certain browsers.
•	We will start with a simple three question quiz where feedback of 'right' or 'wrong' is given for each answer at the end of the quiz. We will use a basic progress bar so the user can see visible feedback of how much of the quiz has been completed thus far.
•	We don't just want a top down list of questions and answers so we need a way to display one question and the possible answers for the question one at a time.
•	In our project there is notice board tab where admin can put notice for the student.
•	Notice board can have details like exam time, exam date or any other important notice regarding the class.
•	Student can join live classes as we have video call feature.
•	We have used “jitsi” api to integrate video call function in our project.
•	Students can have one to one interaction with their faculty to clarify doubts.


**[⬆ Back to Index](#index)**


### Technologies Used 

➢	FRONT-END<br><br>
•	HTML5- HTML5 is a markup language used for structuring and presenting content on the World Wide Web. It is the fifth and latest major version of HTML that is a World Wide Web Consortium (W3C) recommendation.<br>
•	CSS- Cascading Style Sheets (CSS) is a style sheet language used for describing the presentation of a document written in a markup language like HTML. CSS is designed to enable the separation of presentation and content, including layout, colors, and fonts. CSS information can be provided from various sources. These sources can be the web browser, the user and the author. <br>
•	JavaScript- JavaScript s a high-level, interpreted scripting language that conforms to the ECMAScript specification. JavaScript has curly-bracket syntax, dynamic typing, prototype-based object-orientation, and first-class functions. Alongside HTML and CSS, JavaScript is one of the core technologies of the World Wide Web. JavaScript enables interactive web pages and is an essential part of web applications.<br>


➢	BACK-END<br><br>
•	PHP- PHP is a server side scripting language that is used to develop Static websites or Dynamic websites or Web applications. PHP stands for Hypertext Pre-processor, that earlier stood for Personal Home Pages. Hypertext Preprocessor (or simply PHP) is a general-purpose programming language originally designed for web development.<br>
•	MySQl- MySQL is an open source relational database management system (RDBMS) based on Structured Query Language (SQL). Currently My SQL is owned by Oracle. My SQL database is available on most important OS platforms. <br>


**[⬆ Back to Index](#index)**


### Module Description 

This project involves following phases:<br><br>
<b>--> ADMINISTRATOR AUTHENTICATION:<br></b>
            This proposed system is completely authenticated in order to enhance security and corruptions of database as well as the software. A person is given access permission to this system when he/she has got a valid username and password i.e. the administrator. Hence this authentication module includes two fields where administrator (programmer) is asked to enter the username and password. The details include:<br>
•	Username<br>
•	Password<br><br>
QUESTION GENERATION:<br>
            This includes the various categorized question generation. In this   the administrator can perform add, modify, delete, move next, move previous, clear all operation. This   may be the most important   in proposed system, because it is the one where the entire system gets the categorized question.<br><br>
REPORT GENERATION:<br>
            This contains various report generation related to our system such as Administrator report, Participant report, rank etc. the report gives the overall view about our system.<br><br>
NOTICE GENERATION:<br>
            This contains a notice publishing module. From the admin can make new announcements or notices for the user/student.<br><br>
MEET SCHEDULING:<br>
            This contains a meet link publishing and instant meet start-up module. From here the admin or the teacher can take online live classes and share its joining link with the user/student.<br><br><br>
<b>--> PARTICIPANT AUTHENTICATION:<br></b>
            This proposed system is completely authenticated in order to enhance security and corruptions of database as well as the software. A person is given access permission to this system when he/she has got a valid username and password. Hence this authentication module includes two fields where participant is asked to enter their username and password. The details include:<br>
•	Username<br>
•	Password<br><br>
REGISTRATION:<br>
          ➢  If the participant is an existing user then he can enter into the system, using his valid username and password.<br>
          ➢ If the participant is a new one then he has to fill the registration form. Now valid username and password will assign to the user. Using that he can enter into the system.<br><br>
RULES AND CATEGORY SELECTION:<br>
            This   provides the students with a set of rules and regulations to be followed while attending the quiz. It is useful for the user who is new to the online process so that they can have a clear idea of what has to be done. <br><br>
QUESTION BANK:<br>
            This   provides the students a set of multiple-choice questions<br><br>
RESULT GENERATION:<br>
            The result of the corresponding student is generated based on his, her performance in the test. The result is generated at the end of the quiz.<br><br>
NOTICE BOARD:<br>
            All the new announcements and notices are published here from here the student can view and respond to them.<br><br>
MEETING DESCRIPTION:<br>
            It displays list of all the upcoming meeting/classes with their joining link and details of their schedule.<br><br>


**[⬆ Back to Index](#index)**


### Scope of Development 

•	The main aim of our project is creating a good interaction between the student and teacher.<br>
•	We are trying to do the project at best level to satisfy all the end users (i.e., student/faculty).<br>
•	In our future we are decided to provide more security to our website which may not be hacked.<br>
•	And we give the choice to student to add their name under the faculty who they wish and get advice for their betterment.<br>
•	It will be more empowering.<br>
•	Next, we are aiming to provide some online classes in to our website.<br>


**[⬆ Back to Index](#index)**


### Conclusion

This online quiz system provides facility to conduct online examination world-wide. It saves time as it allows number of students to give the exam at a time and displays the results as the test gets over, so no need to wait for the result. It is automatically generated by the server. Administrator has a privilege to create, modify and delete the test papers and its particular questions. User can register, login and give the test with his specific id, and can see the results as well. The system is operated at a high level of efficiency and all the teachers and user associated with the system understands its advantage. The system solves the problem. It was intended to solve as requirement specification.

**[⬆ Back to Index](#index)**
