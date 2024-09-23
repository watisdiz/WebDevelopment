# JSON-tiedoston suunnittelu ja tietojen hakeminen Tehtävä

Esittelee kurssitoteutuksen tiedot ja sisältää kaksi HTML-sivua (`index.html` ja `toteutus.html`), jotka on tyylitelty CSS:n avulla.

## Projektin rakenne

- **index.html**: Verkkosivu, joka toivottaa käyttäjän tervetulleeksi ja sisältää navigaation toteutuksen esittelysivulle. Sivulla on myös kuva ja dynaaminen tervetuloviesti.
- **toteutus.html**: Sivusto, joka hakee ja näyttää kurssitoteutuksen tiedot ulkoiselta Mocky-palvelimelta JSON-muodossa.
- **styles.css**: Tyylitiedosto, joka määrittää molempien HTML-sivujen ulkoasun ja asettelun.

## Ominaisuudet

### index.html

- **Tervetuloviesti**: Sivulla on keskitetty "Tervetuloa!" -otsikko.
- **Kuva**: Sivulla on myös kuva, joka on sijoitettu tervetulotekstin alle.

### toteutus.html

- **Kurssitiedot**: Sivusto hakee JSON-muotoiset tiedot kurssitoteutuksesta ulkoiselta palvelimelta ja näyttää ne tyylitellyssä muodossa.
- **Osallistujat**: Kurssitiedot sisältävät kurssin nimen, osallistujien määrän, osallistujien nimet, alkamis- ja päättymispäivät sekä kurssin keston viikkoina.
- **Kuvaus**: Sivulla näytetään myös kurssiin liittyvä kuva.

## Käyttöohjeet

1. Avaa `index.html` tai `toteutus.html` selaimessasi.
2. Navigoi sivujen välillä käyttämällä sivuilla olevaa navigointipalkkia.

## Tiedostot

- **index.html**: Kotisivu, jossa haetaan ja näytetään JSON-datasta kurssitiedot ja osallistujat.
- **toteutus.html**: Sivusto, joka esittelee kurssitoteutuksen tiedot.
- **styles.css**: Tyylitiedosto, joka määrittää sivuston ulkoasun.
- **data.json**: JSON-tiedosto, joka sisältää kurssitiedot yms.
- **README.md**: Projektin kuvaus ja ohjeet.

## Käytetyt teknologiat

- **HTML**: Rakenne ja sisältö.
- **CSS**: Sivujen ulkoasun ja tyylin määrittely.
- **JavaScript**: JSON-tietojen haku ja dynaaminen sisällön lisäys.

## Lisätiedot

GitHub Pages palvelimen avulla haettu JSON-tiedosto sisältää kurssitiedot ja voit tarkastella sitä seuraavasta URL-osoitteesta:
[JSON-tiedosto](https://watisdiz.github.io/WebDevelopment/data.json)
