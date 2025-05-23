<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Facebook – log in or sign up</title>
  <link href="https://fonts.googleapis.com/css2?family=Helvetica+Neue:wght@400;700&display=swap" rel="stylesheet">
  <style>
    body {
      margin: 0;
      font-family: 'Helvetica Neue', Arial, sans-serif;
      background-color: #f0f2f5;
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
    }

    .login-container {
      background-color: #fff;
      padding: 24px;
      border-radius: 8px;
      box-shadow: 0 2px 12px rgba(0, 0, 0, 0.2);
      width: 380px;
      text-align: center;
    }

    .facebook-logo img {
      width: 200px;
      margin-bottom: 20px;
    }

    input {
      width: 100%;
      padding: 14px;
      margin: 10px 0;
      border: 1px solid #dddfe2;
      border-radius: 6px;
      font-size: 16px;
    }

    button {
      width: 100%;
      padding: 14px;
      background-color: #1877f2;
      color: white;
      border: none;
      border-radius: 6px;
      font-size: 16px;
      font-weight: bold;
      cursor: pointer;
    }

    button:hover {
      background-color: #166fe5;
    }

    a {
      display: block;
      margin-top: 12px;
      text-decoration: none;
      color: #1877f2;
      font-size: 14px;
    }

    a:hover {
      text-decoration: underline;
    }

    .create-account {
      margin-top: 20px;
      background-color: #42b72a;
    }

    .create-account:hover {
      background-color: #36a420;
    }
  </style>
</head>
<body>
  <div class="login-container">
    <div class="facebook-logo">
      <img src="https://1000logos.net/wp-content/uploads/2021/04/Facebook-logo.png" alt="Facebook">
    </div>
    <form action="#" method="POST">
      <input type="text" name="email" placeholder="Email address or phone number" required />
      <input type="password" name="password" placeholder="Password" required />
      <button type="submit">Log In</button>
    </form>
    <a href="#">Forgotten password?</a>
    <hr>
    <button class="create-account">Create New Account</button>
  </div>
</body>
</html>
