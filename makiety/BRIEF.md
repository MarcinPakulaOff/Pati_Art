# Brief — makiety strony „skart” (portfolio malarki)

## Klientka
Patrycja („Pati”), maluje ręcznie na płótnie: **obrazy strukturalne** (gruba farba, szpachla, relief) oraz zwykłe obrazy malowane pędzlem (m.in. pejzaże górskie). Chce stronę, która **pokazuje sztukę**. Sklep NIE teraz. Formularz kontaktowy „kiedyś” — w makiecie może być, ale tylko wizualnie.
Ogląda na **iPhonie (Safari)** — to jest główny ekran testowy (390×844). Wcześniejsze makiety nie działały jej na telefonie, więc mobile ma być dopieszczone.

## Marka
- Nazwa: **skart**. Logo jak we wzorze: małe „sk” pismem odręcznym (kaligrafia) nad/obok dużego „ART” antykwą (np. „sk” w Pinyon Script / Great Vibes, „ART” w Cormorant Garamond / Marcellus). Można też zapisać jednym słowem „skart”, ale kaligraficzne „sk” to podpis marki.
- Motto (ze wzoru): „Nie każda historia wymaga słów. Niektóre znajdują swój wyraz w sztuce.”
- Klimat ze wzoru: beż, krem, ciepły brąz, czerń; miękkie światło z okna; pociągnięcia pędzla. Elegancko, spokojnie, „drogo”.
- **Bez zdjęcia kobiety w hero.** Hero = logo + motto (ewentualnie tło: faktura/światło), albo prawie nic.

## Menu — TYLKO 4 pozycje
`O mnie` · `Galeria` · `Proces twórczy` · `Kontakt`
(Strona jednostronicowa z kotwicami jest OK. Na telefonie: hamburger albo przewijane menu — musi być łatwe kciukiem.)

## Treści (po polsku, prawdziwe zdania, bez lorem ipsum)
- **O mnie** (propozycja): „Maluję obrazy, które chce się dotknąć. Pracuję szpachlą i pędzlem, warstwa po warstwie, aż farba zacznie rzucać własny cień. Tworzę obrazy strukturalne i klasyczne płótna — pejzaże, abstrakcje, światło. Każdy powstaje ręcznie, w jednym egzemplarzu.” Podpis: „— Patrycja”.
- **Galeria** — 12 prac. Każda: tytuł, technika, wymiar, rok. Użyj tych danych (wymyślone, ale wiarygodne):
  | plik | tytuł | technika | wymiar | rok |
  |---|---|---|---|---|
  | praca-01.jpg | Szum | akryl, pasta strukturalna, płótno | 80×80 cm | 2025 |
  | praca-02.jpg | Szron | akryl, szpachla, płótno | 60×80 cm | 2025 |
  | praca-03.jpg | Zapiski | olej, płótno | 50×70 cm | 2024 |
  | praca-04.jpg | Len | pasta strukturalna, akryl | 60×90 cm | 2025 |
  | praca-05.jpg | Krata | technika mieszana | 70×100 cm | 2024 |
  | praca-06.jpg | Odwilż | akryl, szpachla | 100×80 cm | 2025 |
  | praca-07.jpg | Brzeg | akryl, pasta strukturalna | 120×80 cm | 2025 |
  | praca-09.jpg | Jesień w glinie | olej, szpachla | 80×60 cm | 2024 |
  | praca-10.jpg | Ochra | olej, szpachla | 80×60 cm | 2024 |
  | praca-11.jpg | Pastel | pasta strukturalna, akryl | 40×60 cm | 2025 |
  | praca-13.jpg | Biel | gips akrylowy, relief | 50×90 cm | 2025 |
  | praca-14.jpg | Żar | olej, szpachla | 90×60 cm | 2024 |
  | gory-01.jpg | Jezioro pod szczytem | olej, płótno | 100×70 cm | 2023 |
  | gory-02.jpg | Dolina | olej, płótno | 100×70 cm | 2023 |
  Kategorie do filtra (jeśli koncepcja ma filtr): „Strukturalne” (wszystkie praca-*), „Malowane” (gory-*, praca-03).
- **Proces twórczy** — prawdziwa sekwencja (numeracja ma sens):
  1. Płótno — „Zaczynam od czystego płótna i szkicu w głowie, rzadko na papierze.” (proces-01-plotno.jpg)
  2. Narzędzia — „Szpachle, pędzle, pasta strukturalna. Każde narzędzie zostawia inny ślad.” (proces-02-szpachle.jpg)
  3. Warstwy — „Nakładam farbę grubo, warstwa po warstwie. Część musi schnąć kilka dni.” (proces-03-farba.jpg)
  4. Światło — „Na końcu sprawdzam obraz w bocznym świetle — dopiero wtedy widać fakturę.” (proces-04-sztaluga.jpg lub proces-05-pracownia.jpg)
- **Kontakt**: „Chcesz zapytać o obraz albo zamówić pracę na wymiar? Napisz.” E-mail: `kontakt@skart.pl` (przykładowy, pokazany jako tekst do zaznaczenia), Instagram: `@skart.art` (przykładowy). Formularz: imię, e-mail, wiadomość, przycisk „Wyślij”. Po kliknięciu: `preventDefault()` i komunikat w stronie „To makieta — formularz zacznie działać na prawdziwej stronie.” Żadnych `alert()`.
- Stopka: „© 2026 skart · Wszystkie obrazy malowane ręcznie” + mała linia „Zdjęcia w makiecie: Unsplash (zastępcze)”.

## Zdjęcia — `img/` (względnie od pliku HTML: `img/nazwa.jpg`)
- Prace: praca-01..14 (bez 08, 12), gory-01, gory-02
- Tła/faktury: tlo-fala-01..04 (beżowe reliefy w fale), tlo-swiatlo.jpg (światło z okna na ścianie, pion), tlo-piasek.jpg (pion)
- Proces: proces-01-plotno, proces-02-szpachle, proces-03-farba, proces-04-sztaluga (pion), proces-05-pracownia, proces-paleta (pion), proces-pedzle (pion)
- Wnętrza (skala obrazu na ścianie): wnetrze-01 (pion, biały relief na półce), wnetrze-02 (beżowy salon), wnetrze-03 (pion, dwa obrazy), wnetrze-04 (sypialnia)
Wszystkie ~1400 px, 100–250 KB. Używaj `loading="lazy"` poza hero, zawsze `alt` po polsku.

## Twarde wymagania techniczne
1. Jeden samodzielny plik HTML na koncepcję, zaczyna się od `<!doctype html>`, `<meta charset="utf-8">`, `<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">`, własny `<title>` i `<style>`. CSS i JS inline.
2. Czcionki wyłącznie z Google Fonts (`fonts.googleapis.com`) z porządnym fallbackiem. Skrypty zewnętrzne wyłącznie z `cdnjs.cloudflare.com` z przypiętą wersją (np. three.js r128: `https://cdnjs.cloudflare.com/ajax/libs/three.js/r128/three.min.js`). Nic innego z zewnątrz (żadnych obrazków z sieci, żadnych iframe).
3. **iPhone Safari**: działa na 390 px szerokości, brak poziomego przewijania strony, boczny margines `max(16px, env(safe-area-inset-left))`, przyciski min. 44 px, `100svh`/`100dvh` zamiast `100vh` tam, gdzie wysokość ekranu. Bez `alert/confirm/prompt`, bez `window.open`, bez `<a download>`, bez `mailto:` jako jedynego sposobu (pokaż adres jako tekst).
4. Strona jest **jednym motywem jasnym** (świadomie) — ustaw `color-scheme: light`, jawne tło na `body`, kolory jako tokeny w `:root`.
5. `prefers-reduced-motion` respektowane. Widoczny focus klawiatury.
6. Galeria: kliknięcie pracy otwiera podgląd (lightbox) z tytułem/techniką/wymiarem; zamykanie X, tłem i klawiszem Esc; na telefonie przesuwanie palcem albo strzałki.
7. Wszystko widoczne bez czekania na animację (żadnych sekcji na `opacity:0` czekających na scroll — animacja może startować z widocznego stanu).
8. Na górze pliku krótki komentarz HTML: nazwa koncepcji i jej idea w 1–2 zdaniach.
9. Każda makieta ma w rogu dyskretny link „← Wszystkie koncepcje” do `index.html`.

## Czego unikać
Krzykliwych kolorów, gradientów fiolet-niebieski, emoji, kart z cieniem wszędzie, wszystkiego wycentrowanego, generycznego wyglądu „szablonu”. Obraz jest bohaterem — interfejs cichy.
