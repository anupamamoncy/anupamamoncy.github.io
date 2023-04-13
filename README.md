# anupamamoncy.github.io
<!DOCTYPE html>
<html>
<head>
	<title>Hospital Website</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<style>
		/* CSS styles for the website */
		body {
			font-family: Arial, sans-serif;
			margin: 0;
			padding: 0;
		}
		header {
			background-color: #0071c5;
			color: white;
			padding: 20px;
		}
		h1 {
			margin: 0;
		}
		nav {
			background-color: #4d4d4d;
			color: white;
			padding: 10px;
		}
		nav ul {
			list-style-type: none;
			margin: 0;
			padding: 0;
			overflow: hidden;
		}
		nav li {
			float: left;
		}
		nav li a {
			display: block;
			color: white;
			text-align: center;
			padding: 14px 16px;
			text-decoration: none;
		}
		nav li a:hover {
			background-color: #0071c5;
		}
		.container {
			width: 80%;
			margin: auto;
			padding: 20px;
		}
		form {
			background-color: #f2f2f2;
			padding: 20px;
			border-radius: 5px;
			box-shadow: 0px 0px 5px #ccc;
			margin-top: 30px;
		}
		label {
			display: block;
			margin-top: 10px;
		}
		input[type=text], input[type=email], input[type=tel], select, textarea {
			width: 100%;
			padding: 12px;
			border: 1px solid #ccc;
			border-radius: 4px;
			box-sizing: border-box;
			margin-top: 6px;
			margin-bottom: 16px;
			resize: vertical;
		}
		input[type=submit] {
			background-color: #0071c5;
			color: white;
			padding: 12px 20px;
			border: none;
			border-radius: 4px;
			cursor: pointer;
		}
		input[type=submit]:hover {
			background-color: #004f99;
		}
	</style>
</head>
<body>
	<header>
		<h1>Hospital Name</h1>
	</header>
	<nav>
		<ul>
			<li><a href="#">Home</a></li>
			<li><a href="#">About</a></li>
			<li><a href="#">Services</a></li>
			<li><a href="#">Contact</a></li>
		</ul>
	</nav>
	<div class="container">
		<h2>Book an Appointment</h2>
		<form action="appointment.php" method="post">
			<label for="name">Name</label>
			<input type="text" id="name" name="name" placeholder="Enter your name" required>

			<label for="email">Email</label>
			<input type="email" id="email" name="email" placeholder="Enter your email" required>

			<label for="phone">Phone</label>
			<input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required>

			<label for
