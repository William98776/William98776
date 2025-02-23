<!DOCTYPE html>

<html lang="en">

<head>

    <meta charset="UTF-8">

    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title> Facebook Login</title>

    <style>

        body {

            font-family: Arial, sans-serif;

            background-color: #e9ebee;

            display: flex;

            justify-content: center;

            align-items: center;

            height: 100vh;

            margin: 0;

        }

        

        .login-container {

            background-color: #fff;

            border-radius: 8px;

            box-shadow: 0 4px 10px rgba(0,0,0,0.1);

            padding: 40px;

            width: 300px;

            text-align: center;

        }


        .login-container h1 {

            font-size: 24px;

            color: #1877f2;

            margin-bottom: 20px;

        }


        .input-group {

            margin-bottom: 15px;

        }


        input[type="text"], input[type="password"] {

            width: 100%;

            padding: 10px;

            border: 1px solid #ddd;

            border-radius: 5px;

            font-size: 16px;

        }


        input[type="submit"] {

            width: 100%;

            padding: 10px;

            background-color: #1877f2;

            color: white;

            border: none;

            border-radius: 5px;

            cursor: pointer;

            font-size: 16px;

        }


        input[type="submit"]:hover {

            background-color: #165e9c;

        }


        .forgot-password {

            margin-top: 15px;

        }


        .forgot-password a {

            font-size: 14px;

            color: #1877f2;

            text-decoration: none;

        }


        .forgot-password a:hover {

            text-decoration: underline;

        }


        .or-divider {

            margin: 20px 0;

            font-size: 14px;

            color: #65676b;

        }


        .register-button {

            padding: 10px;

            border: 1px solid #ccc;

            background-color: #42b72a;

            color: white;

            font-size: 16px;

            width: 100%;

            border-radius: 5px;

            cursor: pointer;

        }


        .register-button:hover {

            background-color: #36a420;

        }

    </style>

</head>

<body>


    <div class="login-container">

        <h1>Facebook</h1>

        <form action="#">

            <div class="input-group">

                <input type="text" placeholder="Email or phone" required>

            </div>

            <div class="input-group">

                <input type="password" placeholder="Password" required>

            </div>

            <input type="submit" value="Log In">

        </form>

        <div class="forgot-password">

            <a href="#">Forgotten password?</a>

        </div>

        <div class="or-divider">or</div>

        <button class="register-button">Create New Account</button>

    </div>


</body>

</html>

