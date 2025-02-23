# Ex03 Time Table
## Date:18-03-2024

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
    <title>Semester Timetable</title>
</head>
<body align="center">
    <img width="700" height="100" align="center" src="/static/logo.png">
    <br>
    <table align ="center" border="5" cellspacing="3" bgcolor="yellow">
        <caption><h3>SLOT TIME TABLE - SANTHOSH T(212223220100)</h3></caption>
        <tr bgcolor="orange" align="center">
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr align="center">
            <td bgcolor="orange" >8-10</td>
            <td>ML</td>
            <td>MAT</td>
            <td>FWAD</td>
            <td colspan="2" align="center">FREE SLOT </td>
        </tr>
        <tr align="center">
            <td bgcolor="orange" >10-12</td>
            <td>ROB</td>
            <td>FWAD</td>
            <td>ML</td>
            <td>CS</td>
            <td>C PROG.</td>
        </tr>
        <tr align="center">
            <td bgcolor="orange">12-1</td>
            <td colspan="5" align="center">LUNCH</td>
        </tr>
        <tr align="center">
            <td bgcolor="orange">1-3</td>
            <td>FWAD</td>
            <td>PHY</td>
            <td>PHY(1HR)</td>
            <td>MAT</td>
            <td>CN</td>
        </tr>
        <tr align="center">
            <td bgcolor="orange">3-5</td>
            <td>C PROG.</td>
            <td>FREE SLOT</td>
            <td>CN</td>
            <td>FREE SLOT</td>
            <td>ROB</td>
        </tr>
    </table>
    <br>
    <table align ="center" border="3" cellspacing="2">
        <tr align="center" bgcolor="silver">
            <th>S.No</th>
            <th>Subject Code</th>
            <th>Subject Name</th>
        </tr>
        <tr align="center">
            <td>1.</td>
            <td >19AI304</td>
            <td>Fundamentals of C Programming(C PROG.)</td>
        </tr>
        <tr align="center">
            <td>2.</td>
            <td>19AI410</td>
            <td>Introducation to Machine Learning(ML)</td>
        </tr>
        <tr align="center">
            <td>3.</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development(FWAD)</td>
        </tr>
        <tr align="center">
            <td>4.</td>
            <td align="center">19AI533</td>
            <td>Introduction To Robotics(ROB)</td>
        </tr>
        <tr align="center">
            <td>5.</td>
            <td align="center">19CS406</td>
            <td>Computer Networks(CN)</td>
        </tr>
        <tr align="center">
            <td>6.</td>
            <td align="center">19EY702</td>
            <td>Creative Skills For Communication(CS)</td>
        </tr>
        <tr align="center">
            <td>7.</td>
            <td align="center">19MA212</td>
            <td>Algebra and Number Theory(MAT)</td>
        </tr>
        <tr align="center">
           <td>8.</td>
           <td align="center">19PH214</td>
           <td>Physics for Quantum Computing(PHY)</td>    
        </tr>
    </table>
</body>
</html>
```

## OUTPUT
![alt text](image.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
