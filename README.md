# Ex02 Time Table
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
    <title>Time Table</title>
</head>

<body>

    
    
    <center>
        <img src="C:\Users\acer\Desktop\exp web\ex 01 orm\slot_timetable\slot\table\static\logo.png " width="60%">
        </center>    
    <h2 align="center">TIME TABLE</h2>

    <table border="1" cellpadding="15" cellspacing="0" align="center">    
        <tr>
            <th bgcolor="cyan">DAY</th>
            <th bgcolor="peachpuff">8 - 10</th>
            <th bgcolor="peachpuff">10 - 12</th>
            <th bgcolor="peachpuff">1 - 3</th>
            <th bgcolor="peachpuff">3 - 5</th>
        </tr>

        <tr>
            <th bgcolor="lightgray">MONDAY</th>
            <td bgcolor="lavender">FREE SLOT</td>
            <td bgcolor="lightblue">Operating System</td>
            <td bgcolor="lavender">FREE SLOT</td>
            <td bgcolor="lavender">FREE SLOT</td>
        </tr>

        <tr>
            <th bgcolor="lightgray">TUESDAY</th>
            <td bgcolor="cyan">FREE SLOT</td>
            <td bgcolor="lightgreen">Fundamental of Web Application</td>
            <td bgcolor="lightgreen">Fundamental of Web Application</td>
            <td bgcolor="lavender">FREE SLOT</td>
        </tr>

        <tr>
            <th bgcolor="lightgray">WEDNESDAY</th>
            <td bgcolor="lightblue">Operating System</td>
            <td bgcolor="lightgreen">Fundamental of Web Application</td>
            <td bgcolor="lavender">FREE SLOT</td>
            <td bgcolor="lightpink">Fundamental of C Programming</td>
        </tr>

        <tr>
            <th bgcolor="lightgray">THURSDAY</th>
            <td bgcolor="lightblue">Operating System</td>
            <td bgcolor="lavender">FREE SLOT</td>
            <td bgcolor="lightpink">Fundamental of C Programming</td>
            <td bgcolor="lightpink">Fundamental of C Programming</td>
        </tr>

        <tr>
            <th bgcolor="lightgray">FRIDAY</th>
            <td bgcolor="lightblue">Operating System</td>
            <td bgcolor="lightgreen">Fundamental of Web Application</td>
            <td bgcolor="lightpink">Fundamental of C Programming</td>
            <td bgcolor="lavender">FREE SLOT</td>
        </tr>

        <tr>
            <th bgcolor="lightgray" >SATURDAY</th>
            <td bgcolor="lavender">FREE SLOT</td>
            <td bgcolor="lavender" >FREE SLOT</td>
            <td bgcolor="lavender">FREE SLOT</td>
            <td bgcolor="lavender">FREE SLOT</td>
        </tr>

    </table>

    <br><br>

    <table border="1" cellpadding="10" align="center">

        <tr>
            <th>S.No</th>
            <th>Subject</th>
        </tr>

        <tr>
            <td>1</td>
            <td>Operating System</td>
        </tr>

        <tr>
            <td>2</td>
            <td>Fundamental of Web Application</td>
        </tr>

        <tr>
            <td>3</td>
            <td>Fundamental of C Programming</td>
        </tr>

    </table>

</body>

</html>
```

## OUTPUT
![alt text](image-1.png)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
