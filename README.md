# Adela Hopek

Wizytówka dla rekruterów: Quality Assurance Engineer / Business Analyst. Strona jest statyczna (HTML, CSS i JavaScript), po polsku i po angielsku.

Adres na żywo: [adelahopek.pl](https://adelahopek.pl/)

## Podgląd na komputerze

W tym katalogu:

```powershell
python -m http.server 8080
```

Potem otwórz [http://127.0.0.1:8080/](http://127.0.0.1:8080/).

## Pliki

| Plik | Po co |
| --- | --- |
| `index.html` | Start: doświadczenie, wykształcenie, certyfikaty, aktualności |
| `testy.html` | Szerzej o testach |
| `analiza.html` | Szerzej o analizie |
| `style.css` | Wygląd |
| `lang.js` | Przełącznik PL / EN |
| `aktualnosci.js` | Karty Aktualności i Poza pracą |
| `aktualnosci.json` | Treść tych kart |
| `aktualnosci/` | Zdjęcia postów |
| `cv_zdjecie.jpg` | Zdjęcie w kolumnie kontaktu |
| `Adela_Hopek_CV.pdf` | CV po polsku, link „Pobierz CV” |
| `Adela_Hopek_CV_EN.pdf` | CV po angielsku, link „Download CV” |

Przycisk PL / EN czyta atrybuty `data-pl` i `data-en`. Po angielsku link CV wskazuje plik `_EN`.

## Aktualności

Wpisy biorą się z `aktualnosci.json`, nie z logowania do LinkedIn ani Instagrama. W `linkedin` i `instagram` są najwyżej dwa wpisy, najnowszy pierwszy. Zdjęcie leży w `aktualnosci/`, a w JSON ścieżka jest względem `index.html`, na przykład `aktualnosci/li-2026-10-13.jpg`.

Tekst posta wkleja się z oryginału. Drugi język jest tłumaczeniem tego tekstu, bez dopisywania faktów.
