<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>CSS Box Model Demonstration</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 40px;
      background-color: #f9f9f9;
    }

    h1 {
      color: darkblue;
    }

    /* Outer Box */
    .outer-box {
      width: 250px;
      height: 250px;
      margin: 20px auto;
      padding: 30px;
      border: 5px solid orangered;
      background-color: gold;
      display: flex;
      align-items: center;
      justify-content: center;
    }

    /* Inner Box */
    .inner-box {
      width: 100%;
      height: 100%;
      background-color: deepskyblue;
      color: white;
      font-weight: bold;
      display: flex;
      align-items: center;
      justify-content: center;
    }


 
  </style>
</head>
<body>
  <h2>CSS Box Model Demonstration</h2>

  <!-- Outer Box containing Inner Box -->
  <div id="outerBox" class="outer-box">
    <div id="innerBox" class="inner-box">
      Content
    </div>

  </div>
