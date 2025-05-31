<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Welcome to Z-Corp</title>
  <style>
    /* Reset some default styles */
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    }

    body, html {
      height: 100%;
      background: linear-gradient(135deg, #2c3e50, #3498db);
      color: white;
      display: flex;
      justify-content: center;
      align-items: center;
      text-align: center;
      padding: 20px;
    }

    .container {
      max-width: 600px;
      background: rgba(255, 255, 255, 0.1);
      padding: 40px 30px;
      border-radius: 15px;
      box-shadow: 0 8px 20px rgba(0,0,0,0.3);
      backdrop-filter: blur(10px);
    }

    img {
      max-width: 100%;
      border-radius: 12px;
      margin-bottom: 25px;
      box-shadow: 0 4px 15px rgba(0,0,0,0.4);
      object-fit: cover;
      height: 250px;
      width: 100%;
    }

    h1 {
      font-size: 3rem;
      margin-bottom: 15px;
      letter-spacing: 2px;
      text-transform: uppercase;
      font-weight: 700;
    }

    p {
      font-size: 1.25rem;
      margin-bottom: 30px;
      color: #e0e0e0;
    }

    .btn {
      text-decoration: none;
      background: #2980b9;
      color: white;
      padding: 15px 40px;
      border-radius: 30px;
      font-weight: 600;
      font-size: 1.1rem;
      transition: background 0.3s ease;
      box-shadow: 0 5px 15px rgba(41, 128, 185, 0.4);
      display: inline-block;
    }

    .btn:hover {
      background: #1c5980;
      box-shadow: 0 8px 20px rgba(28, 89, 128, 0.6);
    }

    @media (max-width: 480px) {
      h1 {
        font-size: 2.2rem;
      }

      p {
        font-size: 1rem;
      }

      .btn {
        padding: 12px 30px;
        font-size: 1rem;
      }

      img {
        height: 180px;
      }
    }
  </style>
</head>
<body>
  <div class="container">
    <img src="https://z-corp.s3.eu-north-1.amazonaws.com/z-corp.jpg" />
    <h2>Welcome to Z-Corp</h2>
    <p>Your trusted partner in innovation and excellence.</p>
    <a href="#" class="btn">Learn More</a>
  </div>
</body>
</html>
