<html>
<head>
</head>
<body>
<form method="post">
Enter number:<input type="text" name="num"><br>
<input type="submit" name="submit"><br>
Factorial is:
</form>
<?php

function fact($f)
{
	if($f==0||$f==1)
	{
		return 1;
	}
	else{
		return $f*fact($f-1);
	}
}		
if(isset($_POST['submit']))
{
	$f=$_POST['num'];
	echo fact($f);

}
?>
</body>
</html>
