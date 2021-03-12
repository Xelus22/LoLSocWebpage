---
layout: post
title: Gangplank, The Saltwater Scourge
subtitle: ''
gallery: []

---
<h4> Gangplank Art </h4>
<meta name="viewport" content="width=device-width, initial-scale=1">

<body>

<div class="slideshow-container">
  <div class="mySlides fade">
    <div class="numbertext">1 / 7</div>
    <img src="https://github.com/UNSWLoLSoc/LoLSocWebpage/blob/master/uploads/young-gangplank-saved-by-illaoi.png?raw=true" style="width:100%">
    <div class="text">Young Gangplank saved by Illaoi</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">2 / 7</div>
    <img src="https://github.com/UNSWLoLSoc/LoLSocWebpage/blob/master/uploads/gangplank-shotting-miss-fortune-and-her-parents.jpg?raw=true" style="width:100%">
    <div class="text">Gangplank shooting Miss Fortune and her parents</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">3 / 7</div>
    <img src="https://github.com/UNSWLoLSoc/LoLSocWebpage/blob/master/uploads/the-dreadway.png?raw=true" style="width:100%">
    <div class="text">The Dreadway Warship</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">4 / 7</div>
    <img src="https://github.com/UNSWLoLSoc/LoLSocWebpage/blob/master/uploads/the-leviathan.png?raw=true" style="width:100%">
    <div class="text">The Leviathan Warship</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">5 / 7</div>
    <img src="https://github.com/UNSWLoLSoc/LoLSocWebpage/blob/master/uploads/gangplank_and_his_jagged_hooks.jpg?raw=true" style="width:100%">
    <div class="text">Gangplank and his Jagged Hooks</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">6 / 7</div>
    <img src="https://github.com/UNSWLoLSoc/LoLSocWebpage/blob/master/uploads/miss-fortune-planning-her-revenge-on-gangplank.png?raw=true" style="width:100%">
    <div class="text">Miss Fortune planning her revenge on Gangplank</div>
  </div>

  <div class="mySlides fade">
    <div class="numbertext">7 / 7</div>
    <img src="https://github.com/UNSWLoLSoc/LoLSocWebpage/blob/master/uploads/gangplank-before-_left_-and-after-_right_-being-shot-by-miss-fortune.jpg?raw=true" style="width:100%">
    <div class="text">Gangplank before (left) and after (right) being shot by Miss Fortune</div>
  </div>

  <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
  <a class="nextbut" onclick="plusSlides(1)">&#10095;</a>
</div>

<br>

<div style="text-align:center">
    <span class="dot" onclick="currentSlide(1)"></span> 
    <span class="dot" onclick="currentSlide(2)"></span> 
    <span class="dot" onclick="currentSlide(3)"></span> 
    <span class="dot" onclick="currentSlide(4)"></span> 
    <span class="dot" onclick="currentSlide(5)"></span> 
    <span class="dot" onclick="currentSlide(6)"></span> 
    <span class="dot" onclick="currentSlide(7)"></span> 
</div>

<script>
var slideIndex = 1;
showSlides(slideIndex);

function plusSlides(n) {
  showSlides(slideIndex += n);
}

function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("dot");
  if (n > slides.length) {slideIndex = 1}    
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
      slides[i].style.display = "none";  
  }
  for (i = 0; i < dots.length; i++) {
      dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";  
  dots[slideIndex-1].className += " active";
}
</script>

</body>