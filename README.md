<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link href='https://unpkg.com/boxicons@2.1.4/css/boxicons.min.css' rel='stylesheet'>
    <link rel="stylesheet" href="style.css">
    <title>Ludiflex | Login & Registration</title>
</head>
<body>
<div class="wrapper">
    <nav class="nav">
        <div class="nav-logo">
            <p>LOGO .</p>
        </div>
        <div class="nav-menu">
            <ul>
                <li><a href="#" class="link active">Home</a></li>
                <li><a href="#" class="link">Blog</a></li>
                <li><a href="#" class="link">Services</a></li>
                <li><a href="#" class="link">About</a></li>
            </ul>
        </div>
        <div class="nav-button">
            <button class="btn white-btn" id="loginBtn">Sign In</button>
            <button class="btn" id="registerBtn">Sign Up</button>
        </div>
        <div class="nav-menu-btn">
            <i class="bx bx-menu"></i>
        </div>
    </nav>
    
<!-------------------- Form box -------------------->
    <div class="form-box">
    


        <!------------------ login form ------------------>
        <div class="login-container" id="login">
            <div class="top">
                <span>Don't have an account? <a href="#" onclick="register()"Sign Up</a></span>
                <header>Sign Up</header>
            </div>
            <div class="two-forms">
                 <div class="input-box">
                    <input type="text" class="input-field" placeholder="Firstname">
                    <i class="bx.bx-user"></i>
                </div>
                <div class="input-box">
                    <input type="text" class="input-field" placeholder="Lastname">
                    <i class="bx.bx-user"></i>
                </div>
            </div>
            <div class="input-box">
                    <input type="text" class="input-field" placeholder="Email">
                    <i class="bx.bx-envelope"></i>
        </div> 
        <div class="input-box">
                    <input type="password" class="input-field" placeholder="Password">
                    <i class="bx.bx-lock-alt"></i>
            </div>
            <div class="input-box">
                    <input type="submit" class="submit" value="Register">
            </div>
            <div class="two-col">
                <div class="one">
                    <input type="checkbox" id="register-check">
                    <label for="register-check"> Remember Me</label>
                </div>
                <div class="two">
                    <label><a href="#">Terms & conditions</a></label>
                </div>
            </div>
        </div>
    </div>
</div>
</body>
</html>


