---
layout: page
title: Who's That Champion?
permalink: edDyNto6cs7r7p8s36sY

---
<center>

<img src="https://github.com/UNSWLoLSoc/LoLSocWebpage/blob/master/uploads/1-1.png?raw=true" width="648" height="648" class="center" id = "test">

</center>

<center>  
<button type="button" id = "soln"  onclick="reveal()" style="background-color: transparent;">Reveal Solution</button>

<button type="button" onclick="reRoll()" style="background-color: transparent;">Re-roll</button>

</center>

<script type = "text/javascript">
    var champion = "champion";
    var prev = 0; 
    function reRoll(){
      dice1 = Math.floor(Math.random() * 19) + 1;
      if(dice1 == prev) {
          dice1++;
      }
      prev = dice1;
      var silhouette = "https://raw.githubusercontent.com/UNSWLoLSoc/LoLSocWebpage/master/uploads/Silhouette/";
      switch(dice1) {
        case 1:
          champion = "alistar";          
          break;
        case 2:
          champion = "amumu";
          break;
        case 3:
          champion = "cass";
          break;
        case 4:
          champion = "diana";
          break;
        case 5:
          champion = "draven";
          break;
        case 6:
          champion = "ekko";
          break;
        case 7:
          champion = "elise";
          break;
        case 8:
          champion = "fiddle";
          break;
        case 9:
          champion = "fiora";
          break;
        case 10:
          champion = "fizz";
          break; 
        case 11:
          champion = "galio";
          break;
        case 12:
          champion = "janna";
          break;
        case 13:
          champion = "kat";
          break;
        case 14:
          champion = "malz";
          break; 
        case 15:
          champion = "ornn";
          break;
        case 16:
          champion = "qiayana";
          break;
        case 17:
          champion = "reksai";
          break;
        case 18:
          champion = "sett";
          break; 
        case 19:
          champion = "shyv";
          break;
        case 20:
          champion = "tristana";
          break;
      }
      silhouette += champion;
      silhouette += ".png";
      document.getElementById("test").src= silhouette;
    }
    
    function reveal(){
    var silhouette = "https://raw.githubusercontent.com/UNSWLoLSoc/LoLSocWebpage/master/uploads/Solutions/";
    document.getElementById("test").src= silhouette + champion + ".png";
    }

</script>
