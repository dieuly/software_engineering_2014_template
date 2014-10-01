### Chapter describing the functional and non-functional requirements

* functional requirements (FR): a listing of details that are related to use cases

 - Choose.location : there is virtual wall in every location at school, teachers, staff or students have to be or nearby specific location within one meter radius from that location.
 - Log in : to create or read the note, system wants to know who is the author or reader. If creators do nothing for 15 minutes, system will require them to log in again.
 - Create note : there will be two options for creator to choose : text note or voice note. If the message is long, creators may prefer recording voice to avoid wasting time. Or if the voice of creators is not so clear, they may prefer writting text note.
 - Create.text.title : the subject of note should be defined to capture attention and give clear overview for readers.
 - Create.text.content : The main content of note will be written here and it will be set limit characters to avoid long and unnecessary words.
 - Edit.text.note : system provides that creators can decorate their text as in WordOffice, such as highlight, resize text.
 - Create.voice.note : the record panel will be shown and creators have to press record button to start recording their voice.
 - Edit.voice.note : system offers for creators to increase high quality of their voice record or they can cut off some parts of record if needed.
 - SetUpTime : if creators want their note available in certain time, for example, in 1 hour, system has set up time feature for their note.
 - Read.note : the app will show up the new note for readers if they reached or nearby the location where note is created and open the app in their mobile phone.
 - Save.note : system provides helpful function for students if they want to save vacancy news or school's club information to keep contact information for later purpose.
 - Share.note : system allows students to share their note for public or for specific groups, depending on their demand. This function is not necessary for teachers and staff because most of their notes or annoucenments are public for all students.
 - Log out : users should log out after they have done all their actions and save their personal information.



* FRs tells in detail what have to be considered when use cases are implemented in the system
  * Good functional requirements are traceable and verifiable: from the end product you can easily see does the FR in documentation exist in the software
  * Sommerville "These are statements of services the system should provide, how the system should react to particular inputs, and how the system should behave in particular situations. ..." (p. 85 in Sommerville: Software engineering 9)
 


* non-functional requirements: requirements describing the system in general
  * constraints related to system performance, reliability, security, accessibility, price, process model, etc.

 - Usability:
 This system is mobile application so the interface is designed simple and concise. When users open the application, they will be reuired to log in immediatelly, this is very simple step that every one can do. As for creating and editing written note, it is easy like doing in word office. Or the other actions like save note or share note, users will not feel confused to do that. System will ask pop-up questions for users to choose review or confirm in the submiting step, so they are easy to choose between options. But for set up time, system will not ask users, so users may skip that part after they created their note. Also, the phone gap should be taken into consideration when building this app to avoid misdisplaying of interface on mobile screen.

 - Reliability:
 When readers open to read new note, system also show up the author and date of that note, because from the beginning, system required users to log in by their own accounts. If the note is for the whole class, then it should be created by the teacher, not by student from other class.

 - Price:
 The most expensive component for this system is building virtual walls in every location at school. Virtual wall plays the important role in receiving and sending signal from mobile phone.
 

