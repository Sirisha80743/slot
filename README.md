# Ex03 Time Table

## Date: 13-03-2025

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
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    <center>
    <img src="saveetha logo.png" height="100px" width="580px" alt="Something went wrong">
    <h3>SLOT TIME TABLE - P SIRISHA (212224040321)</h3>
    <form>
        <table border="4" width="540" cellspacing="2" cellpadding="4">
            <tr bgcolor="yellow" style="text-align: center;">
                <th>Day/Time</th>
                <th>Monday</th>
                <th>Tuesday</th>
                <th>Wednesday</th>
                <th>Thursday</th>
                <th>Friday</th>
            </tr>
            <tr>
                <th bgcolor="yellow" style="text-align: center;">8-10</th>
                <td colspan="3" bgcolor="cyan" style="text-align: center;">FREE SLOT</td>
                <td bgcolor="cyan" style="text-align: center;">PHY</td>
                <td bgcolor="cyan" style="text-align: center;">CHE</td>
            </tr>
            <tr>
                <th  bgcolor="yellow">10-12</th>
                <td bgcolor="cyan" style="text-align: center;">GER</td>
                <td bgcolor="cyan" style="text-align: center;">FREE SLOT</td>
                <td bgcolor="cyan" style="text-align: center;">FWAD</td>
                <td bgcolor="cyan" style="text-align: center;">FWAD</td>
                <td bgcolor="cyan" style="text-align: center;">PHY</td>
            </tr>
            <tr>
                <th  bgcolor="yellow" style="text-align: center;">12-1</th>
                <td colspan="5" bgcolor="cyan" style="text-align: center;">LUNCH</td>
            </tr>
            <tr>
                <th  bgcolor="yellow" style="text-align: center;">1-3</th>
                <td colspan="2" bgcolor="cyan" style="text-align: center;">FREE SLOT</td>
                <td bgcolor="cyan" style="text-align: center;">MAT</td>
                <td bgcolor="cyan" style="text-align: center;">MAT</td>
                <td bgcolor="cyan" style="text-align: center;">SS</td>
            </tr>
            <tr>
                <th bgcolor="yellow" style="text-align: center;">3-5</th>
                <td colspan="2" bgcolor="cyan" style="text-align: center;">FREE SLOT</td>
                <td bgcolor="cyan" style="text-align: center;">GER</td>
                <td bgcolor="cyan" style="text-align: center;">CHE</td>
                <td bgcolor="cyan" style="text-align: center;">FWAD</td>
            </tr>
        </table>
        <br>
        <table border="3" width="540" cellspacing="2" cellpadding="4">
            <tr>
                <th>S.NO.</th>
                <th>Subject Code</th>
                <th style="text-align: center;">Subject Name</th>
            </tr>
            <tr>
                <td style="text-align: center;">1.</td>
                <td style="text-align: center;">19AI414</td>
                <td>Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td style="text-align: center;">2.</td>
                <td style="text-align: center;">19EN612</td>
                <td>German Basic(GER)</td>
            </tr>
            <tr>
                <td style="text-align: center;">3.</td>
                <td style="text-align: center;">19PH206</td>
                <td>Physics for Information Technology(PHY)</td>
            </tr>
            <tr>
                <td style="text-align: center;">4.</td>
                <td style="text-align: center;">19CY205</td>
                <td>Principles of Chemistry in Engineering(CHE)</td>
            </tr>
            <tr>
                <td style="text-align: center;">5.</td>
                <td style="text-align: center;">19MA201</td>
                <td>Calculus and MatriX Algebra(MAT)</td>
            </tr>
            <tr>
                <td style="text-align: center;">6.</td>
                <td style="text-align: center;">19EY701</td>
                <td>Soft Skills(SS)</td>
            </tr>
        </table></center>
    </form>
</body>
</html>
```

## OUTPUT

![Web EX-3](https://github.com/user-attachments/assets/78c3f0f4-8c83-4b9e-b2f1-c1d83494c9cf)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
