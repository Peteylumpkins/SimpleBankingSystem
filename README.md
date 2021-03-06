# SimpleBankingSystem

This is my simple banking system application. It supports the basic functionality you might find at a bank, and stores account information in an SQL database. 

# Goal

The goal of this project was to reinforce the principles of object-oriented design I have been studying in my coursework, and expose myself to new technologies. 
In my coursework, we studied the theory behind object-oriented programming, and I was looking to put those ideas into practice, while also exposing myself to new 
ideas and technology, namely SQL databases, build tools such as Gradle, and the Luhn algorithm.

# Functionality

- Creating bank accounts
- Logging in and out of accounts
- Depositing, withdrawing, and transferring funds between accounts
- Viewing current account balance
- Closing accounts

# What I learned

- Store data in an SQL database (SQLite) and make basic searches and queries
- Use the Luhn algorithm to verify and validate account numbers
- Import project dependencies using Gradle build tools
- Principles of Object-Oriented Design
- Experience with Java programming language

# Where's the source code
If you're looking for the Java source code, navigate to the src folder, located in the SimpleBankingSystem folder:
```
SimpleBankingSystem >>> src
```
Under the src folder there should be 3 additional folders 
```
src >>> | Main
        | bank
        | exceptions
```
The source code for the application should be available under these three folders (Main, bank, exceptions).
       
# How to get started

To run the application, I'm pretty sure you need to have the following installed on your machine:

- JVM 14.0.1 
- Gradle 6.5.1
- SQLite3 3.28 

Assuming that you have everything installed on your machine, all you have to do is run the file at Main.java located here:
```
SimpleBankingSystem >>> src/main/java >>> Main >>> Main.java
```

Hopefully, it doesn't crash when you try to run it. If it's working correctly, the console should present you with the following options:
#
1. Create Account
2. Log into Account
0. Exit
#
To select an option, input the number that corresponds to the option. For instance, if you want to create an account, enter 1. If you want to log in to an account, enter 2. If you want to exit the system, enter 0.






