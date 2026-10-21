# Elmerin Piha-apu – nettisivu

Yhden sivun (`index.html`) staattinen sivusto. Ei rakennusvaihetta eikä riippuvuuksia.

## Julkaisu GitHub Pagesilla
1. Lisää kaikki tiedostot repositorion juureen.
2. Repositoriossa: **Settings → Pages → Build and deployment → Source: Deploy from a branch**.
3. Valitse branch `main` ja kansio `/ (root)`, paina **Save**.
4. Sivu avautuu hetken kuluttua osoitteessa `https://KÄYTTÄJÄ.github.io/REPO/`.

## Sisällön muokkaaminen (`index.html`)
- **Hinnat ja alennukset:** etsi tiedostosta `/* ===== Muokattavat tiedot ===== */`.
  - `FENCE` = aidan hinta (perushinta + hinta/m). Nyt 30 m ≈ 150 €, 100 m ≈ 400 €.
  - `LAWN` = nurmikon hinta-arviot kokoluokittain (`to` = yläraja m², `a`–`b` = haarukka €).
  - `DISCOUNTS` = alennukset. Aseta `on:false`, kun kampanja päättyy.
- **Ennen/jälkeen-kuvat:** korvaa tiedostot kansiossa `images/` samannimisillä, 4:3-kuvasuhteen kuvilla (esim. 640 × 480 px).
- **Asiakaspalautteet:** `REVIEWS`-lista skriptin alussa. Kaksi ensimmäisen jälkeistä on esimerkkejä, korvaa ne oikeilla.
- **Varaus:** Vellon varausosio lisätään kohtaan `<!-- VELLO-VARAUSOSIO TÄHÄN -->`.
- **Puuttuvat kuvat:** 4H-logo (nyt "4H"-merkki), kuva Elmeristä työn touhussa ja kunniakirjan kuva ovat paikkamerkkejä.
