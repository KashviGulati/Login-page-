# Login-page-
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book recommendation website</title>
    <link rel="stylesheet" href="login.css">
</head>
<body>
    <form action="action_page.php" method="post">
        <h2>Login Page</h2>
      
        <div class="container">
          <label for="uname"><b>Username</b></label>
          <input type="text" placeholder="Enter Username" name="uname" required><br>
      
          <label for="psw"><b>Password</b></label>
          <input type="password" placeholder="Enter Password" name="psw" required><br>
      
          <button type="submit">Login</button>
          <label>
            <input type="checkbox" checked="checked" name="remember"> Remember me
          </label><br><br>
        </div>
      
        <div class="container" style="background-color:#f1f1f1">
          <button type="button" class="cancelbtn">Cancel</button><br>
          <span class="psw">Forgot <a href="#">password?</a></span>
        </div>
      </form>
      </body>
      </html>
