### This will be the third chapter, describing Use cases

* Define the user groups / actors 

 <table>
  <tr>
    <th>User group</th>
    <th>Definition</th>
  </tr>
  <tr>
    <td>Teachers and staff</td>
    <td>The main actors who create announcements or notes to give students immediate information in right time at right place in school</td>
  </tr>
  <tr>
    <td>Students</td>
    <td> The ones who receive message from teachers and staff whenever they go nearby locations which have created notes by the first group. They also can create notes, but only in the place where they are gave permission</td>
  </tr>
 </table> 

 <table>
  <tr>
    <th>Primary Actors</th>
    <th>Use case</th>
  </tr>
  <tr>
    <td>Teachers and staff </td>
    <td>1. Log in <br/>
        2. Create note <br/>
        3. Edit note <br/>
        4. Set up time for note <br/>
        5. Log out <br/>
    </td>
  </tr>
  <tr>
    <td>Students</td>
    <td>1. Log in <br/>
        2. Create note <br/>
        3. Read note <br/>
        4. Save note <br/>
        5. Share note <br/>
        6. Log out <br/>
    </td>
  </tr>
 </table> 

* Use case diagram showing the actors and primary use cases
 
<img src="http://users.metropolia.fi/~dieun/sw.jpg" alt="useCaseDi"/>

* Main use cases described more in detail, based on a template

 <table>
  <tr>
    <td><strong>Use Case ID:</strong></td>
    <td>1</td>
  </tr>
  <tr>
    <td><strong>Use Case Name:</strong></td>
    <td>Create note</td>
  </tr>
  <tr>
    <td><strong>Actor:</strong></td>
    <td>Teachers and staff</td>
  </tr>
  <tr>
    <td><strong>Initial state:</strong></td>
    <td>1. Teachers or staff chose their location where they want the note to appear. <br/>
        2. Teachers or staff open the "Flying note" application in their mobile phones. <br/>
        3. Log in by their own accounts.</td>
  </tr>
  <tr>
    <td><strong>Normal Flow:</strong></td>
    <td>1. Teachers or staff choose "Create note" bar <br/>
        2. The app will show two options : create a text note or voice note<br/>
        3  a. If text note option is chosen <br/>
        3  a  1. The app will show the format form <br/>
        3  a  2. They will fill title and content fields <br/>
        3  a  3. Submit their complete note <br/>
        4. The app ask if they want to review before delivering their note <br/>
        5  a. If reviewing option is chosen <br/>
        5  a  1. The app will show the content again <br/>
    </td>
  </tr>
   <tr>
    <td><strong>Alternative Flow:</strong></td>
    <td>
        3  b. If voice note option is chosen <br/>
        3  b  1. The app will show record voice panel <br/>
        3  b  2. Start recording their voice <br/>
        3  b  3. After finishing record, submit the voice note <br/>
        5  b. If confirming option is chosen <br/>
        5  b  1. The app will delivery their note <br/>
    </td>
  </tr>
  <tr>
    <td><strong>Exceptions:</strong></td>
    <td>1. If they go far away from the location when creating the note <br/>
        -> They have to come back to near the location, return to step 1 of initial state <br/>
        2. If the app is crashed <br/>
        -> They have to return to step 2 of initial state <br/>
        3. If the internet connection is lost <br/>
        -> System will return step 2 of normal flow and inform about internet connection problem <br/>
    </td>
  </tr>
  <tr>
    <td><strong>End state:</strong></td>
    <td> When the notes is shown in "New note" section of dashboard in the app</td>
  </tr>
 </table> 
 
  <table>
  <tr>
    <td><strong>Use Case ID:</strong></td>
    <td>2</td>
  </tr>
  <tr>
    <td><strong>Use Case Name:</strong></td>
    <td>Read note</td>
  </tr>
  <tr>
    <td><strong>Actor:</strong></td>
    <td>Students</td>
  </tr>
  <tr>
    <td><strong>Initial state:</strong></td>
    <td>1. Students reached the location have created note
    </tr>
  <tr>
    <td><strong>Normal flow:</strong></td>
    <td>1. Students will get notification of the new note in that location <br/>
        2. Open the "Fyling note" application in mobile phone  <br/>
        3. Log in by their own accounts <br/>
        4. The new note will be displayed in dashboard of the app <br/>
        5. Read the new note <br/>
    </td>
  </tr>
  <tr>
    <td><strong>Exceptions:</strong></td>
    <td>1. If students go far away from the location  <br/>
        -> Return to the step 1 of initial state <br/>
        2. If students do not get notification when they are nearby the location <br/>
        -> Turn on the notification from the settings, then return to step 1 of normal flow <br/>
    </td>
  </tr>
   <tr>
    <td><strong>End state:</strong></td>
    <td>When students finished reading and the notification signal got off  </td>
  </tr>
</table> 

  
  
