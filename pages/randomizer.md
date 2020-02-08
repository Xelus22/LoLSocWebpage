---
layout: page
title: Who's That Champion?
permalink: edDyNto6cs7r7p8s36sY

---
<center>

<img src="https://github.com/UNSWLoLSoc/LoLSocWebpage/blob/master/uploads/1-1.png?raw=true" width="500" height="600" class="center" id = "test">

</center>

<script type = "text/javascript">
document.getElementById('test').onclick= function(){
  	var prev = 0;
	dice1 = Math.floor(Math.random() * 3) + 1;
  	console.log(dice1);
  	if(dice1 == prev) {
     	dice1++;
      	prev++;
    }
  	switch(dice1) {
      case 1:
        document.getElementById("test").src="https://cdn.discordapp.com/attachments/484757042226135050/599894159213723648/0098rwcomh931.jpg";
        break;
        
      case 2:
        document.getElementById("test").src="https://cdn.discordapp.com/attachments/410167703043702794/675588173841301525/IMG_20200207_222553.jpg";
        break;
        
      case 3:
        document.getElementById("test").src="https://i.imgur.com/RYm7WP2.jpg";
        break;
        
      case 4:
        document.getElementById("test").src="https://i.imgur.com/RYm7WP2.jpg";
        break;
    }
}
</script>