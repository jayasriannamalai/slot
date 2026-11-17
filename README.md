# Ex04 Time Table
## Date:20-11-2026

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
        <title>SCHEDULE</title>
    </head>
    <body bgcolor="skyblue">
        <center>
            <h2 align="center"><img src="logo.png" width="400" height="100" align="center"></h2
            <br>
        </center>
        <center>
            <h3>SCHEDULE:JAYASRI A(26014582)</h3>
        </center>
        <table border="2" bgcolor="pink" align="center">
            <tr bgcolor="lightgreen">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
                <th>Saturday</th>
            </tr>
            <tr>
                <th bgcolor="orange">8-9.30</th>
                <th>MAT</th>
                <th>FREE</th>
                <th>MAT</th>
                <th>PYT</th>
                <th>DE</th>
                <th>FREE</th>
            </tr>
            <tr>
                <th bgcolor="orange">9.45-11.15</th>
                <th>PYT</th>
                <th>WEB</th>
                <th colspan="2">FREE</th>
                <th>WEB</th>
                <th>CE</th>
            </tr>
            <tr>
                <th bgcolor="orange">11.30-12.15</th>
                <th colspan="6" align="center">MENTOR MEET</th>
            </tr>
            <tr>
                <th bgcolor="orange">1.15-2.45</th>
                <th>WEB</th>
                <th>DE</th>
                <th>FREE</th>
                <th>CE</th>
                <th colspan="2">FREE</th>

            </tr>
            <tr>
                <th bgcolor="orange">3.00-4.30</th>
                <th>FREE</th>
                <th>PYT</th>
                <th>CDS</th>
                <th>BEEE</th>
                <th colspan="2">FREE</th>
            </tr>
        </table>
        <br><br>


        <table border="3" align="center" bgcolor="gray">
            <tr bgcolor="red">
                <th>S. No.</th>
                <th>Subject Code</th>
                <th align="center">Subject Name</th>

            </tr>
            <tr>
                <th>1.</th>
                <th>19MA211</th>
                <th>Statistics and Numerical Problems(MAT)</th>

            </tr>
            <tr>
                <th>2.</th>
                <th>19AI414</th>
                <th>Fundamentals of Web Application Development(WEB)</th>

            </tr>
            <tr>
                <th>3.</th>
                <th>19EE404</th>
                <th>Digital Electronics(DE)</th>
                
            </tr>
            <tr>
                <th>4.</th>
                <th>19AI301</th>
                <th>Python programming(PYT)</th>

            </tr>
            <tr>
                <th>5.</th>
                <th>19EN101 </th>
                <th>Communicative English(CE)</th>
            </tr>
             <tr>
                <th>6.</th>
                <th>19EY708</th>
                <th>Career Development Skills(CDS)</th>
             </tr>
             <tr>
                <th>7.</th>
                <th>19EE305</th>
                <th>Basic Electrical, Electronics and Measurement Engineering(BEEE)</th>
             </tr>
        </table>

        

    </body>
</html>
```

## OUTPUT
![alt text](<Screenshot (37).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
