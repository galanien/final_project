link of video:https://drive.google.com/file/d/1hVEKuwycZ3TBMwOCrFazY_ZSkzQCFNfa/view?usp=share_link

<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sign Up</title>
    <link rel="stylesheet" href="styles/style.css">
</head>

<body>
    <div class="signUpBody">
        <div class="signUpPage">
            <div class="form-group">
                <input type="text" id="username" required placeholder="Username">
            </div>
            <div class="form-group">
                <input type="password" id="password" required placeholder="Password">
            </div>
            <button class="signUpButton" onclick="signUp()">Sign Up</button>
            <p id="signupMessage"></p>
            <p>Already have an account? <a class="signUpPar" href="signIn.html"> Sign In</a></p>
        </div>
    </div>

    <script src="js/script.js"></script>
</body>

</html>
