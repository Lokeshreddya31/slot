# Ex03 Time Table
## Date:31.10.2023

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
<<html>
<head>
<title>slot Timetable</title>
</head>
<body>
<center>
<img src="/static/logo.png" height="100" width="540">
</center>
<br>
<table align="center" wiidth="540" cellspacing="2" cellpadding="4" border="5" bgcolor="green">
<caption><b>SLOT TIME TABLE - LOKESH REDDY A (23007600)</b></caption>
<tr align="center">
<th bgcolor="orange">Day/Time</th>
<th bgcolor="orange">Monday</th>
<th bgcolor="orange">Tuesday</th>
<th bgcolor="orange">Wednesday</th>
<th bgcolor="orange">Thursday</th>
<th bgcolor="orange">Friday</th>
</tr>
<tr align="center">
<th bgcolor="orange">8-10</th>
<td >ENGINEERING DESIGN MODELLING</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>CALCULUS AND MATRIX ALGEBRA</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="orange">10-12</th>
<td >FREE SLOT</td>
<td>CALCULUS AND MATRIX ALGEBRA</td>
<td>ENGINEERING DESIGN MODELLING</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
</tr>
<tr>
<th bgcolor="orange">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="orange">1-3</th>
<td >PHYSICS FOR QUANTUM COMPUTING</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
<td>FUNDAMENTALS OF C PROGRAMMING</td>
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT</td>
</tr>
<tr align="center">
<th bgcolor="orange">3-5</th>
<td>FREE SLOT</td>
<td>SOFT SKILLS</td>
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
<td>FREE SLOT</td>
<td >PHYSICS FOR QUANTUM COMPUTING</td>
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="4" border="2">
<tr align="center">
<th>S. No.</th>
<th>Subject Code</th>
<th>Subject Name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI302</td>
<td>ENGINEERING DESIGN MODELLING (EDM)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI304</td>
<td>FUNDAMENTALS OF C PROGRAMMING (C PROGRAM)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19AI414</td>	
<td>FUNDAMENTALS OF WEB APPLICATION DEVELOPMENT (FWAD)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>	
<td>PRINCIPLES OF CHEMISTRY IN ENGINEERING (CHE)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA201</td>	
<td>CALCULUS AND MATRIX ALGEBRA (MAT)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19PH214</td>	
<td>PHYSICS FOR QUANTUM COMPUTING (PHY)</td>
</tr>
</table>
</body>
</html>
```


## OUTPUT
![Alt text](<Screenshot (13).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
