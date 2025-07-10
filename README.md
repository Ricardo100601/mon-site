# <!DOCTYPE html>

<html lang="fr">

<head>

  <meta charset="UTF-8">

  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Mon Site Personnel</title>

  <style>

    * {

      margin: 0;

      padding: 0;

      box-sizing: border-box;

    }



    body {

      font-family: Arial, sans-serif;

      line-height: 1.6;

      background-color: #f4f4f4;

      color: #333;

      padding: 0;

    }



    header {

      background-color: #0077cc;

      color: white;

      padding: 20px 0;

      text-align: center;

    }



    nav {

      background-color: #005fa3;

      display: flex;

      justify-content: center;

    }



    nav a {

      color: white;

      text-decoration: none;

      padding: 15px 20px;

      display: inline-block;

    }



    nav a:hover {

      background-color: #004b84;

    }



    main {

      max-width: 1000px;

      margin: 30px auto;

      padding: 20px;

      background: white;

      box-shadow: 0 0 10px rgba(0,0,0,0.1);

    }



    section {

      margin-bottom: 40px;

    }



    footer {

      text-align: center;

      padding: 20px;

      background-color: #222;

      color: #ccc;

      margin-top: 50px;

    }



    img.profil {

      max-width: 150px;

      border-radius: 50%;

      display: block;

      margin: 20px auto;

    }



    .reseaux a {

      margin: 0 10px;

      text-decoration: none;

      color: #0077cc;

    }



    @media (max-width: 600px) {

      nav {

        flex-direction: column;

      }

    }

  </style>

</head>

<body>



  <header>

    <h1>Bienvenue sur mon site</h1>

    <p>Développeur Web | Étudiant | Passionné de technologie</p>

  </header>



  <nav>

    <a href="#presentation">Présentation</a>

    <a href="#projets">Projets</a>

    <a href="#contact">Contact</a>

  </nav>



  <main>

    <section id="presentation">

      <h2>Présentation</h2>

      <img src="https://via.placeholder.com/150" alt="Ma photo" class="profil">

      <p>Bonjour ! Je m'appelle <strong>Ton Prénom</strong>. Je suis passionné par le développement web, le design, et la technologie. Ce site me permet de partager mes projets et de me présenter.</p>

    </section>



    <section id="projets">

      <h2>Mes projets</h2>

      <ul>

        <li>🖥️ Portfolio personnel (HTML, CSS)</li>

        <li>📱 Application mobile en cours (Flutter)</li>

        <li>💡 Mini-jeux JavaScript (en développement)</li>

      </ul>

    </section>



    <section id="contact">

      <h2>Contact</h2>

      <p>📧 Email : <a href="mailto:ton.email@example.com">ton.email@example.com</a></p>

      <p class="reseaux">

        🔗 Réseaux :

        <a href="https://github.com/tonpseudo" target="_blank">GitHub</a> |

        <a href="https://linkedin.com/in/tonprofil" target="_blank">LinkedIn</a> |

        <a href="https://instagram.com/toncompte" target="_blank">Instagram</a>

      </p>

    </section>

  </main>



  <footer>

    <p>&copy; 2025 Ton Nom - Tous droits réservés</p>

  </footer>



</body>

</html>
