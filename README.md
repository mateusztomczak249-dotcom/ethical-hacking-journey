# 🚀 Raport z Dnia 2025-09-26 - Przejście poziomów Natas 7-9

## 🔓 POZIOM 7 - LFI (Local File Inclusion)

### Co zrobiłem:
- Odkryłem, że parametr `?page=` na stronie pozwala na przeglądanie plików
- Wykorzystałem podatność LFI wpisując: `../../../etc/natas_webpass/natas8`
- Zdobyłem hasło do poziomu 8

### Czego się nauczyłem:
- Jak działa Local File Inclusion
- Jak szukać ścieżek do wrażliwych plików
- Że programiści czasem nie zabezpieczają parametrów

---

## 🔓 POZIOM 8 - Reverse Engineering

### Co zrobiłem:
- Znalazłem w kodzie zakodowany sekret: `3d3d516343746d4d6d6c315669563362`
- Odczytałem funkcję szyfrującą w PHP
- Użyłem CyberChef do odwrócenia procesu szyfrowania

### Czego się nauczyłem:
- Jak odczytywać zakodowane dane (Hex + Reverse + Base64)
- Jak używać CyberChef do dekodowania
- Że hasła są często ukrywane przez kodowanie

---

## 🔓 POZIOM 9 - Command Injection

### Co zrobiłem:
- Przetestowałem formularz wpisując różne polecenia
- Wykryłem, że formularz wykonuje polecenia systemowe
- Wykorzystałem to do przeczytania pliku z hasłem

### Czego się nauczyłem:
- Jak wykrywać Command Injection
- Jakie znaki są blokowane (`;`, `|`, `&`)
- Że niewalidowane inputy są niebezpieczne

---

## 🎯 PODSUMOWANIE DNIA:
**Przeszedłem 3 poziomy w jeden dzień**
- ✅ LFI Attack
- ✅ Reverse Engineering  
- ✅ Command Injection

**To były rzeczywiste, praktyczne umiejętności - nie teoria!**

---

## 💭 Dlaczego to takie ważne?
*Miałem dziś tylko ograniczony czas, ale udało mi się przejść 3 poziomy. To pokazuje, że nawet przy niewielkim nakładzie czasu można systematycznie rozwijać praktyczne umiejętności hakowania etycznego. Każdy może to zrobić - wystarczy determinacja i chęć nauki krok po kroku.*# 🔍 Bug Hunter's Journey - Dziennik Praktycznej Nauki
