# Samantha's ePortfolio

## Professional Self-Assessment
###### My Experiences and Strengths
When I started my Computer Science journey, I thought I was going to learn how a computer runs and learn the hardware of computers. Well, I was only half right; computer science is so much more and I absolutely love it. I learned a lot about programming in different languages (I prefer C++ but know a good bit of Java), frontend and back in development, databases, and much more; more importantly I learned what I like working, what I am good at, and what I can potentially see myself doing in the future. 

Working as a team is very important, especially when you are working on something that is large scale. I had an opportunity to work with four other students in my Gam 305 class. We had to work together to create a game in Unreal Engine; we called the game Mouse in the Kitchen. We found we worked well together because everyone had different strengths when it came to programming; we were able to ask each other anything to complete the game on time and someone was always available to talk things out. Having support to cover your weaknesses and help to change those weaknesses to strengths is what teams should be able to do. 

Having the ability to talk to stakeholders to find out what they are looking for in a specific program takes patience and skill to read body language. Though I do not have experience of talking to stakeholders, I do have 20+ years of customer service experience. Working retail involves a lot of communication with customers and management. I have gain skills to know when someone is looking for something but may be afraid to ask for help. When talking to anyone, it is important to listen, not just with your ears but with your eyes; active listening is a great way for the customer, or whomever you are talking to, know that you care about what they are saying or asking for. I have recommended many things to customers when they are unsure what they want to get; especially if we do not carry or are currently out of the specific item they want. It is important that the stakeholders, users, and customers are content at the end of the day.

Data structures and algorithms are important to use and understand; it is how the data is transferred and saved in the program. I use arrays and array-lists all the time; I find them very easy to use and I am comfortable using an object as a attribute type. Binary trees are a fun data structure that I originally learned in C++ and more recently learned in Java; as a part of this ePortfolio, I have included the Java version which differs from C++ only a little. I included a hash map to this ePortfolio as well, more specifically a Concurrent hash map. Retrieving the values in the hash map is faster due to the hashing of the key makes less data to cycle through than array-lists. 

SQL and the lightweight version, SQLite, are reliable databases. SQLite is what I like to use when I create apps in Android Studio. I have used NoSQL database in the form of MongoDB which was also easy to use. I used this when I worked on my Full Stack class; we worked on an multiple page website and made it a single-page application. In the MEAN stack, it used MongoDB for the database, which requires all fields filled in to work (Not Null). Databases are important to hold all types of information.

Security for all programs is very important; we need to secure all programs from hackers. Hashing passwords is one way to do that. SHA-256, PBKDF2, BCrypt are examples of some hashing functions in Java. SHA-256 was what we used when learning about security and hashing, however, it is not recommended for actual use due to the quick speed allowing hackers brute-force passwords. PBKDF2, password-based key derivation function 2, is similar to SHA-256 but is more secure with using randomized salts and high iteration counts.

Software engineering and design is by far the most fun; planning out what the project is going to look like and writing pseudocode to help ensure we do not forget something is just the start of the fun. Seeing the program come together and working as it should be is the best part of software engineering. I have experience writing Python; however, C++ and Java are my strong languages. Object-Oriented Programming (OOP) is the best option when writing programs, in my opinion, it would work faster and is much more organized. Most of the programs I have worked on I used OOP; the only programs I did not use OOP were the two games I created in Unreal Engine. While creating the games, I was learning the programming by the blueprints instead of the code. Engineering a game in Unreal with blueprints is different, it works the similar to writing code, but it is easier to reference different classes. (I really enjoyed making games in Unreal.)

###### Portfolio Summary

I had created an Android Application for a program that I worked on in April of 2024 in my Computer Science 300 – DSA: Analysis and Design class. I transferred the program from C++ to Java, added a login page that allows for adding a user that hashes the password for added security, and added a database to hold the data to be recalled later. The hashing algorithm I used was PBKDF2 to hash the passwords and I used the SQLite for the databases I created. 

Due to the way I designed my enhancements to work with each other I have specific classes that were created to work with each other. There are also some methods not in-use due to the addition of the database. However, I am ensuring that all classes are being used. Listed below are the classes that were added for each enhancement. 

######	Category – Software Engineering & Design

  o	AddCourse.java - An activity page that calls on BinaryTreeClass.java and uses Course.java. It also calls on CourseDatabase.java
  
  o	BinaryTreeClass.java - A class that has many methods to add nodes and to display nodes. 

  o	Course.java -An object class

  o	ListCourseNames.java - An activity page that calls on BinaryTreeClass.java and CourseDatabase.java.	Mainly call CourseDatabase.java in the final version. 

  o	ListSingleCourse.java -	An activity page that calls BinaryTreeClass.java and CourseDatabase.java.	In final version it calls on BinaryTreeClass.java

  o	MainActivity.java - An activity page that directs to other activities.

###### Category – Algorithms and Data Structure

o	HashClass.java - This is an object class.

o	HashingHere.java - This contains the hashing methods for the password. 

o	LoginPage.java - This is an activity class that accesses HashingHere.java and Users.java classes. It uses the HashClass.java as well

o	Users.java - This class contains a database.

###### Category – Databases

o	CourseDatabase.java - This is the Database class that also has the methods to use the database. 

## Informal Code Review
This link will take you to YouTube for an Informal Code Review that will explain what artifact I had decided to enhance and how I planned to enhance it.

[Informal Code Review](https://youtu.be/p9U3vIqFfx8) 

## Link to the Artifact: Advising Assistance
[Download Artifact](https://github.com/tweetytime724/tweetytime724.github.io/blob/main/Artifact___Advising%20Assistance%20Program%20.zip)

## Software Design and Engineering
[Download Software Design and Engineering version of Advising Assistant App here](https://github.com/tweetytime724/tweetytime724.github.io/blob/main/Advising%20Assistant%20Final%20Software%20and%20Design%20Version.zip) 

I chose a program called Advising Assistance Program from course CS 300; I created it in April 2024 in C++. This artifact is being used for all three of my enhancements. The program holds and changes course information using a Binary Tree. I chose this program because I thought it would give me the opportunity to show skills towards making an application with it. Therefore, I chose to change the code from C++ to Java and create the app. The artifact improved by changing the viewing process; instead of having the program printed out on the computer in a list, potentially, you can have the ability to display the courses on the phone. Also, the enhancement is now object-oriented, meaning I have multiple classes, with a few class objects that makes it look cleaner and work faster.

I learned how to create the Binary Tree in Java; it is similar to C++ but there are some differences too. I found out that it would be best to call the root from different functions because the root was not being saved the same way the C++ program was. The program was challenging until I figured that out. The feedback that was given was to verify the courses were being retrieved which helped me to figure out my situation. 
###### Course Outcomes
1.	Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science.
###### I feel I demonstrated in-code comments that are easily readable and understandable in this enhancement. 
2.	Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.
###### I feel all of the written comments were of professional quality.
3.	Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices
###### I do not believe I touched on this in this enhancement.
4.	Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.
###### I know that I have used Log.d() method of diagnosing and catching my issues. I have since deleted them to make the code look more professional, but that is how I tested my code and solved my coding problems in the enhancement.
5.	Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources.
###### I did not touch this outcome in this enhancement.

## **The next two sections will be using the Final Version of the Advising Assistant App
[Download Advising Assistant App - Final Version here](https://github.com/tweetytime724/tweetytime724.github.io/blob/main/Advising%20Assistant.zip)

## Algorithms and Data Structure
The artifact I used for the software design and engineering category is the same one I used for this category of algorithms and data structures. I did not have any algorithms or data structures in this C++ program, Advising Assistance that I created for my CS 300 class that taught me Binary Trees back in April of 2024. So to continue with my application from before I added a Login page that allows the user to create an username and password, hashes the password, saves the salt and hashed password in a database. I also decided to create a database for storing the username and password. 

I was not successful at first getting my hashing to work properly but after the feedback I did get it working. I had to use a lot of Log.d() methods to figure out what was going on and that is also when I decided to add a database to hold the username and hashed passwords. The program improved from what the artifact had basically from having no security to having some form of security. Hashing passwords is one way to keep the program a little more secure and control who has access to the program. I had to learn a lot when it came to programming hashing algorithms. I used PBKDF2 algorithm to hash the passwords. 
###### Course Outcomes
1.	Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science.
###### I feel I demonstrated in-code comments that are easily readable and understandable in this enhancement. 
2.	Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.
###### I feel all of the written comments were of professional quality.
3. Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices.
###### I was able to solve my problems in logical way to get my hashing program up and running. Saving the salt was the hardest part of the programming. I tried saving the salt in the database but whenever I retrieved it, it changed. I read that is a known problem but there is no for sure way to fix it. Therefore, I have the decided to keep the hashed password and salt saved in a concurrent hash map. 
4.	Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.
###### I know that I have used Log.d() method of diagnosing and catching my issues. I have since deleted them to make the code look more professional, but that is how I tested my code and solved my coding problems in the enhancement.
5.	Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources.
###### Hashing passwords is the beginning of having a security mindset. Saving a salt with the hashed password does not pose a security risk because a hacker would not know what the password was that was hashed.

## Databases
I am using the same artifact that I used for the other two categories: the Advising Assistance Program in C++. Throughout this term, I have made the program into an application in Java and added more to the program. This artifact did not have a database when it was first written, therefore it would be an improvement in the set up. Due to the fact that there are two different ways I can have the code call for the courses, I have the list of courses be called from the database and the single course list be called from the Binary Tree from the Design and Engineering category. 

I did learn a lot about databases in this enhancement. I learned that some certain portions of a program need to be fully operational before adding others. This is a good lesson to learn due to the Agile Development Process being used more than the Waterfall Methodology. (I was able to work on the Login Page and Hashing Algorithm before I fixed my issues with the Design and Engineering Enhancement was being looked at for feedback.) I also learned how to work with the Context parameter; I could not connect my database to my program for three days while I researched what was going on. In addition to my Course Database, I do have an additional database for my username and hashed password to be held; it is called Users. I created it after I did my database enhancement.
###### Course Outcomes
1.	Employ strategies for building collaborative environments that enable diverse audiences to support organizational decision making in the field of computer science.
###### I feel I demonstrated in-code comments that are easily readable and understandable in this enhancement. 
2.	Design, develop, and deliver professional-quality oral, written, and visual communications that are coherent, technically sound, and appropriately adapted to specific audiences and contexts.
###### I feel all of the written comments were of professional quality and can be read by a wide variety of audiences.
3.	Design and evaluate computing solutions that solve a given problem using algorithmic principles and computer science practices and standards appropriate to its solution, while managing the trade-offs involved in design choices
###### I feel I was able to solve problems I came across with good computer science practices that are appropriate to the solution. My problems are stated above for this enhancement. 
4.	Demonstrate an ability to use well-founded and innovative techniques, skills, and tools in computing practices for the purpose of implementing computer solutions that deliver value and accomplish industry-specific goals.
###### I know that I have used Log.d() method of diagnosing and catching my issues. Some of them have been deleted, but that is how I tested my code and solved my coding problems in the enhancement.
5.	Develop a security mindset that anticipates adversarial exploits in software architecture and designs to expose potential vulnerabilities, mitigate design flaws, and ensure privacy and enhanced security of data and resources.	
###### I do not believe I touched on this much in this enhancement.
