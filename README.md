<html>
<meta charset='UTF-8' />
<meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport' />
<meta
 content='IE=edge' http-equiv='X-UA-Compatible' />
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Shippori+Antique&display=swap" rel="stylesheet">
<script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js">

</script>
<script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous">

</script>
<link href="https://gdmorning.likeadream.repl.co/style.css" rel="stylesheet" type="text/css" />
<script src="https://gdmorning.likeadream.repl.co/script.js">

</script>

<head>
	<!-- 
This code was made angga.putra3781!
Instagram: @angga.putra3781
Telegram: @Revfliy
-->
</head>

<body>


	<div id="konten">

		<div id="fotoloveu">
			<div class="image"><img id="photo" src="https://i.postimg.cc/Gtjt6YmT/200.gif" width="150px" height="150px"/></div><span id="sp2"></span><span id="sp3"></span></div>

<div id="ftawal"><div class="image">
<img src="https://i.postimg.cc/nrXnY0xL/santuyy.gif" style="border-radius:10px" width="130px" height="130px"/></div></div>

<div id='subkonten'>
<p class='catatan sek' data-text='&#9829;'>
<b style="font-size:1rem">Halo Kamu</b><br>
Selamat Malam. <br>
Jangan lupa bersyukur. <br>
Jaga kesehatanmu. <br>
Jangan begadang terus.
<br>
<i style="font-size:.80rem">Klik  =></i>
<label onClick="expl()">&#128157;</label>
</p>
</div>

<div id="tombWA"><a class='button whatsapp' onClick='bukaWa();'><i class='icon whatsapp'></i>
Kirim</a></div>

</div>

<script> 
function play() {
//Link Audio Bisa Diganti
  var audio = new Audio('https://www.mboxdrive.com/01.mp3');audio.play();} 
//Teks klik love
var a=0,finish;
finish = "Selamat Beristirahat!";
//Teks klik love
var i=0,finish2;
finish2 = "Tidur ya, pulihkan tenagamu. Besok kamu harus semangat lagi :)";          
//Pesan WhatsApp
 function bukaWa(){window.location = "https://api.whatsapp.com/send?phone=&text=Good Night too" + "%0A%0A" + "- " + dateTime;} 
</script>
 
<script type="text/javascript">            
            var today = new Date();var date = today.getDate()+'/'+(today.getMonth()+1)+'/'+today.getFullYear()+'.';var dateTime = date;
            const swals = Swal.mixin({
                allowOutsideClick: false,
            });
            async function mulai(){
                await swals.fire('Special for you');
                setTimeout(showDiv, 900);play();                                      
            }            
            mulai();
</script>
<script>
const body = document.querySelector("body");
function createHeart() {
    const heart = document.createElement("div");
    heart.className = "fas fa-heart";
    heart.style.left = (Math.random() * 90)+"vw";
    heart.style.animationDuration = (Math.random()*3)+2+"s"
    body.appendChild(heart);
}
setInterval(function name(params) {
    var heartArr = document.querySelectorAll(".fa-heart")
    if (heartArr.length > 100) {
       heartArr[0].remove()
    }
},100)
</script>
</body>
</html>
