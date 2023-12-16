link of video:https://drive.google.com/file/d/1hVEKuwycZ3TBMwOCrFazY_ZSkzQCFNfa/view?usp=share_link
# task_management
The Task Manager Web Application provides a user-friendly interface to manage tasks. Users can add, edit, mark as complete, and delete tasks. The application supports filtering tasks based on completion status.
# features:
~Add tasks with titles, descriptions, and deadlines.
~Edit existing tasks to update information.
~Mark tasks as complete or incomplete.
~Filter tasks to view all tasks, completed tasks, or active tasks.
~Delete tasks to declutter the task list
# API integration 
The project uses a mock API for user authentication and task storage. If you wish to integrate with your own API:
const apiUrl = 'https://657db8a13e3f5b189463070b.mockapi.io/user';




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
