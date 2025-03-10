<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=devicjkhkexfe-width, initial-scale=1.0">
    <title>Facebook</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0f2f5;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            flex-direction: column;
        }
        .container {
            display: flex;
            justify-content: space-between;
            width: 900px;
        }
        .left {
            width: 50%;
        }
        .left h1 {
            color: #1877f2;
            font-size: 3rem;
        }
        .right {
            background: white;
            padding: 20px;
            border-radius: 8px;
            box-shadow: 0 2px 4px rgba(0, 0, 0, 0.1);
            width: 350px;
            text-align: center;
        }
        input {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border: 1px solid #ccc;
            border-radius: 5px;
        }
        .login-btn {
            background-color: #1877f2;
            color: white;
            font-size: 1rem;
            border: none;
            padding: 10px;
            cursor: pointer;
            width: 100%;
            border-radius: 5px;
        }
        .signup-btn {
            background-color: #42b72a;
            color: white;
            font-size: 1rem;
            border: none;
            padding: 10px;
            cursor: pointer;
            width: 100%;
            border-radius: 5px;
            margin-top: 10px;
        }
        .contact {
            margin-top: 20px;
            text-align: center;
            font-size: 1rem;
            color: #333;
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="left">
            <h1>Facebook</h1>
            <p>Connect with friends and the world around you on Facebook.</p>
        </div>
        <div class="right">
            <input type="text" placeholder="Email or Phone">
            <input type="password" placeholder="Password">
            <button class="login-btn">Log In</button>
            <p><a href="#">Forgotten password?</a></p>
            <hr>
            <button class="signup-btn">Create New Account</button>
        </div>
    </div>
    <div class="contact">
        <p>Contact us: 123-456-7890</p>
    </div>
</body>
</html>
