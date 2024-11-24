# Oppimispäiväkirja: Paikallinen git

__Mikä osion tehtävissä oli vaikeaa ja mikä helppoa? Mikä auttoi minua oppimaan? Miten selvitin esteet?__
Helppoa oli se, että olin jo pakostakin ehtinyt käyttämään gitiä kursseilla, joten se ei ollut täysin uusi juttu. Ohjelmistoprojekti1-kurssin aikana on ollut pakko tulla tutuksi Gitin kanssa. Vaikeaa on ollut se, että aloitin tämän kurssin jo ajat sitten, enkä yhtään muista, mitä olen tehnyt tuolloin.
Kuitenkin tuli vastaan monia uusiakin ominaisuuksia ja asioita. 

Hello-tehtävien kanssa ei erityisemmin esiintynyt ongelmia. Ehkä vaikein on tässä vaiheessa se, että komentoja on vaikea muistaa, mutta nehän voi aina tarpeen tullen tarkistaa.

Haarojen kanssa tajusin, että master olisi varmaan pitänyt vaihtaa suositelluksi mainiksi ja sitä yritinkin, mutta en jostain syystä onnistunut ja annoin lopulta olla, kun tehtävissäkin käytettiin masteria.

Hieman myös mietin, että mitä eroa mahtaa olla checkoutilla ja switchillä, mutta toisaalta väliäkö tuolla - käytän varmaankin itse mieluummin switchiä, koska sitä näyttää materiaaleissa olevan enemmän ja on myös selkeämpi/helpompi muistaa. Ilmeisesti kuitenkin checkout tekee saman asian, koska yhdessä kohdassa haaraan vaihdettiin ko. komennolla.


## Osiossa käyttämäni Git-komennot

| Komento | Kuvaus |
| --------| ------ |
| git config –-global user.name  | Nimen konfigurointi |
| git config –-global user.email | Sähköpostiosoitteen konfigurointi |
| git init | Uuden paikallisen repositorion luonti |
| git clone | Repositorion kopiointi omalle koneelle paikalliseksi repositorioksi |
| git status | Muutosten tilan tarkistus (hyvä käyttää vähän joka välissä) |
| git add "tiedosto" | Yksittäisen tiedoston muutosten lisäys |
| git add . | Kaikkien tehtyjen muutosten lisäys |
| git commit -m "viesti" | Commit eli "tallennus" |
| git log | Tehtyjen muutosten loki |
| git log --stat | Tehtyjen muutosten loki, jossa kerrotaan tarkemmin muutoksista |
| git reset "tiedosto" | add-komennon peruminen yksittäisen tiedoston osalta |
| git checkout "tiedoston lokitunniste (7 ensimmäistä merkkiä)" | edellisen commitin tilanteeseen palaaminen |
| git reset --hard| Kaikkien tiedostojen kaikkien muutosten peruutus edellisen commitin tilaan |
| git revert "tiedoston lokitunniste (7 ensimmäistä merkkiä)"| Kokonaisen commitin peruutus (jää historiaan) |
| git switch –c "haaran nimi"| Uuden haaran luominen ja siihen vaihtaminen |
| git switch "haaran nimi"| Toiseen haaraan vaihtaminen |
| git merge "haaran nimi"| yhdistäminen |