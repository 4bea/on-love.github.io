<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Image Gallery</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      background-color: #f0f0f0;
    }
    .image-container {
      margin-top: 20px;
    }
    .image-container img {
      max-width: 100%;
      height: auto;
      border: 5px solid #ddd;
      border-radius: 10px;
    }
    .navigation {
      margin-top: 20px;
    }
    .navigation a {
      text-decoration: none;
      padding: 10px 20px;
      background-color: #007BFF;
      color: white;
      border-radius: 5px;
      margin: 0 10px;
    }
    .navigation a:hover {
      background-color: #0056b3;
    }
  </style>
</head>
<body>

  <h1>Welcome to the Image Gallery</h1>

  <!-- Page 1 -->
  <div id="page1" class="image-container">
    <img src="image1.jpg" alt="Image 1">
  </div>
  <div class="navigation">
    <a href="page2.html">Next Image</a>
  </div>

  <!-- Page 2 -->
  <div id="page2" class="image-container" style="display:none;">
    <img src="image2.jpg" alt="Image 2">
  </div>
  <div class="navigation">
    <a href="page1.html">Previous Image</a>
    <a href="page3.html">Next Image</a>
  </div>

  <!-- Page 3 -->
  <div id="page3" class="image-container" style="display:none;">
    <img src="image3.jpg" alt="Image 3">
  </div>
  <div class="navigation">
    <a href="page2.html">Previous Image</a>
    <a href="page4.html">Next Image</a>
  </div>

  <!-- Page 4 -->
  <div id="page4" class="image-container" style="display:none;">
    <img src="image4.jpg" alt="Image 4">
  </div>
  <div class="navigation">
    <a href="page3.html">Previous Image</a>
    <a href="page5.html">Next Image</a>
  </div>

  <!-- Page 5 -->
  <div id="page5" class="image-container" style="display:none;">
    <img src="image5.jpg" alt="Image 5">
  </div>
  <div class="navigation">
    <a href="page4.html">Previous Image</a>
    <a href="page6.html">Next Image</a>
  </div>

  <!-- Page 6 -->
  <div id="page6" class="image-container" style="display:none;">
    <img src="image6.jpg" alt="Image 6">
  </div>
  <div class="navigation">
    <a href="page5.html">Previous Image</a>
  </div>

</body>
</html>
