# Ex03 Time Table
## Date:14/05/2025

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
    <title>Weekly Class Planner</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        }

        body {
            background-color: #f5f7fa;
            color: #2c3e50;
        }

        .Navbar h1 {
            background-color: #34495e;
            color: #ecf0f1;
            text-align: center;
            padding: 15px;
            font-size: 22px;
            letter-spacing: 1px;
        }

        .tab {
            padding: 25px;
        }

        .tab table {
            width: 100%;
            border-collapse: separate;
            border-spacing: 0 10px;
        }

        .tab th, .tab td {
            padding: 14px;
            text-align: center;
            background-color: #ffffff;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
        }

        .tab th {
            background-color: #2ecc71;
            color: white;
            text-transform: uppercase;
        }

        .subject {
            padding: 30px;
        }

        .subject h2 {
            margin-bottom: 15px;
            color: #2c3e50;
        }

        .subject table {
            width: 100%;
            border-collapse: collapse;
        }

        .subject th, .subject td {
            padding: 12px;
            text-align: left;
            border-bottom: 1px solid #ccc;
        }

        .subject th {
            background-color: #3498db;
            color: white;
        }
    </style>
</head>
<body>
    <img src="logo.png" width="100%" height="125px" alt="College Logo">
    <div class="Navbar">
        <h1>Saveetha Engineering College (Autonomous) — TNEA CODE: 1216</h1>
    </div>

    <div class="tab">
        <table>
            <tr>
                <th>Day / Time</th><th>8–10 AM</th><th>10–12 PM</th><th>12–1 PM</th><th>1–3 PM</th><th>3–5 PM</th>
            </tr>
            <tr>
                <td>Monday</td><td>Open Slot</td><td>Machine Learning Basics</td><td>Lunch</td><td>Chemistry</td><td>C Programming</td>
            </tr>
            <tr>
                <td>Tuesday</td><td>English Skills</td><td>Web Tech</td><td>Lunch</td><td>Microcontroller Lab</td><td>AI Concepts</td>
            </tr>
            <tr>
                <td>Wednesday</td><td>Chemistry</td><td>AI Concepts</td><td>Lunch</td><td>Ethics & Values</td><td>Microcontroller Lab</td>
            </tr>
            <tr>
                <td>Thursday</td><td>Web Development</td><td>Data Structures</td><td>Lunch</td><td>ML Basics</td><td>Open Slot</td>
            </tr>
            <tr>
                <td>Friday</td><td>Web Development</td><td>C Programming</td><td>Lunch</td><td>Free Slot</td><td>Free Slot</td>
            </tr>
            <tr>
                <td>Saturday</td><td>Data Structures</td><td>English Skills</td><td>Lunch</td><td>Free Slot</td><td>Free Slot</td>
            </tr>
        </table>
    </div>

    <div class="subject">
        <h2>Subject Information</h2>
        <table>
            <tr>
                <th>S.No</th>
                <th>Code</th>
                <th>Subject Title</th>
            </tr>
            <tr><td>1</td><td>19AI414</td><td>Web Application Development Fundamentals</td></tr>
            <tr><td>2</td><td>19AI405</td><td>Artificial Intelligence Foundations</td></tr>
            <tr><td>3</td><td>19AI304</td><td>Programming in C Language</td></tr>
            <tr><td>4</td><td>19EN101</td><td>English Proficiency</td></tr>
            <tr><td>5</td><td>19AI403</td><td>Introduction to Data Structures</td></tr>
            <tr><td>6</td><td>19AI410</td><td>Machine Learning Fundamentals</td></tr>
            <tr><td>7</td><td>19CY205</td><td>Chemical Principles</td></tr>
            <tr><td>8</td><td>19HS801</td><td>Ethical and Professional Values</td></tr>
        </table>
    </div>
</body>
</html>

```


## OUTPUT
![alt text](<Screenshot 2025-05-16 105005.png>)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
