# BiteBook
- Käyttäjä pystyy luomaan tunnuksen ja kirjautumaan sisään sovellukseen
- Käyttäjä pystyy lisäämään, muokkaamaan ja poistamaan ravintoloita
- Käyttäjä pystyy näkee sovellukseen lisätyt ravintolat
- Käyttäjä pystyy hakemaan ravintoloita nimellä
- Käyttäjä pystyy merkkaamaan missä ravintoloissa käynyt
- Käyttäjäsivu näyttää montako ravintolaa käyttäjä on lisännyt ja monessa ravintolassa hän on käynyt
- Käyttäjä pystyy luokittelemaan ravintolan (esim. pizzeria, bistro, nepalilainen, aasialainen)
- Käyttäjä voi arvioida ravintolan ja kommentoida ravintolaa, ravintolasta näytetään komentit ja keskimääräinen arvio

# 2 välipalautus
- Käyttäjän luominen ja sisäänkijrautuminen on mahdollista
- Ravintolan lisääminen, poistaminen ja muokkaus on mahdollista
- Arvostelun lisääminen ja poistaminen on mahdollista
- Sovellukseen lisättyjen ravintoloiden tarkastelu on mahdollista
- Ravintoloiden haku ravintolan nimien tai nimen osien perusteella mahdollista
  
# Asennusohjeet
Aluksi luo tiedosto database.db tiedoston schema.sql perusteella
<pre>$ sqlite3 database.db < schema.sql </pre>
Luo seuraavaksi virtuaaliympäristö komennolla
<pre>$ python3 -m venv venv</pre>
Siirry tämän jälkeen virtuaaliympäristöön komennolla
<pre>$ source venv/bin/activate</pre>
Seuraavaksi asenna flask-kirjasto
<pre>$ pip install flask</pre>
Tämän jälkeen voit käynnistää sovelluksen komennolla
<pre>$ flask run</pre>
