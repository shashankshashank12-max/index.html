<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Personalized Greetings</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(135deg, #667eea, #764ba2);
      color: white;
      text-align: center;
      padding: 50px;
    }

    h1 {
      font-size: 2.5rem;
      margin-bottom: 20px;
    }

    input, textarea, button {
      padding: 10px;
      margin: 10px;
      border-radius: 10px;
      border: none;
      font-size: 1rem;
    }

    button {
      background: #ff4081;
      color: white;
      cursor: pointer;
      transition: 0.3s;
    }

    button:hover {
      background: #e91e63;
    }

    .greeting-card {
      margin-top: 20px;
      padding: 20px;
      background: rgba(255,255,255,0.1);
      border-radius: 15px;
      animation: fadeIn 1.5s;
    }

    @keyframes fadeIn {
      from { opacity: 0; transform: scale(0.8); }
      to { opacity: 1; transform: scale(1); }
    }
  </style>
</head>
<body>
  <h1>🎉 Personalized Greetings 🎉</h1>
  
  <input type="text" id="name" placeholder="Enter Name">
  <textarea id="wish" placeholder="Enter Greeting / Wish"></textarea>
  <button onclick="saveGreeting()">Save Greeting</button>
  <button onclick="showGreeting()">Show Greeting</button>

  <div id="greetingDisplay" class="greeting-card"></div>

  <!-- Background Music -->
  <audio id="bgMusic" autoplay loop>
    <source src="your-music.mp3" type="audio/mpeg">
  </audio>

  <script>
    // Store greetings in browser localStorage
    function saveGreeting() {
      let name = document.getElementById('name').value;
      let wish = document.getElementById('wish').value;

      if(name && wish) {
        localStorage.setItem(name, wish);
        alert("Greeting saved for " + name + " 🎉");
      } else {
        alert("Please enter both name and greeting!");
      }
    }

    function showGreeting() {
      let name = document.getElementById('name').value;
      let wish = localStorage.getItem(name);

      if(wish) {
        document.getElementById('greetingDisplay').innerHTML = 
          `<h2>Hello ${name}! 🎂</h2><p>${wish}</p>`;
      } else {
        document.getElementById('greetingDisplay').innerHTML = 
          `<p>No greeting found for ${name} 😢</p>`;
      }
    }
  </script>
</body>
</html>