# HTML-web-site


<!DOCTYPE html>
<html>
<head>
<title>Tervetuloa</title>
<meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <style>
    /* Set height of the grid so .sidenav can be 100% (adjust as needed) */
    .row.content {height: 550px}
    
    /* Set gray background color and 100% height */
    .sidenav {
      background-color: #f1f1f1;
      height: 100%;
    }
        
    /* On small screens, set height to 'auto' for the grid */
    @media screen and (max-width: 767px) {
      .row.content {height: auto;} 
    }
<style>

#home {
  width: 46px;
  height: 44px;
  background: url(img_navsprites.gif) 0 0;
}

* {
  box-sizing: border-box;
}

/* Style the body */
body {
  font-family: Arial;
  margin: 0;
}

/* Header/logo Title */
.header {
  padding: 60px;
  text-align: center;
  background: white;
  color: lightblue;
}

/* Style the top navigation bar */
.navbar {
  display: flex;
  background-color: white
}

/* Style the navigation bar links */
.navbar a {
  color: lightblue;
  padding: 20px 20px;
  text-decoration: none;
  text-align: center;
}

.fa {
  padding: 10px;
  font-size: 20px;
  width: 50px;
  text-align: center;
  text-decoration: none;
  margin: 5px 2px;
}

.fa-facebook {
  background: blue;
  color: white;
}

.fa-youtube {
  background: red;
  color: white;
}

.fa-instagram {
  background: #125688;
  color: white;
}

/* Change color on hover */
.navbar a:hover {
  background-color: #ddd;
  color: black;
}

/* Column container */
.row {  
  display: flex;
  flex-wrap: wrap;
}

/* Create two unequal columns that sits next to each other */
/* Sidebar/left column */
.side {
  flex: 30%;
  background-color: #f1f1f1;
  padding: 20px;
}

/* Main column */
.main {
  flex: 70%;
  background-color: white;
  padding: 20px;
}

/* Fake image, just for this example */
.fakeimg {
  background-color: #aaa;
  width: 100%;
  padding: 20px;
}

/* Footer */
.footer {
  padding: 20px;
  text-align: center;
  background: darkgray;
}

/* Responsive layout - when the screen is less than 960px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 960px) {
  .row, .navbar {   
    flex-direction: column;
  }
}

</style>
</head>
<body>

<!-- Navigation Bar -->

<div class="navbar">
<!-- Logo ylhäällä -->
  <img id="home" src="logo.jpg" width="100" height="100">
  <a id="myAnchor" href="index.html">Etusivu</a>
  <a id="myAnchor" href="index.html">Esittely video</a>
  <a id="myAnchor" href="index.html">Tarjouspyyntö</a>
</div>

<!-- Header -->
<div class="header">
<img src="tullinranta.jpg" style="width:60%">
  <h1>Vaasan Saaristomaisemointi Oy</h1>
  <p><b>Saaristomaisemointi työt Vaasan alueella Ammattitaidolla</b></p>
  <button type="kiitos_sivu.html" class="btn btn-primary btn-sm">Pyydä tarjous</button>
</div>

<div class="row">
        <div class="col-sm-3">
          <div class="well">
            <h4>1. Maisema suunnittelu</h4>
            <p>Palveluumme kuuluu myös suunnittelu työt.<br><br><br><br>
            </p> 
          </div>
        </div>
        <div class="col-sm-3">
          <div class="well">
            <h4>2. Piha työt ja maisemointi</h4>
            <p>Suoritamme kaikkia maanrakennus- ja pihatöitä.</p><br><br>
          </div>
        </div>
        <div class="col-sm-3">
          <div class="well">
            <h4>3. Avaimet käteen</h4>
            <p>Toimitamme asiakkalleemme myös Avaimet käteen - periaatteella.<br> 
Suunnittelusta, pihan siistimiseen asti.</p> 
          </div>
<div>
<button type="kiitos_sivu.html" class="btn btn-primary btn-sm">Pyydä tarjous</button>
</div>
        </div>
        </div>

<!-- videosivun koodi alkaa tästä -->

<br><br><br><br><br><br><br>
    <h1>Esittely videomme</h1>
    <p></p>

      <!-- tämän elementin tilalletulee videoplayeri -->

<iframe style="width:60%" src="https://www.youtube.com/embed/-8WIOgAjlAQ" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br>
<a href="https://www.youtube.com/watch?v=-8WIOgAjlAQ">Tekijä: Rannikon Merityö</a>
<br>
<div>
<button type="kiitos_sivu.html" class="btn btn-primary btn-sm">Pyydä tarjous</button>
</div>

<!-- The flexible grid (content) -->
 
  <div class="main">
    
    <p><a name="signup"></a>
<h1>Pyydä tarjous</h1>
<p>Tarjouksen saamiseksi, <br>
pyydämme täyttämään alla olevat kentät.</p>

<!-- Tähän lisätään form elementti lomakekäsittelyä varten -->

<table border="0" bgcolor="lightblue">
<form action="kiitos_sivu.html">
<tr>
<td colspan="2" align="left">
  Etunimi: &nbsp&nbsp&nbsp&nbsp&nbsp
  <input type="text"><br><br>
  Sukunimi:&nbsp&nbsp&nbsp
  <input type="text"><br><br>
  Sähköposti:
  <input type="text"><br><br>
  Käyttäjä:&nbsp&nbsp&nbsp&nbsp&nbsp
  <input type="text"><br><br>
  Salasana:&nbsp&nbsp&nbsp
  <input type="text"><br><br>

<tr>
<td colspan="2" align="left">
  Sukupuoli:
  <input type="radio" id="male" name="gender" value="male"> Mies
  <input type="radio" id="female" name="gender" value="female"> Nainen
  <input type="radio" id="other" name="gender" value="other"> Muu

<br><br>

Suunnitelmat:<br>
<input type="checkbox" id="vehicle1" name="vehicle1" value="Bike">
Hyrskyn myrskyn<br>
<input type="checkbox" id="vehicle2" name="vehicle2" value="Car">
Puskat pois<br>
<input type="checkbox" id="vehicle3" name="vehicle3" value="Boat">
Kaikki sileeks vs 2.0
<br>

<h3>Lisätiedot</h3>

<form action="/action_page.php">
Tähän voitte kertoa lisätietoa kohteestanne:<br>
<textarea rows="3" cols="50">
</textarea>

<tr>
<td colspan="2" align="center">
<button type="kiitos_sivu.html" class="btn btn-primary btn-sm">Lähetä</button>
</td>
</tr>
</form>
</table></p>
    <br>

  </div>
</div>

<!-- Footer -->
<div class="footer">
    <div class="fakeimg" style="height:160px;">
  <p>Vaasan Saaristomaisemointi Oy<br>
      Saaristokatu 1, 65170 Vaasa<br>
      P. 040-1234567<br>
      info@maisemointi.fi<br></p><a href="#" class="fa fa-facebook"></a>
                                 <a href="#" class="fa fa-youtube"></a>
                                 <a href="#" class="fa fa-instagram"></a>
</div>
  </div>

</body>
</html>
