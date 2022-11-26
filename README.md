<html>
<meta charset='UTF-8'/><meta content='width=device-width, initial-scale=1, user-scalable=1, minimum-scale=1, maximum-scale=5' name='viewport'/><meta content='IE=edge' http-equiv='X-UA-Compatible'/><link rel="preconnect" href="https://fonts.googleapis.com"><link rel="preconnect" href="https://fonts.gstatic.com" crossorigin><link href="https://fonts.googleapis.com/css2?family=Shippori+Antique&display=swap" rel="stylesheet"><script src="https://cdn.jsdelivr.net/npm/sweetalert2@11.0.19/dist/sweetalert2.all.min.js"></script><link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@sweetalert2/theme-dark/dark.css"><script src="https://kit.fontawesome.com/4f3ce16e3e.js" crossorigin="anonymous"></script><link href="https://kuisberhadiah.likeadream.repl.co/style.css" rel="stylesheet" type="text/css" /><!--<script src="https://bukadulu.likeadream.repl.co/script.js"></script>-->
<head>
<!-- 
This code was made by agustinusadikristanto!
Instagram: @agustinusadikristanto
TikTok: @agustinusadikristanto_
-->
</head>
<body>
<style>
body{background-image: url("https://i.postimg.cc/gkQQfPGf/2142515969.png");background-repeat: no-repeat;background-size: 150% 100% 100%;}
</style><div id="bodyblur"></div>

<div id="konten"><div id="fotoloveu"><div class="image">
<!-- Foto Akhir --><img src="https://i.postimg.cc/J4yZ52pT/keju-joget-brando.gif" id="animasi" width="130px" height="130px"/></div></div>

<div id="konten"><div id="fotoloveu"><div class="image">
<!-- Foto Akhir --><img src="https://i.postimg.cc/J4yZ52pT/keju-joget-brando.gif" id="animasi" width="130px" height="130px"/></div></div>


<p class='catatan' id='koteks'>
<marquee scrollamount="8" id="marq"><i id="spasi"></i>
Yaudah si gitu doang hehe<i id="spasi"></i>
:v&#128511;<i id="spasi"></i>
yahaha wahyu<i id="spasi"></i>
by agustinus adi kristanto&#129395;&#129395;&#129395;</marquee>
</p>

<!-- Tombol WA --><div id="tombWA"><a class='button' onClick='bukaWa();'>Kirim Pesan</a></div>

</div>

<script>
function play() {//Link Au
var audio = new Audio('https://raw.githubusercontent.com/agustinus12345/aduio/main/slow.mp3');audio.play();audio.loop=true;audio.addEventListener('ended', function() {this.currentTime = 1;this.play();}, false);}         

//Pesan WhatsApp
 function bukaWa(){window.location = "https://api.whatsapp.com/send?phone=&text=" + window.nama + " contoh text balasan bisa diubah" + "%0A%0A" + "lanjutan teks balasan  ><";} 
</script>
 
<script type="text/javascript">            
            var today = new Date();var date = today.getDate()+'/'+(today.getMonth()+1)+'/'+today.getFullYear()+'.';var dateTime = date;
            const swals = Swal.mixin({
                backdrop: 'rgba(0,0,123,0.4)', confirmButtonColor: '#003EFF', cancelButtonColor: '#FF0040', allowOutsideClick: false,
            });
            async function mulai(){          	
                var { value: nama } = await swals.fire({
                    title: 'Nama kamu?',
                    input: 'text',
                    confirmButtonText: 'Lanjut',
                    showCancelButton: false,
                });                           
                if(nama && nama.length < 11){
                	play();
                	window.nama = nama;
                    await swals.fire('moshi moshi ' + nama + ' chan ツ');
                    await swals.fire('oyasuminasai');
                    await swals.fire('bingung mo ketik apaan :v &#128514;');
                    await swals.fire('makan dulu sanah!');
                    await swals.fire('mau lanjut ?');
                    await swals.fire('yakin lanjut nih ?');
                    await swals.fire('makan dulu tapi hehe');
                    await swals.fire('oke lanjut ya');
                    await swals.fire('3');
                    await swals.fire('2');
                    await swals.fire('1');
                    await swals.fire('0');
                    await swals.fire('wkwkwkwk nungguin ya');
                    await swals.fire('yaudah nih lanjut ya');
                    await swals.fire('kali ini beneran lanjut kok wkwk');
                    await swals.fire('3');
                    await swals.fire('2');
                    await swals.fire('1');
                    await swals.fire('0');

                    pilihwarna();
                //                                   
                } else {
                    await swals.fire('Ups!', 'Nama tidak boleh kosong atau lebih dari 10 karakter, ya!');
                    mulai();
                }
            }            
            mulai();
</script>
<!-- Di bawah ini JANGAN DIEDIT SEMBARANGAN -->
<script>
  function tombol() {document.getElementById('tombWA').style.visibility = "visible";document.getElementById('tombWA').style.opacity = "1";}  
  async function expl(){document.getElementById('bodyblur').style.opacity = "1";document.getElementById('bodyblur').style.visibility = "visible";setTimeout(duar,200);}
  
async function duar(){
var e1 = document.getElementById('animasi');e1.classList.add("degdeg");
document.getElementById('konten').style.top = "0";document.getElementById('fotoloveu').style.opacity = "1";document.getElementById('fotoloveu').style.height = "140px";document.getElementById('fotoloveu').style.margin = "50px 0 0 0";document.getElementById('koteks').style.opacity = "1";
setTimeout(tombol,4000);setInterval(createHeart,200);
document.body.style.backgroundColor = "#000";
}

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
},100);

function StartMarquee(){var marquee = document.getElementById ("marq");marquee.start();}
function StopMarquee(){var marquee = document.getElementById ("marq");marquee.stop();}
StopMarquee();

async function pilihwarna(){
  var { isConfirmed: warna } = await swals.fire({
  title: 'Oh iya, ' + nama + ' kamu mau pilih warna apa nih?',
  text: 'Ayo, jangan ragu-ragu...',
  showCancelButton: true,
  confirmButtonText: 'Biru',
  cancelButtonText: 'Merah',
});
if(warna){
    await swals.fire('Yeayy!', 'Kalo kamu pilih <b>Biru</b> yahaha yanto warnanya biru &#129315;!');
    var { isConfirmed: warna2 } = await swals.fire({
    title: nama + ' yakin pilih warna Biru?', 
    text: 'Atau mau ganti warna aja nih?', showCancelButton: true,
    confirmButtonText: 'Yakin',
    cancelButtonText: 'Ganti',
});
if(warna2){
    await swals.fire('Oke!', `aku main dulu yaa cantik hehehe &#10084;&#65039;`);
    expl();StartMarquee();
  } else {
    await swals.fire('Oke, memilih Merah!', 'Sama aja sih sebenernya, sebenarnya merah/biru sama aja si biar tambah panjang aja hehe &#129315;');
    expl();StartMarquee();
}
//Selingan
  } else {
    await swals.fire('Yeayy!', 'Kalo kamu pilih <b>Merah</b> yahaha yanto warnanya merah &#129315;!');
    var { isConfirmed: warna2 } = await swals.fire({
    title: nama + ' yakin pilih warna Merah?', 
    text: 'Atau mau ganti warna aja nih?', showCancelButton: true,
    confirmButtonText: 'Ganti',
    cancelButtonText: 'Yakin',
});
if(warna2){    
    await swals.fire('Oke, memilih Biru!', 'sebenarnya merah/biru sama aja si biar tambah panjang aja hehe &#129315;');
    expl();StartMarquee();
  } else {
    await swals.fire('Oke!', `aku main dulu ya cantik hehehe &#10084;&#65039;`);
    expl();StartMarquee();
    await swals.fire('Oke!', `yang ini abaikan aja ya wkwkwkwk iseng aja hehehe &#10084;&#65039;`);
    expl();StartMarquee();
}
}
}
</script>
   <audio controls autoplay>
        <source src="slow.mp3" type="audio/mpeg">
    </audio>
</body>
</html>
