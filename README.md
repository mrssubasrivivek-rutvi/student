student html project
!DOCTYPE html>
<html>
<head>
    <title>Student Database Form</title>
</head>
<body>

    <h2>Student Database Form</h2>

    <form>

        <label for="name">Full Name:</label><br>
        <input type="text" id="name" name="name"><br><br>

        <label for="roll">Roll Number:</label><br>
        <input type="text" id="roll" name="roll"><br><br>

        <label for="email">Email:</label><br>
        <input type="email" id="email" name="email"><br><br>

        <label for="phone">Phone Number:</label><br>
        <input type="tel" id="phone" name="phone"><br><br>

        <label for="gender">Gender:</label><br>
        <input type="radio" name="gender" value="Male"> Male<br>
        <input type="radio" name="gender" value="Female"> Female<br>
        <input type="radio" name="gender" value="Other"> Other<br><br>

        <label for="address">Address:</label><br>
        <textarea id="address" name="address"></textarea><br><br>

        <input type="submit" value="Submit">
        <input type="reset" value="Reset">

    </form>

</body>
</html>

