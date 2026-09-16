---
title: AutoKlik — Polityka prywatności
lang: pl
---

[English](../)

# AutoKlik — Polityka prywatności

**Ostatnia aktualizacja:** 13 września 2026
**Dotyczy:** AutoKlik (`com.dismonder.autoclicker`), wszystkie wersje od 1.1.0

## W skrócie

AutoKlik nie zbiera, nie przesyła ani nie udostępnia żadnych danych osobowych.
Wszystko, co aplikacja zapisuje, pozostaje na Twoim urządzeniu. Aplikacja nie ma
dostępu do internetu — nie deklaruje uprawnienia `INTERNET`, więc technicznie nie
jest w stanie niczego nigdzie wysłać.

## Co aplikacja zapisuje i gdzie

Wszystkie poniższe dane trafiają wyłącznie do prywatnej pamięci AutoKlika na Twoim
urządzeniu:

| Dane | Cel | Gdzie |
| --- | --- | --- |
| Profile automatyzacji (nazwy, współrzędne dotknięć i gestów, czasy, ustawienia pętli) | Scenariusze, które tworzysz | Lokalna baza na urządzeniu |
| Historia uruchomień (czas startu, czas trwania, liczba kliknięć i pętli, wynik) | Ekran historii | Lokalna baza na urządzeniu |
| Ustawienia aplikacji (przezroczystość nakładki, domyślne czasy, przełączniki) | Twoje preferencje | Lokalny plik preferencji na urządzeniu |

Nic z powyższych nie jest wysyłane, kopiowane do chmury ani udostępniane deweloperowi
czy podmiotom trzecim. Kopia zapasowa w chmurze i transfer między urządzeniami są
wyłączone.

## Czego aplikacja **nie** robi

- Brak analityki, telemetrii, raportowania awarii i SDK reklamowych.
- Brak konta, logowania i jakiegokolwiek identyfikatora użytkownika.
- Brak dostępu do kontaktów, lokalizacji, aparatu, mikrofonu, zdjęć, plików i połączeń.
- Nie odczytuje zawartości innych aplikacji ani nie rejestruje wpisywanego tekstu.

## Uprawnienia i po co są potrzebne

**Usługa ułatwień dostępu.** AutoKlik wykonuje zapisane przez Ciebie dotknięcia i
gesty przy użyciu systemowego API gestów (`dispatchGesture`). To jedyny sposób, aby
aplikacja mogła dotykać ekranu w Twoim imieniu bez uprawnień root.

Usługa jest skonfigurowana tak wąsko, jak pozwala Android:

- **Nie może odczytywać zawartości okien** — nie widzi, co masz na ekranie.
- **Nie filtruje zdarzeń klawiszy** — nie może śledzić tego, co wpisujesz, ani w
  AutoKliku, ani w żadnej innej aplikacji.
- Nie subskrybuje żadnych zdarzeń ułatwień dostępu opisujących Twoją aktywność.

Usługa wyłącznie wysyła gesty. Nic, do czego ma dostęp, nie jest zbierane,
zapisywane ani przesyłane.

**Wyświetlanie nad innymi aplikacjami.** Pokazuje pływający panel sterowania i
markery kliknięć nad innymi aplikacjami, żebyś mógł uruchamiać, wstrzymywać i
zatrzymywać scenariusz bez ich opuszczania.

**Powiadomienia.** Pokazuje powiadomienie sterujące, gdy scenariusz jest wczytany lub
działa. Opcjonalne — aplikacja działa bez niego.

**Wibracje.** Potwierdzenie dotykowe przy korzystaniu z pływających przycisków.

## Dzieci

AutoKlik nie jest kierowany do dzieci i nie zbiera danych od nikogo, w tym od dzieci.

## Zmiany polityki

W razie zmiany polityki zaktualizowana wersja zostanie opublikowana pod tym samym
adresem, a data „Ostatnia aktualizacja" powyżej ulegnie zmianie.

## Kontakt

Pytania dotyczące polityki: **dismonder@gmail.com**
