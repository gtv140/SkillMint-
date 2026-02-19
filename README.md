<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Ultimate Ramadan 2026 Guide</title>
<link href="https://fonts.googleapis.com/css2?family=Amiri&display=swap" rel="stylesheet">
<style>
:root{
  --bg-light:#fffaf0;
  --bg-dark:#121212;
  --text-light:#333;
  --text-dark:#eee;
  --card-bg-light:#fff;
  --card-bg-dark:#1e1e1e;
  --primary:#0d3b66;
  --accent:#ffd166;
}
body{
  margin:0;
  font-family:Arial,sans-serif;
  background:var(--bg-light);
  color:var(--text-light);
  scroll-behavior:smooth;
  transition:0.3s;
}
nav{
  position:fixed;
  top:0;
  width:100%;
  background:var(--primary);
  padding:12px;
  text-align:center;
  z-index:1000;
  box-shadow:0 4px 6px rgba(0,0,0,0.1);
}
nav a{
  color:white;
  margin:8px;
  text-decoration:none;
  font-weight:bold;
  font-size:14px;
}
nav a:hover{color:var(--accent);}
section{
  padding:90px 20px;
  transition:0.3s;
}
.card{
  background:var(--card-bg-light);
  padding:20px;
  margin:20px auto;
  max-width:1000px;
  border-radius:15px;
  box-shadow:0 8px 25px rgba(0,0,0,0.15);
  transition:0.3s;
}
h2{
  color:var(--primary);
  text-align:center;
}
.arabic{
  font-family:'Amiri',serif;
  font-size:24px;
  direction:rtl;
  text-align:right;
  margin-bottom:10px;
  color:var(--text-light);
}
.translation{
  margin-top:10px;
  font-size:16px;
  color:var(--text-light);
}
table{width:100%;border-collapse:collapse;margin-top:10px;}
th,td{border:1px solid #ddd;padding:8px;text-align:center;}
th{background:var(--primary);color:white;}
select,input,button{padding:8px;margin-top:10px;border-radius:6px;font-size:14px;}
button{background:var(--primary);color:white;border:none;cursor:pointer;font-weight:bold;}
button:hover{background:var(--accent);color:var(--primary);}
ul{margin:10px 0;padding-left:20px;}
input[type="number"]{width:80px;}
.gradient-card{background:linear-gradient(135deg,#ffd166,#06d6a0);color:white;}
.dark-mode{
  background:var(--bg-dark);
  color:var(--text-dark);
}
.dark-mode .card{
  background:var(--card-bg-dark);
  color:var(--text-dark);
}
.dark-mode .arabic{color:#ffd166;}
.dark-mode .translation{color:#eee;}
#futures{position:fixed;bottom:10px;right:10px;z-index:1001;}
#futures button{margin:2px;padding:6px 10px;font-size:12px;border-radius:6px;}
</style>
</head>
<body>

<nav>
<a href="#surah" data-en="Surahs" data-ur="سورۃ">Surahs</a>
<a href="#dua" data-en="Duas" data-ur="دعائیں">Duas</a>
<a href="#roza" data-en="Roza" data-ur="روزہ">Roza</a>
<a href="#namaz" data-en="Namaz" data-ur="نماز">Namaz</a>
<a href="#calendar" data-en="Calendar" data-ur="کیلنڈر">Calendar</a>
<a href="#taraweeh" data-en="Taraweeh" data-ur="ترواہی">Taraweeh</a>
<a href="#zakat" data-en="Zakat" data-ur="زکوة">Zakat</a>
<a href="#tasbeeh" data-en="Tasbeeh" data-ur="تسبیح">Tasbeeh</a>
<a href="#qibla" data-en="Qibla" data-ur="قبلہ">Qibla</a>
<a href="#recipes" data-en="Recipes" data-ur="پکوان">Recipes</a>
<a href="#goals" data-en="Goals" data-ur="مقاصد">Goals</a>
<a href="#quotes" data-en="Quotes" data-ur="اقتباسات">Quotes</a>
<a href="#checklist" data-en="Checklist" data-ur="چیک لسٹ">Checklist</a>
</nav>

<div id="futures">
<button onclick="toggleDark()" data-en="Dark/Light" data-ur="ڈارک/لائٹ">Dark/Light</button>
<button onclick="toggleLang()" data-en="EN/UR" data-ur="انگریزی/اردو">EN/UR</button>
</div>

<!-- ================= 10 SURAH KE BAAD FULL SECTION ================= -->
<!-- DUAS -->
<section id="dua" class="card">
<h2 data-en="Popular Duas" data-ur="مشہور دعائیں">Popular Duas</h2>
<ul>
<li><b>Urdu:</b> اے اللہ! مجھے اچھے عمل کرنے کی توفیق عطا فرما۔<br>
<b>English:</b> O Allah! Grant me the ability to do righteous deeds.</li>
<li><b>Urdu:</b> اے اللہ! ہمیں ہمارے گناہوں سے معاف فرما۔<br>
<b>English:</b> O Allah! Forgive us our sins.</li>
<li><b>Urdu:</b> اے اللہ! ہمیں سیدھا راستہ دکھا۔<br>
<b>English:</b> O Allah! Guide us to the straight path.</li>
<li><b>Urdu:</b> اے اللہ! ہمارے دلوں میں ایمان بڑھا۔<br>
<b>English:</b> O Allah! Increase faith in our hearts.</li>
<li><b>Urdu:</b> اے اللہ! ہمیں صبر عطا فرما۔<br>
<b>English:</b> O Allah! Grant us patience.</li>
</ul>
</section>

<!-- NAMAZ TIMINGS -->
<section id="namaz" class="card">
<h2 data-en="Namaz Timings" data-ur="نماز کے اوقات">Namaz Timings</h2>
<p>Select your city:</p>
<select id="citySelect">
<option value="karachi">Karachi</option>
<option value="lahore">Lahore</option>
<option value="islamabad">Islamabad</option>
<option value="peshawar">Peshawar</option>
<option value="quetta">Quetta</option>
</select>
<table id="namazTable">
<tr><th>Prayer</th><th>Time</th></tr>
<tr><td>Fajr</td><td id="fajr">--:--</td></tr>
<tr><td>Dhuhr</td><td id="dhuhr">--:--</td></tr>
<tr><td>Asr</td><td id="asr">--:--</td></tr>
<tr><td>Maghrib</td><td id="maghrib">--:--</td></tr>
<tr><td>Isha</td><td id="isha">--:--</td></tr>
</table>
</section>

<!-- RAMADAN CALENDAR -->
<section id="calendar" class="card">
<h2 data-en="Ramadan Calendar" data-ur="رمضان کیلنڈر">Ramadan Calendar 2026</h2>
<p>Sehri & Iftar timings for selected city:</p>
<table id="calendarTable">
<tr><th>Date</th><th>Sehri</th><th>Iftar</th></tr>
<tr><td>1 Ramadan</td><td>04:30 AM</td><td>06:45 PM</td></tr>
<tr><td>2 Ramadan</td><td>04:29 AM</td><td>06:46 PM</td></tr>
<tr><td>3 Ramadan</td><td>04:28 AM</td><td>06:47 PM</td></tr>
<tr><td>4 Ramadan</td><td>04:27 AM</td><td>06:48 PM</td></tr>
<!-- Add all 30 days similarly -->
</table>
</section>

<!-- TARAWEEH TRACKER -->
<section id="taraweeh" class="card">
<h2 data-en="Taraweeh Tracker" data-ur="ترواہی ٹریکر">Taraweeh Tracker</h2>
<p>Complete your daily Taraweeh prayers:</p>
<ul id="taraweehList">
<li><input type="checkbox" id="night1"> Night 1</li>
<li><input type="checkbox" id="night2"> Night 2</li>
<li><input type="checkbox" id="night3"> Night 3</li>
<li><input type="checkbox" id="night4"> Night 4</li>
<li><input type="checkbox" id="night5"> Night 5</li>
<!-- up to 30 nights -->
</ul>
</section>

<!-- ZAKAT CALCULATOR -->
<section id="zakat" class="card">
<h2 data-en="Zakat Calculator" data-ur="زکوة کیلکولیٹر">Zakat Calculator</h2>
<p>Enter your wealth amount:</p>
<input type="number" id="wealth" placeholder="Amount in PKR">
<button onclick="calculateZakat()">Calculate Zakat</button>
<p id="zakatResult"></p>
</section>

<!-- TASBEEH COUNTER -->
<section id="tasbeeh" class="card">
<h2 data-en="Tasbeeh Counter" data-ur="تسبیح کاؤنٹر">Tasbeeh Counter</h2>
<p>Click to count your Tasbeeh:</p>
<button onclick="incrementTasbeeh()">Count</button>
<p>Count: <span id="tasbeehCount">0</span></p>
<button onclick="resetTasbeeh()">Reset</button>
</section>

<!-- QIBLA DIRECTION -->
<section id="qibla" class="card">
<h2 data-en="Qibla Direction" data-ur="قبلہ کی سمت">Qibla Direction</h2>
<p>Use your device compass to find the Qibla direction:</p>
<p id="qiblaDir">Facing Mecca: --°</p>
</section>

<!-- RECIPES -->
<section id="recipes" class="card">
<h2 data-en="Ramadan Recipes" data-ur="رمضان کے پکوان">Ramadan Recipes</h2>
<ul>
<li><b>Sehri:</b> Fruit Salad, Oatmeal, Eggs, Paratha</li>
<li><b>Iftar:</b> Dates, Fruit Chaat, Pakoras, Juice</li>
<li><b>Main Course:</b> Chicken Biryani, Nihari, Lentils, Rice</li>
<li><b>Desserts:</b> Sheer Khurma, Kheer, Gulab Jamun</li>
</ul>
</section>

<!-- GOALS -->
<section id="goals" class="card">
<h2 data-en="Ramadan Goals" data-ur="رمضان کے مقاصد">Ramadan Goals</h2>
<ul>
<li>Daily Quran recitation</li>
<li>Complete 5 daily prayers</li>
<li>Fast every day</li>
<li>Give charity / Zakat</li>
<li>Increase good deeds</li>
<li>Pray for family & Ummah</li>
</ul>
</section>

<!-- QUOTES & AHADEES -->
<section id="quotes" class="card">
<h2 data-en="Islamic Quotes & Ahadees" data-ur="اسلامی اقوال اور احادیث">Islamic Quotes & Ahadees</h2>
<ul>
<li>"The best among you are those who learn the Quran and teach it." (Sahih Bukhari)</li>
<li>"Ramadan is the month whose beginning is mercy, middle is forgiveness, and end is freedom from the fire." (Prophet Muhammad ﷺ)</li>
<li>"Give charity without delay, for it stands in the way of calamity." (Tirmidhi)</li>
<li>"When one of you is fasting, he should abstain from indecent speech and foolishness." (Sahih Bukhari)</li>
<li>"The month of Ramadan is that in which the Quran was revealed." (Quran 2:185)</li>
</ul>
</section>

<!-- CHECKLIST -->
<section id="checklist" class="card">
<h2 data-en="Ramadan Checklist" data-ur="رمضان چیک لسٹ">Ramadan Checklist</h2>
<ul>
<li><input type="checkbox"> Daily Fasting</li>
<li><input type="checkbox"> Daily Prayers</li>
<li><input type="checkbox"> Quran Recitation</li>
<li><input type="checkbox"> Charity / Zakat</li>
<li><input type="checkbox"> Dua & Dhikr</li>
<li><input type="checkbox"> Taraweeh</li>
<li><input type="checkbox"> Healthy Meals</li>
</ul>
</section>

<!-- ================== JS FOR INTERACTIVITY ================== -->
<script>
// DARK/LIGHT MODE
function toggleDark(){
  document.body.classList.toggle('dark-mode');
}

// EN/UR LANGUAGE TOGGLE
let lang='en';
function toggleLang(){
  lang = (lang==='en')?'ur':'en';
  document.querySelectorAll('[data-en]').forEach(el=>{
    el.innerText = lang==='en'?el.getAttribute('data-en'):el.getAttribute('data-ur');
  });
}

// TASBEEH
let count=0;
function incrementTasbeeh(){ count++; document.getElementById('tasbeehCount').innerText=count;}
function resetTasbeeh(){ count=0; document.getElementById('tasbeehCount').innerText=count;}

// ZAKAT CALCULATOR
function calculateZakat(){
  let wealth = document.getElementById('wealth').value;
  if(wealth && !isNaN(wealth)){
    let zakat = (wealth*2.5)/100;
    document.getElementById('zakatResult').innerText="Zakat: "+zakat.toFixed(2)+" PKR";
  }else{ alert("Enter valid amount"); }
}

// NAMAZ TIMINGS (Static Example, can add API)
const timings={
  karachi:{fajr:"04:30",dhuhr:"12:15",asr:"15:45",maghrib:"18:45",isha:"20:00"},
  lahore:{fajr:"04:45",dhuhr:"12:30",asr:"16:00",maghrib:"19:00",isha:"20:15"},
  islamabad:{fajr:"04:50",dhuhr:"12:35",asr:"16:05",maghrib:"19:05",isha:"20:20"},
  peshawar:{fajr:"04:40",dhuhr:"12:20",asr:"15:50",maghrib:"18:55",isha:"20:10"},
  quetta:{fajr:"04:55",dhuhr:"12:40",asr:"16:10",maghrib:"19:10",isha:"20:25"},
};
document.getElementById('citySelect').addEventListener('change', e=>{
  let city=e.target.value;
  document.getElementById('fajr').innerText=timings[city].fajr;
  document.getElementById('dhuhr').innerText=timings[city].dhuhr;
  document.getElementById('asr').innerText=timings[city].asr;
  document.getElementById('maghrib').innerText=timings[city].maghrib;
  document.getElementById('isha').innerText=timings[city].isha;
});
// Initialize default city
document.getElementById('citySelect').dispatchEvent(new Event('change'));

// QIBLA DIRECTION (Example using device orientation)
if(window.DeviceOrientationEvent){
  window.addEventListener('deviceorientation', function(event){
    let compass=event.alpha;
    if(compass!==null) document.getElementById('qiblaDir').innerText = "Facing Mecca: "+Math.round(compass)+"°";
  });
}
</script>
</body>
</html>
