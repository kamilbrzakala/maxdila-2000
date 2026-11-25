# MaxDila 2000 – remake

Przeglądarkowy remake polskiej gry tekstowo-handlowej **MaxDila v1.0** (oryginał: (C) All41, 2000) – klon w stylu Dope Wars.

Aktualna wersja: **1.3.0** – zmiany w [CHANGELOG.md](CHANGELOG.md).

Cała gra to jeden plik `index.html` (HTML + CSS + JS, bez zależności). Otwórz go w przeglądarce albo włącz GitHub Pages.

## Mechanika
- 6 miast (Katowice, Tychy, Oświęcim, Murcki, Zabrze, Gliwice); każdy przejazd to nowy dzień
- 10 towarów z cenami zależnymi od miasta, dnia i losowych wydarzeń rynkowych
- Dług rośnie 5% dziennie, depozyt 1%; finanse: depozyt, pobranie, spłata, pożyczka
- Napady: doliniarze, osiedlowy gang, nalot policji – Uciekam / Stoję / Bronię się
- Trafienia losowane w części ciała (noga, tyłek, plecy, ręka, brzuch, głowa) z różnymi obrażeniami
- Sklep (kurtka, torba, aktówka, Fiat 126p, gnat, kałach, granat, shurikan…), szpital, gang z dniówką i morale
- Wykres cen (36–360 dni), tabela najlepszych wyników w localStorage

## Wersje
Numer wersji jest w `index.html` (`const VERSION`). Po każdym pushu na `main` GitHub Action tworzy tag `vX.Y.Z` i Release z plikiem gry – poprzednie wersje są do pobrania w zakładce **Releases**.
