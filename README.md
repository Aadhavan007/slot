# Ex02 Time Table
## Date: 30.11.2025

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
```
<html>
 <head>
  <title> Slot Timetable </title>
 </head>
 <body>
    <center>
        <img src=" " height="100" width="500">
    </center>
  <h1 align="center">SLOT TIME TABLE - AADHAVAN NAGARAJAN M (25011373)</h1>
  <table border="4" cellpadding="15" cellspacing="3" align="center">
  <tr>
   <th bgcolor="brown">Day/Time</th>
   <th bgcolor="brown">Monday</th>
   <th bgcolor="brown">Tuesday</th>
   <th bgcolor="brown">Wednesday</th>
   <th bgcolor="brown">Thursday</th>
   <th bgcolor="brown">Friday</th>
   <th bgcolor="brown">Saturday</th>
  </tr>
  <tr>
    <th bgcolor="brown">8-10</th>
    <td bgcolor="lightgreen">FOC</td>
    <td bgcolor="lightgreen">FREE SLOT</td>
    <td bgcolor="lightgreen">FWAD</td>
    <td bgcolor="lightgreen">FOCP</td>
    <td bgcolor="lightgreen">FREE SLOT</td>
    <td bgcolor="lightgreen">FWAD</td>
 </tr>
 <tr>
   <th bgcolor="brown">10-12</th>
   <td bgcolor="lightgreen" colspan="3" align="center">FWAD</td>
   <td bgcolor="lightgreen">FOCP</td>
   <td bgcolor="lightgreen">FOC</td>
   <td bgcolor="lightgreen">FREE SLOT</td>
 </tr>
 <tr>
   <th bgcolor="brown">12-1</th>
   <td colspan="6" align="center">LUNCH</td>
 </tr>
 <tr>
   <th bgcolor="brown">1-3</th>
   <td bgcolor="lightgreen">FOCP</td>
   <td bgcolor="lightgreen">FOC</td>
   <td bgcolor="lightgreen" colspan="3" align="center">FREE SLOT</td>
   <td bgcolor="lightgreen">FOC</td>
 </tr>
 <tr>
   <th bgcolor="brown">3-5</th>
   <td bgcolor="lightgreen" colspan="2" align="center">FREE SLOT</td>
   <td bgcolor="lightgreen">FOCP</td>
   <td bgcolor="lightgreen" colspan="2" align="center">FREE SLOT</td>
   <td bgcolor="lightgreen">FOCP</td>
 </tr>
 </table>
<br>
<br>
 <table cell border="2" cell padding="10" align="center">
 <tr>
  <th>S.No.</th>
  <th>Subject Code</th>
  <th>Subject Name</th>
 </tr>
 <tr>
  <td>1.</td>
  <td>19AI414</td>
  <td>Fundamentals of Web Application Development</td>
 </tr>
 <tr>
  <td>2.</td>
  <td>19AI304</td>
  <td>Fundamentals Of C Programming</td>
 </tr>
 <tr>
  <td>3.</td>
  <td>19CS547</td>
  <td>Fundamentals Of Cryptocurrency</td>
 </tr>
 </table>
</body>
</html>
```


## OUTPUT

![alt text](<Screenshot (67).png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
