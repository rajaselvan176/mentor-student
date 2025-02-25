# ZEN-Mentos-Backend

# Mentor and Student Assigning with Database

FrontEnd  https://mentor-student-4.onrender.com/Mentors

Agenda

----------------------------------------------------------------------------------------------

1.Write API to create Mentor

2.Write API to create Student

3.Write API to Assign a student to Mentor
   > Select one mentor and Add multiple Student
   
   > A student who has a mentor should not be shown in List

4.Write API to Assign or Change Mentor for particular Student
   > Select One Student and Assign one Mentor
   
5.Write API to show all students for a particular mentor

--------------------------------------------------------------------------------------------------

Base URL https://mentor-student-4.onrender.com

# Mentor Api's

<pre>GET          <a href="https://mentor-student-4.onrender.com/Mentors">/Mentors </a></pre>

<pre>POST         <a href="https://mentor-student-4.onrender.com/Mentors">/Mentors </a></pre>

<pre>GET by ID    <a href="https://mentor-student-4.onrender.com/Mentors/get-mentor/67b1c9bba089112c6aa6d138">/Mentors/get-mentor/:ID </a></pre>

# Student Api's

<pre>GET          <a href="https://mentor-student-4.onrender.com/Students"> /Students </a></pre>

<pre>POST         <a href="https://mentor-student-4.onrender.com/Students"> /Students </a></pre>

<b>To get list of students whose mentors weren't assigned </b>

<pre>GET          <a href="https://mentor-student-4.onrender.com/Students/no-mentors">/Students/no-mentors</a></pre>

<b>To assign or change Mentor for student</b>

<pre>PATCH        <a href="https://mentor-student-4.onrender.com/Students/assign-mentor/67b1d139beb99f2a6328bed1">/Students/assign-mentor/:student-id</a></pre>

<b> To assign mentors for multiple Students </b>

<pre>PATCH        <a href="https://mentor-student-4.onrender.com/Students/assign-mentor-students">/Students/assign-mentor-students</a></pre>

<b> To Assign or Change Mentor for particular student </b>
  > Pass Mentor ID in request Body

<pre>PATCH        <a href="https://mentor-student-4.onrender.com/Students/assign-mentor/67b1c9bba089112c6aa6d138">/Students/assign-mentor/:student-id</a> </pre>

<b> To Assign mentor for multiple students </b>
  > Pass Mentor ID and Student ID as list in body
 
<pre>PATCH        <a href="https://mentor-student-4.onrender.com/Students/assign-mentor-students">/Students/assign-mentor-students</a> </pre>

<b> To get all students of particular Mentor

<pre>GET          <a href="https://mentor-student-4.onrender.com/Students/mentor-students/67b1c9bba089112c6aa6d138">/Students/mentor-students/:mentor-id </a></pre>
 





