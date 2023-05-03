Download Link: https://assignmentchef.com/product/solved-cs-115-introduction-to-programming-in-python-lab-guide-07a
<br>
Lab Objectives:  Classes

<strong>Instructions:</strong> Upload your solutions as a single .zip file to the Lab07 assignment on Moodle before the end of your lab session. Use the following naming convention:

SS_Lab07_Surname_FirstName.zip where SS is the section number 01, 02, 03, etc.




<ol>

 <li>Write a class called Person  (<strong>py</strong>) that represents a typical Person object.

  <ol>

   <li>The class will store the following attributes:

    <ul>

     <li>Name</li>

     <li>Age</li>

     <li>Gender</li>

     <li>Location</li>

    </ul></li>

   <li>Your class should have <strong>an init() method </strong>that takes the values of all four attributes as parameters.</li>

   <li>Your class should have the following <strong>methods</strong>:

    <ul>

     <li>Name: returns the value of the attribute</li>

     <li>Age:                 returns the value of the attribute</li>

     <li>Gender: returns the value of the attribute</li>

     <li>Location: returns the value of the attribute + updates value of the attribute</li>

    </ul></li>

  </ol></li>

</ol>




<ol>

 <li>You should also write IncreaseAge() method for increasing the person’s age.</li>

 <li>In addition to the accessor/mutator methods, your class should define a __repr__ method that returns the string information about the Person in the following format, where</li>

</ol>

“gulsah” is the name, “21” is the age, and “female” is the gender and “ankara” location):




Name    : gulsah Age     : 21

Gender  : female

Location: ankara







<ol start="2">

 <li>Create a script that does the following:

  <ol>

   <li>Define method getByLocation(): takes a list of Persons as a parameter and returns the list of Persons who have the location passed as a parameter.</li>

   <li>Define method getByGender(): takes a list of Persons as a parameter returns the list of Persons who have the gender passed as a parameter.</li>

   <li>Read data from the file input.txt and creates a list of People using data from the file.</li>

   <li>Using the list and the functions defined in part a and b, print all the females in Ankara.</li>

  </ol></li>

</ol>




<strong>Sample Run: </strong>

—————Printing Females in Ankara—————

Name: gizem

Age: 21

Gender: female

Location: ankara




Name: gulsah

Age: 21

Gender: female

Location: ankara Output will appear as follows:











