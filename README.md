# Ex03 Time Table
## Date:13/03/2024

## AIM
To write a html webpage page to display your slot timetable.

## ALGORITHM
### STEP 1
Create a Django-admin Interface.

### STEP 2
Create a static folder and inert HTML code.

### STEP 3
Create a simple table using ```<table>``` tag in html.

### STEP 4
Add header row using ```<th>``` tag.

### STEP 5
Add your timetable using ```<td>``` tag.

### STEP 6
Execute the program using runserver command.

## PROGRAM
```
<html>
<head>
<title>Timetable</title>
</head>
<body>
<center>
<img src="C:\Users\lathi\slot\Slot\Slot\static\logo.png" height="100" width="800">
</center>
<br>
<br>
<table border="4" cellspacing="4" cellpadding="5" align="center" height="50" width="200">
<caption><h2>Slot TimeTable-LATHIKA L J (212223220050)</h2></caption>
<tr>
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
<th bgcolor="yellow">Saturday</th>
</tr>
<tr>
<th bgcolor="yellow">8-10</th>
<td bgcolor="sky blue">Logic and Combinatorics</td>
<td  bgcolor="sky blue" align="center">Free Slot</td>
<td bgcolor="sky blue">Fundamentals of Web Appllication Development</td>
<td bgcolor="sky blue">Logic and Combinatorics</td>
<td  bgcolor="sky blue"colspan="2" align="center">Free Slot</td>
</tr>
<tr>
<th bgcolor="yellow">10-12</th>
<td bgcolor="sky blue">Basic Electrical,Electronis and Measurement</td>
<td bgcolor="sky blue">Fundamentals of Web Appllication Development</td>
<td bgcolor="sky blue">Physics For Quantum Computing</td>
<td bgcolor="sky blue">Computer Architecture<br>(11-12)</td>
<td bgcolor="sky blue">Python Programming</td>
<td bgcolor="sky blue">Operating System</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</td>
<td bgcolor="sky blue" colspan="6" align="center">Lunch Break</td>
</tr>
<th bgcolor="yellow">1-3</th>
<td bgcolor="sky blue">Fundamentals of Web Appllication Development</td>
<td bgcolor="sky blue" align="center">Free Slot</td>
<td bgcolor="sky blue">Creative Skill</td>
<td bgcolor="sky blue">Basic Electrical,Electronis and Measurement</td>
<td bgcolor="sky blue">Computer Architecture</td>
<td bgcolor="sky blue" align="center">Free Slot</td>
</tr>
<th bgcolor="yellow">3-4</th>
<td bgcolor="sky blue">Operating System</td>
<td bgcolor="sky blue">Physics For Quantum Computing
(3-4)</td>
<td bgcolor="sky blue"align="center">Free Slot</td>
<td bgcolor="sky blue">Python Programming</td>
<td bgcolor="sky blue" colspan="2" align="center">Free Slot</td>
</tr>
</table>
<br>
<br>
<table border="5" cellspacing="4" cellpadding="5" align="center" width="750">
<caption align="center"></caption>
<tr>
<th>S.NO</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td>1</td>
<td>19AI301</td>
<td>Python Programming</td>
</tr>
<tr>
<td>2</td>
<td>19AI414</td>
<td>Fundamentals of Web Appllication Development</td>
</tr>
<tr>
<td>3</td>
<td>19CS305</td>
<td>Computer Architecture</td>
</tr>
<tr>
<td>4</td>
<td>19CS405</td>
<td>Operating System</td>
</tr>
<tr>
<td>5</td>
<td>19EE305</td>
<td>Basic Electrical,Electronis and Measurement</td>
</tr>
<tr>
<td>6</td>
<td>19EY702</td>
<td>Creative Skill</td>
</tr>
<tr>
<td>7</td>
<td>19MA206</td>
<td>Logic and Combinatorics</td>
</tr>
<tr>
<td>7</td>
<td>19PH214</td>
<td>Pysics For Quantum Computing</td>
</tr>
```
## OUTPUT

![alt text](<Screenshot 2024-03-13 190605.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
