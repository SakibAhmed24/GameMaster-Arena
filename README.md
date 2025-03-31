<!DOCTYPE html><html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GameMaster Arena</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #1e1e2f;
            color: white;
            text-align: center;
        }
        .container {
            width: 50%;
            margin: auto;
            background: #2a2a3a;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.3);
        }
        input, button {
            width: 100%;
            padding: 10px;
            margin: 10px 0;
            border-radius: 5px;
            border: none;
        }
        button {
            background: #007bff;
            color: white;
            cursor: pointer;
        }
        button:hover {
            background: #0056b3;
        }
        .contact {
            margin-top: 20px;
        }
    </style>
</head>
<body>
    <h1>GameMaster Arena</h1>
    <div class="container">
        <h2>Squad Registration</h2>
        <form>
            <input type="text" placeholder="Squad Name" required>
            <input type="text" placeholder="Leader Name" required>
            <input type="email" placeholder="Leader Email" required>
            <input type="text" placeholder="Free Fire ID" required>
            <button type="submit">Register</button>
        </form>
    </div>
    <div class="contact">
        <h3>Contact Us</h3>
        <p>Email: sakibahmed1647@gmail.com</p>
        <p>Phone: 01789746191</p>
    </div>
</body>
</html>
<!DOCTYPE html><html>
<head>
    <title>Squad Login Form</title>
    <style>
        body { font-family: Arial, sans-serif; text-align: center; }
        form { max-width: 400px; margin: auto; padding: 20px; border: 1px solid #ccc; border-radius: 10px; }
        input { display: block; width: 100%; margin: 10px 0; padding: 8px; }
        button { background-color: #28a745; color: white; padding: 10px; border: none; cursor: pointer; }
    </style>
</head>
<body>
    <h2>Squad Login</h2>
    <form>
        <label for="uid1">Squad Member 1 UID:</label>
        <input type="text" id="uid1" name="uid1" required><label for="uid2">Squad Member 2 UID:</label>
    <input type="text" id="uid2" name="uid2" required>
    
    <label for="uid3">Squad Member 3 UID:</label>
    <input type="text" id="uid3" name="uid3" required>
    
    <label for="uid4">Squad Member 4 UID:</label>
    <input type="text" id="uid4" name="uid4" required>
    
    <label for="leader">Team Leader Name:</label>
    <input type="text" id="leader" name="leader" required>
    
    <label for="contact">Contact Number:</label>
    <input type="tel" id="contact" name="contact" required>
    
    <button type="submit">Login</button>
</form>

</body>
</html>
