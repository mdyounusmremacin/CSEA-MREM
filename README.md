# CSEA-MREM
This is my  first repo
<br>
Author name YOUNUS(got an exception)
goto college <!DOCTYPE html>
<html>
<head>
    <title>Registration Form</title>
</head>
<body>
    <h2>User Registration Form</h2>
    <form action="submit_form.php" method="post">
        
        <!-- Full Name -->
        <label for="fullname">Full Name:</label><br>
        <input type="text" id="fullname" name="fullname" required><br><br>

        <!-- Email -->
        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email" required><br><br>

        <!-- Password -->
        <label for="password">Password:</label><br>
        <input type="password" id="password" name="password" required><br><br>

        <!-- Gender -->
        <label>Gender:</label><br>
        <input type="radio" id="male" name="gender" value="Male" required>
        <label for="male">Male</label>
        
        <input type="radio" id="female" name="gender" value="Female" required>
        <label for="female">Female</label><br><br>

        <!-- Date of Birth -->
        <label for="dob">Date of Birth:</label><br>
        <input type="date" id="dob" name="dob" required><br><br>

        <!-- Submit Button -->
        <input type="submit" value="Register">
    </form>
</body>
</html>
