<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>flexbox</title>
  <style>
    .container{
      height: 500px;
      width: 60%;
      border: 2px solid black;
      display: flex;
      /* flex property for flex container */
      /* flex-direction: row-reverse; */
      /* flex-direction: row; */
      /* flex-wrap: wrapj; */
      justify-content: center;

      
    }
 
    .item{
      width: 100px;
      height: 200px;
      border: 2px solid chocolate;
      background-color:  rgb(199, 224, 199);
      margin: 10px;
      padding: 3px;

    }
  </style>
</head>
<body>
  <h1>coursera assignment -2 </h1>
  <div class="container">
    <div class="item" id="item1">box1 </div>
    <div class="item" id="item2">box 2</div>
    <div class="item" id="item3">box3 </div>
    <div class="item" id="item4">box4 </div>
    <div class="item" id="item15">box5 </div>
  </div>
</body>
</html>
