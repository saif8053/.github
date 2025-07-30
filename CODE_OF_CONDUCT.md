<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Instagram Login</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #fafafa;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }
    .login-container {
      background-color: #fff;
      border: 1px solid #dbdbdb;
      padding: 40px;
      width: 300px;
      text-align: center;
    }
    .login-container img {
      width: 175px;
      margin-bottom: 20px;
    }
    input {
      width: 100%;
      padding: 10px;
      margin: 5px 0;
      background-color: #fafafa;
      border: 1px solid #dbdbdb;
      border-radius: 3px;
    }
    button {
      width: 100%;
      padding: 10px;
      background-color: #3897f0;
      color: white;
      font-weight: bold;
      border: none;
      border-radius: 4px;
      margin-top: 10px;
      cursor: pointer;
    }
    .divider {
      margin: 20px 0;
      color: #999;
      font-size: 13px;
    }
    .login-container a {
      font-size: 13px;
      color: #00376b;
      text-decoration: none;
    }
    .signup-box {
      margin-top: 15px;
      font-size: 14px;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/2/2a/Instagram_logo.svg/2560px-Instagram_logo.svg.png" alt="Instagram" />
    <form>
      <input type="text" placeholder="Phone number, username, or email" required />
      <input type="password" placeholder="Password" required />
      <button type="submit">Log In</button>
    </form>
    <div class="divider">OR</div>
    <a href="#">Log in with Facebook</a>
    <div class="signup-box">
      Don't have an account? <a href="#">Sign up</a>
    </div>
  </div>
</body>
</html>
