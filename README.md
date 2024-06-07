# feedback-project
<!DOCTYPE html> 
<html lang="en"> 

<head> 
	<meta charset="UTF-8"> 
	<meta name="viewport"
		content="width=device-width,initial-scale=1.0"> 
	<title>Responsive Form Card</title> 
	<link rel="stylesheet" href= 
"https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css"> 
	<link rel="stylesheet" href="index.css"> 
</head> 

<body> 
	<h1>Fauzadar beej bhandar mai </h1> 
	<h3>Feedback For seed and pestisides
		
	</h3> 
	<div class="form-box"> 
		<div class="textup"> 
			<i class="fa fa-solid fa-clock"></i> 
			It only takes two minutes!! 
		</div> 
		<form> 
			<label for="uname"> 
				<i class="fa fa-solid fa-user"></i> 
				Name 
			</label> 
			<input type="text" id="uname"
				name="uname" required> 

			<label for="email"> 
				<i class="fa fa-solid fa-envelope"></i> 
				Email Address 
			</label> 
			<input type="email" id="email"
				name="email" required> 

			<label for="phone"> 
				<i class="fa-solid fa-phone"></i> 
				Phone No 
			</label> 
			<input type="tel" id="phone"
				name="phone" required> 

			<label> 
				<i class="fa-solid fa-face-smile"></i> 
				Do you satisfy with our service? 
			</label> 
			<div class="radio-group"> 
				<input type="radio" id="yes"
					name="satisfy" value="yes" checked> 
				<label for="yes">Yes</label> 

				<input type="radio" id="no"
					name="satisfy" value="no"> 
				<label for="no">No</label> 
			</div> 

			<label for="msg"> 
				<i class="fa-solid fa-comments"
				style="margin-right: 3px;"></i> 
				Write your Suggestions: 
			</label> 
			<textarea id="msg" name="msg"
					rows="4" cols="10" required> 
			</textarea> 
			<button type="submit"> 
				Submit 
			</button> 
		</form> 
	</div> 
</body> 

</html>
