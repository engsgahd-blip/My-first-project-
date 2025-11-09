 https://github.com/<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>WE School</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: linear-gradient(to bottom, #0b132b, #1c2541);
      background-repeat: no-repeat;
      background-size: cover;
      color: white;
      display: flex;
      flex-direction: column;
      min-height: 100vh;
    }

    header {
      display: flex;
      color: #fff;
      justify-content: space-between;
      align-items: center;
      padding: 20px;
    }

    header a {
      color: white;
      text-decoration: none;
      margin-left:20pxpx;
      font-size: 15px;
    }
   .just{
      margin: 10px;
    }

    .container {
      padding: 20px;
    }

    .container h2 {
      color: #1f6feb;
    }

    .team-section {
      padding: 10px;
      text-align: center;
    }

    .team-section h2 {
      color: #1f6feb;  
    }

    .team-cards {
      display: flex;
      justify-content: center;
      gap: 30px; 
      margin-top: 20px;
    }

    .team-card {
      background-color: rgba(255, 255, 255, 0.1);  
      border-radius: 10px;
      padding: 15px;
      text-align: center;
      width: 220px;
      box-shadow: 0 0 8px rgba(0, 0, 0, 0.3);
      
    }

    .team-card img {
      width: 100%;
      height: 100p;
    }

    footer {
      text-align: center;
      padding: 15px;
      margin-right: auto;
      margin-top: 300px;
      
    }
  </style>
</head>
<body>
  <header>
    <h1>WE School</h1>
    <nav>
      <a href="#" class="just">Home</a>
      <a href="#" class="just">About</a>
      <a href="#" class="just">Booking</a>
      <a href="#" class="just">Login</a>
    </nav>
  </header>

  <div class="team-section">
    <h2>Blog</h2>
   <div class="team-cards">
    <div class="team-card">
       <a href="https://example.com/link1" target="_blank">
     <img src="https://via.placeholder.com/200x120?text=Image+1" alt="Image 1">
        </a>
        <h4>understanding css Grid</h4>
        <p>Grid lets you design responsive layouts with rows and colums</p>
        <button>Read more</button>
     </div>

      <div class="team-card">
        <a href="https://example.com/link2" >
     <img src="https://via.placeholder.com/200x120?text=Image+2" alt="Image 2">
        </a>
        <h4>Flexbox in practice</h4>
        <p>Flexbox simpliesis </p>
      </div>

      <div class="team-card">
        <a href="https://example.com/link3" >
          <img src="https://via.placeholder.com/200x120?text=Image+3" alt="Image 3">
        </a>
        <h4>Sarah</h4>
        <p>Backend Instructor</p>
       </div>
      </div>
   </div>

  <footer>
    © WE School
  </footer>
</body>
</html>
