# Rytmipelin pisteiden kirjanpito

## Sovelluksen toiminnot
* Käyttäjä voi luoda tunnuksen ja kirjautumaan sisään sivustolle.
* Käyttäjä voi etsiä biisin biisi-tietokannasta, lisätä omat pisteensä.
* Käyttäjä voi asettaa pistetuloksen ohessa suoritukselle luokittelun, joka kertoo mitä asetusta he käyttivän suorituksen aikana
* Käyttäjä voi päivittää oman pistetuloksensa jo suorittamissaan biiseissä.
* Käyttäjä voi nähdä kaikkien pelaajien pistetulokset biisissä, ja voi järjestää ne suuremmasta pienempään, päinvastoin, tai filtteröidä asetuksen mukaan.
* Käyttäjä voi nähdä kaikki pistetulokset pelaajann profiilissa.
* Käyttäjä voi lisätä jokaiseen pistetulokseen (myös muiden käyttäjien) emoji-reaktion muutamasta vaihtoehdosta.

Pelaaja voi tehdä suoritusmerkinnän vain biisille, joka on oikeasti olemassa. Suoritusmerkintä on pääasiallinen tietokohde, emoji-reaktiot ovat toissijainen tietokohde, ja itse biisi-database on käyttäjälle näkymätön ja staattinen.

## Sovelluksen Asennus
Todo

## Pelin selitys, ja miten se liittyy sovellukseen.
Lyhyt kuvaus Beatmania IIDX -pelistä: Kyseessä on rytmipeli, jossa biisien hankaluustaso on skaalalla 1-12. Yhdellä biisillä on 3-4 eri vaikeustasoa, joita kutsutaan nimillä Easy, Normal, Hyper ja Another. Esimerkki biisistä voisi olla vaikka Biisinnimi(3, 6, 10), jossa Beginner on vaikeuskaalalla 3, Normal on 6, ja Hyper on 10. Ideana on, että pelaajat antavat pisteet yhdelle näistä saatavilla olevista suoritustavoista per suoritus. Toiminnoissa mainittiin "asetus" (ei mitään, sudden, lift, sud+lift). Tämä vaikuttaa siihen, miltä peli-alue näyttää suorituksen aikana. Ideana on, että pelaajilla on riitaa siitä, mikä asetus on paras. Siksi tietokannassamme kirjaamme mitä asetusta pelaaja käytti, jotta pelaajat saavat dataa siitä, mikä asetus on paras.
