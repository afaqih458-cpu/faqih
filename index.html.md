#   
<!DOCTYPE html>  
<html lang="id">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>Arga & Nara Wedding</title>  
  
<style>  
*{margin:0;padding:0;box-sizing:border-box}  
body{  
  font-family: 'Georgia', serif;  
  background:#faf9f7;  
  color:#333;  
  text-align:center;  
}  
section{padding:60px 20px}  
h1{font-size:38px;margin-bottom:10px}  
h2{font-size:26px;margin-bottom:20px}  
p{line-height:1.8;font-size:16px}  
.card{  
  background:#fff;  
  max-width:650px;  
  margin:auto;  
  padding:35px;  
  border-radius:14px;  
  box-shadow:0 10px 30px rgba(0,0,0,.08)  
}  
.btn{  
  display:inline-block;  
  margin:12px;  
  padding:14px 30px;  
  background:#8b6f47;  
  color:#fff;  
  text-decoration:none;  
  border-radius:40px;  
  font-size:15px  
}  
.countdown{  
  display:flex;  
  justify-content:center;  
  gap:15px;  
  margin-top:25px;  
  flex-wrap:wrap  
}  
.time{  
  background:#fff;  
  padding:15px;  
  border-radius:12px;  
  min-width:80px;  
  box-shadow:0 5px 15px rgba(0,0,0,.06)  
}  
footer{  
  padding:50px 20px;  
  color:#777;  
  font-size:14px  
}  
</style>  
</head>  
  
<body>  
  
<section>  
  <h2>The Wedding of</h2>  
  <h1>Arga & Nara</h1>  
</section>  
  
<section class="card">  
  <p>Assalamu’alaikum Warahmatullahi Wabarakatuh</p><br>  
  <p>Dengan memohon rahmat dan ridho Allah SWT, kami bermaksud mengundang Bapak/Ibu/Saudara/i untuk menghadiri pernikahan kami.</p>  
</section>  
  
<section>  
  <h2>💍 Mempelai</h2>  
  <p><strong>Arga Pratama</strong><br>Putra Bapak A & Ibu B</p><br>  
  <p><strong>Nara Kirana</strong><br>Putri Bapak C & Ibu D</p>  
</section>  
  
<section class="card">  
  <h2>🕊 Akad Nikah</h2>  
  <p>Sabtu, 12 Juli 2026</p>  
  <p>08.00 WIB – selesai</p>  
  <p>Masjid An-Nur, Jakarta</p>  
</section>  
  
<section class="card" style="margin-top:30px">  
  <h2>🎉 Resepsi</h2>  
  <p>Sabtu, 12 Juli 2026</p>  
  <p>11.00 – 14.00 WIB</p>  
  <p>Gedung Serbaguna Harmoni, Jakarta</p>  
  <a class="btn" href="https://maps.google.com" target="_blank">📍 Google Maps</a>  
</section>  
  
<section>  
  <h2>⏳ Hitung Mundur</h2>  
  <div class="countdown">  
    <div class="time"><span id="days">0</span><br>Hari</div>  
    <div class="time"><span id="hours">0</span><br>Jam</div>  
    <div class="time"><span id="minutes">0</span><br>Menit</div>  
    <div class="time"><span id="seconds">0</span><br>Detik</div>  
  </div>  
</section>  
  
<section class="card">  
  <p>Merupakan suatu kehormatan dan kebahagiaan bagi kami apabila Bapak/Ibu/Saudara/i berkenan hadir dan memberikan doa restu.</p>  
  <a class="btn" href="https://wa.me/6281234567890" target="_blank">💬 RSVP WhatsApp</a>  
</section>  
  
<footer>  
  <p>Terima kasih atas doa dan restu Anda</p>  
  <p><strong>Arga & Nara</strong></p>  
</footer>  
  
<script>  
const weddingDate = new Date("July 12, 2026 08:00:00").getTime();  
setInterval(() => {  
  const now = new Date().getTime();  
  const distance = weddingDate - now;  
  
  document.getElementById("days").innerHTML = Math.floor(distance / (1000 * 60 * 60 * 24));  
  document.getElementById("hours").innerHTML = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));  
  document.getElementById("minutes").innerHTML = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));  
  document.getElementById("seconds").innerHTML = Math.floor((distance % (1000 * 60)) / 1000);  
}, 1000);  
</script>  
  
</body>  
</html>  
