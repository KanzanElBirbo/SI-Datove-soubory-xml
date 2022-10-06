# Filmy
Zde jsem vytvořil příklad databáze filmů ve formátu **xml** jako úkol pro pana učitele [Michala Bubílka](https://github.com/bubilem)


# Návod

- do databáze se dají přidávat jakékoliv filmy
- každý film má svoje unikátní identifikační číslo **id** 
> *&lt;movie id="1"&gt;*
- jméno je v kolonce **name** 
> *&lt;name&gt; "The Fast And The Furious" &lt;/name&gt;*
- žánr můžete zapsat do kolonky **genre** 
> *&lt;genre&gt; "Action" &lt;/genre&gt;*
- herci i s jejich charakteristikou se přidávají do kolonky **actor** 
> *&lt;actor  name="Vin Diesel"  gender="male"  CharacterName="Dominic Toretto"/&gt;*
- pro rok vydání slouží kolonka **ReleaseYear** 
> *&lt;ReleaseYear&gt; "2001" &lt;/ReleaseYear&gt;*
- poslední v databázi je kolonka **place**, která slouží k pojmenování oblasti, kde se film odehrává 
> *&lt;place&gt; "USA" &lt;/place&gt;*
