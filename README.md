<meta name='viewport' content='width=device-width, initial-scale=1'/><!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Transfert Zelle - Best Deal Enterprise</title>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>

    <header>
        <h1>Transfert d'Argent</h1>
        <nav>
            <ul>
                <li><a href="index.html">Accueil</a></li>
                <li><a href="produits.html">Boutique</a></li>
                <li><a href="contact.html">Contact</a></li>
            </ul>
        </nav>
    </header>
<meta name='viewport' content='width=device-width, initial-scale=1'/>
<!DOCTYPE html>
<html>
<head>
  <title>Formulaire Transfert</title>
</head>
<body>

  <h2>F猫 yon transf猫 Zelle</h2>

  <input type="text" id="nom" placeholder="Non kliyan"><br><br>
  <input type="text" id="montant" placeholder="Montant an USD"><br><br>
  <input type="text" id="email" placeholder="Im猫l kliyan"><br><br>
  <input type="text" id="beneficiaire" placeholder="Non moun k ap resevwa a"><br><br>
  <input type="text" id="zelle" placeholder="Zelle moun nan (Im猫l oubyen nimewo)"><br><br>
  <textarea id="remarque" placeholder="Remak espesyal" rows="4" cols="40"></textarea><br><br>

  <button onclick="voyeWhatsApp()">Voye sou WhatsApp</button>

  <script>
    function voyeWhatsApp() {
      var nom = document.getElementById("nom").value;
      var montant = document.getElementById("montant").value;
      var email = document.getElementById("email").value;
      var beneficiaire = document.getElementById("beneficiaire").value;
      var zelle = document.getElementById("zelle").value;
      var remarque = document.getElementById("remarque").value;

      var mesaj = 
        "*Nouvo Demann Transf猫 Zelle*%0A" +
        "馃懁 Non Kliyan: " + nom + "%0A" +
        "馃挼 Montant: " + montant + " USD%0A" +
      "馃摟 Im猫l: " + email + "%0A" +
        "馃懁 Benefisy猫: " + beneficiaire + "%0A" +
        "馃摬 Zelle: " + zelle + "%0A" +
        "馃摑 Remak: " + remarque;

      var link = "https://wa.me/50942006945?text=" + mesaj;

      window.open(link, "_blank");
    }
  </script>
</body>

    <footer>
        <p>&copy; 2024 Best Deal Enterprise - Tous droits r茅serv茅s.</p>
    </footer>

</body>
</html><style>body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
    color: #333;
}

/* Style Header */
header {
    background-color: #008000;
    color: white;
    padding: 20px;
    text-align: center;
}

nav ul {
    list-style: none;
    padding: 0;
}

nav ul li {
    display: inline;
    margin: 0 15px;
}

nav ul li a {
    color: white;
    text-decoration: none;
    font-weight: bold;
}

/* Style Seksyon Hero */
#hero {
    text-align: center;
    padding: 50px 20px;
    background: url('hero.jpg') no-repeat center center/cover;
    color: white;
}

.btn {
    background-color: #ff9900;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    font-weight: bold;
    display: inline-block;
    margin-top: 20px;
}

/* Style S猫vis */
#services {
    text-align: center;
    padding: 60px;
    background-color: #f9f9f9;
}

.service {
    background-color: white;
    padding: 30px;
    margin: 20px auto;
    border-radius: 10px;
    max-width: 600px;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s;
}

.service:hover {
    transform: scale(1.05);
}

.service ul {
    text-align: left;
    list-style: none;
    padding: 0;
}

.service ul li {
    padding: 5px 0;
    font-size: 16px;
    color: #333;
}

.service h3 {
    color: #008000;
}

.btn {
    background-color: #ff9900;
    color: white;
    padding: 12px 18px;
    text-decoration: none;
    font-weight: bold;
    display: inline-block;
    border-radius: 5px;
    margin-top: 15px;
    transition: background 0.3s;
}
.btn:hover {
    background-color: #cc7a00;
}
#about {
    padding: 60px;
    background-color: #ffffff;
    text-align: center;
}

.about-container {
    display: flex;
    flex-wrap: wrap;
    align-items: center;
    justify-content: center;
}

.about-text {
    max-width: 600px;
    text-align: left;
    font-size: 18px;
line-height: 1.6;
    color: #333;
}

.about-text p {
    margin-bottom: 15px;
}

.about-image img {
    max-width: 100%;
    border-radius: 10px;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.1);
    width: 300px;
}
/* Section Pourquoi Nous Choisir */
#why-choose-us {
    padding: 60px;
    background-color: #f9f9f9;
    text-align: center;
}

.reasons-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 20px;
}

.reason {
    background: #ffffff;
padding: 20px;
    width: 300px;
    border-radius: 10px;
    box-shadow: 0px 5px 15px rgba(0, 0, 0, 0.1);
    transition: transform 0.3s ease;
}

.reason:hover {
    transform: translateY(-5px);
}

.reason img {
    width: 80px;
}

.reason h3 {
    color: #27ae60;
    margin-top: 10px;
}

.reason p {
    color: #555;
}
    
/* Style Footer */
footer {
    background-color: #008000;
    color: white;
    text-align: center;
    padding: 10px;
    margin-top: 20px;
}

#transfert-form {
    max-width: 500px;
    margin: 50px auto;
    padding: 20px;
    background: white;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    text-align: center;
}

#transfert-form h2 {
    color: #2d98da;
}

form {
    display: flex;
    flex-direction: column;
}

label {
    font-weight: bold;
    margin: 10px 0 5px;
}

input, textarea {
    width: 100%;
    padding: 10px;
    margin-bottom: 15px;
    border: 1px solid #ccc;
    border-radius: 5px;
}

.btn {
    background: #2d98da;
    color: white;
    padding: 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: 0.3s;
}

.btn:hover {
    background: #2271b1;
}

#confirmation {
    max-width: 600px;
    margin: 50px auto;
    padding: 20px;
    background: white;
    box-shadow: 0px 0px 10px rgba(0, 0, 0, 0.1);
    border-radius: 10px;
    text-align: center;
}

#confirmation h2 {
    color: #2d98da;
}

p {
    font-size: 18px;
    margin-bottom: 20px;
}

.btn {
    background: #2d98da;
    color: white;
    padding: 10px;
    border: none;
    border-radius: 5px;
    cursor: pointer;
    transition: 0.3s;
}

.btn:hover {
    background: #2271b1;
}</style>