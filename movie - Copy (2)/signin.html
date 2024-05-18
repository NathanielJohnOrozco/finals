<?php
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
    $password = $_POST['password']; // Note: For real-world application, you should hash the password

    // Insert data into the database
    $sql = "INSERT INTO users (username, password) VALUES ('$username', '$password')";
    if (mysqli_query($conn, $sql)) {
        echo "<script type='text/javascript'>
                alert('Sign up successful. You can now login.');
                window.location.href = 'index.php';
              </script>";
        exit;
    } else {
        echo "Error: " . $sql . "<br>" . mysqli_error($conn);
    }
}

// Close connection
mysqli_close($conn);
?>

<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8">
  <title>Signin Form</title>
  <link rel="stylesheet" href="style.css">
  <script src="https://kit.fontawesome.com/a076d05399.js"></script>
</head>
<body>
<div class="bg-img">
  <div class="content">
    <header>SignIn Form</header>
    <form action="#" method="POST">
      <div class="field">
        <span class="fa fa-user"></span>
        <input type="text" name="username" required placeholder="Username">
      </div>
      <div class="field space">
        <span class="fa fa-lock"></span>
        <input type="password" name="password" class="pass-key" required placeholder="Password">
        <span class="show">SHOW</span>
      </div>
      <div class="pass">
        <a href="#">Forgot Password?</a>
      </div>
      <div class="field">
        <input type="submit" name="save" value="SIGNUP">
      </div>
    </form>

    <div class="links">

    </div>
    <div class="signup">Have an account?
      <a href="index.php">LogIn Now</a>
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
</script>

</body>
</html>
