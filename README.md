<html>
<head>
  <title></title>
  <link rel="stylesheet" type="text/css" href="style.css">
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.12.1/css/all.min.css">
<style>
				* {
  margin: 0;
  padding: 0;
}
body {
  display: flex;
  min-height: 100vh;
  align-items: center;
  justify-content: center;
  background: #ffe400;
}
.rating-css {
  height: 250px;
  width: 400px;
  background: #101012;
  border: 4px solid #838383;
  padding: 20px;
}
.rating-css div {
  color: #ffe400;
  font-size: 30px;
  font-family: sans-serif;
  font-weight: 800;
  text-align: center;
  text-transform: uppercase;
  padding: 20px 0;
}
.rating-css input {
  display: none;
}
.rating-css input + label {
  font-size: 60px;
  text-shadow: 1px 1px 0 #ffe400;
  cursor: pointer;
}
.rating-css input:checked + label ~ label {
  color: #838383;
}
.rating-css label:active {
  transform: scale(0.8);
				
</style>

</head>

<body>

  <div class="rating-css">
    
    <div class="star-icon">
      <input type="radio" name="rating1" id="rating1">
      <label for="rating1" class="fa fa-star"></label>
      <input type="radio" name="rating1" id="rating2">
      <label for="rating2" class="fa fa-star"></label>
      <input type="radio" name="rating1" id="rating3">
      <label for="rating3" class="fa fa-star"></label>
      <input type="radio" name="rating1" id="rating4">
      <label for="rating4" class="fa fa-star"></label>
      <input type="radio" name="rating1" id="rating5">
      <label for="rating5" class="fa fa-star"></label>
    </div>
  </div>

 
</body>

</html>
