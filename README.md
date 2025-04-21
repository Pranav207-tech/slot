# Ex03 Time Table
## Name: Pranav K
## Ref no: 212224040240
## Date: 19.04.25

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
		<title>
			Software Companies
		</title>


	</head>
	<body align="center" bgcolor="skyblue" >
		 <center>
            <img src= "logo.png" height="100" width="800">
         </center>
		<table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="yellow">
			<caption>SLOT TIME TABLE- Pranav K (212224040240) </caption>
            <br>
			<tr>
				<th bgcolor="lightgray"> Day/Time </th>
				<th bgcolor="lightgray"> Monday </th>
				<th bgcolor="lightgray"> Tuesday </th>
                <th bgcolor="lightgray"> Wednesday </th>
                <th bgcolor="lightgray"> Thursday </th>
                <th bgcolor="lightgray"> Friday </th>
                <th bgcolor="lightgray"> Saturday </th>
			</tr>
			<tr>
				<th bgcolor="sky blue"> 8-10 </td>
                <td> Free SLOT </td>
                <td> UI/UX DESIGN </td>
                <td> FREE SLOT </td>
                <td> UI/UX DESIGN </td>
                <td> FREE SLOT </td>
                <td> FREE SLOT </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 10-12 </th>
				<td> SOFTWARE ENGINEERING </td>
                <td> CALCULUS </td>
                <td> REASONING </td>
                <td> FWAD </td>
                <td> PYTHON </td>
                <td> SOFTWARE ENGINEERING </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 12-1 </th>
                <td colspan="6" align="center"> LUNCH </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 1-3 </th>
                <td> PYTHON </td>
                <td> FWAD </td>
                <td> MENTOR MEET </td>
                <td> STATISTICS </td>
                <td> CALCULUS </td>
                <td> STATISTICS </td>
			</tr>
			<tr>
                <th bgcolor="sky blue"> 3-5 </td>
                <td> FREE SLOT </td>
                <td> FREE SLOT </td>
                <td> FREE SLOT </td>
                <td> FREE SLOT </td>
                <td> FREE SLOT </td>
                <td> FREE SLOT </td>
			</tr>
			</table>
            <br>
            <table align="center" border="5" cellspacing="6" cellpadding="5" bgcolor="pink">
                <br>
                <tr>
                    <th align="center"> S.No </th>
                    <th align="center"> Subject Code </th>
                    <th align="center"> Subject Name </th>
                </tr>
                <tr>
                    <th> 1. </td>
                    <td align="center"> 19MA305 </td>
                    <td align="center"> Statistics and numerical method </td>
                </tr>
                <tr>
                    <th align="center"> 2. </td>
                    <td align="center"> 19AI414 </td>
                    <td align="center"> Fundamentals of web applications (FWAD) </td>
                </tr>
                <tr>
                    <th align="center"> 3. </td>
                    <td align="center"> 19AI304 </td>
                    <td align="center"> Python programming </td>
                </tr>
                <tr>
                    <th align="center"> 4. </td>
                    <td align="center"> 19MA101 </td>
                    <td align="center"> Calculus and matrix algebra </td>
                </tr>
                <tr>
                    <th align="center"> 5. </td>
                    <td align="center"> 19AI214 </td>
                    <td align="center"> Software engineering</td>
                </tr>
                <tr>
                    <th align="center"> 6. </td>
                    <td align="center"> 19CS542 </td>
                    <td align="center"> UI/UX DESIGNING </td>
                </tr>
                <tr>
                    <th align="center"> 7. </td>
                    <td align="center"> 19EY702 </td>
                    <td align="center"> Reasoning ability</td>
                </tr>
                
                </table>
	</body>

</html>

```

## OUTPUT

![alt text](<Screenshot (21).png>)

## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
