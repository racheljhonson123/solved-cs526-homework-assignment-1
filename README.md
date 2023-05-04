Download Link: https://assignmentchef.com/product/solved-cs526-homework-assignment-1
<br>
This assignment has two parts and the goal of the assignment is:

<ul>

 <li>A practice of using basic Java features, including arrays, loops, selection statements, and simple I/O.</li>

 <li>A practice of using Java’s linked list and writing a small interactive program.</li>

</ul>




<h1>Part 1 (40 points)</h1>




Create a file named <em>ArrayConrolPractice</em>.<em>java</em> and write the following methods in it:




<ul>

 <li>Write a Java method named <em>sumOfEvenNumbers</em> that receives an integer <em>n</em> and returns the sum of all positive even integers less than or equal to <em>n</em>.</li>

</ul>




<ul>

 <li>Write a Java method named <em>allDistinct</em> that receives an array of integers and determines whether all the integers are different from each other. The method returns <em>true </em>if all numbers are different from each other and returns <em>false</em></li>

</ul>




<ul>

 <li>Write a Java method named <em>statistics</em> that receives an array of double numbers, calculates the largest number, the smallest number, and the average of all numbers. The method, then, stores these three statistics, in that order, in an array of size 3 and returns the array.</li>

</ul>




<ul>

 <li>Write a <em>main</em> method to test the above methods:</li>

</ul>




<ul>

 <li>Invoke <em>sumOfEvenNumbers</em> twice once with <em>n</em> =100 and then with <em>n</em> = 200, and print each result on the screen. o Create an array with 20 integers that include some duplicates, invoke <em>allDistinct</em> and pass this array as an argument, and print the result on the screen. Repeat the same but this time with an array with all distinct integers.</li>

 <li>Create an array with 10 double numbers, and invoke <em>statistics</em> and pass this array as an argument, and print the result (max, min, average) on the screen. Repeat the same with an array with different double numbers.</li>

</ul>




<h1>Part 2 (60 points)</h1>




Your program receives information about students interactively from the user and stores them in Java’s <em>LinkedList</em>. Then, your program performs a few basic operations on the student list as dictated by the user. Name your program <em>StudentManagement.java.</em> A <em>Student</em> class is already defined and it is posted along with this assignment (<strong>do not use the <em>Student</em> class that comes with the textbook</strong>). You should not modify the given <em>Student</em> class. As an example of a simple menudriven program, <em>CarManagement.java</em> file is also posted on Blackboard. You may want to study this file before writing your program.




The requirements are given below:




When your program starts, it must display the following main menu:




Choose an option:




<ol>

 <li>Add a student</li>

 <li>Remove a student</li>

 <li>Update student GPA</li>

 <li>Display student information</li>

 <li>Display all students</li>

 <li>Exit</li>

</ol>




If the user chooses option 1, your program performs the following:




<ul>

 <li>Prompts the user to enter a studentID, and reads it.</li>

 <li>If a student with the given studentID is already in the list, your program displays an appropriate error message, and displays the main menu.</li>

 <li>Otherwise:</li>

 <li>Prompts the user to enter a name, and reads it.</li>

 <li>Prompts the user to enter a GPA, and reads it.</li>

 <li>Creates a student object and adds it to a <em>LinkedList</em>, displays an appropriate message indicating a successful operation, and displays the main menu</li>

</ul>




If the user chooses option 2, your program performs the following:




<ul>

 <li>Prompts the user to enter a studentID, and reads it.</li>

 <li>If a student with the given studentID does not exist in the list, displays an appropriate error message, and displays the main menu.</li>

 <li>Otherwise, removes the student with the given studentID from the list, displays appropriate message indicating a successful operation, and displays the main menu.</li>

</ul>




If the user chooses option 3, your program performs the following:




<ul>

 <li>Prompts the user to enter a studentID, and reads it.</li>

 <li>If a student with the given studentID does not exist in the list, displays an appropriate error message, and displays the main menu.</li>

 <li>Otherwise:</li>

 <li>Prompts the user to enter a GPA, and reads it</li>

 <li>Updates the GPA of the student with the new GPA, displays an appropriate message indicating a successful operation, and displays the main menu.</li>

</ul>




If the user chooses option 4, your program performs the following:




<ul>

 <li>Prompts the user to enter a studentID, and reads it.</li>

 <li>If a student with the given studentID does not exist in the list, displays an appropriate error message, and displays the main menu.</li>

 <li>Otherwise, displays the student information in the following format:</li>

</ul>




Name: John Smith

Student ID: U1234

GPA: 3.85




Then, displays the main menu.




If the user chooses option 5, your program prints all students in the list in the following format:




Name: John Smith

Student ID: U1234

GPA: 3.85




Name: Susan Smith

Student ID: U2345

GPA: 3.92

. . .




Then, displays the main menu.




If the user chooses option 6, your program terminates after displaying an appropriate message, such as “Bye.”




<h1>Documentation</h1>




No separate documentation is needed. However, you must include sufficient inline comments within your program.




<strong><u>Deliverables</u> </strong>




Submit your <em>ArrayControlPractice.java</em> and <em>StudentManagement.java</em> files to Blackboard.




<h1>Grading</h1>




Part 1: Each method will be tested with different input arguments and 5 points will be deducted for each method if your output is incorrect.




Part 2: 5 operations (menu choices 1 – 5) will be tested in the following way:




<ol>

 <li>Add a student: Will be tested twice, once with an existing studentID and once with a nonexisting studentID. 3 points will be deducted for each wrong operation.</li>

 <li>Remove a student: Will be tested twice, once with an existing studentID and once with a nonexisting studentID. 3 points will be deducted for each wrong operation.</li>

 <li>Update student GPA: Will be tested twice, once with an existing studentID and once with a non-existing studentID. 3 points will be deducted for each wrong operation.</li>

 <li>Display student information: Will be tested twice, once with an existing studentID and once with a non-existing studentID. 3 points will be deducted for each wrong operation.</li>

 <li>Display all students: Will be tested once and 3 points will be deducted if the output is incorrect.</li>

</ol>








