# Badanie przebiegu zmienności funkcji f(x) = eˣ/x

## Politechnika Lubelska

**Wydział:** Matematyki i Informatyki Technicznej  
**Kierunek:** Inżynieria i Analiza Danych  
**Przedmiot:** Narzędzia informatyczne II  
**Projekt:** Maxima  
**Wykonala:** Maja Darczuk

---

## Opis projektu

Projekt zaliczeniowy z przedmiotu Narzędzia informatyczne II, którego celem jest zbadanie przebiegu zmienności funkcji wymiernej:

$$f(x) = \frac{e^x}{x}$$

Badanie obejmuje analizę:
- Dziedziny funkcji
- Asymptot (pionowych, poziomych, ukośnych)
- Miejsc zerowych
- Znaków funkcji
- Pochodnej i ekstremów lokalnych
- Przedziałów monotoniczności
- Zbioru wartości
- Wykresu funkcji

---


## Uruchomienie

### Wersja konsolowa

1. Zainstaluj program Maxima:
   - Windows: pobierz z [maxima.sourceforge.io](https://maxima.sourceforge.io)
   - Linux: `sudo apt install maxima`
   - macOS: `brew install maxima`

2. Uruchom plik w Maxima:
   ```bash
   maxima -b projekt.max
   ```

### Wersja z interfejsem graficznym

1. Uruchom wxMaxima
2. Otwórz plik `projekt.max`
3. Wykonaj komórki (Shift+Enter) lub całość (Ctrl+Enter)

---

## Wyniki analizy

| Cecha | Wynik |
|-------|-------|
| Dziedzina | D = ℝ \ {0} |
| Asymptota pionowa | x = 0 |
| Asymptota pozioma | brak |
| Asymptota ukośna | brak |
| Miejsce zerowe | nie istnieje |
| Znak funkcji | dodatnia dla x > 0, ujemna dla x < 0 |
| Ekstremum lokalne | minimum w x = 1, f(1) = e |
| monotoniczność | malejąca na (0,1), rosnąca na (-∞,0) ∪ (1,∞) |
| Zbiór wartości | (-∞, 0) ∪ (e, ∞) |

---

## Źródła

- Prezentacje wykładu "Narzędzia Informatyczne II" dr inż. Anny Futy
- Dokumentacja Maxima: https://maxima.sourceforge.io/documentation.html
