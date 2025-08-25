ich mochte das du wie ein senior software enginier als frontend developer an die sache rangehst. ich will das du alle dinge die ich dir in diesem Prompt schreibe genau ausfuehrst wie es geschrieben steht und garnicht haluzinierst. ich mochte das du nur den frontend machst und keinen backend. zu dem frontend gehoeren auch requests aber keine annahme der requests.


hier ist ein ganz roher bespielcode den ich schnell mal erstellt habe:
index.html:
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
    <title>Amalia the Dishwasher</title>
</head>
<body>
    <header>
        <nav>
            <div class="title">Hello, I'm the best dishwasher in the whole world</div>
        </nav>
    </header>
    <main>
        
        <div class="div_grid">
            <img src="foto.png" alt="Image not available" class="dishwasher_photo">
            <div class="about">
                <h2>Amalia Mishchenko</h2>
                <p>I am the ultimate dishwasher – the best in the world at what I do! Reliable, efficient, and thorough, I make sure every plate, glass, and utensil sparkles like new. Whether it’s a small kitchen or a large commercial setup, I can handle any workload with speed and precision.

                Now available for rent at the most competitive price, I am ready to take on any task you need. From delicate glassware to heavily soiled pots and pans, I guarantee spotless results every time. Your satisfaction is my priority, and I am committed to delivering excellence in every wash.

                Don’t settle for anything less than perfection – let me take care of your dishes and make your life easier. I am here to serve, adapt, and exceed your expectations, whatever your needs may be!</p>
                <h3>400$ /h</h3>
                <a href="https://www.linkedin.com/in/amalia-mishchenko-17b147380?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=ios_app" target="_blank"><button class="linkedin_button">My LinkedIn</button></a>
            </div>
        </div>
    </main>
    <footer>
        
    </footer>
</body>
</html>

style.css:
/* Grundfarben & Body */
body {
    background-color: rgb(53, 48, 51);
    margin: 0;
    font-family: Arial, sans-serif;
}

/* Header / Titel */
.title {
    color: pink;
    font-size: 50px;
    text-align: center;
    padding: 20px;
}

/* LinkedIn Button */
.linkedin_button {
    background-color: rgb(249, 169, 182);
    color: white;
    font-family: Arial, sans-serif;
    font-size: 20px;
    width: 200px;
    height: 40px;
    border-radius: 10px;
    border: none;
    margin: 20px;
    box-shadow: 4px 4px 10px rgba(0,0,0,0.5);
    cursor: pointer;
    transition: background-color 0.3s ease, transform 0.2s ease;
}

.linkedin_button:hover {
    background-color: rgb(210, 132, 145);
    transform: scale(1.05);
}

/* Bild */
.dishwasher_photo {
    width: 100%;
    max-width: 300px;
    height: auto;
    border-radius: 10px;
}

/* Grid / Layout */
.div_grid {
    display: flex;
    gap: 20px;
    justify-content: center;
    margin-top: 30px;
    flex-wrap: wrap; /* erlaubt Umbruch auf kleinen Bildschirmen */
}

/* Textbereich */
.about {
    color: pink;
    max-width: 400px;
}

h2 {
    text-decoration: underline;
    padding: 20px 0 10px 0;
    text-align: left;
}

h3 {
    padding: 0 0 20px 0;
}

p {
    width: 100%;
    max-width: 400px;
    word-wrap: break-word;
    padding: 0 0 20px 0;
}

@media (max-width: 600px) {
    .div_grid {
        flex-direction: column; 
        align-items: center;
    }

    h2, h3, p, img{
        text-align: center;
        padding: 10px;
        max-width: 400px;
    }

    .linkedin_button {
        width: 100%;
        max-width: 450px;
    }
}
foto.png:
![alt text](foto.png)

also was du genau machen musst:
- ueberarbeite den code das der sauber ist wie man das als senior macht
- halte dich an die gegebenen farben aber du darfst die leicht abaendern oder was hinzufeugen wenn du meinst das es dann besser aussieht.
- ich will das du mehr content einfuegst aber ueber das selbe thema.
- erstelle eigene sections fuer jeden teil
- ich will das du alles in einem sehr modernen stil machst
- es sollen animationen vorhanden sein: ich will das der titel geschreiben wird als animation also so als wuerde das jemand gerade tippen. alle buttons sollen hover und klick animationen haben. es soll einen kleinen scrollefect geben aber nicht zu doll. die navbar soll als erstes ueber das ganze bildschirm gehen und dann wenn man runterscrollt soll es nur oben eine leiste werden.
- ich will auch das du einen footer erstellst wo ein copyright ist von Guralnik 2025
- ich will das du auch eine kontakt box machst wo man seine daten eingeben kann und die werden dann gefetched an localhost:55555/contact
- ich will das du das foto was auf der webseite ist das es nicht einfach da ist sondern in so einem eigenartigen shape ist aber keine scherbe oder einfach kreis sondern es soll etwas cooles einfallsreiches sein.

gebe es mir in folgendem format zurueck:
ich will das du mir eine index.html, style.css und script.js gibst