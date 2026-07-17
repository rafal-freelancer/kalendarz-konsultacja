# Podgląd strony — Remedy Warsaw (do pokazania klientce)

Strona jest gotowa do opublikowania jako **wstępny podgląd**. Kilka rzeczy to dane przykładowe — podmień je przed wersją finalną.

## Co jest PRZYKŁADOWE / do potwierdzenia z Remedy

- **Ceny pakietów** (Komfort 1 490 zł · Lato 2 990 zł · Pełny 3 990 zł) oraz kwoty „pojedynczo" i „oszczędzasz" — to przykłady pod mechanizm anchoringu. Podmień na realny cennik Remedy (mechanika porównania zostaje, tylko liczby).
- **Opinie** (Aleksandra K., Marta W., Joanna R.) — przykładowe. Wstaw prawdziwe (za zgodą, inicjały nazwiska).
- **Kontakt:** telefon `+48 500 000 000`, e-mail `kontakt@remedy.pl` — placeholdery. Adres `Grochowska 75, Praga-Południe` — potwierdź. Podmień Instagram (`#`).
- **Pasek zaufania / USP** (kameralność, stała specjalistka, laser medyczny, stała cena) — wynikają z Twojej strategii; potwierdź, że wszystko zgadza się z Remedy.
- **Godziny w kalendarzu** (pon–sob, 10–18) — ustaw realne godziny Remedy w `CONFIG` (na dole pliku).

## Żeby rezerwacja realnie wysyłała (opcjonalne na etapie podglądu)

W `CONFIG` wpisz `formspreeEndpoint` (formspree.io → New Form). Wtedy: Remedy dostaje maila ze zgłoszeniem, klientka — auto-potwierdzenie. Bez tego kalendarz działa w trybie demo (pokazuje ekran sukcesu, nic nie wysyła) — na podgląd to wystarczy.

## Zdjęcia (opcjonalne)

Na dole w `CONFIG.media` możesz wgrać: `portret` (specjalistka — najmocniejsze zaufanie) i `galeria` (wnętrze). Puste = sloty się chowają, strona wygląda dobrze bez nich. Zdjęcia dostają jednolity filtr pod paletę.

## MDR / zgodność (pilnuj przy każdej podmianie)

Bez nazw/modeli urządzeń, bez zdjęć „przed/po", bez obietnic trwałości efektu.

## Publikacja (GitHub Pages)

Osobne repo (np. `remedy-laser`) → `index.html` do roota → Settings → Pages → Source `main` / `/root`. Podgląd pojawi się pod `https://twoj-login.github.io/remedy-laser/`. Domena własna: Settings → Pages → Custom domain.

## Kolejność sekcji (zgodna z Twoją strategią)

hero (efekt + 3 kroki + 2 CTA) → pasek USP → lustro problemu → dlaczego Remedy → **dlaczego laser medyczny** → czym jest konsultacja → proces → **pakiety z porównaniem wartości** → bezpieczeństwo → opinie → **kalendarz** → FAQ → domknięcie. Kalendarz świadomie nisko — najpierw wartość, potem rezerwacja. CTA w całej stronie przewijają do kalendarza.
