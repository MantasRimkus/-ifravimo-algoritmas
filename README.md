AES Šifravimo Sistema
Projekto aprašymas

Šis projektas yra žiniatinklio sistema, skirta tekstui šifruoti ir dešifruoti naudojant AES (Advanced Encryption Standard) algoritmą.

Funkcionalumas:
Teksto šifravimas naudojant AES algoritmą
Teksto dešifravimas naudojant tą patį slaptą raktą
Šifravimo modų pasirinkimas: ECB, CBC ir CFB
AES rakto ilgio pasirinkimas: 128, 192 ir 256 bitų
Slapto rakto įvedimas
Šifruotų duomenų išsaugojimas į .txt failą
Šifruotų duomenų nuskaitymas iš .txt failo
Patogi grafinė vartotojo sąsaja (GUI)

Naudotos technologijos:
HTML5 – vartotojo sąsajai
CSS3 – dizainui
JavaScript – funkcionalumui
CryptoJS – AES šifravimo įgyvendinimui

Projekto paleidimas:
1. Atsisiųskite projektą iš GitHub.
2. Atidarykite failą index.html bet kurioje naršyklėje.
3. Įveskite tekstą ir slaptą raktą.
4. Pasirinkite šifravimo modą ir rakto ilgį.
5. Paspauskite Šifruoti arba Dešifruoti.

AES algoritmo paaiškinimas:
AES (Advanced Encryption Standard) yra simetrinis šifravimo algoritmas, naudojamas saugiam duomenų apsaugai. Tas pats slaptas raktas naudojamas tiek šifravimui, tiek dešifravimui. AES yra vienas saugiausių ir plačiausiai naudojamų šifravimo standartų pasaulyje.

Šifravimo modai:
ECB (Electronic Codebook) – paprasčiausias režimas, tačiau mažiausiai saugus, nes vienodi duomenų blokai šifruojami vienodai.
CBC (Cipher Block Chaining) – naudoja inicijavimo vektorių (IV), kuris padidina saugumą susiejant duomenų blokus.
CFB (Cipher Feedback) – veikia kaip srautinio šifravimo režimas ir leidžia šifruoti duomenis dalimis.
Rakto ilgiai
AES-128 – greitas ir saugus.
AES-192 – didesnis saugumo lygis.
AES-256 – aukščiausias saugumo lygis.

Kuo ilgesnis raktas, tuo sunkiau jį nulaužti naudojant brutalią jėgą.

Projekto struktūra:
index.html – pagrindinis programos failas
README.md – projekto aprašymas
