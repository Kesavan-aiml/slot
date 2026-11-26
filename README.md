# Ex02 Time Table
## Date:27/11/2026

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create an App inside the Django project.

### STEP 2
Create a static folder uder the created App and insert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html with the relevant attributes.

### STEP 4
Add rows using ```<tr>``` tag.

### STEP 5
Add your course schedule using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
~~~ 
<html>
<head>
    <title>Slot Timetable</title>
</head>
<body>

<center>
<img src="/static/logo.png" height="100" width="540">
</center>

<br>

<table align="center" width="900" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">

<caption><b>SLOT TIME TABLE - KESAVAN R (26018039)</b></caption>

<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">Saturday</th>
</tr>

<tr align="center">
<th bgcolor="yellow">8:00-9:30</th>
<td>PYTHON PROGRAMMING</td>
<td>PYTHON PROGRAMMING</td>
<td>PYTHON PROGRAMMING</td>
<td>DIGITAL ELECTRONICS</td>
<td>STATISTICS AND NUMERICAL METHODS</td>
<td>CYBER LAW AND COMPLIANCE</td>
</tr>

<tr align="center">
<th bgcolor="yellow">9:45-11:15</th>
<td>DIGITAL ELECTRONICS</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FREE SLOT</td>
<td>STATISTICS AND NUMERICAL METHODS</td>
<td>FREE SLOT</td>
<td>CAREER DEVELOPMENT SKILLS</td>
</tr>

<tr align="center">
<th bgcolor="yellow">11:30-12:15</th>
<td colspan="6">MENTOR MEET</td>
</tr>

<tr align="center">
<th bgcolor="yellow">12:15-1:15</th>
<td colspan="6">LUNCH</td>
</tr>

<tr align="center">
<th bgcolor="yellow">1:15-2:45</th>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FREE SLOT</td>
<td>CYBER LAW AND COMPLIANCE</td>
<td>FREE SLOT</td>
<td>BASIC ELECTRICAL, ELECTRONICS AND MEASUREMENT ENGINEERING</td>
</tr>

<tr align="center">
<th bgcolor="yellow">3:00-4:30</th>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>

</table>

<br><br>

<table align="center" width="750" cellspacing="2" cellpadding="4" border="2">

<caption><b>SUBJECT DETAILS</b></caption>

<tr align="center" bgcolor="yellow">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>

<tr>
<td>1.</td>
<td>19EE305</td>
<td>BASIC ELECTRICAL, ELECTRONICS AND MEASUREMENT ENGINEERING</td>
</tr>

<tr>
<td>2.</td>
<td>19CS418</td>
<td>CYBER LAW AND COMPLIANCE</td>
</tr>

<tr>
<td>3.</td>
<td>19EY708</td>
<td>CAREER DEVELOPMENT SKILLS</td>
</tr>

<tr>
<td>4.</td>
<td>19MA211</td>
<td>STATISTICS AND NUMERICAL METHODS</td>
</tr>

<tr>
<td>5.</td>
<td>19EE404</td>
<td>DIGITAL ELECTRONICS</td>
</tr>

<tr>
<td>6.</td>
<td>19AI301</td>
<td>PYTHON PROGRAMMING</td>
</tr>

<tr>
<td>7.</td>
<td>19AI414</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>

</table>

</body>
</html>
~~~

## OUTPUT
![alt text](<Screenshot 2026-11-26 142941.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
