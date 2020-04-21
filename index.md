
<!DOCTYPE html>
<html lang="en" dir="ltr">
<head>
  <meta charset="utf-8">
  <title>Portfolio</title>
  <link rel="stylesheet" href="css/style.css">
  <link href="https://fonts.googleapis.com/css?family=Alegreya+Sans|Anton&display=swap" rel="stylesheet">
    <!--<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/css/bootstrap.min.css"> -->
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!--<script src="https://kit.fontawesome.com/f571191d00.js" crossorigin="anonymous"></script> -->
</head>
<body>
    <div class="container">
        <div class="img"><!-- Logo -->
            <img src="medias/Logo.png" class="logo">
        </div>
        <div class="title">Me contacter</div> <!-- Titre -->
        <div class="navigation"> <!-- Menu de navigation -->
        <ul>
            <li class="liNorm"><a href="#" class="acceuil">Acceuil</a></li>
            <li class="liNorm"><a href="#" class="realisations">Réalisations</a></li>
            <li class="liNorm"><a href="#" class="aPropos">À propos</a></li>
            <li class="liNorm"><a href="#" class="meContacter">Me contacter</a></li>
        </ul>
        </div>
        <div class="contenu meContacter_contenu"> <!-- Me contacter-->
                <h2>Si vous souhaitez me contacter pour un projet ou une embauche, voici mes informations de contact.</h2>
                <br>
                <p class="contenu_texte"> Par mail : daniel.fiola@oulook.com <br> </p>
                <a href="https://www.linkedin.com/in/daniel-fiola" target="_blank">LinkedIn</a>
        </div>
        
       <div class="contenu acceuil_contenu"> <!-- Acceuil-->
             <p>Je m'appelle Daniel et voici mon portfolio!</p>
            <img src="medias/Logo.png" class="logoAcc">
        </div>
        <div class="contenu realisations_contenu"> <!-- Realisations-->
            <h2>Voici mes réalisations pertinentes!</h2>
                <div class="slideshow-container">
                  <div class="mySlides1">
                    <img src="medias/Cadenas.png" style="width:100%">
                  </div>

                  <div class="mySlides1">
                    <img src="medias/TDI.gif" style="width:100%">
                  </div>
                  <a class="next" onclick="plusSlides(1, 0)">&#10095;</a>
                </div>
        
        
        </div>
        <div class="contenu aPropos_contenu"> <!-- A propos-->
               <p>Je suis Daniel Fiola, étudiant en dernière session au collège de Maisonneuve en Techniques d'Intégration Multimédia(TIM). Je me spécialise en programmation et plus précisément en programmation de jeux vidéo.</p> 
               
        </div>
    </div>
</body>    
<footer>
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.1/js/bootstrap.min.js"></script>
  <script src="js/jquery-3.5.0.js"></script>
  <script src="js/scripts.js"></script>
</footer>
</html>
