# Távolságibusz adatbázis - specifikáció

## Feladat formális leírása
A feladat célja egy távolságibusz társaság üzemeltetése. Az adatbázisban tárolva vannak az utasok, akik igénybe veszik a szolgáltatást, illetve az elérhető útvonalak listája. 
## Elérhető funkciók
* Járatok kezelése:
    * Járat törlése
    * Új járat létrehozása
    * Járat adatainak módosítása
    * Járatok közötti keresés
* Utasok kezelése:
	* Utas törlése
    * Új utas hozzáadása
    * Utas adatainak módosítása
    * Meglévő utasok között keresés
* Jegyvásárlás kezelése:
    * Csak olyan járatra lehet jegyet venni, ami létezik
    * Vásárolt jegy törlése
## Adatbázis séma
Adatbázisban tárolt attribútumok és entitások:
* Járat: indulási idő, érkezési idő, kiindulási város, érkezési város, ár
* Személy: név, születési dátum
* Jegy vásárlás: Személy, Járat

![image](https://user-images.githubusercontent.com/126917864/236701141-bbcab98b-3958-4656-8927-ad65aeb1e626.png)
