<!DOCTYPE html>
<html lang="fr" id="top">

<head>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SAÉ25 Portfolio - Aku</title>
    <link rel="icon" type="image/png" href="3130c8acbe50ec1af151a862ca5a53fb.jpg">
    <link rel="stylesheet" href="portfolio.css">
    <link href="https://fonts.googleapis.com/css?family=Roboto" rel="stylesheet">
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-0evHe/X+R7YkIZDRvuzKMRqM+OrBnVFBL6DOitfPri4tjfHxaWutUpFmBp4vmVor" crossorigin="anonymous">
</head>

<body>

    <nav>
        <!-- Trigger/Open The Modal -->
        <button id="myBtn">Berneuil Justin</button>

        <!-- The Modal -->
        <div id="myModal" class="modal">

            <!-- Modal content -->
            <div class="modal-content">
                <span class="close">&times;</span>
                <p>Justin site, pas deux...</p>
            </div>

        </div>
        <center>
            <p id="status">
                Étudiant en informatique
            </p>
        </center>
        <img id="PP" src="PP.png" alt="Photo de profil">
        <ul>
            <a href="#Pres">
                <li id="Pres2">Présentation</li>
            </a>
            <a href="#ED">
                <li id="ED2">Études & Diplômes</li>
            </a>
            <a href="#Comp">
                <li id="Comp2">Compétences</li>
            </a>
            <a href="#Proj">
                <li id="Proj2">Projets</li>
            </a>
            <a href="#CI">
                <li id="CI2">Centre d'intérets</li>
            </a>
            <a href="#Cont">
                <li id="Cont2">Contacts</li>
            </a>
        </ul>
    </nav>

    <!--Pour § : pas besoin de balise dans le <details>-->

    <details class="reveal" id="Ac1">
        <summary id="Pres">Présentation</summary>
        <hr>
        <p>Je me nomme Berneuil Justin, j'ai 21 ans et je souhaite travailler dans le domaine de l'informatique. Je suis actuellement étudiant à l'université de Tours, dans la ville de Blois. De nature curieuse, je m'intéresse à énormément de domaines tels
            que les sciences, la musique, le cinéma et bien d'autres encore !
    </details>
    <details class="reveal" id="Ac2">
        <summary id="ED">Études & Diplômes</summary>
        <hr>
        <p>Titulaire d'un bac STI2D (Sciences et Technologies de l'Industrie et du Développement Durable) spécialité SIN (Système d'Information et Numérique), j'ai d'abord fait une première année dans le supérieur dans une licence en mathématiques et informatique,
            avant de me réorienter vers un BUT (Bachelor Universitaire de Technologie) Réseaux et Télécommunications.
        </p>
    </details>
    <details class="reveal" id="Ac2">
        <summary id="Comp">Compétences</summary>
        <hr>
        <p>J'ai commencé à m'intéresser au développement web en terminale, pour simple utilité, histoire d'avoir une bonne note. Dès lors, je me suis intéressé à ce domaine, plus comme une passion que comme une vocation. J'ai pu affiner mes connaissances
            lors de ma première année en licence, en travaillant surtout sur le design de mes sites.
            <br>
            <div class="alinea"> Je suis donc compétent dans l'utilisation de l'HTML5 mais aussi du CSS3, qui sont les seuls languages utilisés pour réaliser ce site. Je aussi quelques notions en JavaScript que j'ai d'ailleurs utilisé pour faire un easter egg. De plus, je
                connais aussi le PHP et le SQL, et j'ai des compétences dans l'administration de serveur MySQL et Apache, nécessaire pour faire fonctionner un site web. Tout cela sera illustré dans la section suivante avec les projets que j'ai pu réaliser.</div>
        </p>
        <img src="html5-css3-300x205.webp" id="htmlcss">
        <div class="progress" id="barhtmlcss">
            <div class="progress-bar progress-bar-striped progress-bar-animated bg-warning" style="width:75%">75%</div>
        </div>
        <img src="PHP-logo.png" id="php">
        <div class="progress" id="barphp">
            <div class="progress-bar progress-bar-striped progress-bar-animated bg-danger" style="width:45%">45%</div>
        </div>
        <img src="sql.png" id="sql">
        <div class="progress" id="barsql">
            <div class="progress-bar progress-bar-striped progress-bar-animated bg-success" style="width:70%">70%</div>
        </div>
        <img src="1200px-MySQL.svg.png" id="mysql">
        <div class="progress" id="barmysql">
            <div class="progress-bar progress-bar-striped progress-bar-animated bg-primary" style="width:65%">65%</div>
        </div>
    </details>
    <details class="reveal" id="Ac2">
        <summary id="Proj">Projets</summary>
        <hr>
        <p>Lors de mes débuts dans la programmation en terminale, comme dit précédemment, j'avais dû faire un site web, il n'est pas en ligne évidemment. Ce n'était pas très esthétique, mais ce qui compter était le code, pas son apparence.<br>
        </p>
        <img src="T1.png" id="SiteTerm"><img src="T2.png" id="SiteTerm">
        <p>L'année passée, lors de ma licence, j'ai aussi dû en faire un pour un partiel, celui-la aussi n'est pas en ligne. Je me suis quand même amélioré durant cette année, aussi bien sur l'esthétique que sur le plan technique.<br></p>
        <img src="HxH1.PNG" id="SiteHxH"><img src="HxH2.PNG" id="SiteHxH">
        <p>Durant cette année en BUT, j'ai aussi eu à faire quelques sites web pour des examens, mais je vais seulement parler du <a href="https://akutog.github.io/Portfolio/" target="LienCon1">portfolio</a> fait au premier semestre, car celui-ci est en
            ligne et donc accessible à n'importe quel moment.
        </p>
    </details>
    <details class="reveal" id="Ac2">
        <summary id="CI">Centre d'intérets</summary>
        <hr>
        <h4><u>Musique:</u></h4><br>
        <p>J'en écoute tout le temps, de tous les styles, même si j'ai une préfèrence pour celles ayant un message. Celles que j'apprécie particulièrement sont <a href="https://www.youtube.com/watch?v=WYeDsa4Tw0c" target="LienCon1">"Conquest of paradise"</a>            de Vangelis,
            <a href="https://www.youtube.com/watch?v=Dkqsh0kkjFw" target="LienCon1">Armstrong</a> de Claude Nougaro, mais aussi des musiques plus urbaines tels que
            <a href="https://www.youtube.com/watch?v=exsKGwuZuMQ" target="LienCon1">Fil bleu</a> de Lefa ou encore
            <a href="https://www.youtube.com/watch?v=_y7Gd3uHGag&list=OLAK5uy_mzxiPxw1VZvWSuqrcU_R7z1SFdYz0H_mo" target="LienCon1">l'album V</a> de Vald.</p>
        <h4><u>Cinéma:</u></h4><br>
        <p>Je regarde énormément de films, des récents, mais aussi des films plus ancien. En comédie, je pense notamment à
            <a href="https://www.allocine.fr/film/fichefilm_gen_cfilm=36184.html" target="LienCon1">Y a-t-il un pilote dans l'avion ?</a> ou
            <a href="https://www.allocine.fr/film/fichefilm_gen_cfilm=47702.html" target="LienCon1">Mais qui a tué Pamela Rose ?</a> et <a href="https://www.allocine.fr/film/fichefilm_gen_cfilm=179227.html" target="LienCon1">La Famille Addams</a>, en
            horreur c'est <a href="https://www.allocine.fr/video/player_gen_cmedia=18675289&cfilm=42552.html" target="LienCon1">Le cercle - The ring</a> sorti en 2002 qui me vient à l'esprit.
        </p>
    </details>
    <details class="reveal" id="Ac3">
        <summary id="Cont">Contacts</summary>
        <hr>
        <a href="mailto:justin.berneuil@etu.univ-tours.fr" target="LienCon1"><img src="Circle-icons-mail.svg.png" class="LienCon1">justin.berneuil@etu.univ-tours.fr</a><br>
        <a href="https://www.linkedin.com/in/justin-berneuil-a671b0226" target="LienCon1"><img src="174857.png" class="LienCon1">LinkedIn</a><br>
        <a href="https://github.com/AkuToG" target="LienCon1"><img src="Octicons-mark-github.svg" class="LienCon1">GitHub</a>
    </details>

    <div id="button_top">
        <a href="#top"><img src="arrow2.png" alt="Retourner en haut" /></a>
    </div>

</body>

</html>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.0-beta1/dist/js/bootstrap.bundle.min.js" integrity="sha384-pprn3073KE6tl6bjs2QrFaJGz5/SUsLqktiwsUTF55Jfv3qYSDhgCecCxMW52nD2" crossorigin="anonymous"></script>

<script>
    // Get the modal
    var modal = document.getElementById("myModal");

    // Get the button that opens the modal
    var btn = document.getElementById("myBtn");

    // Get the <span> element that closes the modal
    var span = document.getElementsByClassName("close")[0];

    // When the user clicks on the button, open the modal
    btn.onclick = function() {
        modal.style.display = "block";
    }

    // When the user clicks on <span> (x), close the modal
    span.onclick = function() {
        modal.style.display = "none";
    }

    // When the user clicks anywhere outside of the modal, close it
    window.onclick = function(event) {
        if (event.target == modal) {
            modal.style.display = "none";
        }
    }
</script>
