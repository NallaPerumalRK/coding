coding
======

this contains PHP codings
<html>
<head>

<body>


<h2>New Users Sign up here </h2>

<form method="post" action="k.php">
Name: <input type="text" name="name" value="">

<br><br>
E-mail: <input type="text" name="email" value="">
<br><br>
Re-enter E-mail: <input type="text" name="email" value="">


<br><br>
password: <input type="text" name="Password" value="*">
<br><br>
Re-enter password: <input type="text" name="Password" value="*">


<br><br>
Gender:
<input type="radio" name="gender"  value="female">Female
<input type="radio" name="gender"  value="male">Male

<br><br>
<input type="submit" name="submit"  value="Submit" onclick="k.php">
</form>


</body>
</html>








<html>
<body>

Welcome<?php  echo $_POST["name"]; ?><br>
Your email address Has: <?php echo $_POST["email"]; ?>

</body>
</html>











