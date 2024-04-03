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
html code:
```
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-QWTKZyjpPEjISv5WaRU9OFeRpok6YctnYmDr5pNlyT2bRjXh0JMhjY6hW+ALEwIH" crossorigin="anonymous">
</head>


<body>
    <center>
        <img src="/static/logo.png" style="height: 150px;" alt=""><br>
        SLOT TIME TABLE -SETHUKKARASI C (212223230201)
        <table class="table table-bordered">
            <tr>
                <th style="background-color:fuchsia">Day/Time</th>
                <th style="background-color:fuchsia">Monday</th>
                <th style="background-color:fuchsia">Tuesday</th>
                <th style="background-color:fuchsia">Wednesday</th>
                <th style="background-color:fuchsia">Thursday</th>
                <th style="background-color:fuchsia">Friday</th>
                <th style="background-color:fuchsia">Saturday</th>
            </tr>
            <tr>
                <th style="background-color:fuchsia">8-10</th>
                <td style="background-color: yellow;">C# & ARVR</td>
                <td style="background-color: yellow;">BEEE</td>
                <td style="background-color: yellow;">FWAD</td>
                <td style="background-color: yellow;">C# & ARVR</td>
                <td style="background-color: yellow;">BEEE</td>
                <td style="background-color: yellow;">FWAD</td>
            </tr>
            <tr>
                <th style="background-color:fuchsia">10-12</th>
                <td style="background-color: aqua;text-align: center;">FREE SLOT</td>
                <td style="background-color: yellow;">SM & CO</td>
                <td style="background-color: yellow;">PHY</td>
                <td style="background-color: aqua;text-align: center;">FREE SLOT</td>
                <td style="background-color: yellow;">DE</td>
                <td style="background-color: yellow;">C# & ARVR</td>
            </tr>
            <tr>
                <th style="background-color:fuchsia">12-01</th>
                <td colspan="6" style="background-color: chartreuse;text-align: center;">LUNCH</td>
            </tr>
            <tr>
                <th style="background-color:fuchsia">01-03</th>
                <td style="background-color: yellow;">CHEM</td>
                <td style="background-color: yellow;">DE</td>
                <td style="background-color: yellow;">CSC</td>
                <td style="background-color: yellow;">SM & CO</td>
                <td style="background-color: aqua;text-align: center;" colspan="2">FREE SLOTS</td>
            </tr>
            <tr>
                <th style="background-color:fuchsia">03-05</th>
                <td style="background-color: yellow;">FWAD</td>
                <td style="background-color: yellow;">PHY</td>
                <td style="background-color: aqua;text-align: center;" colspan="3">FREE SLOTS</td>
                <td style="background-color: yellow;">CHEM</td>
            </tr>
        </table>
        <table class="table table-bordered">
            <tr>
                <th style="background-color: red;">S.No</th>
                <th style="background-color: red;">Subject Code</th>
                <th style="background-color: red;">Subject Name</th>
            </tr>
            <tr>
                <td style="background-color: greenyellow;">1.</td>
                <td style="background-color: greenyellow;">19AI308C</td>
                <td style="background-color: greenyellow;">C Sharp and Virtual Reality(C# & ARVR)</td>
            </tr>
            <tr>
                <td style="background-color: greenyellow;">2.</td>
                <td style="background-color: greenyellow;">19CY205</td>
                <td style="background-color: greenyellow;">Principles of Chemistry in Engineering(CHEM)</td>
            </tr>
            <tr>
                <td style="background-color: greenyellow;">3.</td>
                <td style="background-color: greenyellow;">19AI414</td>
                <td style="background-color: greenyellow;">Fundamentals of Web Application Development(FWAD)</td>
            </tr>
            <tr>
                <td style="background-color: greenyellow;">4.</td>
                <td style="background-color: greenyellow;">19EE305</td>
                <td style="background-color: greenyellow;">Basic Electrical,Electronics and Measurement Engineering(BEEE)</td>
            </tr>
            <tr>
                <td style="background-color: greenyellow;">5.</td>
                <td style="background-color: greenyellow;">19EE404</td>
                <td style="background-color: greenyellow;">Digital Electronics(DE)</td>
            </tr>
            <tr>
                <td style="background-color: greenyellow;">6.</td>
                <td style="background-color: greenyellow;">19MS155</td>
                <td style="background-color: greenyellow;">Stock Market and Company Operations(SM & CO)</td>
            </tr>
            <tr>
                <td style="background-color: greenyellow;">7.</td>
                <td style="background-color: greenyellow;">19PH214</td>
                <td style="background-color: greenyellow;">Physics for Quantum Computing(PHY)</td>
            </tr>
            <tr>
                <td style="background-color: greenyellow;">8.</td>
                <td style="background-color: greenyellow;">19EY702</td>
                <td style="background-color: greenyellow;">Creative Skills for Communication(CSC)</td>
            </tr>
        </table>
    </center>
</body>

</html>
```

## OUTPUT
![output](<Screenshot 2024-04-04 002109.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
