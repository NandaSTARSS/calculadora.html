# calculadora.html
<!DOCTYPE html>
<head>
    <title>calculadora</title>
</head>
<body bgcolor="#0000003" text="gold"><form name="calculator"><input type="button" 
    value="1" onclick="document.calculator.ans.value+=1">
    <input type="button" value="2" onclick="document.ans.value=2">
    <input type="button" value="3" onclick="document.ans.value=3">
    <input type="button" value="4" onclick="document.ans.value=4">
    <input type="button" value="5" onclick="document.ans.value=5">
    <input type="button" value="6" onclick="document.ans.value=6">
    <input type="button" value="-" onclick="document.ans.value=-">
    <input type="button" value="7" onclick="document.ans.value=7">
    <input type="button" value="8" onclick="document.ans.value=8">
    <input type="button" value="9" onclick="document.ans.value=9">
    <input type="button" value="*" onclick="document.ans.value=*">
    <input type="button" value="/" onclick="document.ans.value=/">
    <input type="button" value="0" onclick="document.ans.value=0">
    <onClick="document.calculator.ans.value+="0">
    <input type="reset" value="Reset"><input type="button"value="="
    onClick="document.calculator.ans.value=eval(document.calculator.ans.value)">Solution is
     <input type="textfield" name="ans" value=""></form>
     </body>
     </html>
     
