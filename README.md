# Ex03 Time Table
## Date: 24.02.2024

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
<title> My Time Table </title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
<table border="3" cellspacing="6" cellpading="6">
<caption>SLOT TIMETABLE - NIVETHA.S(212223040137)</caption>
<tr>
<th bgcolor="blue">Day/Time</th>
<th bgcolor="blue">Monday</th>
<th bgcolor="blue">Tuesday</th>
<th bgcolor="blue">Wednesday</th>
<th bgcolor="blue">Thursday</th>
<th bgcolor="blue">Friday</th>
</tr>
<tr>0 
<td bgcolor="blue">8-10</td>
<td rowspan="2" bgcolor="mulberry">BEEE</td>
<td bgcolor="mulberry">FREE</td>
<td bgcolor="mulberry">FREE</td>
<td bgcolor="mulberry">FREE</td>
<td bgcolor="mulberry">web</td>
</tr>
<tr>
<td bgcolor="blue">10-12</td>
<td bgcolor="lavender">FREE</td>
<td bgcolor="lavender">CN</td>
<td bgcolor="lavender">C</td>
<td bgcolor="lavender">FREE</td>
</tr>
<tr>
<td bgcolor="mulberry">12-1</td>
<td colspan="5" bgcolor="lavender">------------BREAK TIME------------</td>
</tr>
<tr>
<td bgcolor="blue">1-3</td>
<td bgcolor="lavender">MATHS</td>
<td bgcolor="lavender">wEB</td>
<td bgcolor="lavender">FREE</td>
<td bgcolor="lavender">WEB</td>
<td rowspan="2" bgcolor="lavender">SS</td>
</tr>
<tr>
<td bgcolor="mulberry">3-5</td>
<td bgcolor="lavender">MATH</td>
<td colspan="2" bgcolor="lavender">free</td>
<td bgcolor="lavender">SS</td>
</tr>
</table>
<table border="2" cellspacing="5" cellpading="5">
<tr>
<th>S.NO</th>
<th>SUBJECT CODE</th>
<th>SUBJECT NAME</th>
</tr>
<tr>
<td>1.</td>
<td>19EE305</td>
<td>Basic Electrical, Electronics and Measurement Engineering</td>
</tr>
<tr>
<td>2.</td>
<td>19CS405</td>
<td>Operating System</td>
</tr>
<tr>
<td>3.</td>
<td>19CS406</td>
<td>Computer Networks</td>
</tr>
<tr>
<td>4.</td>
<td>19MA206</td>
<td>Logic And Combnatrics</td>
<tr>
<td>5.</td>
<td>19AI414</td>
<td>Fundamentals of Web Application Development(WEB)</td>
</tr>
<tr>
<td>6.</td>
<td>19CY205</td>
<td>Principles of Chemistry in Engineering</td>
</tr>
<tr>
<td>7.</td>
<td></td>
<td></td>
</tr>
</table>
</center>
</body>
</html>
```

## OUTPUT
![alt text](<time slot web.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
