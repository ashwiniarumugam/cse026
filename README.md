# cse026<html>
<head>
<title>your scores</title>
</head>
<body>
<?php
echo "marks :";
$_var=$_POST['sc'];
echo "$_var";
echo "<br />";
echo "grade:";
if ($_var>'90') 
	echo "A";
	else if ($_var>'70')
		echo "B"; 
			else if ($_var>'60')
			echo "c"; 
else 
		echo "D"; ?>
</body>
</html>
