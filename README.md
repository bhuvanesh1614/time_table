# Ex03 Time Table
# Date:1-10-2025
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```{% load static %}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Slot Time Table - Bhuvanesh S</title>
  <style>
        body{
            background-image: linear-gradient(905deg,aqua,red,yellow)
        }
    </style>
    <style>
        table{
            background-image: linear-gradient(15.875deg,blue,grey,pink,green)
        }
    </style>
    <style>
        caption{
            background-image: linear-gradient(15.875deg,rgb(14, 128, 128),rgb(112, 102, 102),rgb(141, 42, 42),rgb(247, 247, 9),rgb(67, 246, 67))
        }
    </style>
  
  

</head>
<body>

  <center>
    <img src= "{% static "sec.png" %}" height="100" width="540">
  </center>

  <!-- Timetable -->
  <table align="center" width="100" height="25" cellspacing="1" cellpading="1" border="1" bgcolor="black">
    <caption align="center"><b>SLOT TIME TABLE - BHUVANESH S (25017596)</b>
</caption>
    <tr align="center">
      <th bgcolor="yellow">Day/time</th>
      <th bgcolor="yellow">8-10</th>
      <th bgcolor="yellow">10-12</th>
      <th bgcolor="yellow">12-1</th>
      <th bgcolor="yellow">1-3</th>
      <th bgcolor="yellow">3-5</th>
    </tr>
     <tr align="center">
      <th bgcolor="yellow">monday</th>
      <th bgcolor="aqua">FWAD</th>
      <th bgcolor="aqua">Python</th>
      <th  rowspan="6" bgcolor="aqua"></th>
      <th bgcolor="aqua">Freeslot</th>
      <th bgcolor="aqua">Freeslot</th>
    </tr>
         <tr align="center">
      <th bgcolor="yellow">Tuesday</th>
      <th bgcolor="aqua">Freeslot</th>
      <th bgcolor="aqua">Datascience</th>
      
      <th bgcolor="aqua">Freeslot</th>
      <th bgcolor="aqua">Datascience</th>
    </tr>
         <tr align="center">
      <th bgcolor="yellow">Wednesday</th>
      <th bgcolor="aqua">FWAD</th>
      <th bgcolor="aqua">FWAD</th>
      
      <th bgcolor="aqua">Freeslot</th>
      <th bgcolor="aqua">Python</th>
    </tr>
         <tr align="center">
      <th bgcolor="yellow">Thursday</th>
      <th bgcolor="aqua">Python</th>
      <th bgcolor="aqua">Python</th>
      
      <th bgcolor="aqua">Freeslot</th>
      <th bgcolor="aqua">Freeslot</th>
    </tr>
         <tr align="center">
      <th bgcolor="yellow">Friday</th>
      <th bgcolor="aqua">Freeslot</th>
      <th bgcolor="aqua">FWAD</th>
      
      <th bgcolor="aqua">Datascience</th>
      <th bgcolor="aqua">Python</th>
    </tr>
         <tr align="center">
      <th bgcolor="yellow">Saturday</th>
      <th bgcolor="aqua">Datascience</th>
      <th bgcolor="aqua">FWAD</th>
      
      <th bgcolor="aqua">Freeslot</th>
      <th bgcolor="aqua">Datascience</th><br>
    </tr>
    <table align="center" width="500" cellspacing="2" cellpading="4" border="2">
      <tr align="center"><br>
        <th>S.NO</th> 
        <th>Subject Code</th>
        <th>Subject name</th>
      </tr>
      <tr align="center">
        <td>1.</td>
        <td>19I1414</td>
        <td>Fundamental of web application development</td>

      </tr>
      <tr align="center">
        <td>2.</td>
        <td>19I301</td>
        <td>Python progamming</td>

      </tr>
      <tr align="center">
        <td>3.</td>
        <td>19I403</td>
        <td>Introduction to Data science</td>

      </tr>

    </table>
  

  </table>

</body>
</html>
```
# OUTPUT
![alt text](<../../time_table/Screenshot 2025-10-01 132319.png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
