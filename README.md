<doctype html>

<html>

<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>

header {
	font-family:"roboto";
	font-size: 60px;
	color:#e0e0e0;
	margin: 0;
}

img {
  display: block;

}

.dropbtn {
  background-color: #7f93a1;
  color: #cee4ed;
  padding: 16px;
  width: 720px;
  font-size: 20px;
  border: none;
  cursor: pointer;
  margin-left: 0;
  display: block;
  



}

.dropbtn:hover, .dropbtn:focus {
  background-color: #011f47;
}

.dropdown {
  position: relative;
  display: inline-block;
}

.dropdown-content {
  display: none;
  position: absolute;
  background-color: #f1f1f1;
  min-width: 160px;
  overflow: visible;
  box-shadow: 0px 8px 16px 0px rgba(0,0,0,0.2);
  z-index: 1;
}

.dropdown-content a {
  color: black;
  padding: 12px 16px;
  text-decoration: none;
  display: block;
}

.dropdown a:hover {background-color: #ddd;}

.show {display: block;}


  }
</style>
</head>
  <header>
    <h1>#NotARecipe</h1>

  </header>

<img src="HWC_7591-2.jpg" class="center">

<style>


body {

  background-image: url('background.jpg');
}
</style>


<div class="dropdown">
 <button onclick="showBeef()" class="dropbtn">Beef</button>
  <div id="beef" class="dropdown-content">
  <img src="HWC_7475.jpg" alt="BEEF" width="720">
  <img src="HWC_7477.jpg" alt="BEEF" width="720">
  <img src="HWC_7493.jpg" alt="BEEF" width="720">
  </div>
 <button onclick="showOnions()" class="dropbtn">Onions</button>
  <div id="onions" class="dropdown-content">
  <img src="HWC_7510.jpg" alt="onions" width="720">
  </div>
 <button onclick="showTomatoes()" class="dropbtn">Tomatoes</button>
  <div id="tomatoes" class="dropdown-content">
  <img src="HWC_7511.jpg" alt="tomatoes" width="720">
  </div>
 <button onclick="showGinger()" class="dropbtn">Ginger</button>
  <div id="ginger" class="dropdown-content">
  <img src="HWC_7495.jpg" alt="ginger" width="720">
  </div>
<button onclick="showGarlic()" class="dropbtn">Garlic</button>
  <div id="garlic" class="dropdown-content">
  <img src="HWC_7497.jpg" alt="garlic" width="720">
  </div>
<button onclick="showFire()" class="dropbtn">🔥🔥🔥</button>
  <div id="🔥🔥🔥" class="dropdown-content">
  <img src="HWC_7513.jpg" alt="🔥🔥🔥" width="720">
  <img src="HWC_7524.jpg" alt="BEEF" width="720">
  <img src="HWC_7537.jpg" alt="BEEF" width="720">
  </div>
  <button onclick="showTomatopaste()" class="dropbtn">Tomato Paste</button>
  <div id="tomatopaste" class="dropdown-content">
  <img src="HWC_7521.jpg" alt="tomatopaste" width="720">
  </div>
  <button onclick="showSpices()" class="dropbtn">Spices</button>
  <div id="spices" class="dropdown-content">
  <div class="dropdown">
	 <button onclick="showStaranise()" class="dropbtn">Star Anise</button>
 		 <div id="staranise" class="dropdown-content">
 		 <img src="HWC_7482.jpg" alt="staranise" width="720">
 		 </div>
	 <button onclick="showCloves()" class="dropbtn">Cloves</button>
 		 <div id="cloves" class="dropdown-content">
 		 <img src="HWC_7482.jpg" alt="cloves" width="720">
 		 </div>
	 <button onclick="showNutmeg()" class="dropbtn">Nutmeg</button>
 		 <div id="nutmeg" class="dropdown-content">
 		 <img src="HWC_7485.jpg" alt="nutmeg" width="720">
 		 </div>
	 <button onclick="showCinnamon()" class="dropbtn">Cinnamon</button>
 		 <div id="cinnamon" class="dropdown-content">
 		 <img src="HWC_7486.jpg" alt="cinnamon" width="720">
 		 </div>
 	 <button onclick="showSichuan()" class="dropbtn">Sichuan Peppercorn</button>
 		 <div id="sich" class="dropdown-content">
 		 <img src="HWC_7490.jpg" alt="sich" width="720">
 		 </div>
  	 <button onclick="showWhite()" class="dropbtn">White Pepper</button>
 		 <div id="white" class="dropdown-content">
 		 <img src="HWC_7489.jpg" alt="white" width="720">
 		 </div>
   	 <button onclick="showDong()" class="dropbtn">Dong Quai</button>
 		 <div id="dong" class="dropdown-content">
 		 <img src="HWC_7483.jpg" alt="dong" width="720">
 		 </div>
 	 <button onclick="showChili()" class="dropbtn">Chili Pepper</button>
 		 <div id="chili" class="dropdown-content">
 		 <img src="HWC_7492.jpg" alt="chili" width="720">
 		 </div>
 	 <button onclick="showPeel()" class="dropbtn">Orange Peel</button>
 		 <div id="peel" class="dropdown-content">
 		 <img src="HWC_7503.jpg" alt="peel" width="720">
 		 </div>
 	 <button onclick="showPack()" class="dropbtn">Pack</button>
 		 <div id="pack" class="dropdown-content">
 		 <img src="HWC_7504.jpg" alt="pack" width="720">
 		 </div>
  </div>
  </div>
 <div class="dropdown">
 <button onclick="showRice()" class="dropbtn">Rice Wine</button>
 	<div id="rice" class="dropdown-content">
 	<img src="HWC_7527.jpg" alt="rice" width="720">
 	</div>
  <button onclick="showWine()" class="dropbtn">Red Wine</button>
 	<div id="wine" class="dropdown-content">
 	<img src="HWC_7530.jpg" alt="wine" width="720">
 	</div>
  <button onclick="showSoy()" class="dropbtn">Soy Sauce</button>
 	<div id="soy" class="dropdown-content">
 	<img src="HWC_7535.jpg" alt="soy" width="720">
 	</div>
   <button onclick="showSes()" class="dropbtn">Sesame Oil</button>
 	<div id="ses" class="dropdown-content">
 	<img src="HWC_7557.jpg" alt="ses" width="720">
 	</div>
  <button onclick="showWater()" class="dropbtn">💧💧💧</button>
 	<div id="water" class="dropdown-content">
 	<img src="HWC_7542.jpg" alt="water" width="720">
 	<img src="HWC_7548.jpg" alt="water" width="720">
 	</div>
   <button onclick="showTime()" class="dropbtn">⏲⏲⏲</button>
 	<div id="time" class="dropdown-content">
 	<img src="HWC_7544.jpg" alt="time" width="720">
 	</div>
   <button onclick="showDaikon()" class="dropbtn">Daikon</button>
 	<div id="daikon" class="dropdown-content">
 	<img src="HWC_7558.jpg" alt="daikon" width="720">
	<img src="HWC_7564.jpg" alt="daikon" width="720">
 	</div>
   <button onclick="showPickles()" class="dropbtn">Pickles</button>
  <div id="pickles" class="dropdown-content">
  <div class="dropdown">
	 <button onclick="showGreens()" class="dropbtn">Mustard Greens</button>
 		 <div id="greens" class="dropdown-content">
 		 <img src="HWC_7570.jpg" alt="greens" width="720">
 		 </div>
	 <button onclick="showGinger2()" class="dropbtn">Ginger</button>
 		 <div id="ginger2" class="dropdown-content">
 		 <img src="HWC_7560.jpg" alt="ginger2" width="720">
 		 </div>
	 <button onclick="showGarlic2()" class="dropbtn">Garlic</button>
 		 <div id="garlic2" class="dropdown-content">
 		 <img src="HWC_7562.jpg" alt="garlic2" width="720">
 		 </div>
	 <button onclick="showThai()" class="dropbtn">Thai Chili</button>
 		 <div id="thai" class="dropdown-content">
 		 <img src="HWC_7567.jpg" alt="thai" width="720">
 		 </div>
 	 <button onclick="showHeat()" class="dropbtn">🔥🔥🔥</button>
 		 <div id="heat" class="dropdown-content">
 		 <img src="HWC_7572.jpg" alt="heat" width="720">
 		 <img src="HWC_7594.jpg" alt="heat" width="720">
 		 </div>
  </div>
  </div>
 <div class="dropdown">
 <button onclick="showGreen()" class="dropbtn">Green Onions</button>
 	<div id="green" class="dropdown-content">
 	<img src="HWC_7576.jpg" alt="green" width="720">
 	</div>
 <button onclick="showCil()" class="dropbtn">Cilantro</button>
 	<div id="cil" class="dropdown-content">
 	<img src="HWC_7579.jpg" alt="cil" width="720">
 	</div>
  <button onclick="showBok()" class="dropbtn">Bok Choy</button>
 	<div id="bok" class="dropdown-content">
 	<img src="HWC_7584.jpg" alt="bok" width="720">
 	</div>
  <button onclick="showNood()" class="dropbtn">Noodles</button>
 	<div id="nood" class="dropdown-content">
 	<img src="HWC_7583.jpg" alt="nood" width="720">
 	<img src="HWC_7589.jpg" alt="nood" width="720">
 	</div>
   <button onclick="showCombine()" class="dropbtn">Combine</button>
 	<div id="combine" class="dropdown-content">
 	<img src="HWC_7591.jpg" alt="combine" width="720">
 	</div>
</div>
  </div>
</div>



<script>
/* When the user clicks on the button, 
toggle between hiding and showing the dropdown content */
function showBeef() {
  document.getElementById("beef").classList.toggle("show");
}
function showOnions() {
  document.getElementById("onions").classList.toggle("show");
}
function showTomatoes() {
  document.getElementById("tomatoes").classList.toggle("show");
}
function showGinger() {
  document.getElementById("ginger").classList.toggle("show");
}
function showGarlic() {
  document.getElementById("garlic").classList.toggle("show");
}
function showFire() {
  document.getElementById("🔥🔥🔥").classList.toggle("show");
}
function showTomatopaste() {
  document.getElementById("tomatopaste").classList.toggle("show");
}
function showBeanpaste() {
  document.getElementById("beanpaste").classList.toggle("show");
}
function showSpices() {
  document.getElementById("spices").classList.toggle("show");
}
function showStaranise() {
  document.getElementById("staranise").classList.toggle("show");
}
function showCloves() {
  document.getElementById("cloves").classList.toggle("show");
}
function showNutmeg() {
  document.getElementById("nutmeg").classList.toggle("show");
}
function showCinnamon() {
  document.getElementById("cinnamon").classList.toggle("show");
}
function showSichuan() {
  document.getElementById("sich").classList.toggle("show");
}
function showWhite() {
  document.getElementById("white").classList.toggle("show");
}
function showDong() {
  document.getElementById("dong").classList.toggle("show");
}
function showChili() {
  document.getElementById("chili").classList.toggle("show");
}
function showPeel() {
  document.getElementById("peel").classList.toggle("show");
}
function showPack() {
  document.getElementById("pack").classList.toggle("show");
}
function showRice() {
  document.getElementById("rice").classList.toggle("show");
}
function showWine() {
  document.getElementById("wine").classList.toggle("show");
}
function showSoy() {
  document.getElementById("soy").classList.toggle("show");
}
function showSes() {
  document.getElementById("ses").classList.toggle("show");
}
function showWater() {
  document.getElementById("water").classList.toggle("show");
}
function showTime() {
  document.getElementById("time").classList.toggle("show");
}
function showDaikon() {
  document.getElementById("daikon").classList.toggle("show");
}
function showPickles() {
  document.getElementById("pickles").classList.toggle("show");
}
function showGreens() {
  document.getElementById("greens").classList.toggle("show");
}
function showGinger2() {
  document.getElementById("ginger2").classList.toggle("show");
}
function showGarlic2() {
  document.getElementById("garlic2").classList.toggle("show");
}
function showThai() {
  document.getElementById("thai").classList.toggle("show");
}
function showHeat() {
  document.getElementById("heat").classList.toggle("show");
}
function showGreen() {
  document.getElementById("green").classList.toggle("show");
}
function showCil() {
  document.getElementById("cil").classList.toggle("show");
}
function showBok() {
  document.getElementById("bok").classList.toggle("show");
}
function showNood() {
  document.getElementById("nood").classList.toggle("show");
}
function showCombine() {
  document.getElementById("combine").classList.toggle("show");
}
// Close the dropdown if the user clicks outside of it
window.onclick = function(event) {
  if (!event.target.matches('.dropbtn')) {
    var dropdowns = document.getElementsByClassName("dropdown-content");
    var i;
    for (i = 0; i < dropdowns.length; i++) {
      var openDropdown = dropdowns[i];
      if (openDropdown.classList.contains('show')) {
        openDropdown.classList.remove('show');
      }
    }
  }
}
</script>



</html>
