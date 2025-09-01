<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title> Birthday Wishes</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #fff0f5;
      text-align: center;
      padding: 50px;
      color: #333;
    }

    h1 {
      color: #d63384;
      font-size: 3em;
    }

    p {
      font-size: 1.2em;
      margin: 20px 0;
    }

    .photos {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 100px;
      margin-top: 20px;
    }

    .photo-placeholder {
      width: 350px;
      height: 500px;
      background-color: #ffe6f0;
      border: 3px dashed #d63384;
      display: flex;
      align-items: center;
      justify-content: center;
      font-size: 1em;
      color: #d63384;
      border-radius: 500px;
      transition: background-color 0.3s;
    }

    .photo-placeholder:hover {
      background-color: #fff;
    }

    footer {
      margin-top: 50px;
      font-style: italic;
      color: #888;
    }

    .btn {
      margin-top: 40px;
      padding: 10px 25px;
      background-color: #ff4081;
      color: white;
      border: none;
      border-radius: 20px;
      font-size: 18px;
      cursor: pointer;
      box-shadow: 2px 2px 5px rgba(0,0,0,0.3);
    }

    .btn:hover {
      background-color: #e91e63;
    }
  </style>
</head>
<body>

  <h1>🎉 Happy Birthday Miss beauty! 🎂</h1>
  <p>Wishing you a day filled with laughter, love, and endless joy — even before it arrives!</p>
  <p>Here’s a little preview of the fun and memories coming your way! 🥳</p>

  <div class="photos">
    <div class="photo-placeholder"><img src="image1.jpeg" alt="Photo" class="photo" width="250"></div>
    <div class="photo-placeholder"><img src="image2.jpeg" alt="Photo" class="photo" width="250"></div>
    <div class="photo-placeholder"><img src="image3.jpeg" alt="Photo" class="photo" width="225"></div>
    <div class="photo-placeholder"><img src="image4.jpeg" alt="Photo" class="photo" width="250"></div>
  </div>

  <footer>
    Created with 💖 just for you!
  </footer>

  <button class="btn" onclick="alert('🎉 Surprise! A gift is waiting for u! 🎉')">
    Click for a Surprise!
  </button>

</body>
</html>
