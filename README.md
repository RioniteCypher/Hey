<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>The Sentimental Museum</title>
  <style>
    body {
      margin: 0;
      font-family: 'Courier New', monospace;
      background-color: #252525;
      color: #EBEBC6;
    }
    header {
      background-color: #474744;
      padding: 1em;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    .logo {
      font-size: 1.5em;
      font-weight: bold;
    }
    nav a {
      color: #EBEBC6;
      text-decoration: none;
      margin: 0 1em;
      font-size: 1em;
    }
    .hero {
      text-align: center;
      padding: 3em 1em;
      background-color: #252525;
    }
    .hero h1 {
      font-size: 3em;
      margin: 0;
      font-family: monospace;
    }
    .hero p {
      font-size: 1.2em;
      margin-top: 1em;
      font-style: italic;
      color: #E1E1C9;
    }
    .rooms {
      display: flex;
      justify-content: space-around;
      padding: 2em;
    }
    .room-tile {
      width: 20%;
      background: #474744;
      padding: 1em;
      text-align: center;
      border-radius: 10px;
      cursor: pointer;
      transition: background 0.3s;
    }
    .room-tile:hover {
      background: #3a3a3a;
    }
    .room-tile img {
      width: 80%;
      border-radius: 8px;
    }
    .room-tile p {
      margin-top: 0.5em;
      font-size: 1em;
      color: #EBEBC6;
    }
    footer {
      text-align: center;
      padding: 2em;
      font-size: 0.9em;
      color: #777;
    }
  </style>
</head>
<body>
  <header>
    <div class="logo">The Sentimental Museum</div>
    <nav>
      <a href="#">Entrance</a>
      <a href="#rooms">Rooms</a>
      <a href="#about">About Me</a>
      <a href="#legacy">Legacy Log</a>
    </nav>
  </header>

  <section class="hero">
    <h1>Amor Fati. Memento Mori.</h1>
    <p>Enter with intention.</p>
  </section>

  <section class="rooms" id="rooms">
    <div class="room-tile">
      <img src="/path/to/room1.jpg" alt="Room 1" />
      <p>Concilium Hall (SBSSC)</p>
    </div>
    <div class="room-tile">
      <img src="/path/to/room2.jpg" alt="Room 2" />
      <p>Maybank Pavilion</p>
    </div>
    <div class="room-tile">
      <img src="/path/to/room3.jpg" alt="Room 3" />
      <p>HSBC Strategy Arena</p>
    </div>
    <div class="room-tile">
      <img src="/path/to/room4.jpg" alt="Room 4" />
      <p>PwC Audit Floor</p>
    </div>
  </section>

  <footer>
    &copy; 2025 Laetitia Walter | Designed with sentiment and structure
  </footer>
</body>
</html>
