# THP-Googlehomepage

Bonsoir !
voici d'abord le code html, et à la suite le css.

<!DOCTYPE html>
<html>
<head>
	<title>Google</title>
	<meta charset="utf-8">
	<link rel="stylesheet" type="text/css" href="styles.css">
	<link rel="icon" type="image/png" href="img/favicon.png">
</head>
<body>
	<header>
		<div class="menu">
		  <nav>
			<ul>
			 <li><a href="https://www.gmail.com">Gmail</a></li>
			 <li><a href="https://www.google.fr/imghp?hl=fr&tab=wi&ogbl">Images</a></li>
			</ul>	
		  </nav>
		</div>
	</header>
	    <div id="container">
	    	<div class="google"><img src="img/googlelogo.png"></div>

	    	<div class="recherche"><input type="text" name="recherche"><img class="loupe" src="img/iconeloupe.png"></div>

	    	<div class="boutons">
	    	  <button class="btn">Recherche Google</button>
	    	  <button class="btn">J'ai de la chance</button>
	    	</div>

	    	<div class="jugement"><a href="https://support.google.com/websearch/answer/9586983?p=fr_tos&visit_id=637427072354171291-4231467859&rd=1" style="color:blue">Jugement de TJ de Paris du 12 février 2019</a></div>

	    	<div class="english">Google disponible en : <a href="https://www.google.fr/"><span>English</span></a></div>
	    </div>

	  <footer>
	  	<div id="pied">
	  	 <div class="footer1"><span class="france">France</span></div>

	  	 <div class="footer2">
	  	 	<ul>	
	  	 	   <li><img src="img/feuille.png" class="feuille"><a href="https://sustainability.google/intl/fr/commitments-europe/?utm_source=googlehpfooter&utm_medium=housepromos&utm_campaign=bottom-footer&utm_content=" class="lien">Neutre en carbonne depuis 2007</a></li>
	  	 	   <li><a href="https://support.google.com/websearch/answer/7585859?p=fr_consumer_info&hl=fr&fg=1&visit_id=637454717561222831-3580402941&rd=1" class="lien">Info Consommateurs</a></li>
	  	 	   <li><a href="https://policies.google.com/privacy?hl=fr&fg=1" class="lien">Confidentialité</a></li>
	  	 	   <li><a href="https://policies.google.com/terms?hl=fr&fg=1" class="lien">Conditions</a></li>
	  	 	   <li><a href="https://www.google.fr/preferences?hl=fr" class="lien">Paramètres</a></li>
	  	 	</ul>
	  	  </div>
	    </footer>  
</body>
</html>


PUIS CSS :

nav ul li
{
	list-style-type: none;
	display: inline;
}

nav li
{
	float: right;
	width: 5%;
}

a
{
	text-decoration: none;
	color: black;
	font-family: arial;
	font-size: 14px;
	margin-right: 20px;
}

nav ul li:hover
{
	text-decoration: underline;
}

.menu
{
	height: 130px;
}

#container
{
	border: solid white 1px;
	width: 100%;
	height: 278px;
	display: flex;
	flex-direction: column;
	justify-content : center;
	align-items: center;
	padding-bottom: 80px;
}

.google
{
	height: 120px;
}

img
{
	width: 290px;
	height: 100px;
}

.recherche
{
	height: 70px;
}

input
{
	border: solid 1px #BABABA;
	border-radius: 100px;
	height: 40px;
	width: 550px;
}

.loupe
{
	width: 16px;
	height: 16px;
	position: absolute;
}

input:hover
{
	box-shadow: #BABABA 1px 1px 2px;
}

.btn
{
	border: none;
	background-color: white;
	width: 150px;
	height: 40px;
	font-family: arial;
	margin-bottom: 20px;
}

.btn:hover
{
	border: solid grey 1px;
}

.jugement
{
	width: 293px;
	height: 22px;
	border: black solid 1px;
	text-align-last: center;
	
}

.jugement:hover
{
	text-decoration: underline;
}

.english
{
	font-family: arial;
	font-size: 13px;
	margin-top: 20px;
}

span
{
	color: blue;
}

#pied
{
	margin-bottom: 10px;
	width: 1255px;
}

.footer1
{
	height: 25px;
    background-color: #EFEFEF;
    border: solid 1px #BABABA;
    padding-top: 10px;
    margin-top: 10px;
}

.france
{
	padding-left: 40px;
	color: grey;
	font-family: arial;
}

.footer2
{
	height: 50px;
	border: solid 1px #BABABA;
	background-color: #EFEFEF;
}

li
{
	list-style-type: none;
	display: inline;
	font-family: arial;
}

.lien
{
	color: grey;
}
.lien:hover
{
	text-decoration: underline;
}

.feuille
{
	width: 16px;
	height: 16px;
}




