# Color-change-

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
   <style>
    @keyframes color-change{
        0% {background-color: aqua;}
        50% {background-color: blue;}
        100% {background-color: brown;}
    }

    .container{
      
        width: 500px;
        height: 400px;
        background-color: blue;
        animation-name: color-change;
        animation-duration: 5s;
        animation-iteration-count: infinite;
    }
    
    .box{
       
        width: 200px;
        height: 90px;
        background-color: aqua;
        animation-name: color-change;
        animation-duration: 2s;
        animation-iteration-count: infinite;
    }
    
   </style>
</head>
<body>
    <div class="container">
        <div class="box">Name  </div>
        <div class="box"> class</div>
        <div class="box"> Roll-no</div>
        <div class="box"> Subject</div>
    </div>
</body>
</html>
