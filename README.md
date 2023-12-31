# CS-255
System Analysis and Design
--------------------
Briefly summarize the DriverPass project. Who was the client? What type of system did they want you to design?
What did you do particularly well?
  The DrivePass project was a scenario in which a company that provides drivers ed to people trying to pass that DMV written and driving test. They provide online practice tests, online classes, and in person driving lessons to students depending on the package they purchase. The client wanted a web based application that would allow users to login to their accounts on any device and be able to manage their appointments with drivers, view driver notes, take classes and tests, etc. The owner also wanted special permissions for their employees depending on their role in the company.
--------------------
If you could choose one part of your work on these documents to revise, what would you pick? How would you improve it?
  If I were to choose one area of my work to revise it would be my UML Sequence Diagram for a user logging in. I think that it is a bit crowded and hard to read, and I think a factor of logging in that I neglected to add is the option to have a password reset by the receptionist instead of just a email link. To improve the diagram I would space things out better and not worry so much about making it fit on to a Word document and I would add the alternative for the password reset.
--------------------
How did you interpret the user’s needs and implement them into your system design? Why is it so important to consider the user’s needs when designing?
  I used the provided transcript of a hypothetical interview between the development leaders and the client. Going through that line by line I made notes of every request and answer that was made and then turned those notes into a usable Buisness Requirement document. Then when I was moving forward with the project I returned to both the transcript and my document for guidance on what the client wanted. Keeping what the client wants and needs in mind when developing is the most important part of development. If someone wants an app that allows a user to create and share cooking recipes and you come back with an app that calorie counts the client will not pay for the service and their reviews will ensure no one else uses you again. They want an app that does a specific task, and my job as a developer is to deliver an app that accomplishes that task.
--------------------
How do you approach designing software? What techniques or strategies would you use in the future to analyze and design a system?
  I learned the agile methodology early in my schooling and that kind of cyclic thinking is how I approach designing software and I think that that is the technique I will continue to use. For example when I was thinking about the UML diagrams I was writing I started with the high level thinking of user logs on. Then I broke that down into a new user would make an account and an old user would enter in a username and password. Then I thought of incorrectly entering a username and password and added that an account would need brute force attack protection, so it would lock after 3 trys. Finally I thought of how the account would become unlocked so the user could use their account and added that the account would be unlocked with a password reset link that was sent to their email.
--------------------
