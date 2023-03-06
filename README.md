* {
    box-sizing: border-box;
    margin: 0;
    padding: 0;
  }
  
  body {
    font-family: Arial, sans-serif;
    font-size: 16px;
    line-height: 1.5;
  }
  
  header, nav, main, section, footer {
    display: block;
  }
  
  header {
    background-color: #1E90FF;
    color: #FFF;
    padding: 10px;
  }
  
  nav {
    background-color: #F5F5F5;
    border-bottom: 1px solid #CCC;
    padding: 10px;
  }
  
  nav ul {
    list-style: none;
    margin: 0;
    padding: 0;
  }
  
  nav li {
    display: inline-block;
    margin-right: 10px;
  }
  
  nav li:last-child {
    margin-right: 0;
  }
  
  nav a {
    color: #000;
    text-decoration: none;
    padding: 5px;
  }
  
  nav a:hover {
    background-color: #1E90FF;
    color: #FFF;
  }
  
  main {
    padding: 20px;
  }
  
  #hero {
    background-image: url("https://via.placeholder.com/800x400");
    background-size: cover;
    background-position: center;
    text-align: center;
    padding: 100px 0;
  }
  
  #hero h2 {
    font-size: 40px;
    color: #FFF;
    margin-bottom: 20px;
  }
  
  #hero p {
    font-size: 20px;
    color: #FFF;
    margin-bottom: 20px;
  }
  
  #hero button {
    background-color: #1E90FF;
    color: #FFF;
    padding: 10px 20px;
    font-size: 18px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
  }
  
  #hero button:hover {
    background-color: #FFF;
    color: #1E90FF;
  }
  
  #artists, #albums, #playlists {
    margin-top: 50px;
  }
  
  .artist, .album, .playlist {
    display: inline-block;
    margin-right: 20px;
    vertical-align: top;
    width: 200px;
    border: 1px solid #CCC;
    padding: 10px;
    text-align: center;
  }
  
  .artist img, .album img, .playlist img {
    display: block;
    margin: 0 auto 10px;
    max-width: 100%;
  }
  
  .artist h3, .album h3, .playlist h3 {
    font-size: 18px;
    margin-bottom: 10px;
  }
  
  .artist p, .album p, .playlist p {
    font-size: 14px;
    line-height: 1.2;
  }
