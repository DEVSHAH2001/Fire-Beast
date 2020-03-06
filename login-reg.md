<html>
<head>
	<title>Travelville - Login or Register</title>
	<link rel="stylesheet"  href="style1.css">
</head>
<body>
	<div class="hero">
		<div class="form-box">
			<div class="button-box">
				<div id="btn"></div>
				<button type="button" class="toggle-btn" onclick="login()">Log In</button>
				<button type="button" class="toggle-btn" onclick="register()">Register</button>
			</div>
			<div class="social-icons">
			<a href="https://www.facebook.com/login/device-based/regular/login/?login_attempt=1&lwv=110" target="_blank"><img src="login-img/fb.png"></a>
			<a href="https://twitter.com/login"><img src="login-img/tw.png"></a>
			<a href="https://accounts.google.com/ServiceLogin/signinchooser?service=accountsettings&passive=1209600&osid=1&continue=https%3A%2F%2Fmyaccount.google.com%2Fintro%3Futm_source%3Dsign_in_no_continue%26pli%3D1&followup=https%3A%2F%2Fmyaccount.google.com%2Fintro%3Futm_source%3Dsign_in_no_continue%26pli%3D1&csig=AF-SEnaZtcjuaeVQX_qP%3A1582830525&flowName=GlifWebSignIn&flowEntry=ServiceLogin"><img src="login-img/gp.png"></a>
		    </div>
            
		<form id="login" class="input-group">
			<input type="text" class="input-field" placeholder="User Id" required>
			<input type="text" class="input-field" placeholder="Enter Password" required>
			<input type="checkbox" class="check-box"><span>Remember Password</span>
			<button type="submit" class="submit-btn">Log In</button>
		</form> 
        <form id="register" class="input-group">
			<input type="text" class="input-field" placeholder="User Id" required>
			<input type="email" class="input-field" placeholder="Email Id" required>
			<input type="text" class="input-field" placeholder="Enter Password" required>
			<input type="checkbox" class="check-box" required="checkbox">
			<span>By clicking Sign Up I agree to the Terms and Conditions.</span>
			<button type="submit" class="submit-btn">Register</button>
		</form>
        </div>
    </div>
     <script>
    	var x = document.getElementById("login");
    	var y = document.getElementById("register");
    	var z = document.getElementById("btn");
        
        function register()
        {
        	x.style.left = "-400px";
        	y.style.left = "50px";
        	z.style.left = "110px";
        }
         
        function login()
        {
        	x.style.left = "50px";
        	y.style.left = "450px";
        	z.style.left = "0";
        }
    </script>
    
    </body>
</html>
