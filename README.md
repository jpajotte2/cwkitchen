# cwkitchen
cwkitchen project
  <!DOCTYPE html>
<html>
<head>
	<title>C.W. Kitchen TT</title>
<link rel="stylesheet" type="text/css" href="style.css">
 <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/font-awesome/4.4.0/css/font-awesome.min.css">
<link href="https://fonts.googleapis.com/css?family=Abril+Fatface" rel="stylesheet">
 <link href="https://fonts.googleapis.com/css?family=Kaushan+Script|Open+Sans|Lato" rel="stylesheet">
 <link href="https://fonts.googleapis.com/css?family=Roboto:300,400,700" rel="stylesheet">
</head>
<body>
<header>
	<nav>
		<a href="#one"> About</a>
		<a href="#products"> Products</a>
		<a href="#distributors">Distributors/Events</a>
		<a href="#Contact">Contact</a>
	</nav>
</header>	

<section id="hero" class="center-content">
	<div id="social-media">
	<!-- <a href="#"><img src="images/insta.png"></a>	 -->
	</div>
</section>

<div id="one" class="center-content">
	<img src="cwlogoonline.jpg" width="200" height=200" center-content>
	<h3>Taste it. Dream it. Love it. Repeat!</h3>

		<p> At C.W. Kitchen we specialize in homemade seasonings, pepper sauces and many other authentic, Caribbean culinary products produced in Trinidad and Tobago. We've spent a lot of time experimenting with local peppers, seasonings and various spices to bring you the perfect combination of ingredients needed to create our items.</p>

		<p><span>Our ingredients are 100% organic and are sourced from local farmers commited to bringing you the very best the island has to offer!<span></p>
</div>


<section id="products">
<h1>Our Products</h1>
<div class="product">
    <h3>Cranberry Pepper Sauce</h3>
    <img src="images/CranberryPSsize25.jpg" alt="" title="">
   <a href="#CranberryPepperSauce" class="View-More"> View More</a>
</div>

<div class="product">
    <h3>Pineapple Pepper Sauce</h3>
    <img src="images/PinapplePS.JPG" alt="" title="">
   <a href="#PineapplePepperSauce" class="View-More">View More</a>
</div>

<div class="product">
    <h3>Pimento Seasoning</h3>
    <img src="images/PimentoS.JPG" alt="" title="">
   <a href="#PimentoSeasoning" class="View-More">View More</a>
</div>


<div class="product">
    <h3>Mesmorizing Seasoning</h3>
    <img src="images/GreenSeasoning.JPG" alt="" title="">
   <a href="#MesmorizingSeasoning" class="View-More">View More</a>
</div>

<div class="product">
    <h3>Enchanting Pepper Sauce</h3>
    <img src="images/EnchantingPS.jpg" alt="" title="">
     <a href="#EnchantingPepperSauce" class="View-More">View More</a>
</div>
</section>



<section id="distributors">
	<h1>#GotTheSauce?</h1>
	<p>Looking for the C.W. Kitchen brand products? Find them on a shelf near you at one of our distributors listed below:</p>
	<img src="images/HoneyComb2CW.jpg" alt="honey" width="1000" height="600">
</section>

<section id="Contact">
<h1>Contact Us</h1>
<p>For questions, concerns or bulk orders, please contact us below:</p>
	<!-- <p>For orders (including wholesale and/or international) or to attend one of our taste-testing events, use the form below to reach out to us: </p> -->
	<div id="contactinfo" class="two">
	<h4><i class="fa fa-map-marker fa-fw" aria-hidden="true"></i>Petit Valley, Trinidad and Tobago, W.I.</h4>
	<h4><i class="fa fa-phone fa-fw" aria-hidden="true"></i>(868)-758-8244 or (868)-492-7383</h4>
	<h4><i class="fa fa-envelope fa-fw" aria-hidden="true"></i> cwkitchen@hotmail.com</h4>
	</div>
<!-- <div id="form"  class="two">    -->
	<!-- <form action="/action_page.php"> -->
	<form action="acknowledge.php" method="post">
		<label for="name"> Name</label>
		<input type="text" id="name" name="name" placeholder="Your name">

		<label for="email"> E-mail</label>
		<input type="text" id="email" name="email" placeholder="Your email">

		<label for="number"> Number</label>
		<input type="text" id="number" name="phone number" placeholder="Your number">

		<label for="message"> Message</label>
		<textarea id="message" placeholder="How can we help?" style="height: 200px'"></textarea>

		<input type="submit" value="Submit">
	</form>

	<form action="mailto:jnll_p@yahoo.com?Subject=Hello%20CW" method="post" enctype="text/plain">
</section>


<footer>
	<!-- <a href="#"><img src="images/instagramlogo.png" alt="Insta logo"></a> -->
	<!-- <a href="#"><img src="images/twitter.png" alt="Twitter logo"></a> -->
	<p>&copy;2018 C.W. Kitchen</p>
</footer>



<div id="overlay">
      <div id="overlay-content">
        
        <div id="CranberryPepperSauce">
          <h3>Cranberry Pepper Sauce</h3>
          <img src="images/CranberryPSsize25.jpg" alt="" title="">
          <div class="product-description">
            <h4>Product Name</h4>
            <p>Cranberry Pepper Sauce</p>
            <h4>Product Size</h4>
            <p>250 (ml)</p>
            <h4>Product Price</h4>
            <p>$30.00 (TT)</p>
            <h4>About This Product</h4>
            <p>Ingredients: Scotch-Bonnet Peppers, Cranberries, Sugar, Salt, Cinamon</p>
            <!-- <p class="add-to-cart"><a href="#">+ to <span class="fa fa-shopping-cart"></span></a></p> -->
          </div>
        </div>


		<div id="PineapplePepperSauce">
          <h3>Pineapple Pepper Sauce</h3>
          <img src="images/PinapplePS.JPG" alt="" title="">
          <div class="product-description">
            <h4>Product Name</h4>
            <p>Pineapple Pepper Sauce</p>
            <h4>Product Size</h4>
            <p>250 (ml)</p>
            <h4>Product Price</h4>
            <p>$30.00 (TT)</p>
            <h4>About This Product</h4>
            <p>Ingredients: Scotch-Bonnet Peppers, Pineapple Chunks, Salt, Vinegar.</p>
            <!-- <p class="add-to-cart"><a href="#">+ to <span class="fa fa-shopping-cart"></span></a></p> -->
          </div>
        </div>


        <div id="PimentoSeasoning">
          <h3>Pimento Seasoning</h3>
          <img src="images/PimentoS.JPG" alt="" title="">
          <div class="product-description">
            <h4>Product Name</h4>
            <p>Pimento Seasoning</p>
            <h4>Product Size</h4>
            <p>250 (ml)</p>
            <h4>Product Price</h4>
            <p>$22.50 (TT)</p>
            <h4>About This Product/Ingredients</h4>
            <p>Ingredients: Pimento Seasoning Peppers, Garlic, Salt, Ginger.</p>
            <!-- <p class="add-to-cart"><a href="#">+ to <span class="fa fa-shopping-cart"></span></a></p> -->
          </div>
        </div>



        <div id="MesmorizingSeasoning">
          <h3>Pimento Seasoning</h3>
          <img src="images/GreenSeasoning.JPG" alt="" title="">
          <div class="product-description">
            <h4>Product Name</h4>
            <p>Mesmorizing Seasoning</p>
            <h4>Product Size</h4>
            <p>750 (ml) | 500 (ml)</p>
            <h4>Product Price</h4>
            <p>$25.00 (TT) | $20.00 (TT)</p>
            <h4>About This Product</h4>
            <p>Ingredients: Pimento Seasoning Peppers, Chives, Celery, Ginger, Chadon Beni, Thyme, Salt, Vinegar, Lemon Juice, Clove</p>
            <!-- <p class="add-to-cart"><a href="#">+ to <span class="fa fa-shopping-cart"></span></a></p> -->
          </div>
        </div>


        <div id="EnchantingPepperSauce">
          <h3>Pimento Seasoning</h3>
          <img src="images/EnchantingPS.jpg" alt="" title="">
          <div class="product-description">
            <h4>Product Name</h4>
            <p>Enchanting Pepper Sauce</p>
            <h4>Product Size</h4>
            <p>300 (ml) | 250 (ml)</p>
            <h4>Product Price</h4>
            <p>$15.00 (TT) | $20.00 (TT)</p>
            <h4>About This Product/Ingredients</h4>
            <p>Garlic, Salt, Ginger and Pimento/Seasoning Peppers.</p>
           <!--  <p class="add-to-cart"><a href="#">+ to <span class="fa fa-shopping-cart"></span></a></p> -->
          </div>
        </div>


    </div>
      <a href="#" id="overlay-close" class="fa fa-close"></a>

    </div>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/1.11.3/jquery.min.js"></script>
    <script src="project.js"></script>

</body>
</html>
