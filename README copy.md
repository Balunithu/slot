# Ex03 Time Table
## Date:

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
        <title>Slot Timetable</title>
    </head>
    <body>
        <center>
            <img src="/static/logo.png" height="100"width="540">
        </center>
        <br>
        <table align="center" width="540">
            <caption><b>SLOT TIMETABLE NITHYA SHREE (212223220071)</b></caption>
            <tr align="center">
                <th bgcolor="pink">Day/Time</th>
                <th bgcolor="pink">Monday</th>
                <th bgcolor="pink">Tuesday</th>
                <th bgcolor="pink">Wednesday</th>
                <th bgcolor="pink">Thursday</th>
                <th bgcolor="pink">Friday</th>
            </tr>
            <tr align="center">
                <th bgcolor="green">8-10</th>
                <td bgcolor="pink">FREE SLOT</td>
                <td bgcolor="pink">CALCULUS AND MATRIX ALGEBRA</td>
                <td bgcolor="pink">PHYSICS FOR INFORMATION TECHNOLOGY</td>
                <td bgcolor="pink">GERMAN BASIC</td>
                <td bgcolor="pink">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="pink">10-12</th>
                <td bgcolor="green">FREE SLOT</td>
                <td bgcolor="green">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="green">FREE SLOT</td>
                <td bgcolor="green">PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
                <td bgcolor="green">PHYSICS FOR INFORMATION TECHNOLOGY</td>
            </tr>
            <tr align="centre">
                <th bgcolor="pink">12-1</th>
                <td bgcolor="green">LUNCH</td>
                <td bgcolor="green">MENTOR MEET</td>
                <td bgcolor="green">LUNCH</td>
                <td bgcolor="green">LUNCH</td>
                <td bgcolor="green">LUNCH</td>
            </tr>
            <tr align="centre">
                <th bgcolor="pink">1-3</th>
                <td bgcolor="green">SOFT SKILLS</td>
                <td bgcolor="green">FREE SLOT</td>
                <td bgcolor="green">FREE SLOT</td>
                <td bgcolor="green">CALCULUS AND MATRIX ALGEBRA</td>
                <td bgcolor="green">FREE SLOT</td>
            </tr>
            <tr align="centre">
                <th bgcolor="pink">3-5</th>
                <td bgcolor="green">PRINCIPLES OF CHEMISTRY IN ENGINEERING</td>
                <td bgcolor="green">FREE SLOT</td>
                <td bgcolor="green">FUNDAMENTALS OF WEB APPLICATION DEVLOPMENT</td>
                <td bgcolor="green">GERMAN BASIC</td>
                <td bgcolor="green">FREE SLOT</td>
            </tr>
        </table>
        <br>
        <table align="center" cellspacing="2" cellpadding="4" border="2">
            <tr align="center">
                <th>S.No.</th>
                <th>Subject Code</th>
                <th>Subject Name</th>
            </tr> 
            <tr>
                <td align="center">1.</td>
                <td align="center">19AI414</td>
                <td>Fundamentals of Web Application Development (FWAD)</td>
            </tr>
            <tr>
                <td align="center">2.</td>
                <td align="center">19EN612</td>
                <td>GERMAN BASIC (GER)</td>
            </tr>
            <tr>
                <td align="center">3.</td>
                <td align="center">19PH206</td>
                <td>PHYSICS FOR INFORMATION TECHNOLOGY (PHY)</td>
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
                <td align="center">19EY701</td>
                <td>SOFT SKILLS (SS)</td>
            </tr>
        </table>
    </body>
</html>
```

## OUTPUT


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
