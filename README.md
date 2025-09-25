<html>
<head>
  <title> My First Landing Page for codekrafters😅 </title>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  
  <link rel="stylesheet" href="style.css">
</head>
<body>

  
  <div class="header">
    <h1> Hey, Welcome to my page </h1>
    <p> (yep.. I made this for Codekrafters 🎉) </p>
  </div>

  
  <div class="main">
    <img src="https://ethereum.org/content/developers/tutorials/getting-started-with-ethereum-development-using-alchemy/ethereum-alchemy.png" alt="random image">

    <p> hi there! this is my first landing page.. i used 
      <b>HTML + CSS + JS + backend integration </b>
    </p>

    
    <button onclick="sayHello()"> click me pls 🚀 </button>

    <br><br>

    
    <a href="https://ethereum.org" target="_blank"> go to ethereum </a>
  </div>
  
<div class="login-box">
  <h2> Login </h2>
  <form action="/login" method="POST">
    <input type="text" name="username" placeholder="Enter username"><br><br>
    <input type="password" name="password" placeholder="Enter password"><br><br>
    <button type="submit"> Login </button>
  </form>
</div>


  
  <div class="footer">
    <p> made with ❤️ by me and passionate with blockchain , innovate more with blockchain </p>
  </div>

  
  <script src="script.js"></script>
</body>
</html>
body {
  margin: 0;
  text-align: center;
  font-family: Verdana, sans-serif;
  background: linear-gradient(to right, #FFFFFF, #FFFAE5); 
  color: #000; 
}


.header {
  padding: 25px;
  background: #000000; 
  color: #FFB800; 
}

.header h1 {
  font-size: 30px;
  margin: 5px;
}


.main {
  padding: 20px;
}

.main img {
  border: 4px solid #FFB800; 
  border-radius: 12px;
  margin: 15px;
  max-width: 80%;
}

button {
  background: #FFB800; 
  color: #000; 
  border: none;
  padding: 12px 20px;
  border-radius: 6px;
  cursor: pointer;
}

button:hover {
  background: #e6a200; 
}


.main a {
  color: #FFB800; 
  text-decoration: none;
}

.main a:hover {
  text-decoration: underline;
}


.footer {
  background: #000000; 
  padding: 15px;
  color: #FFB800; 
  margin-top: 40px;
}


@media (max-width:600px) {
  .header h1 {
    font-size: 22px;
  }
  .main img {
    width: 100%;
  }
}

