### Chapter 4, system architecture

* High-level overview of the system :

 The "Flying note" application in mobile phone provides the immediate messages or notes from teachers and staff to students, especially in hurry situations, for exmaple, teachers change classroom few hours before class starting. As for students, if they feel the food in cafeteria is not so good, they can leave a note there and share it to other students who reached cafeteria and installed the app in their mobile phone. Another interesting feature is that students can get vacancy news or school's club information quickly when they are passing portal or lobby at school. 

* Main modules and their functions represented :

<img src="http://users.metropolia.fi/~dieun/Sys.jpg" alt="sys"/>

   1. Mobile phone : the application is installed in mobile phone where user can do all actions.
   2. Virtual Wall : used to locate mobile phone via wifi signal, it will make sure user can do actions within allowed location.
   3. Authentication : request user's identification to access into system by requiring user to enter password.
   4. Server : receive the data from user side and answer the user's request.
   5. Database : store created note in certain time, depending on user's demand.

<img src="http://users.metropolia.fi/~dieun/sa.jpg" alt="sysArchi"/>



