<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>BFF Contact Form</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #ffe6f0; /* reddish-pink background */
      padding: 30px;
    }
    form {
      background: #ffffff;
      padding: 20px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(255, 105, 180, 0.3);
      max-width: 400px;
      margin: auto;
    }
    h2 {
      text-align: center;
      color: rgb(255, 80, 120);
    }
    label {
      display: block;
      margin-top: 12px;
      font-weight: bold;
      color: #333;
    }
    input {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 5px;
    }
    button {
      background-color: rgb(255, 80, 120); /* reddish-pink */
      color: white;
      padding: 12px;
      border: none;
      border-radius: 5px;
      margin-top: 20px;
      cursor: pointer;
      width: 100%;
      font-size: 16px;
    }
    button:hover {
      background-color: rgb(220, 50, 100);
    }
  </style>
</head>
<body>
  <form action="YOUR_FORMSPREE_ENDPOINT_HERE" method="POST">
    <h2>🎀 Your School Life BFF's Details 🎀</h2>

    <label for="bffName">BFF's Name:</label>
    <input type="text" id="bffName" name="name" required>

    <label for="phone">BFF's Phone Number:</label>
    <input type="tel" id="phone" name="phone" required pattern="[0-9+ -]{7,15}">

    <label for="food">BFF's Favourite Food:</label>
    <input type="text" id="food" name="food" required>

    <label for="color">BFF's Favourite Color:</label>
    <input type="text" id="color" name="color" required>

    <label for="dob">BFF's Date of Birth:</label>
    <input type="text" id="dob" name="dob" placeholder="DD-MM-YYYY" required>

    <label>💝 GET AMAZING PRIZE IF YOU SUBMIT 💝</label>

    <button type="submit">Send Love</button>
  </form>
</body>
</html>
