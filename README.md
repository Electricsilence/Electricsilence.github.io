# Electricsilence.github.io
<html>
<head>
  <title>My Website</title>
  <style>
    /* Add your custom CSS styles here */
    body {
      font-family: Arial, sans-serif;
      background-color: #f0f0f0;
    }

    .container {
      max-width: 800px;
      margin: 0 auto;
    }

    .navbar {
      display: flex;
      align-items: center;
      justify-content: space-between;
      background-color: #333;
      color: white;
      padding: 10px;
    }

    .navbar a {
      color: white;
      text-decoration: none;
      padding: 10px;
    }

    .navbar a:hover {
      background-color: #555;
    }

    .active {
      background-color: #4caf50;
    }

    .content {
      padding: 20px;
    }

    .music-player {
      display: flex;
      align-items: center;
      justify-content: center;
      margin-top: 20px;
    }

    .music-player audio {
      width: 300px;
    }
  </style>
</head>
<body>
  <div class="container">
    <div class="navbar">
      <a href="index.html" class="active">Home</a>
      <a href="about.html">About</a>
      <a href="contact.html">Contact</a>
      <a href="coming-soon.html">Coming Soon</a>
    </div>
    <div class="content">
      <h1>Welcome to my website!</h1>
      <p>This is the home page of my website. Here you can find some information about me and my interests.</p>
      <div class="music-player">
        <p>Listen to some of my favorite songs:</p>
        <audio controls>
          <source src="song.mp3" type="audio/mpeg">
          Your browser does not support the audio element.
        </audio>
      </div>
    </div>
  </div>
</body>
</html>
