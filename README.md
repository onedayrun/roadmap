![1/cover.png](https://onedayrun.github.io/logo/1/cover.png)

# [roadmap.oneday.run](https://roadmap.oneday.run/#/)

## Tematyka

+ SEO
+ monitoring ładowania assets, tracking strony
+ optymalizacja strony
+ analityka


## Zadanie

sprawdzanie czasu i plików ładowanych
podawanie jakie pliki 

Dopasowane do przeglądarki
aby po załadowaniu jloads.js
sprawdzać co za pomocą niego jest ładowane


Analiza:

1. lista wszystkich URL zasianych w kodzie
2. Lista wszystkich url załadowanych dynamicznie do momentu upłynięcia 1 minuty.
3. Lista url z biblioteki webstream, analityka w ilu procentach korzysta strona z webstream



## Docelowo integracja z marketplace

+ Plugin do chmury
+ API do chmury
+ Dynamiczny Licznik stron, jakie są wykonane w webstream.


## Marketplace +  User +  Digital Assets 

+ Klient bez znajomości programowania
+ bez  nakładu czasu, od razu jest w stanie samodzielnie
+ coś zmienić na stronie
+ dodatkowo support może wesprzeć

USERS:
+ klient
+ programista

Klient wchodzi na projekt
klika co mu się podoba, to jest aktualziowane na nowy branch
projekt na git jest przeglądany przez programistę

łatwa zmiana na stronie to czego potrzebuje

programista rozwija kod źródłówy
a wygląd może być zmieniany przez asystenta lub bezpośrendio klienta
Chat głosowy lub tekstowy
Cobrowsing


## Aplikacja dla Usera - asystenta

Klient bezpośrednio na stronie chmury.
Kod źródłowy przez webpack bierze zmiany 
sprawdza zmiany na kodzie i sprawdza JS kod, linijkę
wyrzuca na stronie klienta.


## Webstream oparty o Engine

Streamowanie poprzez natywnce technologie live
Kod aktywnie działający i transkrybowany
Aby każdy kto pisze w innych technologiach, żeby mógł używać swój język, typescript, vue,
css, less, zamieniany i dodawany


Klient widzi dostaje JSON i widzi zrenderowan.
Dodawanie zmian do kodu na branchu projektu.



### Developer

USER API na marketplace
USER GIT API
USER PŁATNOŚĆ MARKETPLACE, sprzedaż pod subdomenami

domena marketplace: 
subdomeny generowane do:

Developerzy z podpiętym kontem 

Dla developerów jloads z demo projektami

Dla developerów modułów z domyślną wersją jloads
otwieranie plików JSON ze specyfikacji jloads

https://www.electronjs.org/


### Bazowanie na Electron

Skompilowanie chromium dla własnych potrzeb

1. Electron - chromium z włączoną developerska konsolą, śledzącą zmiany
2. każda zmiana jloads to refresh całej strony dynamicznie
3. Ładowanie offline plików z jloads


### Klient

multiplatformowe tracking klikniętych elementów

Analiza, tracking ruchu użytkownika, aby przeprowadzić analizę błędów

Cobrowse dla komunikacji aby możliwa współpraca z klientami

Wrzucać na git



## Pluginy do przeglądarki

żeby działało w przeglądarce:

1. Chrome, Chromium, Brave
2. Firefox


### plugin.dev
Log na Edge XMLHttpReqests
+ na wzór: fbevents.js / analytics.js
+ na początku bez logowania, potem możliwosć tworzenia ticketów z błedów

testowanie na każdej przeglądarce
dla programistów budujących sourcocode webestream

+ testowanie jloads, diagnostyka
+ na stronie opartej o jloads
+ do developowania, testowanie requestów, czasów ładowania, co nie działa i dlaczego


### plugin.module

+ na początku bez logowania, potem możliwosć tworzenia ticketów z błedów
+ licencjonowanie
+ wytwarzanie na marketplace
+ automatyczne dodawanie nowego repo
+ wystawianie ticketów
+ 
przeznaczony dla developerów, modułów, społecznosći webstream
dla sprzedawców na marketplace

+ do tworzenia
+ pobieranie zasobów 
+ reverse engeeniering do sprawdzania powiązań, zewnętrznych paczek
+ przeszukać wszystkie klasy elementów, dane, jakie pliki są powiązane i w jakim sensie
+ wyszukiwanie powiązań tagów, klas, ID: 
    + xpath handler
    + url resource

2 iframe:
+ lewa strona www źródłowa
+ prawa efekt końcowy z ładowaniem jloads



### webstream dla klienta
plartforma dla klientów działa niezależnie od providera

klient musi się zalogować:

+ szukanie modułów na marketplace 
+ wybór providerów:
    + hosting, vps
    + domain registrar, API
    + DNS
    + CDN
     
+ bazując na subskrypcji support na rok z góry
+ chat z kontaktem do opiekuna klienta
+ zlecanie i odbieranie nowych modułów pod klienta, konsultacje

Lista stron www korzystajacych z jloads
przeznaczony dla klientów używających webstream na swoich domenach internetowych 





## Sprzedaż

+ [pricing.oneday.run](https://pricing.oneday.run/#/)

Model subskrypcji ze zmienną w ilości świadczonych godzin supportu
możliwa przedpłata, wykupienie kilku godzin tygodniowo/miesięcznie/rocznie

Klienci i Partnerzy będą pozyskiwaniu przy indywidualnych rozmowach.
Wzrost będzie organiczny.
Pozyskiwanie partnerów będzie w naturalny sposób zwiększało nasz udział w rynku.
W ten sposób zbudujemy silną społeczność i usługa będzie miała warunki, by dojrzeć do aktualnych potrzeb klientów z branży.


### Do 100 klientów/użytkowników końcowych
Początkowy model biznesowy będzie przypominał software house tworzący oprogramowanie dedykowane w krótkoterminowych projektach.
Deficyt specjalistów będzie blokował rozwój.
Rentowność nie będzie wystarczająca, by uzyskać pełne pokrycie w personelu i model będzie odbiegał od docelowego.

Na początku dystrybucji tego systemu będzie mniej niż 100 użytkowników i mniej niż kilkaset używanych aplikacji oraz ich małej ilości dostępnych w marketplace aPaaS

Rozwiązaniem pozwalającym na rentowność będzie pośrednictwo w świadczeniu usług specjalistów 
i to będzie najbardziej dochodowa część, która będzie pozwalała na inwestycję w reklamę oraz pozyskiwanie bezpośrednio poprzez donate 
utalentowanych programistów tworzących ponadprzeciętne dedykowane rozwiązania


### Do 1 000 klientów/użytkowników końcowych
W skali 1 000 klientów osiągalna potencjalnie po kilkunastu miesiącach pozwoli na pokrycie kosztów kolejnych inwestycji 
i rentowność na bardzo dobrym poziomie, zatrudnieniu więcej ilości ekpsertów supportu na pół etatu, gdyż lepiej jest zatrudniać w godzinach szczytu stałych pracowników, pozwalających
na szybką reakcję, a mniejsze pokrycie poza godzinami pracy w obszrze europy.



### Do 10 000 klientów/użytkowników końcowych
Powiększajacac się ilość aplikacji i wielkosć infrastruktury pozwoli na większe możliwości ale i zagrożenia, dlatego będzie potrzebne wsparcie
ekspertów d/s bezpieczeństwa, doradzającym naszym partnerom w kestii głębszej integracji zapobiegającej przyszłym problemom.
To będzie również czas ekspansji na rynku globalne i pozyskiwanie ekspertów z krajów, gdzie praca jest mniej kosztowna


### Ponad 10 000 klientów/użytkowników końcowych
 
Czas na obronę pozycji na rynku, szybszą ekspansję i pozyskiwanie nowych rynków, partnerów, klientów z różnych kultur.
Zmniejszenie rentowności z uwagi na spore inwestycje.
Z drugiej strony pozyskiwanie inwestorów.
Core w Polsce/Europie pozostanie, jednak kolejne rynki będą już zdobywane w kooperacji.
Infrastruktura będzie bardziej narażona na cyber ataki, klienci będą bardizej zróżnciowanie, co przyczyni się do wdrożenia personalizowanej oferty poprzez użycie AI.



## O firmie Softreck
+ [Softreck - Leadership Through Software Development](https://softreck.pl/)
+ [culture.softreck.dev](https://culture.softreck.dev/#/)





---
+ [edit](https://github.com/onedayrun/roadmap/edit/main/README.md)

```
https://github.com/onedayrun/roadmap.git
```
