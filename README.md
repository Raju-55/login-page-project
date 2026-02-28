# login-page-project
this is login page code and register page code.
----------------------------------------------------------
        login page code
-----------------------------------------------------------        
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Login Here</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body{
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:#0f0f0f;
    overflow:hidden;
}

/* Background Circles */
.background{
    position:absolute;
    width:100%;
    height:100%;
}

.shape{
    position:absolute;
    border-radius:50%;
}

.shape1{
    width:300px;
    height:300px;
    background:linear-gradient(45deg,#3a7bd5,#00d2ff);
    top:-80px;
    left:-80px;
}

.shape2{
    width:250px;
    height:250px;
    background:linear-gradient(45deg,#ff512f,#f09819);
    bottom:-80px;
    right:-80px;
}

/* Glass Card */
.container{
    position:relative;
    z-index:2;
}

.login-box{
    width:350px;
    padding:40px;
    background:rgba(255,255,255,0.05);
    border-radius:12px;
    backdrop-filter:blur(15px);
    box-shadow:0 0 25px rgba(0,0,0,0.6);
    color:white;
}

.login-box h2{
    text-align:center;
    margin-bottom:30px;
    font-size:28px;
}

.login-box label{
    display:block;
    margin-top:15px;
    margin-bottom:5px;
    font-size:14px;
}

.login-box input{
    width:100%;
    padding:10px;
    border:none;
    outline:none;
    border-radius:6px;
    background:rgba(255,255,255,0.1);
    color:white;
}

.login-box input::placeholder{
    color:#ccc;
}

.login-box button{
    width:100%;
    margin-top:25px;
    padding:10px;
    border:none;
    border-radius:6px;
    background:#ffffff;
    color:#000;
    font-weight:bold;
    cursor:pointer;
    transition:0.3s;
}

.login-box button:hover{
    background:#ddd;
}

.login-box p{
    margin-top:20px;
    text-align:center;
    font-size:14px;
}

.login-box a{
    color:#00d2ff;
    text-decoration:none;
}
</style>

</head>
<body>

<div class="background">
    <div class="shape shape1"></div>
    <div class="shape shape2"></div>
</div>

<div class="container">
    <div class="login-box">
        <h2>Login Here</h2>

        <form>
            <label>Username</label>
            <input type="text" placeholder="Email or Phone" required>

            <label>Password</label>
            <input type="password" placeholder="Password" required>

            <button type="submit">Log In</button>

            <p>Don't Have an Account? 
                <a href="register.html">Register Here</a>
            </p>
        </form>
    </div>
</div>

</body>
</html>

----------------------------------------------------------------------------
            register page code
---------------------------------------------------------------------------
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Register Here</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body{
    height:100vh;
    display:flex;
    justify-content:center;
    align-items:center;
    background:#0f0f0f;
    overflow:hidden;
}

.background{
    position:absolute;
    width:100%;
    height:100%;
}

.shape{
    position:absolute;
    border-radius:50%;
}

.shape1{
    width:300px;
    height:300px;
    background:linear-gradient(45deg,#3a7bd5,#00d2ff);
    top:-80px;
    left:-80px;
}

.shape2{
    width:250px;
    height:250px;
    background:linear-gradient(45deg,#ff512f,#f09819);
    bottom:-80px;
    right:-80px;
}

.container{
    position:relative;
    z-index:2;
}

.register-box{
    width:350px;
    padding:40px;
    background:rgba(255,255,255,0.05);
    border-radius:12px;
    backdrop-filter:blur(15px);
    box-shadow:0 0 25px rgba(0,0,0,0.6);
    color:white;
}

.register-box h2{
    text-align:center;
    margin-bottom:30px;
    font-size:28px;
}

.register-box label{
    display:block;
    margin-top:15px;
    margin-bottom:5px;
    font-size:14px;
}

.register-box input{
    width:100%;
    padding:10px;
    border:none;
    outline:none;
    border-radius:6px;
    background:rgba(255,255,255,0.1);
    color:white;
}

.register-box input::placeholder{
    color:#ccc;
}

.register-box button{
    width:100%;
    margin-top:25px;
    padding:10px;
    border:none;
    border-radius:6px;
    background:#ffffff;
    color:#000;
    font-weight:bold;
    cursor:pointer;
    transition:0.3s;
}

.register-box button:hover{
    background:#ddd;
}

.register-box p{
    margin-top:20px;
    text-align:center;
    font-size:14px;
}

.register-box a{
    color:#00d2ff;
    text-decoration:none;
}
</style>

</head>
<body>

<div class="background">
    <div class="shape shape1"></div>
    <div class="shape shape2"></div>
</div>

<div class="container">
    <div class="register-box">
        <h2>Register Here</h2>

        <form>
            <label>Username</label>
            <input type="text" placeholder="Email or Phone" required>

            <label>Password</label>
            <input type="password" placeholder="Password" required>

            <button type="submit">Sign Up</button>

            <p>Have an Account? 
                <a href="login.html">Login Here</a>
            </p>
        </form>
    </div>
</div>

</body>
</html>














