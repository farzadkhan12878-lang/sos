<!DOCTYPE html>
<html>
<head>
    <title>Login Form</title>
</head>

<body>

<form>

    <label>Username:</label>
    <input type="text" name="username">
    <br><br>

    <label>Password:</label>
    <input type="password" name="password">
    <br><br>

    <label>City of<br>Employment:</label>
    <input type="text" name="city">
    <br><br>

    <label>Web server:</label>
    <select name="server">
        <option>— Choose a server —</option>
        <option>Apache</option>
        <option>Windows Server</option>
        <option>Linux Server</option>
    </select>

    <br><br>

    <label>Please specify<br>your role:</label>

    <input type="radio" name="role" value="admin"> Admin<br>
    <input type="radio" name="role" value="engineer"> Engineer<br>
    <input type="radio" name="role" value="manager"> Manager<br>
    <input type="radio" name="role" value="guest"> Guest

    <br><br>

    <label>Single Sign-on<br>to the following:</label>

    <input type="checkbox" name="mail"> Mail<br>
    <input type="checkbox" name="payroll"> Payroll<br>
    <input type="checkbox" name="self-service"> Self-service

    <br><br>

    <input type="submit" value="Login">
    <input type="reset" value="Reset">

</form>

</body>
</html>
