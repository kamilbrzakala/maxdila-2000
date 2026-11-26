# Changelog

## 1.5.0 – 2026-11-26
- Autozapis stanu gry w przeglądarce (localStorage) po każdym ruchu.
- Po odświeżeniu lub zamknięciu karty na ekranie startowym jest przycisk „Kontynuuj (dzień X)” obok „Nowa gra”.
- Zapis znika po zakończeniu gry; „Nowa gra” nadpisuje go świeżym stanem.

## 1.4.1 – 2026-11-26
- Limit pożyczki u Zdzisia też rośnie z prestiżem (1500/1000 + prestiż × 120), tak jak limit banku.

## 1.4.0 – 2026-11-25
- Dług rozdzielony na dwie pozycje: **Zdzisio** (lichwiarz) i **bank**.
- Zdzisio: pierwsza pożyczka 10%/dzień, druga 20% i ostatnia. Po pełnej spłacie licznik się zeruje i znów można wziąć 2 razy. Maksymalnie 2 pożyczki naraz — na wypadek gdy ktoś cię obrobi.
- Bank: osobna pożyczka 5%/dzień, limit zależny od prestiżu, jak wcześniej.
- Oba długi rosną co dzień. Wynik końcowy odejmuje oba.

## 1.3.0 – 2026-11-25
- Ucieczka to jedna akcja: albo czysta ucieczka (szansa w oknie), albo jeden atak na ciebie (strzały / kamienie) i uciekasz poraniony – bez kolejnych rund.
- Broń przy ucieczce: +15% szansy, ostrzeliwujesz się (zużywa amunicję), strzela/rzuca w ciebie tylko połowa napastników.
- Automatyczne tagi i GitHub Releases (workflow `.github/workflows/release.yml`) – każda wersja do pobrania w zakładce Releases.

## 1.2.0 – 2026-11-25
- Ucieczka: szansa zawsze 20–90% i jest pokazana w oknie ataku. Każda nieudana próba zwiększa szansę na następną (+10%, goniący się męczą). Trafienie w nogę obniża ją o 10% (maks. −20%).
- Złapany przez policję: pałki, konfiskata towaru i grzywna, potem koniec akcji (bez pętli bicia).
- Złapany przez dresiarzy: lanie, potem 50% szans, że zabiorą kasę/towar i odejdą.
- Po udanej ucieczce strzelają/rzucają za tobą tylko czasem (policja 50%, dresiarze 60%).
- Ostrzeżenie przy kondycji poniżej 30%.
- Numer wersji w tytule okna i w „O grze”.

## 1.1.0 – 2026-11-25
- Pełnoekranowy układ na telefony (pion 320–412 px) i osobny układ dla telefonu w poziomie.

## 1.0.0 – 2026-11-24
- Pierwsza wersja remake'u MaxDila 2000.
