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
    </head>
    <body>
        <IMG src="C:\Users\B.NAVASRI\Downloads\saveetha logo.png" style="display:block; margin-left:auto;margin-right:auto;"alt="Image description" width="900">
        <h2 align="center">SLOT TIME TABLE- B.NAVASRI (AIDS-25006773)</h2>
        <table border="1" bgcolor=skyblue" align ="center" cellpadding="20">
            <tr>
                <th bgcolor="violet">DAYS/TIME</th>
                <th bgcolor="violet">MONDAY</th>
                <th bgcolor="violet">TUESDAY</th>
                <th bgcolor="violet">WEDNESDAY</th>
                <th bgcolor="violet" >THURSDAY</th>
                <th bgcolor="violet">FRIDAY</th>
                <th bgcolor="violet">SATURDAY</th>
            </tr>
            <tr>
                <td bgcolor="violet">8.00-10.00</td>
                <td></td>
                <td>FWAD</td>
                <td></td>
                <td></td>
                <td>Cprogram</td>
                <td>FWAD</td>
            </tr>
            <tr>
                <td bgcolor="violet">10.00-12.00</td>
                <td>FWAD</td>
                <td></td>
                <td></td>
                <td>Cprogram</td>
                <td></td>
                <td></td>
            </tr>
            <tr>
                <td bgcolor="violet">12.00-1.00</td>
                <td colspan="6"><B><center>LUNCH TIME</center></B></td>
            </tr>
            <tr>
                <td bgcolor="violet">1.00-3.00</td>
                <td>Cprogram</td>
                <td>FWAD</td>
                <td></td>
                <td></td>
                <td>FWAD</td>
                <td></td>
            </tr>
            <tr>
                <td bgcolor="violet">3.00-5.00</td>
                <td></td>
                <td></td>
                <td>Cprogram</td>
                <td>Cprogram</td>
                <td></td>
                <td></td>
            </tr>
        </table>
        <br>
        <table border="2" bgcolor="sky blue" align ="center" cellpadding="20" width="900">
            <tr>
                <th bgcolor="violet">S.NO</th>
                <th bgcolor="violet">COURSE CODE</th>
                <th bgcolor="violet">COURSE</th>
            </tr>
            <tr>
                <td bgcolor="violet">1</td>
                <td>19AI304</td>
                <td>FUNDAMENTAL OF C PROGRAMMING</td>
            </tr>
            <tr>
                <td bgcolor="violet">2</td>
                <td>19AI414</td>
                <td>FUNDAMENTAL OF WEB APPLICATION DEVELOPMENT</td>
            </tr>
        </table>
    </body>
</html>


```
# OUTPUT

![alt text](<Screenshot 2025-09-26 134121-1.png>)


# RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
