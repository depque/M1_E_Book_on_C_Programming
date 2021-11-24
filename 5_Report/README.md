# Requirements
## Introduction
 * The COVID-19 has resulted in schools shut all across the world. Globally, over 1.2 billion children are out of the classroom. This project aims on providing education to the Technophile newbies. who are interested to learn C language. C language is a computer programming language that was developed to do system programming for the operating system UNIX and is an imperative programming language.
 * This project first takes the user to a index page where the available contents on c program are listed and asks the user to give input for the respective topic he wants to review or study, after that it takes the user to that topic page where there are options to see further subtopics and example codes. User can also try run the example code by him/herself. User can also give suggestion to us. 

## Research
### E-BOOK ON C PROGRAMMING...
* This is a simple project which simply provide easy contents on c programming to the user after taking input from the user. 
* This project is built using traditional file handling system rather than Data base system. here the user provides his/her desired choice and the code after taking input from the user it runs the respective user defined funtion which prints the contents of the respective topic.
<img src="https://github.com/depque/Typing-Tutor/blob/master/1_Requirements/File-functions.jpg" width="920" height="520">

## Cost and Features
* This project has various features, like it can provide contents on c programming concepts to the user. 
* User can also run the given sample codes and try it by themslef. which is a big plus point for this project.
* users have option also option to give their valuable suggestions in or platform. 
#### above features are shown in the below screenshot. 
<img src="https://github.com/depque/Typing-Tutor/blob/master/1_Requirements/index.png" width="1080" height="720">

## Defining Our System
* System bacically takes input from the user and checks for the file, and then it prints the file.
for ruunig the code it checks for the available code and run it in the compiler i.e GCC and prints the output
* for the suggestion part it takes suggestion from user and stores it in a file.
<img src="https://github.com/depque/Typing-Tutor/blob/master/1_Requirements/system%20definition.png" width="780" height="520">

## SWOT ANALYSIS
![image](https://github.com/depque/Typing-Tutor/blob/master/1_Requirements/SWOT%20analysis.png)

# 4W&#39;s and 1&#39;H

## Who:

* All the tech newbie who wants to step into c programming world.

## What:

* Digital book or electronic book, that provies information about c programming.

## When:

* During the ltts step-In training, this is the Mini project assessment and development started on 16th of November, 2021.

## Where:

* This can be used in all over the globe. any student/working professional of any age can use it.

## How:

* users can use this code to enhance their c knowledge.

# Detail requirements
## High Level Requirements:

| ID | Description | Status (Implemented/Future)
|:---:|:---:|:---:|
|HLR-1| User shall be able to move to cover page and index page. |Implemented|
|HLR-2| System output must display the contents of the file. |Implemented|
|HLR-3| user shall be able to execute the sample codes. |Implemented|
|HLR-4| user shall be able to give suggestion. |Implemented|
|HLR-5| user shall be able to write their own code and execute. |Future|
|HLR-6| user shall be able to access a learning leader board. |Future|


##  Low level Requirements:

| ID | Description | Status (Implemented/Future)
|:---:|:---:|:---:|
|LLR-1| User shall be able to read the text files. |Implemented|
|LLR-2| User shall be able to create their account. |Future|
|LLR-3| User should be able to manage their data. |Future|






# Design

## High Level Design 
-----------------------------------------------------------
### Structural and Behavioural Diagram
#### Usecase behavioural diagram
<img src="https://github.com/depque/Typing-Tutor/blob/master/2_Architecture/Usecase%20Behaviour%20diagram.png" width="1080" height="720">

#### Activity behavioural diagram
<img src="https://github.com/depque/Typing-Tutor/blob/master/2_Architecture/Activity%20behaviour.png" width="1080" height="720">

# ------------------------------------------------------------------------

## Low Level Design 
-----------------------------------------
### Structural and Behavioural Diagram
#### Component structure Diagram
<img src="https://github.com/depque/Typing-Tutor/blob/master/2_Architecture/Component%20Structure%20Diagram.png" width="1080" height="720">





# Implementation

## Folder Structure
Folder        | description
--------------| ----------------------------------------------
`inc`         | All header files
`src`         | All the source codes required for the code
`test`        | test file is placed here.
`build`       | Build output (Not included in git)
`Screenshots` | Screenshots of the applications are present here.

## code output

### start page
-------------------------

<img src="https://github.com/depque/Typing-Tutor/blob/master/3_Implementation/screenshots/start.png" width="920" height="520">

### coverpage of the E-Book
----------------------------

<img src="https://github.com/depque/Typing-Tutor/blob/master/3_Implementation/screenshots/coverpage.png" width="920" height="520">

### Index page of the E-book
-----------------------------

<img src="https://github.com/depque/Typing-Tutor/blob/master/3_Implementation/screenshots/index.png" width="920" height="520">










# TEST PLAN:

## Table no: High level test plan

| **Test ID** | **Description**                                              | **Exp I/P** | **Exp O/P** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  H_01       | Is user able to get into the coverpage of their desired choices | 0 | cover page | coverpage | Requirement based |
|  H_02       | Is the user able to get into the index page | 1 | index page contents | index page contents | Requirement based |
|  H_03       | Is the user able to run the given sample codes | y | expected output | expected output | Scenario Based |
|  H_04       | Is the user able to submit his feedback | user review | review | review | Scenario Based |      

## Table no: Low level test plan

| **Test ID** | **Description**                                              | **Exp IN** | **Exp OUT** | **Actual Out** |**Type Of Test**  |    
|-------------|--------------------------------------------------------------|------------|-------------|----------------|------------------|
|  L_01       | is the user able to get into the contents | 1-9 | respective topic | respective topic|Requirement based |

## Screen shots
---------------------

### unit testing output
<img src="https://github.com/depque/Typing-Tutor/blob/master/4_TestPlan/test%20output.png" width="1020" height="620">

----------------------------------

### example code which the user can run and test by their own.
<img src="https://github.com/depque/Typing-Tutor/blob/master/4_TestPlan/demo%20code.png" width="1020" height="620">

----------------------------------

### index page. from here the user can go to different topics.
<img src="https://github.com/depque/Typing-Tutor/blob/master/4_TestPlan/index.png" width="1020" height="620">