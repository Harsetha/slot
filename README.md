# Ex03 Time Table
## Date:28.03.2024

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
<title>slot timetable</title>
</head>
<body>
<center> 
<img src="/static/logo.png" height="100" width="500">
<br>
<table align="center" width="500" cellsapacing="2" cellpadding="5" border="5">
<caption><b>SLOT TIME TABLE - HARSETHA J (21223220032)</b></caption>
<tr align="center">
<th bgcolor="blue">DAY/TIME</th>
<th bgcolor="blue">MONDAY</th>
<th bgcolor="blue">TUESDAY</th>
<th bgcolor="blue">WEDNESDAY</th>
<th bgcolor="blue">THURSDAY</th>
<th bgcolor="blue">FRIDAY</th>
<th bgcolor="blue">SATURDAY</th>
</tr>
<tr align="center">
<th bgcolor="blue">8-10</th>
<td bgcolor="pink">Fundamentel of Web Application Development</td>
<td bgcolor="pink">digital electronics</td>
<td bgcolor="pink">chemistry</td>
<td bgcolor="pink">digital electronics</td>
<td bgcolor="yellow">Free slot</td>
<td bgcolor="pink">creative skill</td>
</tr>
<tr>
<tr align="center">
<th bgcolor="blue">10-12</th>
<td bgcolor="pink">operating system</td>
<td bgcolor="pink">computer network</td>
<td bgcolor="yellow">free slot</td>
<td bgcolor="pink">computer network</td>
<td bgcolor="pink">Python programming</td>   
<td bgcolor="pink">Algebra number theory</td> 
</tr>
<tr align="center">
<th bgcolor="blue">1-3</th>
<td bgcolor="pink">algebra number theory</td>
<td bgcolor="pink">chemistry</td>
<td bgcolor="pink">operating system</td>
<td bgcolor="pink">Fundamentel of Web Application Development</td>
<td bgcolor="pink">Fundamentel of Web Application Development</td>   
<td bgcolor="pink">Algebra number theory</td> 
</tr>
<tr align="center">
<th bgcolor="blue">3-5</th>
<td bgcolor="yellow">free slot</td>
<td bgcolor="yellow">free slot</td>
<td bgcolor="yellow">free slot</td>
<td bgcolor="pink">python programming</td>
<td bgcolor="yellow">free slot</td>   
<td bgcolor="yellow">free slot</td> 
</tr>
</table>
<br>
<table align="center" cellspacing="2" cellpadding="5" border="5">
<tr align="center">
<th>s. No.</th>
<th>subject Code</th>
<th>subject name</th>
</tr>
<tr>
<td align="center">1.</td>
<td align="center">19AI414</td>
<td>Fundamental of web application development</td>
</tr>
<tr>
<td align="center">2.</td>
<td align="center">19AI301</td>
<td>Python programming</td>
</tr>
<tr>
<td align="center">3.</td>
<td align="center">19CS405</td>
<td>Operating system</td>
</tr>
<tr>
<td align="center">4.</td>
<td align="center">19CS406</td>
<td>Computer network</td>
</tr>
<tr>
<td align="center">5.</td>
<td align="center">19CY205</td>
<td>Principles of chemistry in engineering</td>
</tr>
<tr>
<td align="center">6.</td>
<td align="center">19EE404</td>
<td>Digital electronics</td>
<tr>
<td align="center">7.</td>
<td align="center">19EY702</td>
<td>Creative skill for communication</td>
</tr>
<tr>
<td align="center">8.</td>
<td align="center">19MA212</td>
<td>Algebra and number theory</td>
</tr>
</table>
</body>
</html>
```

## OUTPUT
![alt text](<slot 1.png>)

![alt text](slot2.png)


## RESULT
The program for creating slot timetable using basic HTML tags is executed successfully.
