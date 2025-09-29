# Ex03 Time Table
# Date:29.09.2025
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
<html>
<head>
    <title>Microsoft</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: white;
        }

        img {
            display: block;
            margin-left:auto;
            margin-right: auto;
            width: 900px;
        }

        h2 {
            text-align: center;
            color:black;
            margin-bottom: 30px;
        }

        table {
            border-collapse: collapse;
            margin: 0 auto 40px auto;
            width: 50%;
            padding:20px
        }


        th, td {
            border: 1px solid black;
            padding: 15px;
            text-align: center;
        }

        th {
            background-color: violet;
            color: white;
        }

        td {
            background-color: skyblue;
        }

        .lunch-row td {
            font-weight: bold;
            background-color:pink;
        }
    </style>
</head>
<body>
    <img src="c:\Users\B.NAVASRI\Downloads\saveetha logo.png" alt="Image description">
    <h2>SLOT TIME TABLE - B.NAVASRI (AIDS-25006773)</h2>

    <table>
        <tr>
            <th>DAYS/TIME</th>
            <th>MONDAY</th>
            <th>TUESDAY</th>
            <th>WEDNESDAY</th>
            <th>THURSDAY</th>
            <th>FRIDAY</th>
            <th>SATURDAY</th>
        </tr>
        <tr>
            <td>8.00-10.00</td>
            <td></td>
            <td>FWAD</td>
            <td></td>
            <td></td>
            <td>Cprogram</td>
            <td>FWAD</td>
        </tr>
        <tr>
            <td>10.00-12.00</td>
            <td>FWAD</td>
            <td></td>
            <td></td>
            <td>Cprogram</td>
            <td></td>
            <td></td>
        </tr>
        <tr class="lunch-row">
            <td>12.00-1.00</td>
            <td colspan="6">LUNCH TIME</td>
        </tr>
        <tr>
            <td>1.00-3.00</td>
            <td>Cprogram</td>
            <td>FWAD</td>
            <td></td>
            <td></td>
            <td>FWAD</td>
            <td></td>
        </tr>
        <tr>
            <td>3.00-5.00</td>
            <td></td>
            <td></td>
            <td>Cprogram</td>
            <td>Cprogram</td>
            <td></td>
            <td></td>
        </tr>
    </table>

    <table>
        <tr>
            <th>S.NO</th>
            <th>COURSE CODE</th>
            <th>COURSE</th>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI304</td>
            <td>FUNDAMENTAL OF C PROGRAMMING</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19AI414</td>
            <td>FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT</td>
        </tr>
    </table>
</body>
</html>

```
# OUTPUT

<img width="1915" height="1130" alt="Screenshot 2025-09-29 175919" src="https://github.com/user-attachments/assets/87bafc65-3419-4216-a1c7-cd1604297e1d" />


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
