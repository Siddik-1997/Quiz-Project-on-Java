# Quiz-Project-on-Java

## What are the uses of Java?

Java is a popular high-level, object-oriented programming language that is widely used to develop a wide range of applications, from desktop and mobile applications to web-based applications and enterprise-level software and it is one of the most widely used programming languages in the world. Its popularity is due in part to its platform independence, meaning that Java code can be written once and run on multiple platforms without modification.

Java is commonly used in web development for building server-side applications using frameworks like Spring, Hibernate, and Struts. It is also used in mobile application development for Android and for building desktop applications using Swing and JavaFX. Additionally, Java is a popular choice for developing large-scale enterprise applications.

Java's popularity can be attributed to its many advantages, including its simplicity, object-oriented nature, platform independence, robustness, security, and large community support. The language is also continually evolving with new releases and updates to keep pace with the latest technologies and programming paradigms.

## What is the purpose of using a JSON file? 

The purpose of using a JSON (JavaScript Object Notation) file is to exchange data between different programs and platforms in a lightweight, easy-to-read format. Here are some of the specific purposes of using a JSON file:

- Data Exchange: JSON files are used to exchange data between different programs and platforms in a simple and efficient way. This is especially useful for web applications, where data exchange needs to happen quickly and with minimal bandwidth usage.

- Configuration: JSON files can be used as configuration files for software applications, providing a flexible way to store and manage application settings.

- Data Storage: JSON files can be used to store data in databases, document stores, and other data storage systems. This provides a simple and flexible way to store and retrieve data.

- Web APIs: JSON is the preferred format for many web APIs, making it a standard way to exchange data between web applications and services.

- Data Analysis: JSON files can be used for data analysis and visualization, providing a flexible and easy-to-read format for data scientists and analysts.

In summary, JSON files are used for a variety of purposes, including data exchange, configuration, data storage, web APIs, and data analysis. Its lightweight and easy-to-read format makes it a popular choice for exchanging data between different programs and platforms.

## Technology used: 
- Intellij IDEA
- Java

## Project Scenerio:

**Create a quiz program that will take questions, option and answer from admin user and save it to the question bank. Then if any user want to give the quiz, random 5 questions will be shown to the user from the question bank.**

**Program output:**
1. Add Quiz
2. Start Quiz

**if user select option 1, then system will tell user to input a question, 4 options and correct ans to save data in a quiz bank. The quiz bank will be a json file. For an example,**

System>Please add a ques here:

User>Which testing is done by developer?

System>Input options.

Option a:

User> Unit Testing

Option b:

User> Integration Testing

Option c:

User> Sanity Testing

Option d:

User> Regression Testing

System> Please input the correct ans

User> a

System: Quiz saved at the database. Do you want to add more? (y/n)

**if user press y, then the previous scenario will happen again otherwise the program will be closed.**

**If user select option 2,  then,**
System> You will be asked 5 questions, each questions has 1 marks

1. Which testing is done by developer?

 - a. Unit Testing
  
  - b. Integration Testing
  
 - c. Sanity Testing
  
 - d. Regression Testing

User> a

System> Correct!

else not correct,

System: Not correct

**Finally 5 different random questions will appear from your question database. At least add 15 questions from any category from testing.
Result: You got [correct_marks] out of 5**

**JSON Format:**

[{

"Question":"Which testing is done by developer?",

"option a":"Unit Testing",

"Option b":"Integration Testing",

"Sanity Testing":"Sanity Testing",

"Option d":"Regression Testing",

"answer":"a"

},

{

"Question":"Which is functional testing?",

"option a":"Load Testing",

"Option b":"Security Testing",

"Sanity Testing":"Gorilla Testing",

"Option d":"Benchmark Testing",

"answer":"c"

}]


## Project Output Video:

https://user-images.githubusercontent.com/123433625/221402446-1ec2ce0e-bc88-4056-951a-c2a6a9c87af8.mp4

