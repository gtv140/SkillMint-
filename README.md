<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Complete Ramadan Guide</title>
<link href="https://fonts.googleapis.com/css2?family=Amiri&display=swap" rel="stylesheet">
<style>
body{margin:0;font-family:Arial;background:linear-gradient(to right,#fffaf0,#e0f7fa);scroll-behavior:smooth}
nav{position:fixed;top:0;width:100%;background:#0d3b66;padding:12px;text-align:center;z-index:1000}
nav a{color:white;margin:10px;text-decoration:none;font-weight:bold}
nav a:hover{color:#ffd166}
section{padding:90px 20px}
.card{background:white;padding:20px;margin:20px auto;max-width:1000px;border-radius:12px;box-shadow:0 4px 15px rgba(0,0,0,0.1)}
h2{color:#0d3b66}
.arabic{font-family:'Amiri',serif;font-size:22px;direction:rtl;text-align:right;margin-bottom:10px}
.translation{margin-top:10px;font-size:16px}
table{width:100%;border-collapse:collapse;margin-top:10px}
th,td{border:1px solid #ddd;padding:8px;text-align:center}
th{background:#0d3b66;color:white}
select{padding:8px;margin-top:10px}
ul{margin:10px 0;padding-left:20px}
</style>
</head>
<body>

<nav>
<a href="#surah">Surahs</a>
<a href="#dua">Duas</a>
<a href="#roza">Roza</a>
<a href="#namaz">Namaz</a>
<a href="#calendar">Calendar</a>
<a href="#timings">Namaz Timings</a>
</nav>

<section id="surah" class="card">
<h2>10 Short Surahs with Translation</h2>

<p><b>1. Surah Al-Fatiha</b></p>
<div class="arabic">بِسْمِ اللَّهِ الرَّحْمَٰنِ الرَّحِيمِ ...</div>
<div class="translation"><b>Urdu:</b> اللہ کے نام سے جو نہایت رحم والا، مہربان ہے...<br><b>English:</b> In the name of Allah, the Most Gracious, the Most Merciful...</div>

<p><b>2. Surah Ikhlas</b></p>
<div class="arabic">قُلْ هُوَ اللَّهُ أَحَدٌ ...</div>
<div class="translation"><b>Urdu:</b> کہو اللہ ایک ہے...<br><b>English:</b> Say: He is Allah, the One...</div>

<!-- Continue similarly for Surah 3-10 with Arabic + Urdu + English translation -->
</section>

<section id="dua" class="card">
<h2>Ramzan Special Duas</h2>
<p><b>Roza Dua:</b></p>
<div class="arabic">وَبِصَوْمِ غَدٍ نَّوَيْتُ مِن شَهْرِ رَمَضَانَ</div>
<div class="translation"><b>Urdu:</b> میں کل رمضان کے روزے کے لیے نیت کرتا ہوں<br><b>English:</b> I intend to fast tomorrow in the month of Ramadan</div>
<p><b>Iftar Dua:</b></p>
<div class="arabic">اللَّهُمَّ إِنِّي لَكَ صُمْتُ وَبِكَ آمَنْتُ وَعَلَيْكَ تَوَكَّلْتُ</div>
<div class="translation"><b>Urdu:</b> اے اللہ! میں نے تیرے لیے روزہ رکھا اور تجھ پر ایمان لایا اور تجھ پر بھروسہ کیا<br><b>English:</b> O Allah! I fasted for You, and I believe in You and I put my trust in You</div>
</section>

<section id="roza" class="card">
<h2>Roza (Fasting) Guide</h2>
<ul>
<li>Sehri before Fajr</li>
<li>Make Niyyah (intention) for fasting</li>
<li>Avoid eating, drinking till Maghrib</li>
<li>Break fast with dates & water</li>
<li>Read Quran and Nafl prayers during the day</li>
</ul>
</section>

<section id="namaz" class="card">
<h2>Namaz Guide</h2>
<ul>
<li>Perform Wudu before Salah</li>
<li>Face Qibla</li>
<li>5 Daily Prayers</li>
<li>Include Taraweeh and Nafl prayers</li>
<li>Pray with focus and make Dua after Salah</li>
</ul>
</section>

<section id="calendar" class="card">
<h2>Ramadan 30-Day Calendar</h2>
<table>
<tr><th>Day</th><th>Sehri</th><th>Iftar</th></tr>
<script>
for(let i=1;i<=30;i++){document.write('<tr><td>'+i+'</td><td>04:30 AM</td><td>06:50 PM</td></tr>');}
</script>
</table>
</section>

<section id="timings" class="card">
<h2>Namaz Timings</h2>
<select onchange="changeCity(this.value)">
<option value="karachi">Karachi</option>
<option value="lahore">Lahore</option>
<option value="islamabad">Islamabad</option>
<option value="dubai">Dubai</option>
<option value="london">London</option>
</select>
<table>
<tr><th>Prayer</th><th>Time</th></tr>
<tr><td>Fajr</td><td id="fajr"></td></tr>
<tr><td>Zuhr</td><td id="zuhr"></td></tr>
<tr><td>Asr</td><td id="asr"></td></tr>
<tr><td>Maghrib</td><td id="maghrib"></td></tr>
<tr><td>Isha</td><td id="isha"></td></tr>
</table>
</section>

<script>
const timings={
karachi:{fajr:"4:35 AM",zuhr:"12:30 PM",asr:"4:45 PM",maghrib:"6:55 PM",isha:"8:15 PM"},
lahore:{fajr:"4:20 AM",zuhr:"12:15 PM",asr:"4:30 PM",maghrib:"6:45 PM",isha:"8:00 PM"},
islamabad:{fajr:"4:15 AM",zuhr:"12:10 PM",asr:"4:25 PM",maghrib:"6:40 PM",isha:"7:55 PM"},
dubai:{fajr:"4:50 AM",zuhr:"12:20 PM",asr:"3:50 PM",maghrib:"6:30 PM",isha:"7:45 PM"},
london:{fajr:"3:45 AM",zuhr:"1:00 PM",asr:"5:00 PM",maghrib:"8:20 PM",isha:"9:45 PM"}
};
function changeCity(city){
document.getElementById("fajr").innerText=timings[city].fajr;
document.getElementById("zuhr").innerText=timings[city].zuhr;
document.getElementById("asr").innerText=timings[city].asr;
document.getElementById("maghrib").innerText=timings[city].maghrib;
document.getElementById("isha").innerText=timings[city].isha;
}
changeCity("karachi");
</script>

</body>
</html>
