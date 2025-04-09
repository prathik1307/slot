# Ex03 Time Table
## Date:09/04/25

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
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - PRATHIKSHA.R 212224040244</title>
</head>
<body>
    <IMG SRC="logo.png"HEIGHT="100"WIDTH="750"BORDER=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE - PRATHIKSHA.R</h3>

    <table border="1">
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td>8-10</td>
            <td></td>
            <td></td>
            <td></td>
            <td>ML</td>
            <td>C programming</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td>10-12</td>
            <td>FWAD</td>
            <td>EVS</td>
            <td>FWAD</td>
            <td>PROBABILITY</td>
            <td>REASONING </td>
        </tr>
         <tr>
            <td>12-1</td>
            <td colspan="5">LUNCH</td>
        </tr>

        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=5 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td>FREE SLOT</td>
            <td>MAT</td>
            <td>MAT</td>
            <td></td>
            <td></td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
             <td>1-3</td>
            <td></td>
            <td>C programming</td>
            <td></td>
            <td>PHY</td>
            <td>PHY</td>
        </tr>
    </table>

    <h3>Subjects</h3>
    <table border="1">
        <tr>
            <th>S. No.</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr>
            <td>1.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19CY806</td>
            <td>Environmental science and sustainablity (EVS)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19PH206</td>
            <td>Physics for quantum computing (PHY)</td>
        </tr>
        <tr>
            <td>4.</td>
            <td>19AI101</td>
            <td>Fundamentals of C programming(C programming)</td>
        </tr>
        <tr>
            <td>5.</td>
            <td>19MA201</td>
            <td>Probability queuing maths (PROBABILITY)</td>
        </tr>
        <tr>
            <td>6.</td>
            <td>19EY701</td>
            <td>REASONING ABILITY (REASONING)</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT
![Screenshot 2025-04-09 112038](https://github.com/user-attachments/assets/db2d68e4-dc66-444c-b051-0f05f389b65c)



## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
