# Ex03 Time Table
## Date:14.05.2023

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
<style>
table, th, td {
    border: 2px solid black;
    border-radius: 10px;
}
th, td {
    border-color: #FFFFFF;
    text-align: center;
    vertical-align: middle;
}
table {
    background-color: #800080;
}
th {
    background-color: #FF0000;
}
td {
    background-color: #96D4D4;
}
td:nth-child(1),
th:nth-child(1) {
    background-color: yellow;
}
</style>
</head>
<body>
<center>
<img src="/static/sec-logo-01as.png"heigth="100" widht="540">
</center>
<table style="width:80%">
    <tr>
        <th>TIME</th>
        <th>MON</th>
        <th>TU</th>
        <th>WED</th>
        <th>THUR</th>
        <th>FRI</th>
        <th>SAT</th>
    </tr>
    <tr>
        <td>8-10</td>
        <td>RPA</td>
        <td style="background-color: green;">FREE</td>
        <td>SE</td>
        <td>PQC</td>
        <td style="background-color: green;">FREE</td>
        <td style="background-color: green;">FREE</td>
    </tr>
    <tr>
        <td>10-12</td>
        <td>PYTHON</td>
        <td style="background-color: green;">FREE</td>
        <td>SE</td>
        <td>ADC</td>
        <td>WEB</td>
        <td>ADC</td>
    </tr>
    <tr>
        <td>1-3</td>
        <td>SE</td>
        <td>PQC</td>
        <td>MENTOR MEET</td>
        <td>RPA</td>
        <td>CA</td>
        <td>PYTHON</td>
    </tr>
    <tr>
        <td>3-5</td>
        <td>RA</td>
        <td style="background-color: green;">FREE</td>
        <td>CA</td>
        <td>WEB</td>
        <td style="background-color: green;">FREE</td>
        <td style="background-color: green;">FREE</td>
    </tr>
</table>

</body>
</html>

```

## OUTPUT
![image](https://github.com/user-attachments/assets/4da0293c-86c0-498e-8f6a-70bfb9e2e754)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
