<!DOCTYPE html>
<html lang="en">

<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>My HTML project2</title>
  <style>
    body {
      font-family: Arial, Helvetica, sans-serif, sans-serif;
      margin: 25px;
      background-color: #5f9ddf;


      h1 {
        color: #f3ece2;

      }


      input,
      button {
        margin: 4% 0;
        padding: 10px;
        width: 100%;
        max-width: 300px;
        box-sizing: border-box;
      }

      button {
        background-color: #e71daef1;
        color: rgb(242, 244, 243);
        border: none;
        cursor: pointer;

      }

      button:hover {
        background-color: #0056b3;
      }
  </style>
</head>

<body>
  <h1>About Delwar Hossain Nakib</h1>
  <form id="dataForm">
    <label for="name">Name:</label>
    <input type="text" id="name" placeholder="Enter Name">
    <br>
    <lebel for="password">Password:</lebel>
    <input type="password" id="password" placeholder="Enter password"> <br>
    <label for="age">Age:</label>
    <input type="number" id="age" placeholder="Enter Age">
    <br>
    <label for="email">Email:</label>
    <input type="email" id="email" placeholder="Enter Email">
    <br>
    <label FOR="number">Number:</label>
    <input type="number" id="number" placeholder="Enter Number">
    <br>

    <button type="button"> SUBMIT</button>
  </form>
</body>

</html>
