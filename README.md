# Ex03 Time Table
## Date:24.9.2025

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
        <title>
            My Timetable
        </title>
    </head>
    <body>
        <img src="/static/logo.png" width="530" align="center">
        <h3>SLOT TIMETABLE-SUMAIYA(25016731)</h3>
        <table border="6" bgcolor="cyan" >
            <tr bgcolor="yellow">
                <th>Day/time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">8-10</th>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>FREE</td>
                <td>C</td>
                <td>FWAD</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">10-12</th>
                <td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">
                    12-1
                </th>
                <td colspan="6">
                    LUNCH
                </td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">1-3</th>
                <td>FWAD</td>
                <td>FWAD</td>
                <td>MENTOR-MEET</td>
                <td>C</td>
                <td>FREE</td>
            </tr>
            <tr align="center">
                <th bgcolor="yellow">3-5</th>
                <td>C</td>
                <td>C</td>
                <td>FREE</td>
                <td>FREE</td>
                <td>C</td>
            </tr>
        </table>
        <br>
        <table border="1">
            <tr>
                <th>S.No</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr>
            <tr>
                <td>1.</td>
                <td>19AI414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td>2.</td>
                <td>19AI304</td>
                <td>Fundamentals of C Programming(C)</td>
            </tr>
        </table>
    </body>
</html>

```

## OUTPUT
![alt text](<Screenshot 2025-09-24 144440.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
