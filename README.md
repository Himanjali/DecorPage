
<head>
<script src="/assets/jquery.js"></script>
<link href='https://fonts.googleapis.com/css?family=Londrina+Shadow' rel='stylesheet' type='text/css'>
<style>
body {
  font-family: helvetica, sans-serif;
  margin: 0 auto;
  max-width: 600px;
  background: url("pexels-photo-131637.jpeg");
}
div {
  height: 200px;
  background-size: cover;
  position: relative;
  margin: 40px 0 0 0;
  border-radius: 12px;
}
h1 {
  font-family: 'Londrina Shadow', cursive;
  text-align: center;
  font-size: 200px;
  color:#330011;
  margin: 60px 0 0 0;
}
h2 {
  text-align: center;
  color: #330011;
  margin: 0px 0 70px 0;
}
p {
  color: #990033;
  background: #cc0066;
  background: linear-gradient(bottom, rgba(255, 77, 136,1), rgba(255, 204, 221,.4);
  background: -webkit-linear-gradient(bottom, rgba(255, 77, 136,1),rgba(255, 204, 221,.4));
  background: -moz-linear-gradient(bottom, rgba(255, 77, 136,1), rgba(255, 204, 221,.4));
  padding: 10px;
  line-height: 28px;
  text-align: justify;
  position: absolute;
  bottom: 0;
  margin: 0;
  height: 30px;
  transition: height .5s;
  -webkit-transition: height .5s;
  -moz-transition: height .5s;
}

small {
  opacity: 0;
}

.show-description p {
  height: 150px;
}

.show-description small {
  opacity: 1;
}

.first{
  background-image: url("white-ceiling-lamp-38624.jpeg");
}
.second{
  background-image: url("abstract-close-up-dark-decor-276617.jpeg");
}
.third{
  background-image: url("art-artistic-beautiful-bloom-311458.jpeg");
}
.fourth{
  background-image: url("flowers-books-desk-house-48012.jpeg");
}
.price {
  float: right;
}
@media (max-width: 500px) {
  h1 {
    font-size: 50px;
    margin-top: 20px;
    line-height: 40px;
  }
  h2 {
    font-size: 20px;
    margin: 20px 0 30px 0;
  }
  div {
    margin: 20px 12px 0 12px;
  }
  p {
    font-size: 20px;
    line-height: 24px;
  }
  small {
    font-size: 16px;
  }
}

</style>

</head>

<body>
<h1>Himanjali's Decor</h1>
<h2>Decorating from Scrap</h2>
<div class="first">
  <p>White Ceiling Lamp <span class ="price">$30</span> <br />
   <small> A classic lamp from made from simple yarn which gives a effect with the   yellow luminescence when glown in the dark</small>
  </p>
</div>

<div class="second">
  <p>Wooden Ceiling Lamp <span class = "price">$30</span> <br />
   <small> Lamp made from the wooden pieces and assembled together to give it a nice antique look</small>
  </p>
</div>
  
<div class="third">
  <p> Colorful cactus in a cup <span class = "price"> $15</span> <br />
    <small>A very elegant decorative piece in the home which adds colors and brightens up the entire area</small> 
  </p>
</div>

<div class="fourth">
  <p> Small Flowerpot <span class = "price">$20</span> </br>
    View of fresh flowers in a small pot on your study table just freshens up the mind
  </p>
</div>



<script>
  $('div').on('click', function() {
      $(this).toggleClass('show-description');
  });
</script>

</body>
