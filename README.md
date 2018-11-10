<!DOCTYPE html>

<html lang="en">

<head>

  <!-- Theme Made By www.w3schools.com -->

  <title>Bootstrap Theme Company Page</title>

  <meta charset="utf-8">

  <meta name="viewport" content="width=device-width, initial-scale=1">

  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">

  <link href="https://fonts.googleapis.com/css?family=Montserrat" rel="stylesheet" type="text/css">

  <link href="https://fonts.googleapis.com/css?family=Lato" rel="stylesheet" type="text/css">

  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.3.1/jquery.min.js"></script>

  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>

  <style>

  body {

      font: 400 15px Lato, sans-serif;

      line-height: 1.8;

      color: #333232;      /*kleur van de letters onder Ben je op zoek,*/

  }

  h2 {

      font-size: 24px;

      text-transform: uppercase;

      color: #9b6060;

      font-weight: 600;

      margin-bottom: 30px;

  }

  h4 {

      font-size: 19px;

      line-height: 1.375em;

      color: #f29191;

      font-weight: 400;

      margin-bottom: 30px;

  }  

  .jumbotron {

      background-color: #f29191; <!-- WAS EERST ORANJE f4511e; -->

      color: #fff;

      padding: 100px 25px;

      font-family: Montserrat, sans-serif;

  }

  .container-fluid {

      padding: 60px 50px;

  }

  .bg-grey {

      background-color: #f29191;

  }

  .logo-small {

      color: #f4511e;

      font-size: 50px;

  }

  .logo {

      color: #f4511e;

      font-size: 200px;

  }

  .thumbnail {

      padding: 0 0 15px 0;

      border: none;

      border-radius: 0;

  }

  .thumbnail img {

      width: 100%;

      height: 100%;

      margin-bottom: 10px;

  }

  .carousel-control.right, .carousel-control.left {

      background-image: none;

      color: #f29191;

  }

  .carousel-indicators li {

      border-color: #f29191;

  }

  .carousel-indicators li.active {

      background-color: #f29191;

  }

  .item h4 {

      font-size: 19px;

      line-height: 1.375em;

      font-weight: 400;

      font-style: italic;

      margin: 70px 0;

  }

  .item span {

      font-style: normal;

  }

  .panel {

      border: 1px solid #f29191; 

      border-radius:0 !important;

      transition: box-shadow 0.5s;

  }

  .panel:hover {

      box-shadow: 5px 0px 40px rgba(0,0,0, .2);

  }

  .panel-footer .btn:hover {

      border: 1px solid #f29191;

      background-color: #fff !important;

      color: #f29191;

  }

  .panel-heading {

      color: #fff !important;

      background-color: #f29191 ! important;

      padding: 25px;

      border-bottom: 1px solid transparent;

      border-top-left-radius: 0px;

      border-top-right-radius: 0px;

      border-bottom-left-radius: 0px;

      border-bottom-right-radius: 0px;

  }

  .panel-footer {

      background-color: white !important;

  }

  .panel-footer h3 {

      font-size: 32px;

  }

  .panel-footer h4 {

      color: #aaa;

      font-size: 14px;

  }

  .panel-footer .btn {

      margin: 15px 0;

      background-color: #f4511e;

      color: #fff;

  }

  .navbar {

      margin-bottom: 0;

      background-color: #f4511e;

      z-index: 9999;

      border: 0;

      font-size: 12px !important;

      line-height: 1.42857143 !important;

      letter-spacing: 4px;

      border-radius: 0;

      font-family: Montserrat, sans-serif;

  }

  .navbar li a, .navbar .navbar-brand {

      color: #fff !important;

  }

  .navbar-nav li a:hover, .navbar-nav li.active a {

      color: #f4511e !important;

      background-color: #fff !important;

  }

  .navbar-default .navbar-toggle {

      border-color: transparent;

      color: #fff !important;

  }

  footer .glyphicon {

      font-size: 20px;

      margin-bottom: 20px;

      color: #f4511e;

  }

  .slideanim {visibility:hidden;}

  .slide {

      animation-name: slide;

      -webkit-animation-name: slide;

      animation-duration: 1s;

      -webkit-animation-duration: 1s;

      visibility: visible;

  }

  @keyframes slide {

    0% {

      opacity: 0;

      transform: translateY(70%);

    } 

    100% {

      opacity: 1;

      transform: translateY(0%);

    }

  }

  @-webkit-keyframes slide {

    0% {

      opacity: 0;

      -webkit-transform: translateY(70%);

    } 

    100% {

      opacity: 1;

      -webkit-transform: translateY(0%);

    }

  }

  @media screen and (max-width: 768px) {

    .col-sm-4 {

      text-align: center;

      margin: 25px 0;

    }

    .btn-lg {

        width: 100%;

        margin-bottom: 35px;

    }

  }

  @media screen and (max-width: 480px) {

    .logo {

        font-size: 150px;

    }

  }

  </style>

</head>

<body id="myPage" data-spy="scroll" data-target=".navbar" data-offset="60">



<nav class="navbar navbar-default navbar-fixed-top">

  <div class="container">

    <div class="navbar-header">

      <button type="button" class="navbar-toggle" data-toggle="collapse" data-target="#myNavbar">

        <span class="icon-bar"></span>

        <span class="icon-bar"></span>

        <span class="icon-bar"></span>                        

      </button>

      <a class="navbar-brand" href="#myPage">Logo</a>

    </div>

    <div class="collapse navbar-collapse" id="myNavbar">

      <ul class="nav navbar-nav navbar-right">

        <li><a href="#portfolio">ABOUT ME</a></li> 

		<li><a href="#Service">SERVICE</a></li>

        <li><a href="#Price">PRICE</a></li>

         <li><a href="#contact">CONTACT</a></li>

      </ul>

    </div>

  </div>

</nav>



<div class="jumbotron text-center">

  <h1>WELKOM</h1> 

  <p>Ik ben Selma, en ik ben gespecialiseerd in..</p> 

  <form>

    <div class="input-group">

      <input type="email" class="form-control" size="50" placeholder="Mail me voor vragen" required>

      <div class="input-group-btn">

        <button type="button" class="btn btn-danger">Verzenden</button>

      </div>

    </div>

  </form>

</div>



<!-- Container (About Section) -->

<div id="about" class="container-fluid">

  <div class="row">

    <div class="col-sm-8">

      <h2>Wat doe ik</h2><br>

      <h4>Ben je op zoek naar een fantastische taart voor je feesje, bijeenkomst of simpelweg voor je liefste mama dan ben je hier op het juiste adres.</h4><br>

      <p> Ik maak muffins, gebakjes, taarten en alles wat u nodig heeft voor een onvergetelijke dag .</p>

      <br><button class="btn btn-default btn-lg">Contact</button>

    </div>

    <div class="col-sm-4">

      <span class=""> <img class="img-rounded" src= "http://www.driscolls.nl/assets/styles/header/public/content/header/image/mixed_shortcake_140535.01.jpg" width= "400px"/> </span>

    </div>

  </div>

</div>



<div class="container-fluid bg-grey">

  <div class="row">

    <div class="col-sm-4">

      <span class="glyphicon glyphicon-cutlery"></span>

    </div>

    <div class="col-sm-8">

      <h2>Waarom bij mij...</h2><br>

      

      <p><strong>Heyy:</strong> Ik ben selma en ik maak graag taarten.</p>

    </div>

  </div>

</div>



<!-- Container (Services Section) -->

<div id="Service" class="container-fluid text-center">

  <h2>SERVICE</h2>

  <h4>Waar ik me in onderschijd</h4>

  <br>

  <div class="row slideanim">

    <div class="col-sm-4">

      <span class="glyphicon glyphicon-thumbs-up logo-small"></span>

      <h4>Tevreden</h4>

      <p> Iedereen is zeer tevreden </p>

    </div>

    <div class="col-sm-4">

      <span class="glyphicon glyphicon-heart logo-small"></span>

      <h4>Liefde</h4>

      <p>De taarten met liefde gebakken</p>

    </div>

    <div class="col-sm-4">

      <span class="glyphicon glyphicon-euro logo-small"></span>

      <h4>Prijs</h4>

      <p>De prijs is heel reeel </p>

    </div>

  </div>

  <br><br>

  <div class="row slideanim">

    <div class="col-sm-4">

      <span class="glyphicon glyphicon-leaf logo-small"></span>

      <h4>Groen</h4>

      <p>Ik gebruik groene energie</p>

    </div>

    <div class="col-sm-4">

      <span class="glyphicon glyphicon-certificate logo-small"></span>

      <h4>Cenrificaat</h4>

      <p>Veel wedstrijden gewonnen</p>

    </div>

    <div class="col-sm-4">

      <span class="glyphicon glyphicon-wrench logo-small"></span>

      <h4>Hard werken</h4>

      <p>Ik ben altijd bereid hard te werken</p>

    </div>

  </div>

</div>



<!-- Container (Portfolio Section) -->

<div id="about me" class="container-fluid text-center bg-grey">

  <h2>About me</h2><br>

  <h4>What we have created</h4>

  <div class="row text-center slideanim">

    <div class="col-sm-4">

      <div class="thumbnail">

        <img src="https://marianneontwerpt.files.wordpress.com/2012/01/binnenkant-trouwtaart.jpg" alt="Taart" width="400" height="300">

        <p><strong>lekkerr</strong></p>

        <p>iets makkelijks</p>

      </div>

    </div>

    <div class="col-sm-4">

      <div class="thumbnail">

        <img src="https://i.ytimg.com/vi/XQ3XfC-5v3Y/maxresdefault.jpg" alt="Lolypops" width="400" height="400">

        <p><strong>Ook dit</strong></p>

        <p>Voor een geboorte</p>

      </div>

    </div>

    <div class="col-sm-4">

      <div class="thumbnail">

        <img src="https://www.wellplated.com/wp-content/uploads/2017/04/Low-Sugar-Healthy-Blueberry-Muffins.jpg" alt="Muffins" width="400" height="300">

        <p><strong>Veel soorten, niet gemakkelijk om een keuze te maken :) </strong></p>

        <p>maar ik help je natuurlijk..</p>

      </div>

    </div>

  </div><br>

  

  <h2>Wat de kopers zeiden </h2>

  <div id="myCarousel" class="carousel slide text-center" data-ride="carousel">

    <!-- Indicators -->

    <ol class="carousel-indicators">

      <li data-target="#myCarousel" data-slide-to="0" class="active"></li>

      <li data-target="#myCarousel" data-slide-to="1"></li>

      <li data-target="#myCarousel" data-slide-to="2"></li>

    </ol>



    <!-- Wrapper for slides -->

    <div class="carousel-inner" role="listbox">

      <div class="item active">

      <img class="img-rounded" src= "http://www.driscolls.nl/assets/styles/header/public/content/header/image/mixed_shortcake_140535.01.jpg" alt="Flowers in Chania"  width= "200px"/> 

       <h4>"wooww!"<br><span>Michael Roe, Vice President, Comment Box</span></h4>

      </div>

      

      <div class="item">

       <img class="img-rounded" src= "http://static.articlewedding.com/wp-content/uploads/2016/10/wedding-23104.jpg"  width= "200px"/> 

        <h4>"One word... WOW!!"<br><span>John Doe, Salesman, Rep Inc</span></h4>

      </div>

      

      <div class="item">

    <picture>

  <source media="(min-width: 650px)" srcset="img_pink_flowers.jpg">

  <source media="(min-width: 465px)" srcset="img_white_flower.jpg">

  <img src="img_orange_flowers.jpg" alt="Flowers" style="width:auto;">

</picture>

        <h4>"Could I... BE any more happy with this company?"<br><span>Chandler Bing, Actor, FriendsAlot</span></h4>

      </div>

    </div>



    <!-- Left and right controls -->

    <a class="left carousel-control" href="#myCarousel" role="button" data-slide="prev">

      <span class="glyphicon glyphicon-chevron-left" aria-hidden="true"></span>

      <span class="sr-only">Previous</span>

    </a>

    <a class="right carousel-control" href="#myCarousel" role="button" data-slide="next">

      <span class="glyphicon glyphicon-chevron-right" aria-hidden="true"></span>

      <span class="sr-only">Next</span>

    </a>

  </div>

</div>



<!-- Container (Pricing Section) -->

<div id="Price" class="container-fluid">

  <div class="text-center">

    <h2>Price</h2>

    <h4>De keuze is groot, vandaar dat er groepen bestaan</h4>

  </div>

  <div class="row slideanim">

    <div class="col-sm-4 col-xs-12">

      <div class="panel panel-default text-center">

        <div class="panel-heading">

          <h1>Normaal</h1>

        </div>

        <div class="panel-body">

          <p><strong>20</strong> Cupcake's</p>

          <p><strong>15</strong> Gebakjes</p>

          <p><strong>5</strong> Soesjes met chocola</p>

          <p><strong>2</strong> Lolypop's</p>

          

        </div>

        <div class="panel-footer">

          <h3>10,-</h3>

          <h4>per 10 stuks</h4>

          <button class="btn btn-lg">Kies voor deze</button>

        </div>

      </div>      

    </div>     

    <div class="col-sm-4 col-xs-12">

      <div class="panel panel-default text-center">

        <div class="panel-heading">

          <h1>Normaal</h1>

        </div>

        <div class="panel-body">

          <p><strong>1</strong> Taart</p>

          <p><strong>1</strong> Gebak </p>

          <p><strong>1</strong> Grote taart</p>

          <p><strong>1</strong> taart</p>

     </div>

        <div class="panel-footer">

          <h3>25,-</h3>

          <h4>per stuk</h4>

          <button class="btn btn-lg">Kies voor deze</button>

        </div>

      </div>      

    </div>       

    <div class="col-sm-4 col-xs-12">

      <div class="panel panel-default text-center">

        <div class="panel-heading">

          <h1>Luxe</h1>

        </div>

        <div class="panel-body">

          <p><strong>1</strong> bruiloft taart</p>

          <p><strong>1</strong> Lagen taart</p>

          <p><strong>1</strong> pinata</p>

          <p><strong>1</strong> High tea </p>

        </div>

        <div class="panel-footer">

          <h3>50,-</h3>

          <h4>per month</h4>

          <button class="btn btn-lg">Kies deze</button>

        </div>

      </div>      

    </div>    

  </div>

</div>



<!-- Container (Contact Section) -->

<div id="contact" class="container-fluid bg-grey">

  <h2 class="text-center">Contact</h2>

  <div class="row">

    <div class="col-sm-5">

      <p>Heeft u vragen mail of bel me gerust.</p>

      <p><span class="glyphicon glyphicon-map-marker"></span> Amsterdam, Nederland</p>

      <p><span class="glyphicon glyphicon-phone"></span> +31 6 11 50 95 11</p>

      <p><span class="glyphicon glyphicon-envelope"></span> s_selma2002@yahoo.nl</p>

    </div>

    <div class="col-sm-7 slideanim">

      <div class="row">

        <div class="col-sm-6 form-group">

          <input class="form-control" id="name" name="name" placeholder="Name" type="text" required>

        </div>

        <div class="col-sm-6 form-group">

          <input class="form-control" id="email" name="email" placeholder="Email" type="email" required>

        </div>

      </div>

      <textarea class="form-control" id="comments" name="comments" placeholder="Comment" rows="5"></textarea><br>

      <div class="row">

        <div class="col-sm-12 form-group">

          <button class="btn btn-default pull-right" type="submit">Send</button>

        </div>

      </div>

    </div>

  </div>

</div>



<!-- Image of location/map -->

<img src="https://www.bakkerij-ceulemants.be/images/patisserie01.jpg" class="w3-image w3-greyscale-min" style="width:100%">



<footer class="container-fluid text-center">

  <a href="#myPage" title="To Top">

    <span class="glyphicon glyphicon-chevron-up"></span>

  </a>

  <p>Bootstrap Theme Made By <a href="https://www.google.nl/" title="Visit w3schools">www.w3schools.com</a></p>

</footer>



<script>

$(document).ready(function(){

  // Add smooth scrolling to all links in navbar + footer link

  $(".navbar a, footer a[href='#myPage']").on('click', function(event) {

    // Make sure this.hash has a value before overriding default behavior

    if (this.hash !== "") {

      // Prevent default anchor click behavior

      event.preventDefault();



      // Store hash

      var hash = this.hash;



      // Using jQuery's animate() method to add smooth page scroll

      // The optional number (900) specifies the number of milliseconds it takes to scroll to the specified area

      $('html, body').animate({

        scrollTop: $(hash).offset().top

      }, 900, function(){

   

        // Add hash (#) to URL when done scrolling (default click behavior)

        window.location.hash = hash;

      });

    } // End if

  });

  

  $(window).scroll(function() {

    $(".slideanim").each(function(){

      var pos = $(this).offset().top;



      var winTop = $(window).scrollTop();

        if (pos < winTop + 600) {

          $(this).addClass("slide");

        }

    });

  });

})

</script>



</body>

</html>



