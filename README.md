# Ex03 Time Table
## Date:22-12-25

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
<!DOCTYPE html>
<html>
<head>
    <title>Slot Time Table - KIRTHIKA P</title>
</head>
<body>
    <IMG SRC="logo.png"HEIGHT="150"WIDTH="500"BORDER=6>
    <h2>Saveetha Engineering College</h2>
    <h3>SLOT TIME TABLE -KIRTHIKA P</h3>

    <table border="1">
        <tr BGCOLOR="YELLOW">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
	    <th>Saturday</th>e
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">8-10</td>
            <td>FREE SLOT</td>
            <td>C PROGRAM</td>
            <td>ENG</td>
            <td>ENG</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">10-12</td>
            <td>C PROGRAM</td>
            <td>FREE SLOT</td>
            <td>WEB</td>
            <td>FREE SLOT</td>
            <td>WEB</td>
            <td>WEB</td>

        </tr>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">12-1</td>
            <td COLSPAN=6 ALIGN="CENTER">LUNCH</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">1-3</td>
            <td>WEB</td>
            <td>ENG</td>
            <td>MENTOR MEET</td>
            <td>FREE SLOT</td>
            <td>WEB</td>
            <td>ENG</td>
        </tr>
        <tr BGCOLOR="CYAN">
            <td BGCOLOR="YELLOW">3-5</td>
            <td>FREE SLOT</td>
            <td>C PROGRAM</td>
            <td>C PROGRAM</td>
            <td>C PROGRAM</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
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
            <td>Fundamentals of Web Application Development (WEB)</td>
        </tr>
        <tr>
            <td>2.</td>
            <td>19EN101</td>
            <td>COMMUNICATIVE ENGLISH (ENG)</td>
        </tr>
        <tr>
            <td>3.</td>
            <td>19AI304</td>
            <td>C PROGRAM (C PROGRAM)</td>
        </tr>
      </table>
</body>
</html>



## OUTPUT
![WhatsApp Image 2025-12-24 at 10 38 36 AM](https://github.com/user-attachments/assets/11e3229a-1653-4c10-bbc3-7aeff962640c)


INCLUDE YOUR OUTPUT IMAGE

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
