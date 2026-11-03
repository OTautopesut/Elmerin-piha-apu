# Elmerin Piha-apu – nettisivu

Yhden sivun staattinen sivusto (ei build-vaihetta). Julkaisu GitHub Pagesissa: Settings → Pages → Deploy from branch → `main` / root.

## Muokattavat kohdat (index.html, scriptin alussa)
- **CONTACT** – puhelin ja sähköposti. Hinta-arvio-osion napit, yläpalkin "📞 Soita" -nappi (mobiili) ja varauslomakkeen vastaanottaja käyttävät näitä.
- **CODE** – ensikertalaisen alennuskoodi (nyt `UUSI10`).
- **PAIRS** – ennen/jälkeen-kuvaparit (kuvat kansiossa `images/`, anna myös leveys `w` ja korkeus `h`).
- **REVIEWS** – asiakaspalautteet.

## Varauslomake
Osio `#varaa` on varauspyyntölomake (nimi, sähköposti, puhelin, osoite, palvelu, toivottu päivä, lisätietoja, alennuskoodi). Lähetys menee sähköpostiin `CONTACT.email` palvelun FormSubmit (formsubmit.co) kautta. **Ensimmäisellä lähetyksellä FormSubmit lähettää vahvistusviestin tähän sähköpostiin – klikkaa viestin linkkiä kerran, jonka jälkeen lomake toimii.** Tarkista myös roskaposti. Jos lähetys epäonnistuu, sivu avaa sähköpostiohjelman valmiiksi täytetyllä viestillä.

## Tervetuloikkuna
Näytetään kerran istunnossa: 5,5 s viiveellä tai kun sivua on selattu yli 400 px.

## Yritystiedot alatunnisteeseen
Alatunnisteessa on HTML-kommentti, johon voi lisätä Y-tunnuksen / 4H-yhdistyksen tiedot, vakuutuksen ja huoltajan yhteystiedon, kun ne on vahvistettu.

## Kuvat
`images/` sisältää WebP-kuvat ja 4H-logon. 4H-julkaisun kuvasta on rajattu pois muiden saajien nimet.
