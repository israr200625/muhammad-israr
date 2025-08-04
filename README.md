<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Profile Card</title>
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      background-color: #f4f4f4;
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 20px;
      display: flex;
      justify-content: center;
      align-items: center;
      min-height: 100vh;
    }

    .card {
      background-color: #fff;
      border-radius: 12px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      padding: 30px;
      text-align: center;
      max-width: 350px;
      width: 100%;
    }

    .card img {
      border-radius: 50%;
      width: 120px;
      height: 120px;
      object-fit: cover;
      margin-bottom: 20px;
      border: 3px solid #3498db;
    }

    .card h2 {
      margin: 10px 0 5px;
      color: #333;
    }

    .card p {
      color: #666;
      font-size: 14px;
    }

    .card .btn {
      display: inline-block;
      margin-top: 15px;
      padding: 10px 20px;
      background-color: #3498db;
      color: white;
      border: none;
      border-radius: 25px;
      text-decoration: none;
      font-size: 14px;
      transition: background 0.3s;
    }

    .card .btn:hover {
      background-color: #2980b9;
    }

    @media (max-width: 400px) {
      .card {
        padding: 20px;
      }
    }
  </style>
</head>
<body>

  <div class="card">
    <img src="https://i.pravatar.cc/150?img=3" alt="Profile Image">
    <h2>Israr Khan</h2>
    <p>Web Developer & Student<br>Passionate about front-end design</p>
    <a href="#" class="btn">Contact Me</a>
  </div>

</body>
</html>
