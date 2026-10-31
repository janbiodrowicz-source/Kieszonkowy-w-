# Kieszonkowy Wąż

Snake na kieszonkowej konsolce z ekranem LCD. Wszystko na ekranie, łącznie z napisami, jest rysowane z kropek matrycy 104×112.

## Jak grać

- Przesuń palcem po ekranie albo użyj krzyżaka. Na klawiaturze: strzałki lub WASD.
- START: start i pauza. M wycisza dźwięk.
- Co piąty przysmak wypuszcza żuka. Im szybciej go złapiesz, tym więcej punktów.
- Poziom 1–9 i tryb ścian ustawiasz przyciskami pod ekranem. Przerywana ramka: przechodzisz na drugą stronę. Ciągła: ściana kończy grę.

## APK

Każdy push na `main` uruchamia akcję **Buduj APK** (`.github/workflows/apk.yml`). Gotowy plik `kieszonkowy-waz.apk` ląduje w zakładce **Releases**. To build debug, do instalowania bezpośrednio na telefonie.

## Struktura

- `www/index.html` – cała gra w jednym pliku
- `resources/` – ikona (1024 px) i ikony Androida we wszystkich gęstościach
- `capacitor.config.json` – konfiguracja Capacitora (appId `com.janbiodrowicz.kieszonkowywaz`)
