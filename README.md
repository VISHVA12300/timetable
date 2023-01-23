# Experiment_Time_Table

## AIM
To Write a html webpage page to display your timetable.

# ALGORITHM
### STEP 1
create a simple table using table tag

### STEP 2
Add header row using th tag

### STEP 3
Add your timetable

### STEP 4
Execute the program

# CODE
```
<!DOCTYPE html>
<html lang="en">
<head>
<title>Slot Timetable</title>
</head>
<body>
<center>
<img src="/static/images/logo.png" height="100" width="540">
</center>
<br>
<table align="center" width="540" cellspacing="2" cellpadding="4" border="5" bgcolor="cyan">
<caption><b>SLOT TIME TABLE - ARJUN.M(22008750)</b></caption>
<tr align="center">
<th bgcolor="yellow">Day/Time</th>
<th bgcolor="yellow">Monday</th>
<th bgcolor="yellow">Tuesday</th>
<th bgcolor="yellow">Wednesday</th>
<th bgcolor="yellow">Thursday</th>
<th bgcolor="yellow">Friday</th>
</tr>
<tr align="center">
<th bgcolor="yellow">8-10</th>
<td>C</td>
<td>MAT</td>
<td>MAT</td>
<td>PYTHON</td>
<td>FREE SLOT</td>
</tr>
<tr align="center">
<th bgcolor="yellow">10-12</th>
<td>WEB</td>
<td> FREE SLOT</td>
<td>CHM</td>
<td>FREE SLOT</td>
<td>FREE SLOT</td>
</tr>
<tr>
<th bgcolor="yellow">12-1</th>
<td colspan="5" align="center">L U N C H</td>
</tr>
<tr align="center">
<th bgcolor="yellow">1-3</th>
<td>SOFT SKILL</td>
<td>WEB</td>
<td>WEB</td>
<td>CHM</td>
<td>PYTHON</td>
</tr>
<tr align="center">
<th bgcolor="yellow">3-5</th>
<td> PHY </td>
<td> C </td>
<td>FREE SLOT</td>
<td>PHY</td>
<td>FREE SLOT</td>
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
<td align="center">19AI414</td>
<td>Fundamentals of Web Application Development (WEB)</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19EY701</td>
<td>Soft skills(SOFT SKILL)</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS301P1</td>
<td>Problem Solving and Python Programming P1(PYTHON)</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CY205</td>
<td>Principles of Chemistry in Engineering (CHM)</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19MA201</td>
<td>Calculus and Matrix Algebra(MAT)</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19CS302P1</td>
<td>Programming in C P1(C)</td>
</tr>
<tr>
<td align="center">7.</td>
<td align="center">19PH205</td>
<td>Computational Physics(PHY)</td>
</tr>
</table>
</body>
</html>
```

# OUPUT
![OUTPUT](mypro/static/images/out.png)

# HTML VALIDATOR
![OUTPUT](mypro/static/images/valid.png)

# RESULT
The program for creating slot time table is completed successfully