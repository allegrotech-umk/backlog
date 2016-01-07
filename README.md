Wildsnake startup product backlog
===================================

**SNAKE-1** | 
Jako internauta chcę wiedzieć, że startup "Wildsnake" istnieje i wystartuje w określonym terminie, bo chcę zniecierpliwiony czekać na możliwość zakupu węży.

Warunki satysfakcji:
 - startup jest dostępny w internecie,
 - widoczny jest tekst informujący o dacie otwarcia,
 - widok zgodny z dostarczną makietą.

**SNAKE-2** | 
Jako internauta chcę wiedzieć, jaki asortyment będzie oferował sklep wildsnake, kiedy będzie dostępny.

Warunki satysfakcji:
 - widoczna jest lista oferowanych produktów w formie graficznej
 - asortyment jest konfigurowalny osobno dla środowisk dev/prod
 - asortyment można modyfikować bez wdrażania aplikacji

**SNAKE-3** | Jako internauta chciałbym, aby każdy produkt miał swoją cenę widoczną dla mnie.

**SNAKE-4** | Jako internauta chciałbym, aby produkt miał zdjęcie.

**SNAKE-5** | Jako internauta chciałbym aby listing produktów był zgodny z makietą (images/listing.png).

**SNAKE-6** | Jako developer chciałbym rozdzielić projekt wildsnake na dwa projekty 
- github.com/allegrotech-umk/wildsnake-api (api zwracające produkty, tylko java, żadnych html'i oraz js'ów)
- github.com/allegrotech-umk/wildsnake-front (warstwa prezentacji, czysty html + js)
Taki podział pozwoli rozdzielić warstwę widoku od danych i tym samym uchroni mnie przed tworzeniem monolitu.
