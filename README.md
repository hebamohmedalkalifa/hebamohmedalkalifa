<?php 
session_start();
 ?>
 <!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>in</title>
	
</head>
<body>
<?php 
if($_POST["name"]=="admin" && $_POST["pass"]=="123"){

	$_SESSION['me']='YES';
	echo "you have login successfully";
	echo "<br>";
	echo '<a href="http://localhost/phptota/hello.php">'."Go to edit page";
}
else{
session_start();
$_SESSION['me']='NO';
echo "error";
 
}

?>
</body>
</html>
