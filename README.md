# Flex Box Demo
**index.html**
``` html   
<!DOCTYPE html>
<html>
  <head>
    <title></title>
    <link rel="stylesheet" type="text/css" href="css/normalize.css">
    <link rel="stylesheet" type="text/css" href="css/style.css">
  </head>
  <body>

    <div class="flex-container">
      <div class="blue-box"></div>
      <div class="red-box"></div>
      <div class="green-box"></div>
      <div class="black-box"></div>
    </div>
  </body>
</html>
```   

**css/style.css**
``` css   
body {
  padding: 20px;
  background-color: #ff7a7a;
}

.flex-container {
  display:flex;
  width: 100%;
  height: 600px;
  outline: 1px solid black;
  background-color: #fff;
  
  align-items: center;
  justify-content: center;
  flex-wrap: wrap;
}

.blue-box, .green-box, .red-box, .black-box {
  width: 200px;
  height: 200px;
  margin: 20px;
  flex-grow: 1;
  flex-shrink: 0;
}

.blue-box {
  background-color: #63d6f9;
  flex-grow: 3;
}

.green-box {
  background-color: #63f9c0;
}

.red-box {
  background-color: #f98163;
}

.black-box {
  background-color: #000;
}
```   

