
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8"> 
  <meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" herf="style.css"/>
<title></title>
<style>
  * {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  body{
    background-color: grey;
    text-align: center;
  }
  .container{
    display: grid;
    grid-template-columns:repeat(3,50px)
    grid-template-rows: repeat(3,50px);
    justify-content: center;
    text-align: center;
    gap: 20;
  }
button{
  color: white;
  background-color: rgb(13,15,13);
  height: 50px;
  width: 50px;
  font-size: 10;
  border-radius: 7%;
  border-color: green;
  }
  span{
    color: white;
  }
  .btn{
    color: white;
    height: 30px;
    width: 100px;
    background-color: orange;
    border-color: blue;
    font-size: 20px;
  }
  h1{
    color: mediumspringgreen;
  }
  button:hover{
    background-color: yellow;
  }
  .game-info{
    color: white;
  }
</style>
</head>
<body>
  <h1>welcome, Tic Tac Toe !</h1>
<div class="game">
  <div class="container">
    <button>x</button>
    <button>x</button>
    <button>x</button>
    <button>0</button>
    <button>x</button>
    <button>x</button>
    <button>0</button>
    <button>0</button>
    <button>x</button>
  <div class="game-info">
  <div id="player">
    </br>
  <span>you</span>
  </br>
  <strong>0</strong>
  
  <span>computer</span>
  <strong>0</strong>
  </br>
  <button class="btn">score</button>
  
  
</br>


</body>
</html>
