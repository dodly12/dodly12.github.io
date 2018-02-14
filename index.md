<!DOCTYPE html>
<head>
<script src="jquery-3.3.1.min.js"></script>
<script src="/assets/jquery.js"></script>
<link href="https://fonts.googleapis.com/css?family=Rammetto+One" rel="stylesheet">
<style>
body {
  font-family:'Rammetto One', cursive; ;
  
  margin: 0 auto;
  max-width: 600px;
  background: #232323;
 background:url("https://png.pngtree.com/element_origin_min_pic/16/10/15/2358024cf1e50e3.jpg");
 background-position: center;
}

div {
  height: 200px;
  background-size: cover;
  position: relative;
  margin: 40px 0 0 0;
  border-radius: 12px;
}
h1 {
  font-family: 'Rammetto One', cursive;
  text-align: center;
  font-size: 75px;
  color:#ff0000;
  margin: 160px 0 0 0;
}
h2 {
  font-family: 'Rammetto One', cursive;
  text-align: center;
  color:#ff0000;
  margin: 0px 0 70px 0;
}
p {
  color: rgba(255,255,255,1);
  background:red;
  background: linear-gradient(bottom, rgba(0, 0, 0, 0.4), rgba(0,0,0,.4));
  background: -webkit-linear-gradient(bottom, rgba(255,0,0,1), rgba(255,255,255,.4));
  background: -moz-linear-gradient(bottom, rgba(0,0,0,1), rgba(0,0,0,.4));
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
  background-image: url("https://hdwallsource.com/img/2014/2/italian-food-pizza-wallpaper-44477-45603-hd-wallpapers.jpg");
}
.second{
  background-image: url("http://s1.1zoom.me/big3/51/353805-svetik.jpg");
}
.dessert{
  background-image: url("https://wallpaperscraft.com/image/cheesecake_berry_jam_86885_1920x1080.jpg");
}
.price {
  float: right;
}
.cheesecake {
  margin: 40px 0 0 150px;
}

    input {
      border: 0;
      padding: 10px;
      font-size: 20px;
    }
    input[type="submit"] {
      background:#4F9070;
      color: white;
      text-align:center;
      margin: 50 auto;
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
<h1>Turtle pizza place</h1>
<h2>For crazy pizza experience. </h2>
<div class="first">
  <p>Pizza <span class="price">$14</span><br />
  <small>The best pizza experience on the planet odder a large, small any size you wont regret it . </small></p>
</div>

<div class="second">
  <p> steaks<span class="price">$22</span><br />
  <small>There are alot of defferent type of main apertiser you can order the most popular on is the steaks u can also pick the new smooke fish.</small></p>
</div>
  
<div class="dessert">
  <p>cheesecake<span class="price">$8</span><br />
  <small>There are alot of defferent type of desert you can order the most popular on is the cheese cake u can also pick the new cake.</small></p>
</div>
  <script>
  
  $('div').on('click', function() {
      $(this).toggleClass('show-description');
  });
</script>

<div class="cheesecake">
<input type="email" placeholder="your order" id=Mustard>
<input type="submit" onclick="alert(Mustard.value)">
</div>
</body>
