<html>
	<head>
		<meta charset="utf-8">
	    <meta name="viewport" content="width=device-width, initial-scale=1">
	   <!-- <link rel="stylesheet" href="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/css/bootstrap.min.css">
	    <link rel="stylesheet" type="text/css" href="mystyles.css" media="screen" />-->
	    <link rel="stylesheet" type="text/css" href="main.css" media="screen" />
	    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.2/jquery.min.js"></script>
	    <script src="http://maxcdn.bootstrapcdn.com/bootstrap/3.3.6/js/bootstrap.min.js"></script>
	    <script type="text/javascript"> 
			function search(){
				alert();
				var val= document.getElementById('search_element').value;
				if(val!=''){
					document.getElementById('search_frm').submit();
				}
			}
		 </script>
	</head>
	<body>
		<div id="main">
		<div id ="google">
		<h1 id="heading"> <font color='blue'>G</font><font color='red'>o</font><font color='yellow'>o</font><font color='blue'>g</font><font color='green'>l</font><font color='red'>e</font></h1>

		</div>
		<div id ="text">
		<form name="search_frm" id="search_frm" action="search1.php" method="POST">
		<div id="box">
		<input type="text" name="search_element" value="" id="search_element"><br />
		</div>
		<div id="b">			
		<input type="button" value="search" id="search_button" onclick="search();">
		</div>
		</form>
		</div>
		</div>
	</body>
</html>
