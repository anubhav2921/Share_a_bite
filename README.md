<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Sign Up as Consumer | Share A Bite</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Roboto', sans-serif;
            min-height: 100vh;
            background: linear-gradient(135deg, #eafcea 0%, #baffb9 100%);
            display: flex;
            align-items: center;
            justify-content: center;
        }
        .signup-container {
            background: #fff;
            padding: 36px 32px;
            border-radius: 20px;
            box-shadow: 0 8px 24px rgba(34,139,34, 0.08);
            width: 340px;
            display: flex;
            flex-direction: column;
        }
        .signup-container h2 {
            text-align: center;
            margin-bottom: 20px;
            color: #222;
        }
        .signup-container label {
            font-weight: 500;
            margin-bottom: 4px;
            display: block;
            color: #222;
            font-size: 1rem;
        }
        .signup-container input[type="text"],
        .signup-container input[type="email"],
        .signup-container input[type="password"] {
            width: 100%;
            padding: 10px;
            margin-bottom: 18px;
            border: 1px solid #c6f7b8;
            border-radius: 10px;
            outline: none;
            transition: border-color 0.2s;
        }
        .signup-container input[type="text"]:focus,
        .signup-container input[type="email"]:focus,
        .signup-container input[type="password"]:focus {
            border-color: #34c759;
        }
        .signup-btn {
            width: 100%;
            padding: 12px;
            border: none;
            border-radius: 10px;
            background: linear-gradient(90deg, #34c759 80%, #a8eb12 100%);
            color: #fff;
            font-size: 1.08rem;
            font-weight: bold;
            cursor: pointer;
            box-shadow: 0 2px 8px rgba(52,199,89,0.10);
            margin-bottom: 16px;
            transition: background 0.2s;
        }
        .signup-btn:hover {
            background: linear-gradient(90deg, #28a745 80%, #8fd400 100%);
        }
        .login-link {
            text-align: center;
            color: #222;
            font-size: 0.98rem;
        }
        .login-link a {
            color: #34c759;
            text-decoration: none;
            font-weight: 500;
        }
        .login-link a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <div class="signup-container">
        <h2>Sign Up as Consumer</h2>
        <form>
            <label for="name">Full Name</label>
            <input type="text" id="name" placeholder="Enter your full name" required />

            <label for="email">Email</label>
            <input type="email" id="email" placeholder="Email address" required />

            <label for="username">Username</label>
            <input type="text" id="username" placeholder="Choose a username" required />

            <label for="password">Password</label>
            <input type="password" id="password" placeholder="Create a password" required />

            <!-- Add any specific fields for consumers if needed -->
            <button class="signup-btn" type="submit">Sign Up</button>
        </form>
        <div class="login-link">
            Already have an account?
            <a href="consumerlogin.html">Login</a>
        </div>
    </div>
</body>
</html>
