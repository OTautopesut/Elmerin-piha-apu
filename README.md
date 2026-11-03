# Elmerin Piha-apu – nettisivu

Yhden sivun staattinen sivusto (ei build-vaihetta). Julkaisu GitHub Pagesissa: Settings → Pages → Deploy from branch → `main` / root.

## Muokattavat kohdat (index.html, scriptin alussa)
- **CONTACT** – puhelin ja sähköposti. Varausosion Soita- ja Lähetä viesti -napit, yläpalkin "📞 Soita" -nappi (mobiili) ja varauslomakkeen vastaanottaja käyttävät näitä.
- **PAIRS** – ennen/jälkeen-kuvaparit (kuvat kansiossa `images/`, anna myös leveys `w` ja korkeus `h`).
- **REVIEWS** – asiakaspalautteet.

## Varauslomake
Osio `#varaa` on varauspyyntölomake (nimi, sähköposti, puhelin, osoite, palvelu, lisätietoja). Hinta kerrotaan varauksen vahvistuksen yhteydessä.
- **Ilman avainta** (`FORM_KEY=''`) lomake avaa asiakkaan sähköpostiohjelman valmiiksi täytetyllä viestillä osoitteeseen `CONTACT.email`.
- **Suora lähetys:** hae ilmainen avain osoitteesta web3forms.com (anna sähköposti, avain tulee viestinä) ja liitä se `FORM_KEY`-kohtaan. Silloin varaus tulee suoraan sähköpostiin, ja asiakas näkee kiitosviestin. Jos lähetys epäonnistuu, sivu avaa sähköpostiohjelman.

## Yritystiedot alatunnisteeseen
Alatunnisteessa on HTML-kommentti, johon voi lisätä Y-tunnuksen / 4H-yhdistyksen tiedot, vakuutuksen ja huoltajan yhteystiedon, kun ne on vahvistettu.

## Kuvat
`images/` sisältää WebP-kuvat ja 4H-logon. 4H-julkaisun kuvasta on rajattu pois muiden saajien nimet.
