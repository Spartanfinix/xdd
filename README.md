<!DOCTYPE html>
<html>
<head>
<title>W3.CSS Template</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Inconsolata">
<style>
body, html {
  height: 100%;
  font-family: "Inconsolata", sans-serif;
}

.bgimg {
  background-position: center;
  background-size: cover;
  background-image: url("https://insider-gaming.com/wp-content/uploads/2023/03/resident-evil-4-remake-achievements-e1678692077105.jpg");
  min-height: 75%;
}

.menu {
  display: none;
}
</style>
</head>
<body>

<!-- Links (sit on top) -->
<div class="w3-top">
  <div class="w3-row w3-padding w3-black">
    <div class="w3-col s3">
      <a href="#" class="w3-button w3-block w3-black">INICIO</a>
    </div>
    <div class="w3-col s3">
      <a href="#about" class="w3-button w3-block w3-black">ACERCA DE</a>
    </div>
    <div class="w3-col s3">
      <a href="#menu" class="w3-button w3-block w3-black">MENU</a>
    </div>
    <div class="w3-col s3">
      <a href="#where" class="w3-button w3-block w3-black">DONDE COMPRAR</a>
    </div>
  </div>
</div>

<!-- Header with image -->
<header class="bgimg w3-display-container w3-grayscale-min" id="home">
  <div class="w3-display-bottomleft w3-center w3-padding-large w3-hide-small">
    <span class="w3-tag">Playstation 4/5, Xbox Series S/X y Steam</span>
  </div>
  <div class="w3-display-middle w3-center">
   <span class="w3-text-white" style="font-size: 90px; font-family: 'Nemesis Grant', sans-serif; text-shadow: 4px 4px 5px black;">Resident<br><span style="color: red; text-shadow: none;">E</span>vil <span style="color: red; text-shadow: none;">4</span></span>


  </div>
  <div class="w3-display-bottomright w3-center w3-padding-large">
    <span class="w3-text-white">DISPONIBLE</span>
  </div>
</header>

<!-- Add a background color and large text to the whole page -->
<div class="w3-sand w3-grayscale w3-large">

<!-- About Container -->
<div class="w3-container" id="about">
  <div class="w3-content" style="max-width:700px">
    <h5 class="w3-center w3-padding-64"><span class="w3-tag w3-wide">ACERCA DEL JUEGO</span></h5>
    <p>Resident Evil 4 Remake es la reimaginación del clásico juego de acción y terror en tercera persona desarrollado por Capcom para PlayStation 4 y 5, Xbox One, Xbox Series S y X y PC. Se trata de la puesta al día del survival horror de la saga Resident Evil lanzado en 2005, una ambiciosa puesta al día a nivel jugable y gráfico que nos devuelve a Leon S. Kennedy en su viaje a un récondito pueblo de España en su rescate de la hija del presidente de Estados Unidos.</p>
    <div class="w3-panel w3-leftbar w3-light-grey">
      <p><i>"Resident Evil 4 Nunca se vio mejor".</i></p>
      <p>9/10 IGN.</p>
    </div>
   <center> <iframe width="560" height="315" src="https://www.youtube.com/embed/Id2EaldBaWw?si=jdjFgMHCQCflwhl-" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe></center>
    
    <div>
    <img src="https://www.residentevil.com/re4/assets/images/topics/demo/video_thumb.jpg" style="width:100%;max-width:1000px" class="w3-margin-top">
    
     <img src="https://www.dexerto.com/cdn-cgi/image/width=3840,quality=75,format=auto/https://editors.dexerto.com/wp-content/uploads/2023/03/02/Resident-Evil-4-Remake-preview.jpg" style="width:100%;max-width:1000px" class="w3-margin-top">
     
     <img src="https://www.relyonhorror.com/wp-content/uploads/2023/02/RE4_Jack_Krauser_01-scaled-1.jpg" style="width:100%;max-width:1000px" class="w3-margin-top"> 
    </div>
  
  </div>
</div>

<!-- Menu Container -->
<div class="w3-container" id="menu">
  <div class="w3-content" style="max-width:700px">
 
    <h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">VERSIONES DISPONIBLES</span></h5>
  
    <div class="w3-row w3-center w3-card w3-padding">
      <a href="javascript:void(0)" onclick="openMenu(event, 'Eat');" id="myLink">
        <div class="w3-col s6 tablink">Edicion Deluxe</div>
      </a>
      <a href="javascript:void(0)" onclick="openMenu(event, 'Drinks');">
        <div class="w3-col s6 tablink">Gold Edition</div>
      </a>
    </div>

    <div id="Eat" class="w3-container menu w3-padding-48 w3-card">
    <h5>Juego base</h5>
      <p class="w3-text-grey">la versión completa del juego.</p><br>
      <h5>Trajes adicionales</h5>
      <p class="w3-text-grey">Leon S. Kennedy y Ashley Graham tienen trajes adicionales que se pueden desbloquear.</p><br>
    
      <h5>Armas adicionales</h5>
      <p class="w3-text-grey">incluye el rifle semiautomático “WCX” y la pistola “Samurai Edge”.</p><br>
    
      <h5>Banda sonora original</h5>
      <p class="w3-text-grey">la versión Deluxe incluye la banda sonora original del juego.</p><br>
    

    </div>

    <div id="Drinks" class="w3-container menu w3-padding-48 w3-card">
      <h5>Juego base</h5>
      <p class="w3-text-grey">la versión completa del juego.</p><br>
    
      <h5>DLC Separate Ways</h5>
      <p class="w3-text-grey">un episodio adicional que se centra en Ada Wong..</p><br>
    
      <h5>Armas adicionales</h5>
      <p class="w3-text-grey">incluye el rifle semiautomático “WCX” y la pistola “Samurai Edge”.</p><br>
    
      <h5>Banda sonora original</h5>
      <p class="w3-text-grey">la versión Deluxe incluye la banda sonora original del juego.</p><br>
    
      <h5>Armas extra</h5>
      <p class="w3-text-grey">Sentinel Nine y Skull Shaker.</p>
    </div>  
    <img src="/w3images/coffeehouse2.jpg" style="width:100%;max-width:1000px;margin-top:32px;">
  </div>
</div>



<!-- End page content -->
</div>

<!-- Footer -->
<footer class="w3-center w3-light-grey w3-padding-48 w3-large">
  <p>Powered by <a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a></p>
</footer>

<script>
// Tabbed Menu
function openMenu(evt, menuName) {
  var i, x, tablinks;
  x = document.getElementsByClassName("menu");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  tablinks = document.getElementsByClassName("tablink");
  for (i = 0; i < x.length; i++) {
    tablinks[i].className = tablinks[i].className.replace(" w3-dark-grey", "");
  }
  document.getElementById(menuName).style.display = "block";
  evt.currentTarget.firstElementChild.className += " w3-dark-grey";
}
document.getElementById("myLink").click();
</script>

</body>
</html>
