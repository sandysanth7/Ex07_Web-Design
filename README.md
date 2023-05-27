# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```
<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>
```
## OUTPUT

![5ecac695-cfa7-4f19-9a78-77109b12e268](https://github.com/sandysanth7/Ex07_Web-Design/assets/127816678/0dae012e-ba1f-4ec0-877d-487407464fc3)
![009f83ff-f2d7-4b70-b1ba-069e453ad96c](https://github.com/sandysanth7/Ex07_Web-Design/assets/127816678/95b99505-a7ef-41f8-b268-9262512c92c0)

## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
