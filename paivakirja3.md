# Oppimispäiväkirja: Git projektissa

__Mitä hyötyä voisi olla versionhallinnasta, jos kehität projektia yksin?__

Yksinkin kehittäessä versionhallinta tuo muunmuassa seuraavia hyötyjä:

1. **Muutosten seuranta.** Näen tarkasti, mitä tiedostoihin on muutettu ja milloin.
2. **Palautusmahdollisuus.** Voin helposti palauttaa aiempaan versioon, esimerkiksi jonkin mennessä pieleen.
3. **Turvallinen testailla.** Voin luoda uusia haaroja, joissa testata uusia ominaisuuksia ilman, että pääversio hajoaa.
4. **Dokumentointi.** Jokainen tallennus versionhallintaan toimii muistiinpanona siitä, mitä on tehty ja miksi. Tärkeää siis kommentoida tallennuksia viisaasti!
5. **Varmuuskopiointi.** Etärepositorio (esimerkiksi GitHub) toimii varmuuskopiona, joten työni ei katoa laitteistovian tai oman toheloinnin seurauksena.

__Mitä hyötyä voisi olla versionhallinnasta, jos projektissa on useita kehittäjiä?__

Useiden kehittäjien projekteissa versionhallinnasta on esimerkiksi seuraavia hyötyjä:
1. **Yhteistyö ja koordinointi.** Kaikki näkevät toistensa tekemät muutokset, eikä samaa tiedostoa rikota vahingossa.
2. **Muutoshistoria.** Voidaan tarkistaa, kuka teki mitä ja miksi — tärkeää virheiden selvittämisessä ja vastuullisuudessa.
3. **Kehityshaarojen käyttö.** Kehittäjät voivat työskennellä omilla ominaisuushaaroilla ilman, että pääversio rikkoutuu.
4. **Yhdistäminen ja konfliktien hallinta.** Git auttaa yhdistämään eri kehittäjien muutokset ja näyttää mahdolliset ristiriidat.
5. **Palautusmahdollisuus.** Virheelliset muutokset voidaan helposti kumota tai palauttaa aiempi vakaampi versio.
6. **Dokumentointi ja jäljitettävyys.** Commit-viestit ja pull requestit dokumentoivat muutokset ja päätökset.

__Miten järjestäisit projektitiimin versionhallinnan 3-4 hengen ohjelmistoprojektikurssilla? Laadi tiimiläisille lyhyt ohje, miten projektissa toimitaan.__

Määrittelisin selkeät roolit haarojen käytölle: master- tai main-haara sisältää vain testatut ja valmiit versiot, develop-haara toimii tiimin pääkehityshaarana, ja jokainen tiimin jäsen luo oman ominaisuushaaran uusille muutoksille. Kaikki muutokset dokumentoidaan selkeillä commit-viesteillä, ja ominaisuushaarasta tehdään pull request develop- tai master-haaraan, jonka muut tiimin jäsenet tarkistavat ennen yhdistämistä. Tiimin jäsenet päivittävät säännöllisesti paikallisen repositorionsa etärepositoriosta, jotta konfliktit vähenevät, ja mahdolliset ristiriidat ratkaistaan yhdessä. Kaikki haarat pusketaan etärepositioon, jolloin työ tallentuu ja on muiden nähtävillä, ja pull requestit toimivat samalla dokumentaationa tehdystä työstä.

__Kommenttini opintojaksosta, esim. sisällöstä, materiaalista, työmäärästä, hyödyllisyydestä, työmäärästä. Mitä toivoisit olevan enemmän, mitä vähemmän?__

Opintojakson työmäärä oli mielestäni sopiva, ja materiaalit olivat erittäin kattavat. Aloitin toteutuksen työskentelyn erittäin myöhään, mutta työmäärä ei tuntunut liian kiireiseltä, eikä ollut tarvetta “hosua”. Koin opintojakson sisällön erittäin hyödylliseksi, sillä versionhallintaan ei juurikaan keskitytä muilla kursseilla, vaikka se on tärkeä taito oikeiden projektien työskentelyssä. Toteutuksen projekti antoi konkreettisen kontekstin ja merkityksen jo ihan perustoiminnoillekin.