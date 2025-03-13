# Ex03 Time Table
## Date:  13.03.2025

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
    <title>College Timetable</title>
<style>
    body{
        font-family: Arial,sans-serif;
        text-align: center;
    }
    table{
        width: 80%;
        margin: auto;
        border-collapse: collapse;
    }
    th,td{
        border: 1px solid black;
        padding: 10px;
        text-align: center;
    }
    th{
        background-color: yellow;
    }
    .highlight{
        background-color: lightblue;
    }
</style>
</head>
<body>
    <img src="Saveetha.png" height="200px" width="1200px" alt="something went wrong"></br>
    <h3>Slot Time Table - G Ramanujam (24000309)</h3>
    <table>
        <tr>
            <th>Day/Time</th>
            <th>Monday</th>
            <th>Tuesday</th>
            <th>Wednesday</th>
            <th>Thursday</th>
            <th>Friday</th>
        </tr>
        <tr class="highlight">
            <td>8-10</td>
            <td>FREE SLOT</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>PHY</td>
            <td>CHE</td>
        </tr>
        <tr class="highlight">
            <td>10-12</td>
            <td>GER</td>
            <td>FREE SLOT</td>
            <td>FWAD</td>
            <td>FWAD</td>
            <td>PHY</td>
        </tr>
        <tr class="highlight">
            <td>12-1</td>
            <td colspan="5">LUNCH</td>
        </tr>
        <tr class="highlight">
            <td>1-3</td>
            <td>FREE SLOT</td>
            <td>MAT</td>
            <td>MAT</td>
            <td>SS</td>
            <td>CHE</td>
        </tr>
        <tr class="highlight">
            <td>3-5</td>
            <td>FREE SLOT</td>
            <td>GER</td>
            <td>CHE</td>
            <td>FWAD</td>
            <td>FWAD</td>
        </tr>
    </table>


    <h3>Subjects</h3>
    <table>
        <tr>
            <td>S. No.</td>
            <td>Subject Code</td>
            <td>Subject Name</td>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td>
            <td>Fundamentals of Web Application Development (FWAD)</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19EN612</td>
            <td>German Basic (GER)</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19PH206</td>
            <td>Physics for Information Technology (PHY)</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19CY205</td>
            <td>Principles of Chemistry in Engineering (CHE)</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19MA201</td>
            <td>Calculus and Matrix Alegbra (MAT)</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19EY701</td>
            <td>Soft Skills (SS)</td>
        </tr>
    </table>
</body>
</html>
```

## OUTPUT

![image](https://github.com/user-attachments/assets/fec1d96f-f1a3-4366-b401-79b8c5ea5a7f)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
