<?php
// Start session
session_start();

// Database connection parameters
$host = "localhost"; // Change this to your database host
$username = "root"; // Change this to your database username
$password = ""; // Change this to your database password
$database = "login"; // Change this to your database name

// Establishing a connection to the database
$conn = mysqli_connect($host, $username, $password, $database);

// Check connection
if (!$conn) {
    die("Connection failed: " . mysqli_connect_error());
}

// Check if the form is submitted
if ($_SERVER["REQUEST_METHOD"] == "POST") {
    // Collect form data
    $username = $_POST['username'];
    $password = $_POST['password'];

    // Query the database to check if the username and password match
    $sql = "SELECT * FROM users WHERE username='$username' AND password='$password'";
    $result = mysqli_query($conn, $sql);

    if (mysqli_num_rows($result) == 1) {
        // Login successful
        $_SESSION['login_message'] = "Login successful!";
        // Redirect to success page
        header("Location: movie.html");
        exit;
    } else {
        // Login failed
        $_SESSION['login_error'] = "Invalid username or password. Please try again.";
        // Redirect back to login form
        header("Location: index.php");
        exit;
    }
}

// Close connection
mysqli_close($conn);
?>

<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8">
  <title>Login Form</title>
  <link rel="stylesheet" href="style.css">
  <script src="https://kit.fontawesome.com/a076d05399.js"></script>
  <style>
    .warning {
      color: red;
    }
  </style>
</head>
<body>
<div class="bg-img">
  <div class="content">
    <header>LogIn Form</header>
    <form action="index.php" method="POST" onsubmit="return showSuccessMessage()">
      <div class="field">
        <span class="fa fa-user"></span>
        <input type="text" name="username" required placeholder="Username">
      </div>
      <div class="field space">
        <span class="fa fa-lock"></span>
        <input type="password" name="password" class="pass-key" required placeholder="Password">
        <span class="show">SHOW</span>
      </div>
      <?php
      // Check if there is an error message
      if (isset($_SESSION['login_error'])) {
          echo '<script>alert("' . $_SESSION['login_error'] . '");</script>';
          unset($_SESSION['login_error']); // Remove the error message once displayed
      }
      ?>
      <div class="pass">
        <a href="#">Forgot Password?</a>
      </div>
      <div class="field">
        <input type="submit" name="save" value="LOGIN">
      </div>
    </form>

    <div class="links">
    </div>
    <div class="signup">Don't have an account?
      <a href="signin.php">Sign in now</a>
    </div>
  </div>
</div>

<script>
  const pass_field = document.querySelector('.pass-key');
  const showBtn = document.querySelector('.show');
  showBtn.addEventListener('click', function(){
    if(pass_field.type === "password"){
      pass_field.type = "text";
      showBtn.textContent = "HIDE";
      showBtn.style.color = "#3498db";
    }else{
      pass_field.type = "password";
      showBtn.textContent = "SHOW";
      showBtn.style.color = "#222";
    }
  });

  function showSuccessMessage() {
    <?php
    // Check if there is a success message
    if (isset($_SESSION['login_message'])) {
        echo 'alert("' . $_SESSION['login_message'] . '");';
        unset($_SESSION['login_message']); // Remove the success message once displayed
    }
    ?>
    return true;
  }
</script>

</body>
</html>
