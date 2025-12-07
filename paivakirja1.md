# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__

Gitin perustoiminnot (esim. clone, add, commit, push) ovat tulleet opintojen aika jo entuudestaan tutuiksi ja niiden käyttäminen onkin tavallaan luontevaa, joskin add-commit-push kolmikko on kulkenut käsi kädessä. Harjoitus 2 oli siten siis jo uutta, että tässä vaiheessa toimittiin vielä paikallisesti.

Harjoitus 3:n peruuttelut olivat uusia, ja ensisilmäyksellä vaikuttivat jokseenkin sekavilta. Tehtävien kautta kuitenkin Git-hallinnan ja versionhallinnan ero selkeni lisää, mikä auttoi myös ymmärtämään eri peruutus-komentojen eroja.

## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git init | Luo tyhjän repositorion nykyiseen kansioon. |
| git status | Näyttää työhakemistossa olevien tiedostojen Git-tilan. |
| git add | Lisää tiedoston Git-hallintaan ja tallennettavaksi versionhallintaan. |
| git commit | Tallentaa lisätyt tiedostot versionhallintaan. |
| git mv | Siirtää tai uudelleennimeää tiedoston. |
| git rm | Poistaa tiedoston sekä työhakemistosta että Git-hallinnasta. |
| git log | Näyttää versionhallintaan tallennusten historian. |
| git checkout | Vaihtaa aikaisempaan tallennukseen tai haaraan. |
| git clone | Kopioi olemassa olevan Git-repositorion paikalliseen koneeseen. |
| git switch | Vaihtaa haaraa. pelkkä viiva (-) switchin perässä palauttaa edelliseen haaraan.  |
| git reset | Poistaa tiedoston Git-hallinnasta. |
| git restore | Palauttaa Git-hallinnassa olevan tiedoston viimeisimpään versionhallinnan versioon. |
| git revert | Kumoaa valitun versionhallintatallenteen tallenteen. |
| git branch | Luo uuden kehityshaaran. |
| git merge | Yhdistää kehityshaaran toiseen |