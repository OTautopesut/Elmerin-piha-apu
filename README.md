# Elmerin Piha-apu – nettisivu

Yhden sivun (`index.html`) staattinen sivusto. Ei rakennusvaihetta eikä riippuvuuksia.

## Julkaisu GitHub Pagesilla
1. Lisää kaikki tiedostot repositorion juureen.
2. Repositoriossa: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Valitse branch `main` ja kansio `/ (root)`, paina **Save**.
4. Sivu avautuu hetken kuluttua osoitteessa `https://KÄYTTÄJÄ.github.io/REPO/`.

## Sisällön muokkaaminen (`index.html`)
- **Yhteystiedot:** etsi `var CONTACT={phone:'',email:''};` skriptin alusta ja täytä puhelin ja/tai sähköposti. Napit "Soita" ja "Lähetä viesti" ilmestyvät hinta-arvio-osioon. Sähköpostiviestin pohja täyttyy automaattisesti.
- **Hinta-arvio:** hintalaskuria ei ole. Hinta-arvion antaa Elmeri itse, kun asiakas ottaa yhteyttä.
- **Asiakaspalautteet:** `REVIEWS`-lista samassa kohdassa.
- **Ennen/jälkeen-kuvat:** korvaa tiedostot kansiossa `images/` samannimisillä, 4:3-kuvasuhteen kuvilla (esim. 640 × 480 px).
- **4H-stipendin todiste:** `images/4h-stipendi-julkaisu.jpg`.
- **Ajanvaraus (Vello):** osio `<section id="varaa">`. Liitä Vellon upotuskoodi elementtiin `#vello-varaus` ja poista paikkamerkki `vello-ph`.
- **Ponnahdusikkuna:** `id="pop"` sivun alussa. Se aukeaa joka kerta sivun avautuessa. Poista rivi `setTimeout(openPop,500);`, jos haluat ottaa sen pois. "Hyödynnä alennus" -nappi lisää maininnan 10 % ensikertalaisalennuksesta hinta-arvio-osioon ja sähköpostin pohjaan.
- **Logo:** 4H-logo on vielä paikkamerkki ("4H"-merkki) sivun ylävalikossa.
