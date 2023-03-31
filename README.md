# DevelopersLife.github.io
DevelopersLife Website Source

## Per far partire il progetto

Attenzione : prima di effettuare i passi per far partire il progetto è necessario installare Nodejs

* Scaricare il repository su una propria cartella a piacere
* Portarsi nella directory di root appena scaricata e aprire il proprio terminale preferito (DOS , powershell , bash , ecc)
* lanciare il comando **npm install** per installare tutte le dipendenze
* lanciare il comando **npm start** per visualizzare il sito in locale
* aprire il proprio browser preferito con il seguente url [http://localhost:3000/](http://localhost:3000/)
* ora siete pronti per contribuire al progetto

## Come Aggiungere nuovi membri di DevelopersLife

Sul file data/team.js puoi aggiungere un nuovo elemento così formattato:
```
{
    "name": "Il tuo nome",
    "nick": "il tuo nick",
    "role": "Il tuo ruolo",
    "imageUrl": "la_tua_immagine.png",
    "linkedinUrl": "url_a_linkedin",
    "twitterUrl": "url_a_twitter",
}
```

Alcune cose da sapere:  
  * name: puoi usare il tuo nome e cognome o solo il tuo nome (ma non è possibile usare un nick)
  * nick: il nick che vuoi usare (non obbligatorio e per ora non utilizzato)
  * role: il tuo ruolo in DevelopersLife (concordalo prima con Mich)
  * imageUrl: l'indirizzo alla tua immagine (partendo dalla cartella public/static/photos presente in questo repo)
  * linkedinUrl: l'url del tuo profilo linkedin (senza nessun tipo di tracker o shorter link, non obbligatorio e per ora non utilizzato)
  * twitterUrl: l'url del tuo profilo twitter (senza nessun tipo di tracker o shorter link, non obbligatorio e per ora non utilizzato)
