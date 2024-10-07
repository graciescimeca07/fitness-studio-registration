<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Power Core Gym Registration</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 20px;
            padding: 20px;
            background-color: #f4f4f4;
            border-radius: 10px;
        }
        h1 {
            text-align: center;
            color: #2c3e50;
        }
        h2 {
            text-align: center;
            color: #34495e;
        }
        form {
            background-color: white;
            padding: 20px;
            border-radius: 5px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        label {
            display: block;
            margin: 10px 0 5px;
        }
        input[type="text"],
        input[type="email"],
        input[type="tel"],
        input[type="number"],
        textarea {
            width: 100%;
            padding: 10px;
            border: 1px solid #ccc;
            border-radius: 5px;
            margin-bottom: 10px;
        }
        input[type="radio"] {
            margin-right: 5px;
        }
        fieldset {
            border: none;
            margin-bottom: 10px;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin: 20px 0;
        }
        th, td {
            border: 1px solid #ccc;
            padding: 10px;
            text-align: left;
        }
        th {
            background-color: #2c3e50;
            color: white;
        }
        input[type="submit"] {
            background-color: #2ecc71;
            color: white;
            padding: 10px;
            border: none;
            border-radius: 5px;
            cursor: pointer;
        }
        input[type="submit"]:hover {
            background-color: #27ae60;
        }
    </style>
</head>
<body>
    <h1>Power Core Gym</h1>
    <h2>Your Fitness Journey Starts Here!</h2>

    <form action="#" method="post">
        <label for="name">Name:</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email:</label>
        <input type="email" id="email" name="email" required>

        <label for="phone">Phone Number:</label>
        <input type="tel" id="phone" name="phone" required>

        <label for="age">Age:</label>
        <input type="number" id="age" name="age" required>

        <label for="fitnessLevel">Fitness Level:</label>
        <input type="text" id="fitnessLevel" name="fitnessLevel">

        <label for="goals">Fitness Goals:</label>
        <textarea id="goals" name="goals" rows="4"></textarea>

        <fieldset>
            <legend>Select a Class:</legend>
            <label><input type="radio" name="class" value="Yoga" required> Yoga</label>
            <label><input type="radio" name="class" value="Pilates"> Pilates</label>
            <label><input type="radio" name="class" value="Zumba"> Zumba</label>
            <label><input type="radio" name="class" value="Spin"> Spin</label>
            <label><input type="radio" name="class" value="Strength Training"> Strength Training</label>
        </fieldset>

        <table>
            <tr>
                <th>Membership Name</th>
                <th>Cost</th>
                <th>Description</th>
            </tr>
            <tr>
                <td>Basic</td>
                <td>$29.99/month</td>
                <td>Access to gym equipment and group classes.</td>
            </tr>
            <tr>
                <td>Standard</td>
                <td>$49.99/month</td>
                <td>All Basic features plus personal training sessions.</td>
            </tr>
            <tr>
                <td>Premium</td>
                <td>$69.99/month</td>
                <td>All Standard features plus unlimited classes.</td>
            </tr>
        </table>

        <input type="submit" value="Submit">
    </form>
</body>
</html>
