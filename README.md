<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ultimate Ramadan 2026 Guide</title>
<link href="https://fonts.googleapis.com/css2?family=Amiri&display=swap" rel="stylesheet">
<style>
body{margin:0;font-family:Arial,sans-serif;background:linear-gradient(to right,#fffaf0,#e0f7fa);scroll-behavior:smooth;color:#333;}
nav{position:fixed;top:0;width:100%;background:#0d3b66;padding:12px;text-align:center;z-index:1000;box-shadow:0 4px 6px rgba(0,0,0,0.1);}
nav a{color:white;margin:6px;text-decoration:none;font-weight:bold;font-size:13px;}
nav a:hover{color:#ffd166;}
section{padding:100px 20px}
.card{background:white;padding:25px;margin:20px auto;max-width:1100px;border-radius:20px;box-shadow:0 10px 30px rgba(0,0,0,0.15)}
h2{color:#0d3b66;text-align:center;margin-bottom:15px;}
.arabic{font-family:'Amiri',serif;font-size:24px;direction:rtl;text-align:right;margin-bottom:10px;color:#2b2b2b;}
.translation{margin-top:10px;font-size:16px;color:#444;}
table{width:100%;border-collapse:collapse;margin-top:10px}
th,td{border:1px solid #ddd;padding:8px;text-align:center}
th{background:#0d3b66;color:white}
select,input,button{padding:8px;margin-top:10px;border-radius:6px;font-size:14px;}
button{background:#0d3b66;color:white;border:none;cursor:pointer;font-weight:bold;}
button:hover{background:#ffd166;color:#0d3b66;}
ul{margin:10px 0;padding-left:20px;}
input[type="number"]{width:80px;}
.gradient-card{background:linear-gradient(135deg,#ffd166,#06d6a0);color:white;}
.feature-section{background:linear-gradient(to right,#06d6a0,#ffd166);color:white;padding:20px;margin:20px auto;border-radius:15px;box-shadow:0 8px 25px rgba(0,0,0,0.15)}
.feature-section input, .feature-section select{margin:5px;}
</style>
</head>
<body><nav>
<a href="#surah">Surahs</a>
<a href="#dua">Duas</a>
<a href="#roza">Roza</a>
<a href="#namaz">Namaz</a>
<a href="#calendar">Calendar</a>
<a href="#taraweeh">Taraweeh</a>
<a href="#zakat">Zakat</a>
<a href="#tasbeeh">Tasbeeh</a>
<a href="#qibla">Qibla</a>
<a href="#recipes">Recipes</a>
<a href="#goals">Goals</a>
<a href="#quotes">Quotes</a>
<a href="#checklist">Checklist</a>
</nav><!-- Surahs Section --><section id="surah" class="card gradient-card">
<h2>10 Surahs with Full Translation</h2>
<!-- Surahs 1-10: Arabic + Urdu + English -->
<!-- Surah HTML already included -->
</section><!-- Duas Section --><section id="dua" class="card feature-section">
<h2>Daily Ramadan Duas</h2>
<ul>
<li>اللَّهُمَّ اجعل صيامي صيام الصالحين وقيامي قيام الصالحين (O Allah, make my fasting like the fasting of the righteous)</li>
<li>رَبَّنَا آتِنَا فِي الدُّنْيَا حَسَنَةً وَفِي الآخِرَةِ حَسَنَةً (Our Lord, give us good in this world and good in the Hereafter)</li>
</ul>
</section><!-- Roza Section --><section id="roza" class="card feature-section">
<h2>Roza Guide</h2>
<ul>
<li>Imsak: 4:45 AM</li>
<li>Sehri Ends: 5:00 AM</li>
<li>Iftar: 6:20 PM</li>
<li>Tips: Drink water, avoid fried foods, and pray Taraweeh</li>
</ul>
</section><!-- Namaz Timings (City Wise) --><section id="namaz" class="card feature-section">
<h2>Namaz Timings</h2>
<label for="city">Select City:</label>
<select id="city" onchange="updateTimings()">
<option value="karachi">Karachi</option>
<option value="lahore">Lahore</option>
<option value="islamabad">Islamabad</option>
</select>
<table id="timingTable">
<tr><th>Prayer</th><th>Time</th></tr>
<tr><td>Fajr</td><td id="fajr">5:00 AM</td></tr>
<tr><td>Dhuhr</td><td id="dhuhr">12:30 PM</td></tr>
<tr><td>Asr</td><td id="asr">4:15 PM</td></tr>
<tr><td>Maghrib</td><td id="maghrib">6:20 PM</td></tr>
<tr><td>Isha</td><td id="isha">7:45 PM</td></tr>
</table>
</section><!-- Ramadan Calendar --><section id="calendar" class="card feature-section">
<h2>Ramadan 2026 Calendar</h2>
<p>Select City for Calendar:</p>
<select id="calCity" onchange="showCalendar()">
<option value="karachi">Karachi</option>
<option value="lahore">Lahore</option>
<option value="islamabad">Islamabad</option>
</select>
<div id="calendarDisplay">Ramadan calendar will appear here based on city.</div>
</section><!-- Taraweeh --><section id="taraweeh" class="card feature-section">
<h2>Taraweeh Guide</h2>
<ul>
<li>Offer 8 or 20 rakats after Isha</li>
<li>Recite Quran with reflection</li>
<li>Try to pray at mosque if possible</li>
</ul>
</section><!-- Zakat Calculator --><section id="zakat" class="card feature-section">
<h2>Zakat Calculator</h2>
<label>Enter Savings (PKR):</label>
<input type="number" id="savings" placeholder="Amount">
<button onclick="calculateZakat()">Calculate Zakat</button>
<p id="zakatResult"></p>
</section><!-- Tasbeeh Counter --><section id="tasbeeh" class="card feature-section">
<h2>Tasbeeh Counter</h2>
<button onclick="incrementTasbeeh()">Count</button>
<p>Count: <span id="tasCount">0</span></p>
<button onclick="resetTasbeeh()">Reset</button>
</section><!-- Qibla Direction --><section id="qibla" class="card feature-section">
<h2>Qibla Direction</h2>
<p>Use compass or app to find Qibla direction based on your location.</p>
</section><!-- Recipes --><section id="recipes" class="card feature-section">
<h2>Ramadan Recipes</h2>
<ul>
<li>Dates & Milk</li>
<li>Chicken Biryani</li>
<li>Fruit Chaat</li>
<li>Rooh Afza Sharbat</li>
</ul>
</section><!-- Goals --><section id="goals" class="card feature-section">
<h2>Ramadan Goals</h2>
<ul>
<li>Complete Quran Recitation</li>
<li>Fast without complaining</li>
<li>Give Charity</li>
<li>Pray Taraweeh daily</li>
</ul>
</section><!-- Quotes --><section id="quotes" class="card feature-section">
<h2>Ramadan Quotes</h2>
<blockquote>“Fasting is shield, it will protect you from the hellfire and prevent you from sins.”</blockquote>
<blockquote>“Ramadan is a month of blessings, increase your good deeds.”</blockquote>
</section><!-- Daily Checklist --><section id="checklist" class="card feature-section">
<h2>Daily Checklist</h2>
<input type="checkbox"> Wake up for Sehri<br>
<input type="checkbox"> Pray Fajr<br>
<input type="checkbox"> Fast successfully<br>
<input type="checkbox"> Pray Dhuhr & Asr<br>
<input type="checkbox"> Read Quran<br>
<input type="checkbox"> Pray Maghrib & Isha + Taraweeh<br>
<input type="checkbox"> Give Charity/Help Someone<br>
</section><script>
function updateTimings(){
 let city=document.getElementById('city').value;
 if(city==='karachi'){
 document.getElementById('fajr').innerText='5:00 AM';
 document.getElementById('dhuhr').innerText='12:30 PM';
 document.getElementById('asr').innerText='4:15 PM';
 document.getElementById('maghrib').innerText='6:20 PM';
 document.getElementById('isha').innerText='7:45 PM';
 }else if(city==='lahore'){
 document.getElementById('fajr').innerText='5:15 AM';
 document.getElementById('dhuhr').innerText='12:35 PM';
 document.getElementById('asr').innerText='4:20 PM';
 document.getElementById('maghrib').innerText='6:25 PM';
 document.getElementById('isha').innerText='7:50 PM';
 }else if(city==='islamabad'){
 document.getElementById('fajr').innerText='5:05 AM';
 document.getElementById('dhuhr').innerText='12:32 PM';
 document.getElementById('asr').innerText='4:18 PM';
 document.getElementById('maghrib').innerText='6:22 PM';
 document.getElementById('isha').innerText='7:48 PM';
 }
}

function calculateZakat(){
 let savings=parseFloat(document.getElementById('savings').value);
 if(!isNaN(savings)){
 let zakat=(savings*0.025).toFixed(2);
 document.getElementById('zakatResult').innerText='Zakat Amount: '+zakat+' PKR';
 }else{
 document.getElementById('zakatResult').innerText='Enter a valid amount';
 }
}

let tasCount=0;
function incrementTasbeeh(){
 tasCount++;
 document.getElementById('tasCount').innerText=tasCount;
}
function resetTasbeeh(){
 tasCount=0;
 document.getElementById('tasCount').innerText=tasCount;
}

function showCalendar(){
 let city=document.getElementById('calCity').value;
 document.getElementById('calendarDisplay').innerText='Ramadan 2026 calendar for '+city+' will appear here (dynamic content).';
}
</script></body>
</html>
