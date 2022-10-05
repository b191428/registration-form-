<html>
<head>
<title>  Placement Registration </title>
<center>
<font color="green" font size="10"> Placement Registration <br> Form </font>
</head>
<br>
<body>
<form action="placementregistration.php" method="POST">
<table border="1" bgcolor="#ccffff" >
<td>
<br>
<input type="radio" id="mr" name="gender" value="Mr">Mr
<input type="radio" id="mrs" name="gender" value="Mrs">Mrs
<input type="radio" id="ms" name="gender" value="Ms">Ms
<br>
Student ID : <input type="text" name="student id" placeholder="Student ID"><br>
First Name : <input type="text" name="first name" placeholder="First Name"><br>
Last Name : <input type="text" name="last name" placeholder="Last Name"><br>
User name : <input type="text" name="user name" placeholder="user name"><br>
Password : <input type="password" name="password" placeholder="password"><br>
Address :        <textarea name="address" rows="4" cols="50">
</textarea><br>
city : <input type="text" name="city"><br>
State : <select name="state" >
<option name="Telangana" > Telangana </option>
<option name="Kerala" > Kerala </option>
<option name="Karnataka" > Karnataka </option>
</select><br>
Pincode : <input type="text" name="pincode"><br>
Upload photo : <input type="file" name="photo">
<br>
Email : <input type="text" name="email"><br>
Mobile No. : <input type="text" name="mobile no" value="+91"><br>
Languages known<br> 
<input type="checkbox" name="languages"> English <br>
<input type="checkbox" name="languages"> Telugu <br>
<input type="checkbox" name="languages"> Hindi <br>
Additional info :        <textarea name="add info" rows="4" cols="50">
</textarea><br>
<input type="checkbox" name="languages"> Accepting the terms & conditions <br>
<input type="submit" name="sign up" value="SUBMIT">
<input type="reset" name="sign up" value="RESET">
</table>
</form>
</body>
</html>
