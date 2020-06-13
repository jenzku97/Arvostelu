GIT+Github yksilötehtävä: ryhmätyö reflektointi 7.10. mennessä. 10 pistettä
Tee Markdown muodossa henkilökohtaiseen repositoryyn tiivis ja ytimekäs dokumentti.
1.	Yhteenveto siitä, mitä olet tehnyt ryhmätyössä.
2.	Tärkeimmät asiat jotka olet oppinut
3.	Omat tunnelmat ryhmässä toimimisen suhteen, hyvät ja haasteelliset 
Ei sanamäärärajoituksia.

Tämän minä tein eli asensin koneelle gitin ja bracketsin! ja bracketsiin asensin markdown prewier ohjelman
Tein gitin kautta githubiin toolchain kuvauksia yritykselle, jotka suunnittelin työkaluketjuista ja käytin IDE integrated development environmet CI ratkaisuun asti. Sekä perustelin lyhyesti ja tein ratkaisun. 


Tärkeimmät asiat jotka opin olivat bracketsin asennus, git bash asennus, laajennuksen hallinnasta markdown preview asennus ensin githubissa loin kansion joko public julkiseksi tai private yksityiseksi, joka tulee automaattisesti omalle tietokoneelle näkyviin. Kansioon pääsin painamalla lipun kuvaa + e näppäintä ja sitten painoin paikallinen levy C  ja sitten käyttäjät ja sieltä valitsin Jenna. Sieltä löysin kansion, jonka loin sinne. 

Gitissä luodaan kansio painamalla new -> repository kohtaan kirjoitetaan kansion nimi. Siten jos haluat, että kansio o julkinen paina public. Jos haluat, että kansio on salainen paina silloin private. Tämän jälkeen paina create repository. Näin olet luonut githubissa kansion

Sitten menin gittiin ja kirjoitin cd ja kansion nimen jonka loit githubissa esim cd testi
Sitten kirjoitin ls cd .. sitten kirjoitin git clone ja kopion githubissa linkki: https://github.com/ ssh vierestä koodin ja liitin se gittiin git clonen viereen. Sitten painoin git status ja katsoin missä tilassa olin. Sitten kirjoitin cd kansion nimi esim cd testi. Sitten menin bracketsiin ja aloin kirjoittamaan tekstiä. Painoin näytä -> markdown prewier. Sitten painoin tiedosto -> uusi ja sitten menin paikallinen levy c -> käyttäjät -> jenna -> etsin kansion jonka tein esim testi. Testi kansioon tallensin sen md muodoss testi.md tai new.md voit antaa sille ihan minkä nimen haluat md muodossa. Sitten lopuksi tallenna. Sitten menin takaisin gittiin ja kirjoitin sinne git add tiedoston nimi testi.md. Sitten katoin missä tilassa olin kirjoittamalla git status. Sitten kirjoitin kommentin git commit -m "hauskaa" 

Sitten sen jälkeen kirjoitin gittiin git push ja tämän jälkeen githubiin tuli näkyviin testi.md tiedosto kohtaan kommentti kommentoi
Sitten kun kaikki on kunnossa eikä tarvitse enää kloonata niin silloin menin bracketsiin ja avasin uudestaan testi.md
Painoin näytä -> markdown prewier ja aloin kirjoittamaan bracketsissä testi.md tiedoston kohtaan esim hauskaa. Sitten mene gittiin ja gittiin kirjoita kansion nimi cd testi. Sitten lisää tiedosto git add testi.md ja sitten kirjoita kommentti git commit -m "viesti" Tämän jälkeen kirjoita git fetch, git rebase ja lopuksi git push. Tämän jälkeen teksti näkyy githubissa!.
Sitten opin koodit joilla voi korjata errorit esim git rebase origin/mastee. Tämä koodi näyttää virheen. Jos alkaa keljuttaa ja git rebasen jälkeen tulee error niin opin lisämään perään git push --force joka lisää tiedoston onnistuneesti. git fetch origin/ ja tämän jälkeen rebase joka hakee olemassa olevaa tiedostoa! git rebase -- continue joka ongelmatilanteessa jatkaa muutoksen lisäämistä!
status kohdassa tiedetään missä tilassa ollaan ja git log kohdassa tiedän kuka on tehnyt ja gitin historian
Sitten opin luomaan ssh avaimen kirjoittamalla gittiin clip ~/.ssh/id_rsa.pub ja painoin enter ja tämän koodin kopion ja en kopionut commant not found! ja koopin liitin githubiin. Githubissa ensin painoin omasta profiilistani ja settings kohtaan ja sieltä valitsin ssh and gps key ja liitin koodin key kohtaan ja tallensin painamalla create new GPG Key. Lopuksi loin oman nimen ja sähköpostiosoitteen gittiin! gitissä kirjoitin git config --global user.name "Jenna" ja painoin enter! sitten kirjoitin oman sähköpostiosoitteen gitissä kirjoittamalla git congif --global user.email "jenna.gronvall2@edu.lapinamk.fi.

Ryhmätyössä oli kiva olla ja ryhmtyön suhteet olivat hyvät. Haasteelliset asiat olivat, että gitin käyttäminen oli vaikeaaa, koska ensin opin luomaan kansion git init komennolla ja meni repository tilaan eikä löytänyt kansiota. Näin ei ole ennen tapahtunut niin käytin git init kansiota. Sitten kun jätti pois git init komennon niin ei tämän jälkeen ollut enään hankalaa ja kaikki onnistui!
