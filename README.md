# Szukacz – Allegro REST API Search Tool

Proste narzędzie konsolowe (CLI) integrujące się z oficjalnym REST API Allegro w celu wyszukiwania i filtrowania ofert.

---

## 📌 Funkcjonalności

- Wyszukiwanie ofert po frazie kluczowej
- Filtrowanie po cenie (od / do), stanie produktu (nowy / używany) oraz kategorii
- Sortowanie wyników (np. od najtańszych, trafność)
- Prezentacja wyników w czytelnej tabeli w terminalu lub eksport do JSON/CSV

---

## ⚙️ Wymagania

- Python 3.9+
- Konto Allegro oraz zarejestrowana aplikacja w [Allegro Developer](https://apps.developer.allegro.pl/)

---



## 💻 Użycie

Przykładowe wyszukiwanie ofert:

```bash
python szukacz.py --phrase "thinkpad t480" --min-price 500 --max-price 1500 --sort price_asc
```

---

## 📄 Licencja

Projekt udostępniany na licencji MIT.
