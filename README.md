# ♠ Blackjack Royale

Przeglądarkowa gra w blackjacka dla 1–5 graczy przy jednym stole. Bez instalacji — wystarczy otworzyć `index.html` w przeglądarce.

## Funkcje

- **1–5 graczy** z własnymi imionami i awatarami (klik w awatar losuje nowy, przycisk „🎲 Losowe imiona”)
- **Pełne zasady kasynowe**: dobieranie, stój, podwojenie (także po rozdzieleniu), rozdzielenie do 4 rąk, rozdzielone asy, ubezpieczenie 2:1, poddanie, Blackjack płaci 3:2, krupier sprawdza kartę zakrytą (peek)
- **Konfiguracja**: 1–8 talii w bucie, żetony na start, tempo rozdawania, krupier S17/H17, poddanie wł./wył.
- **Pełna losowość**: tasowanie Fishera–Yatesa z kryptograficznym generatorem `crypto.getRandomValues` (z próbkowaniem z odrzuceniem — zero przekłamań rozkładu), tasowanie buta po rozdaniu 75% kart
- **Grafika**: zielony stół z drewnianą bandą, rysowane karty (układ symboli jak na prawdziwych kartach, figury, rewers), animacje rozdawania i odkrywania, żetony kasynowe
- **Zakłady** żetonami 10/50/100/500, „Powtórz”, „Va banque”, dokupowanie żetonów przy bankructwie, pauzowanie rundy
- **Podpowiedź** według strategii podstawowej, **licznik kart Hi-Lo** (bieżący i prawdziwy)
- **Ranking i statystyki** graczy, historia rozdań, dźwięki (WebAudio), skróty klawiszowe
- **Autozapis** — gra zapisuje się w przeglądarce i można ją kontynuować później
- Działa na komputerze i telefonie

## Skróty klawiszowe

`H` dobierz · `S` stój · `D` podwój · `P` rozdziel · `R` poddaj się · `?` podpowiedź · `T`/`N` ubezpieczenie · `Enter` rozdaj / następna runda
