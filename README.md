# Crossover_CA
Cross  module CA CCT
This assignment is an integrated assessment that spans over 3 modules: Databases, Object Oriented Constructs and Linear Algebra.

You are required to develop a program that will solve systems of linear equations of two and three variables using matrices. Your program will also include a component of data persistency, that will keep track of different users and the operations they perform.

System requirements
Two different user account types must be created. Depending on the account type, different options in the system will be available to them. The two types of users will be:

Admin
⦁	There should be one system administrator pre-registered through the backend database with the following credentials:
⦁	Username: CCT
⦁	Password: Dublin
⦁	The admin should be able to log into the system.
⦁	Once logged in, the administrator will be able to:
⦁	Modify their own profile (name, surname, and any other attribute you define for them).
⦁	Access a list of all other users in the system.
⦁	Remove other users from the system.
⦁	Review the operations performed by other users. 

Regular User
⦁	The regular user should be able to sign up to the system using a self-registration option. 
⦁	Once registered, the regular user should be able to log into the system.
⦁	Once logged in, the regular user will be able to:
⦁	Modify their own profile (name, surname, and any other attribute you define for them).
⦁	Solve systems of linear equations of two and three variables. How to handle the input of the equations is for you to decide. Every time a system of equations has been solved by the system; a record of this operation should be stored in the database.

You will also produce a document where you will include:
⦁	Challenges you faced in the development process and your strategies to overcome them.
⦁	The rationale for your design decisions. 
⦁	Database conceptual design. Include in your report the conceptual design using CHEN notation. You can use tools such as draw.io to achieve this. In the diagram, you need to identify entities, attributes and relationships.
⦁	Logical design. Transform the conceptual representation from above to the logical structure in the Relational Model.
⦁	Validate the Relational Model and determine if Normalisation is necessary Include a short paragraph to explain that design is in 1NF, 2NF, 3NF. 
⦁	Physical design: Produce the SQL create statements for each relation including INSERT statements (dummy data). 
⦁	Appendix with your database file.



Programming Requirements
You are expected to build your program using an object-oriented approach. Thus, all the Object Orientation and SOLID principles should be implemented using abstract classes, interfaces, access modifiers and any other tool that Java provides for this.

The use of other Java constructs such as ENUMS, collections, packages, and wrapper classes, among others, is also recommended.

The program should have a user interface. The minimum requirement is a command line program, but if you want to aim for a distinction, explore other options such as the GUI builder that NetBeans has incorporated. All user input should be correctly validated, and relevant error messages are required to improve the user experience. All business logic and user interactions should be separated.

Linear Algebra Requirements
You are expected to build a program which uses the properties of matrices to solve a system of simultaneous equations. 

You must test your program with the following simultaneous equations:
⦁	

⦁	



Database Requirements
You must design and implement a database in 3NF that meets the requirements of your assignment.

You must provide the logical and conceptual design of your database using appropriate diagrams. 

You must manipulate your data using appropriate CRUD operations in SQL.
