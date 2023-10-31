<!DOCTYPE html>
<html lang="en">
<head>
<title>Adon's kicks</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Roboto">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
</head>
<body class="w3-content" style="max-width:1200px">

<!-- Sidebar/menu -->
<nav class="w3-sidebar w3-bar-block w3-white w3-collapse w3-top" style="z-index:3;width:250px" id="mySidebar">
  <div class="w3-container w3-display-container w3-padding-16">
    <i onclick="w3_close()" class="fa fa-remove w3-hide-large w3-button w3-display-topright"></i>
    <h3 class="w3-wide"><b>Adon's kicks</b></h3>
  </div>
  <div class="w3-padding-64 w3-large w3-text-grey" style="font-weight:bold">
    <a href="#" class="w3-bar-item w3-button">Hats</a>
    <a href="#" class="w3-bar-item w3-button">Shirts</a>
    <a href="#" class="w3-bar-item w3-button">Jumpers/Jackets</a>
    <a href="#" class="w3-bar-item w3-button">Pants</a>
     <a onclick="myAccFunc()" href="javascript:void(0)" class="w3-button w3-block w3-white w3-left-align" id="myBtn">
      Shoes <i class="fa fa-caret-down"></i>
    </a>
    <div id="demoAcc" class="w3-bar-block w3-hide w3-padding-large w3-medium">
      <a href="#" class="w3-bar-item w3-button">All shoes</a>
      <a href="#" class="w3-bar-item w3-button">Nike</a>
      <a href="#" class="w3-bar-item w3-button">Jordan</a>
      <a href="#" class="w3-bar-item w3-button">Adidas</a>
      <a href="#" class="w3-bar-item w3-button">Converse</a>
      <a href="#" class="w3-bar-item w3-button">Reebok</a>
      <a href="#" class="w3-bar-item w3-button">New Balance</a>
      <a href="#" class="w3-bar-item w3-button">Puma</a>
      <a href="#" class="w3-bar-item w3-button">Vans</a>
      <a href="#" class="w3-bar-item w3-button">Crocs</a>
    </div>
  <a href="#footer" class="w3-bar-item w3-button w3-padding">Contact</a> 
  <a href="javascript:void(0)" class="w3-bar-item w3-button w3-padding" onclick="document.getElementById('newsletter').style.display='block'">Newsletter</a> 
  <a href="#footer"  class="w3-bar-item w3-button w3-padding">Subscribe</a>
</nav>

<!-- Top menu on small screens -->
<header class="w3-bar w3-top w3-hide-large w3-black w3-xlarge">
  <div class="w3-bar-item w3-padding-24 w3-wide">Adon's kicks</div>
  <a href="javascript:void(0)" class="w3-bar-item w3-button w3-padding-24 w3-right" onclick="w3_open()"><i class="fa fa-bars"></i></a>
</header>

<!-- Overlay effect when opening sidebar on small screens -->
<div class="w3-overlay w3-hide-large" onclick="w3_close()" style="cursor:pointer" title="close side menu" id="myOverlay"></div>

<!-- !PAGE CONTENT! -->
<div class="w3-main" style="margin-left:250px">

  <!-- Push down content on small screens -->
  <div class="w3-hide-large" style="margin-top:83px"></div>
  
  <!-- Top header -->
  <header class="w3-container w3-xlarge">
    <p class="w3-left">Home Page</p>
    <p class="w3-right">
      <i class="fa fa-shopping-cart w3-margin-right"></i>
      <i class="fa fa-search"></i>
    </p>
  </header>

  <!-- Image header -->
  <div class="w3-display-container w3-container">
    <img src="https://www.picclickimg.com/-HgAAOSwEoRlNjJP/US8-With-Box-2007-Nike-Ajf5-Fusion-Air.webp" alt="Image of my favourite shoe which is the Air Jordan 5 fusion Air Force 1 in the stealth white black bright cactus colourway" style="width:100%">
    <div class="w3-display-topleft w3-text-white" style="padding:24px 48px">
      <h1 class="w3-jumbo w3-hide-small">New arrivals</h1>
      <h1 class="w3-hide-large w3-hide-medium">New arrivals</h1>
      <h1 class="w3-hide-small">COLLECTION 2016</h1>
      <p><a href="#jeans" class="w3-button w3-black w3-padding-large w3-large">SHOP NOW</a></p>
    </div>
  </div>

  <div class="w3-left w3-text-black" id="jeans">
    <p>Hottest sneakers of the year</p>
  </div>
  
  <div class="w3-right text-black" id="jeans">
	<p>View More</p>
  </div>

  <!-- Product grid -->
  <div class="w3-row">
    <div class="w3-col l3 s6">
      <div class="w3-container">
        <img src="https://cdn.shopify.com/s/files/1/0094/2252/files/4_3a7fad0e-b888-4d4a-a45e-0331807483a4.jpg?v=1679404436&width=480%0A" height="200" width="200">
        <p>KITH x Clarks x adidas Samba<br><b>From $578</b></p>
      </div>
      <div class="w3-container">
        <img src="https://cdn.shopify.com/s/files/1/0260/3241/files/September_20_2023-Asics-GMBH-Legacy-02_2048x2048.jpg?v=1695241627" height="200" width="200">
        <p>ASICS x GmbH – GEL-KAYANO LEGACY<br><b>From $283</b></p>
      </div>
    </div>

    <div class="w3-col l3 s6">
      <div class="w3-container">
        <div class="w3-display-container">
          <img src="https://www.newbalance.com.au/dw/image/v2/AASX_PRD/on/demandware.static/-/Library-Sites-NBAU-NBNZ/default/dwe9d6dab6/test-comp-images/comp-s/13681_Comp_E2_Image1.jpg?sw=991&sfrm=jpg" height="200" width="200">
          <div class="w3-display-middle w3-display-hover">
            <button class="w3-button w3-black">Buy now <i class="fa fa-shopping-cart"></i></button>
          </div>
        </div>
        <p>New Balance x Stone Island 574 Legacy<br><b>From $437</b></p>
      </div>
      <div class="w3-container">
        <img src="https://cdn.sanity.io/images/c1chvb1i/production/62eef869f1def0a3d703546cadc2a004fa57f127-1200x631.jpg?rect=39,0,1122,631&w=1200&h=675" height="200" width="200">
        <p>Adidas Stan Smith Homer Simpson<br><b>From $185</b></p>
      </div>
    </div>

    <div class="w3-col l3 s6">
      <div class="w3-container">
        <img src="https://solematesneakers.com/cdn/shop/products/image_1f6915b2-b068-468c-bc8f-7db72c34dc1d.png?v=1679527831&width=1445" height="200" width="200">
        <p>Nike Jordan 4 Retro SB<br><b>From $516</b></p>
      </div>
      <div class="w3-container">
        <div class="w3-display-container">
          <img src="https://solematesneakers.com/cdn/shop/products/image_aef70c50-6f6a-4306-914b-71e2ab1cace5.png?v=1682224509&width=1946" height="200" width="200">
          <div class="w3-display-middle w3-display-hover">
            <button class="w3-button w3-black">Buy now <i class="fa fa-shopping-cart"></i></button>
          </div>
        </div>
        <p>New Balance x Aimé Leon Dore 860v2<br><b class="w3-text-black">From $520</b></p>
      </div>
    </div>

    <div class="w3-col l3 s6">
      <div class="w3-container">
        <img src="https://sneakernews.com/wp-content/uploads/2023/01/CORTEIZ-Nike-Air-Max-95-2023-17.jpg" height="200" width="200">
        <p>Corteiz x Nike Air Max 95 SP<br><b>From $470</b></p>
      </div>
      <div class="w3-container">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcT2EtqT8JetrLgMEOyQLhFrhexQDTKzBcABgqLqqUeMfIFNyB7nAu0RNTwuoVc1ItVG_hA:https://uk.bape.com/cdn/shop/files/001FWJ732905_BEI_A_0d04dc4d-4702-4f28-9ec2-76763e381e24.jpg%3Fv%3D1695723750%26width%3D1200&usqp=CAU" height="200" width="200">
        <p>BAPE x Highsnobiety BAPE STA<br><b>From $550</b></p>
      </div>
    </div>
  </div>
  
      <div class="w3-center w3-padding-32">
      <div class="w3-bar">
        <a href="#" class="w3-bar-item w3-button w3-hover-black">«</a>
        <a href="#" class="w3-bar-item w3-black w3-button">1</a>
        <a href="#" class="w3-bar-item w3-button w3-hover-black">2</a>
        <a href="#" class="w3-bar-item w3-button w3-hover-black">3</a>
        <a href="#" class="w3-bar-item w3-button w3-hover-black">4</a>
        <a href="#" class="w3-bar-item w3-button w3-hover-black">»</a>
      </div>
    </div>

<div>
<p style="font-size: 20px; color:#1F9AFE;">
<a href="Webpage_FilePath">About this site</a>
</p>
</div>

  <!-- Subscribe section -->
  <div class="w3-container w3-black w3-padding-32">
    <h1>Subscribe</h1>
    <p>To get special offers and VIP treatment:</p>
    <p><input class="w3-input w3-border" type="text" placeholder="Enter e-mail" style="width:100%"></p>
    <button type="button" class="w3-button w3-red w3-margin-bottom">Subscribe</button>
  </div>
  
  <!-- Footer -->
  <footer class="w3-padding-64 w3-light-grey w3-small w3-center" id="footer">
    <div class="w3-row-padding">
      <div class="w3-col s4">
        <h4>Contact</h4>
        <p>Questions? Go ahead.</p>
        <form action="/action_page.php" target="_blank">
          <p><input class="w3-input w3-border" type="text" placeholder="Name" name="Name" required></p>
          <p><input class="w3-input w3-border" type="text" placeholder="Email" name="Email" required></p>
          <p><input class="w3-input w3-border" type="text" placeholder="Subject" name="Subject" required></p>
          <p><input class="w3-input w3-border" type="text" placeholder="Message" name="Message" required></p>
          <button type="submit" class="w3-button w3-block w3-black">Send</button>
        </form>
      </div>

      <div class="w3-col s4">
        <h4>About</h4>
        <p><a href="#">About us</a></p>
        <p><a href="#">We're hiring</a></p>
        <p><a href="#">Support</a></p>
        <p><a href="#">Find store</a></p>
        <p><a href="#">Shipment</a></p>
        <p><a href="#">Payment</a></p>
        <p><a href="#">Gift card</a></p>
        <p><a href="#">Return</a></p>
        <p><a href="#">Help</a></p>
      </div>

      <div class="w3-col s4 w3-justify">
        <h4>Store</h4>
        <p><i class="fa fa-fw fa-map-marker"></i> Company Name</p>
        <p><i class="fa fa-fw fa-phone"></i> 0044123123</p>
        <p><i class="fa fa-fw fa-envelope"></i> ex@mail.com</p>
        <h4>We accept</h4>
        <p><i class="fa fa-fw fa-cc-amex"></i> Amex</p>
        <p><i class="fa fa-fw fa-credit-card"></i> Credit Card</p>
        <br>
        <i class="fa fa-facebook-official w3-hover-opacity w3-large"></i>
        <i class="fa fa-instagram w3-hover-opacity w3-large"></i>
        <i class="fa fa-snapchat w3-hover-opacity w3-large"></i>
        <i class="fa fa-pinterest-p w3-hover-opacity w3-large"></i>
        <i class="fa fa-twitter w3-hover-opacity w3-large"></i>
        <i class="fa fa-linkedin w3-hover-opacity w3-large"></i>
      </div>
    </div>
  </footer>

  <div class="w3-black w3-center w3-padding-24">Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-opacity">w3.css</a></div>

  <!-- End page content -->
</div>

<!-- Newsletter Modal -->
<div id="newsletter" class="w3-modal">
  <div class="w3-modal-content w3-animate-zoom" style="padding:32px">
    <div class="w3-container w3-white w3-center">
      <i onclick="document.getElementById('newsletter').style.display='none'" class="fa fa-remove w3-right w3-button w3-transparent w3-xxlarge"></i>
      <h2 class="w3-wide">NEWSLETTER</h2>
      <p>Join our mailing list to receive updates on new arrivals and special offers.</p>
      <p><input class="w3-input w3-border" type="text" placeholder="Enter e-mail"></p>
      <button type="button" class="w3-button w3-padding-large w3-red w3-margin-bottom" onclick="document.getElementById('newsletter').style.display='none'">Subscribe</button>
    </div>
  </div>
</div>

<script>
// Accordion 
function myAccFunc() {
  var x = document.getElementById("demoAcc");
  if (x.className.indexOf("w3-show") == -1) {
    x.className += " w3-show";
  } else {
    x.className = x.className.replace(" w3-show", "");
  }
}

// Click on the "Jeans" link on page load to open the accordion for demo purposes
document.getElementById("myBtn").click();


// Open and close sidebar
function w3_open() {
  document.getElementById("mySidebar").style.display = "block";
  document.getElementById("myOverlay").style.display = "block";
}
 
function w3_close() {
  document.getElementById("mySidebar").style.display = "none";
  document.getElementById("myOverlay").style.display = "none";
}
</script>

</body>
</html>
