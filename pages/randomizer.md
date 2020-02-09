---
layout: page
title: Who's That Champion?
permalink: edDyNto6cs7r7p8s36sY

---
<center>

<img src="https://github.com/UNSWLoLSoc/LoLSocWebpage/blob/master/uploads/1-1.png?raw=true" width="500" height="600" class="center" id = "test">

</center>

<center>  
<button type="button" id = "soln"  onclick="reveal()">Reveal Solution</button>

<button type="button" onclick="reRoll()">Re-roll</button>

</center>

<script type = "text/javascript">

    var prev = 0; 
    function reRoll(){
      dice1 = Math.floor(Math.random() * 3) + 1;
      console.log("before" + dice1 + " " + prev);
      if(dice1 == prev) {
          dice1++;
      }
      prev = dice1;
      console.log("after" + dice1 + " " + prev);
      var string = "https://raw.githubusercontent.com/UNSWLoLSoc/LoLSocWebpage/master/uploads/Silhouette/"
      switch(dice1) {
        case 1:
          string.concat("1.png");
          break;
    
        case 2:
          document.getElementById("test").src="https://cdn.discordapp.com/attachments/410167703043702794/675588173841301525/IMG_20200207_222553.jpg";
          break;
    
        case 3:
          document.getElementById("test").src="https://i.imgur.com/RYm7WP2.jpg";
          break;
    
        case 4:
          document.getElementById("test").src="https://cdn.discordapp.com/attachments/454659822579875851/675865896186806312/83915101_2241594432809064_5953722011183218688_o.png";
          break;
      }
      document.getElementById("test").src= string;
    }
    
    function reveal(){
      switch(prev) {
        case 1:
          document.getElementById("test").src="";
          break;
    
        case 2:
          document.getElementById("test").src="";
          break;
    
        case 3:
          document.getElementById("test").src="";
          break;
    
        case 4:
          document.getElementById("test").src="";
          break;
      }
    }

</script>