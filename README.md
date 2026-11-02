# Elmerin Piha-apu – nettisivu

Yhden sivun staattinen sivusto (ei build-vaihetta). Julkaisu GitHub Pagesissa: Settings → Pages → Deploy from branch → `main` / root.

## Muokattavat kohdat (index.html, scriptin alussa)
- **CONTACT** – lisää `phone` ja/tai `email`. Hinta-arvio-osion napit ja mobiilin yläpalkin "📞 Soita" -nappi ilmestyvät automaattisesti. Kunnes tiedot on lisätty, sivu näyttää "Yhteystiedot lisätään tähän pian." eikä Soita-nappia.
- **CODE** – ensikertalaisen alennuskoodi (nyt `UUSI10`), näkyy vahvistusviestissä ja sähköpostin esitäytetyssä tekstissä.
- **PAIRS** – ennen/jälkeen-kuvaparit (kuvat kansiossa `images/`, anna myös leveys `w` ja korkeus `h`).
- **REVIEWS** – asiakaspalautteet.

## Tervetuloikkuna
Näytetään kerran istunnossa: 5,5 s viiveellä tai kun sivua on selattu yli 400 px.

## Ajanvaraus (Vello)
Liitä Vellon upotuskoodi elementtiin `#vello-varaus` ja poista paikkamerkki `.vello-ph`.

## Yritystiedot alatunnisteeseen
Alatunnisteessa on HTML-kommentti, johon voi lisätä Y-tunnuksen / 4H-yhdistyksen tiedot, vakuutuksen ja huoltajan yhteystiedon, kun ne on vahvistettu.

## Kuvat
`images/` sisältää WebP-kuvat ja 4H-logon. 4H-julkaisun kuvasta on rajattu pois muiden saajien nimet.
