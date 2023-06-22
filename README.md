# Projekt dyplomowy "Automatyzacja i optymalizacja obsługi laserowego tomografu komputerowego"
### Projekt dyplomowy inżynierski wykonany w ramach studiów I stopnia na kierunku "Inżynieria Biomedyczna" (specjalizacja: "Fizyka Medyczna").

Repozytorium zawiera kod źródłowy pracy inżynierskiej napisanej w LaTeXu w środowisku webowym Overleaf. Dodatkowo, plik *projekt_dyplomowy_SR.pdf* zawiera skompilowaną wersję dokumentu.

# Streszczenie
Praca skupia się na aspektach automatyzacji diagnostyki działania laserowego tomografu komputerowego. Wraz z opisem budowy i zasady działania LCT przedstawiono w niej fizyczne aspekty działania akcelerometrów i żyroskopów, na których ma bazować opracowywany prototyp czujnika ze sterownikiem. Opisano również zagadnienie filtru Kalmana oraz zasadność jego wykorzystania w proponowanym rozwiązaniu. Następnie przedstawiono założenie i działanie platformy Arduino oraz modułu SEN0142, a następnie opisano tryb komunikacji pomiedzy poszczególnymi elementami opracowywanego urzadzenia, tj.: komputerem z systemem Microsoft Windows, Arduino, a modułem z akcelerometrem i żyroskopem.

W dalszej części pracy przedstawiona została stworzona aplikacja, jej wyglad, funkcjonal nosci i ograniczenia, wraz z kluczowymi fragmentami kodu. Przytoczony został również skrypt samego sterownika (Arduino), który implementuje uprzednio opisane wzory. Następnie w pracy przedstawiono pomiary wykonane czujnikiem dla różnych położeń, na podstawie których możliwe jest określenie niepewności pomiarów. Wykazano również, że opracowane rozwiązanie nie sprawdza się w przypadku badań dynamicznych. Fakt ten zostaje poddany dalszej analizie.

W podsumowaniu przedstawiono przykładowe propozycje rozwiązań mające na celu zarówno ulepszenie, jak i naprawę działania urzadzenia.

**Słowa kluczowe**: wzorcowanie, akcelerometr, kąty RPY

**Dziedzina nauki i techniki, zgodnie z wymogami OECD**: nauki inżynieryjne i techniczne, inżynieria biomedyczna

# Dodatki
Linki do repozytoriów z opracowanymi rozwiązaniami:

- [Aplikacja okienkowa](github.com/StachRach/dyplom-WPF)
- [Skrypt do Arduino Uno](github.com/StachRach/dyplom-arduino-final)
