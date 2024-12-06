# Ex03 Time Table
# Date:18/11/2024
# AIM
To write a html webpage page to display your slot timetable.

# ALGORITHM
## STEP 1
Create a Django-admin Interface.

## STEP 2
Create a static folder and inert HTML code.

## STEP 3
Create a simple table using `<table>` tag in html.

## STEP 4
Add header row using `<th>` tag.

## STEP 5
Add your timetable using `<td>` tag.

## STEP 6
Execute the program using runserver command.

# PROGRAM
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TIME TABLE</title>
    <center>
    <img src="/static/logo.png" width="1500" height="200">
    </center>
    <title>TIME TABLE</title>
    <center>
    <h3> SLOT TIME TABLE - Sanjana.K.L(24900199)</h3>    
    </center>
    </head>    
    <style>
        body{
            font-family:
    Arial,sans-serif;
          margin:0
          padding:0
            background-colour: antiquewhite;
            border;2px solid 
        }
        table{
            border-collapse: collapse;
            margin: 20px  auto;
            background-color: rgb(112, 78, 224);
                 solid
            box-shadow: 0;
        }
        td{
            border: 20px
        solid
            padding:10px;
            text-align:
        }
    </style>
<table border="1" width="50%" height="25%" style="text-align: center;">
    <tr  style="background-color:rgb(112, 78, 224);text-align: center">
    <th>Day/Time</th>
    <th> 8-10 </th>
    <th> 10-12 </th>
    <th> 12-1 </th>
    <th> 1-2 </th>
    <th> 3-5 </th>
    </tr>
    <tr> 
        <th style="background-color: rgb(112, 78, 224);"></thstyle>Monday</th>
        <td style="background-color:rgb(228, 30, 156);">Free slot</td> 
        <td style="background-color:rgb(228, 30, 156);"> Web</td>
        <td style="background-color:rgb(228, 30, 156);"> Lunch </td>
        <td style="background-color:rgb(228, 30, 156);"> French</td>
        <td style="background-color:rgb(228, 30, 156);"> Free slot </td>
    </tr>
    <tr>
        <th style="background-color: rgb(112, 78, 224);"></thstyle>Tuesday</th>
        <td style="background-color:rgb(228, 30, 156);"> Free slot </td>
        <td style="background-color:rgb(228, 30, 156);"> Physics </td>
        <td style="background-color:rgb(228, 30, 156) ;"> Lunch </td>
        <td style="background-color:rgb(228, 30, 156);"> Python </td>
        <td style="background-color:rgb(228, 30, 156);"> Free slot </td>
    </tr>
    <tr>
        <th style="background-color: rgb(112, 78, 224);"></thstyle>Wesdnesday</th>
        <td style="background-color:rgb(228, 30, 156);"> Python </td>
        <td style="background-color:rgb(228, 30, 156);"> Free slot </td>
        <td style="background-color:rgb(228, 30, 156);"> Lunch </td>
        <td style="background-color:rgb(228, 30, 156);"> Free slot </td>
        <td style="background-color:rgb(228, 30, 156);"> Chemistry </td>
    </tr>  
    <tr>
        <th style="background-color: rgb(112, 78, 224);"></thstyle>Thrusady</th>
        <td style="background-color:rgb(228, 30, 156);"> French </td>
        <td style="background-color:rgb(228, 30, 156);"> Python </td>
        <td style="background-color:rgb(228, 30, 156);"> Lunch </td>
        <td style="background-color:rgb(228, 30, 156);"> Web </td>
        <td style="background-color:rgb(228, 30, 156);"> Free slot </td>
    </tr>
    <tr>
        <th style="background-color: rgb(112, 78, 224);"></thstyle>Friday</th>
        <td style="background-color:rgb(228, 30, 156);"> Physics </td>
        <td style="background-color:rgb(228, 30, 156);"> Free slot </td>
        <td style="background-color: rgb(228, 30, 156);"> Lunch </td>
        <td style="background-color: rgb(228, 30, 156);"> Yoga </td>
        <td style="background-color: rgb(228, 30, 156);"> Free slot </td>
    </tr>
    <tr>
        <th style="background-color: rgb(112, 78, 224);text-align: center;"></thstyle>Saturday</th>
        <td style="background-color: rgb(228, 30, 156);text-align: center"></thstyle>French</td>
        <td style="background-color: rgb(228, 30, 156);text-align: center"></thstyle>PytHon</td>
        <td style="background-color: rgb(228, 30, 156);text-align: center"></thstyle>Lunch</td>
        <td style="background-color: rgb(228, 30, 156);text-align: center"></thstyle>Chemistry</td>
        <td style="background-color: rgb(228, 30, 156);text-align: center"></thstyle>Web</td>
    </tr>    
</table>
</head>
<body>
<table border="4px" width="300" height="400" style="background-color:burlywood; text-align: center;">
        <tr>
            <th> S.NO </th>
            <th> Subject Name </th>
            <th> Subject Code </th>
        </tr>
        <tr>
            <th> 1. </th>
            <td> Fundamentals of web applications </td>
            <td> 19AI401 </td>
        </tr>
        <tr>
            <th> 2. </th>
            <td> Maths for AI/python/linear algebra </td>
            <td> 19MA301 </td>
        </tr>
        <tr>
            <th> 3. </th>
            <td> Principal of chemistry </td>
            <td> 19CY205 </td>
        </tr>
        <tr>
            <th> 4. </th>
            <td> French</td> </td>
            <td> SH5601 </td>
        </tr>
        <tr>
            <th> 5. </th>
            <td> Yoga</td>
            <td> SH5616 </td>
         </tr>   
         <tr>
            <th> 5. </th>
            <td> Physics for Quantum Computing</td>
            <td> SH3214 </td>
         </tr>   
</table>
</body>
</html>
```
# OUTPUT
![alt text](<Screenshot (49).png>)
# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
