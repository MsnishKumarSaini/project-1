<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>web page</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="box">
        <h1>Login</h1>
        <form>
            <label for="email"> </label>
            <input type="email" id="email" name="email" placeholder=" Enter Your Email">
            <label for="password"></label>
            <input type="password" id="password" name="password" placeholder="Password" minlength="6" required><br>
            <div class="check-container">
                <input type="checkbox" id="Showpassword" oncheck="togglepassword()">
                <label for="Showpassword">Show Password</label>
            </div>
            <button>Sign IN </button>
        </form>
        <p class="text">
            Forgot <a href="image 1.jpeg">Password ?</a> <br>
            Don't have an account <a href="reg.html">Sign Up</a>
        </p>
    </div>
    <script src="script.js"></script>
</body>
</html>
