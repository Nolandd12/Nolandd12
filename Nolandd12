<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Login Form</title>
<link rel="stylesheet" href="styles.css">
<style type="text/css" media="all">
    body {
  font-family: Arial, sans-serif;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  margin: 0;
  background-color: #f1f1f1;
}

.container {
  width: 300px;
  padding: 20px;
  background-color: #fff;
  border-radius: 5px;
  box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
}

.input-group {
  margin-bottom: 15px;
}

.input-group label {
  display: block;
  margin-bottom: 5px;
}

.input-group input {
  width: 100%;
  padding: 8px;
  border-radius: 3px;
  border: 1px solid #ccc;
}

button {
  width: 100%;
  padding: 10px;
  background-color: #007bff;
  color: #fff;
  border: none;
  border-radius: 3px;
  cursor: pointer;
}

button:hover {
  background-color: #0056b3;
}

.error-msg {
  color: red;
  margin-top: 10px;
}
</style>
</head>
<body>

<div class="container">
  <form id="loginForm" onsubmit="return validateForm()">
    <h2>Login Form</h2>
    <div class="input-group">
      <label for="username">Username</label>
      <input type="text" id="username" name="username" required>
    </div>
    <div class="input-group">
      <label for="password">Password</label>
      <input type="password" id="password" name="password" required>
    </div>
    <button type="submit">Login</button>
    <p id="error-msg" class="error-msg"></p>
  </form>
</div>

<script src="script.js">function validateForm() {
  var username = document.getElementById("username").value;
  var password = document.getElementById("password").value;
  var errorMsg = document.getElementById("error-msg");

  if (username === "admin" && password === "password") {
    alert("Login successful!");
    return true;
  } else {
    errorMsg.innerHTML = "Invalid username or password.";
    return false;
  }
}</script>
</body>
</html>
