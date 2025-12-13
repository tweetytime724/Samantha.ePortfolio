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

https://youtu.be/p9U3vIqFfx8 

## Link to the Artifact: Avising Assistance

