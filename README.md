# Ex03 Time Table
## Date:07/12/2024

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
<body>
    <center>
    <img src="logo.png">
    
    <br>
    <br>
    <br>
     <h2>SLOT TIME TABLE - KISHORE S M (24009451)</h2>
        <table border="2">
            <style>
                table{ 
                    width: 50%;
                    height: 30%;
                }
            </style>
        <TR>
            <th align="center" bgcolor="yellow">DAYS</th>
            <Th align="center" bgcolor="yellow">8-10</Th>
            <Th align="center" bgcolor="yellow"> 10-12</Th>
            <Th align="center" bgcolor="yellow">12-1</Th>
            <Th align="center" bgcolor="yellow">1-3</Th>
            <Th align="center" bgcolor="yellow">3-5</Th>
        </TR >
    <tr>
        <th align="center" bgcolor="yellow">MONDAY</th>
        <TD align="center" bgcolor="sky blue">---</TD>
        <TD  align="center" bgcolor="sky blue">FWAD</TD>
        <TD style="position: vertical;" rowspan="6" align="center" bgcolor="sky blue">LUNCH</TD>
        <TD  align="center" bgcolor="sky blue">PRINCIPLE OF CHEMISTRY</TD>
        <TD align="center" bgcolor="sky blue">---</TD>
    </tr>
    <TR>
       <th align="center"bgcolor="yellow" >TUESDAY</th>
       <td align="center" bgcolor="sky blue">---</td>
       <td align="center" bgcolor="sky blue">EDM</td>
       <td align="center" bgcolor="sky blue">DE</td>
       <td align="center" bgcolor="sky blue">---</td>
    </TR>
    <tr>
        <th align="center"bgcolor="yellow">WEDNESDAY</th>
        <td  align="center" bgcolor="sky blue">DE</td>
        <td align="center" bgcolor="sky blue">FWAD</td>
        <td align="center" bgcolor="sky blue">MENTOR MEET</td>
        <TD align="center" bgcolor="sky blue">---</TD>
    </tr>
    <tr>
        <th align="center"bgcolor="yellow">THURSDAY</th>
        <td  align="center" bgcolor="sky blue">---</td>
        <td align="center" bgcolor="sky blue"> PRINCIPLE OF CHEMISTRY</td>
        <td  align="center" bgcolor="sky blue">CARRIER SKILL</td>
        <td align="center" bgcolor="sky blue">---</td>
    </tr>
    <tr>
        <th align="center"bgcolor="yellow">FRIDAY</th>
        <TD align="center" bgcolor="sky blue">---</TD>
        <td align="center" bgcolor="sky blue">BEEE</td>
        <td align="center" bgcolor="sky blue">EDM</td>
        <td align="center" bgcolor="sky blue">---</td>
    </tr>
    <tr>
        <th align="center"bgcolor="yellow">SATURDAY</th>
        <td align="center" bgcolor="sky blue">---</td>
        <td align="center" bgcolor="sky blue">---</td>
        <td align="center" bgcolor="sky blue">FWAD</td>
        <td align="center" bgcolor="sky blue">BEEE</td>
    </tr>
    
    </table>
    <br>
    <br>
    <br>
    
    
        <table border="2" >
            <tr>
            <td>S.NO</td>
            <td>SUB CODE</td>
            <td>SUBJECT</td>
        </tr>
        <tr>
            <td>1</td>
            <td>19AI414</td> 
            <td>Fundamental of WEB DEVELOPEMENT</td>
        </tr>
        <tr>
            <td>2</td>
            <td>19CY205</td>
            <td>PRINCIPLE OF CHEMISTRY</td>
        </tr>
        <tr>
            <td>3</td>
            <td>19EE305</td>
            <td>Basic Electrical,Electronic and Mesurement Engineering</td>
        </tr>
        <tr>
            <td>4</td>
            <td>19EE404</td>
            <td>Digital Electronics</td>
        </tr>
        <tr>
            <td>5</td>
            <td>19EY708</td>
            <td>Career Development Skills</td>
        </tr>
        <tr>
            <td>6</td>
            <td>19AI302</td>
            <td>ENGINEERING DESIGN AND MODELLING</td>
        </tr>
        <tr>
            <td>7</td>
            <td>EC-M-SCOFT</td>
            <td>Mentor Meet</td>
        </tr>
       
        </table>
    </center>
    </body>
```

## OUTPUT
![alt text](<Screenshot 2024-12-07 131351.png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
