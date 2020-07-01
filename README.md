<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>flexbox</title>
  <style>
    .container{
      height: 500px;
      width: 90%;
      border: 2px solid black;
      display: flex;
      /* flex property for flex container */
      /* flex-direction: row-reverse; */
      /* flex-direction: row; */
      /* flex-wrap: wrapj; */
      justify-content: center;

      
    }
 
    .item{
      width: 300px;
      height: 300px;
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
    <div class="item" id="item1">
      <h3>box1</h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dignissimos odit quia quos, error ab magni voluptatem,  </div>
    <div class="item" id="item2"><h3>box 2</h3>
    Lorem ipsum dolor sit, amet consectetur adipisicing elit. Excepturi inventore, placeat laboriosam quia voluptate dolore?</div>
    <div class="item" id="item3"><h3>box3</h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. Repellat illo fugiat ipsum molestiae vitae beatae! </div>
    <div class="item" id="item4"><h3>box4 </h3>
    Lorem ipsum, dolor sit amet consectetur adipisicing elit. Est, accusantium. Delectus eum recusandae exercitationem aspernatur!</div>
    <div class="item" id="item15"><h3>box5</h3>
    Lorem ipsum dolor sit amet consectetur adipisicing elit. Ducimus ex sint aliquam ullam. Praesentium, sit. </div>
  </div>
</body>
</html>
