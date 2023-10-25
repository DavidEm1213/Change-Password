<!DOCTYPE html>
<html>
<head>
  <title>Change Password</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      font-family: Arial, sans-serif;
    }

    .login-form {
      padding: 20px;
      background-color: #f8f8f8;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }

    .login-form label {
      display: block;
      margin-bottom: 10px;
      font-weight: bold;
    }

    .login-form input[type="text"],
    .login-form input[type="password"] {
      width: 100%;
      padding: 10px;
      margin-bottom: 20px;
      border-radius: 10px; 
      border: 1px solid #6f05e9;
      background-color: #a40ee9;
    }
    
    .login-form input[type="button"] {
      display: block;
      margin: 0 auto;
      width: 320px;
      padding: 10px;
      flex-shrink: 0;
      border: none;
      border-radius: 60px;
      background-color: #55f37d;
      border: #020a01;
      color: rgb(7, 2, 2);
      font-size: 20px;
      cursor: pointer;
       
    }
    button#toggle-password {
  background: none;
  border: none;
  cursor: pointer;
  font-size: var(--mobile-font-size);
  font-weight: 300;
  padding: 0;
  position: absolute;
  top: 0;
  right: 0;
}
   
    
    .login-form input[type="submit"]:hover {
      background-color: #67f045;
    }
  </style>
</head>
<body>
  <div class="login-form">
    <form>
      <label for="password">Password:</label>
      <input type="password" autocomplete="new-password" id="new-password" name="password" required>
      <label for="password">Confirm the password:</label>
      <input type="password" autocomplete="current-password" id="current-password" name="password" required>
      <a href="https://davidem1213.github.io/q/"><input type="button" value="Change Password" align="center" ></a>
      </form>
  </div>
</body>
</html>
