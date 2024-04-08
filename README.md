
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
  <style>
    @import url("https://fonts.googleapis.com/css?family=Poppins:400,500,600,700&display=swap");
    *{
      margin: 0;
      padding: 0;
      box-sizing: border-box;
      font-family: sans-serif , "poppins";
    }
    html, body{
      display: grid;
      height: 100vh;
      place-items: center;
      background: #000;
    }
    .btn a {
      position: relative;
      color: #f5f5f5;
      height: 70px;
      width: 220px;
      display: block;
      text-align: center;
      border-radius: 10px;
      text-decoration: none;
      background-image: linear-gradient(
        115deg,
        #4fcf70,
        #fad648,
        #a767e5,
        #12bcfe,
        #44ce7b
      );
    }
    .btn a:hover{
      animation: rotate 0.4s linear infinite;
    }
    @keyframes rotate {
      100%{
        filter: hue-rotate(-360deg);
      }
    }
    .btn a span{
      height: 88%;
      width: 96%;
      background: #111;
      display: block;
      position: absolute;
      top: 50%;
      left: 50%;
      border-radius: 6px;
      line-height: 62px;
      font-size: 25px;
      transform: translate(-50%,-50%);
    }
  </style>
</head>
<body>
  <div class="btn">
    <a href="#"><span>Submit</span></a>
  </div>
</body>
</html>
