# VibSense  
Polityka prywatności / Privacy Policy

**Kontakt / Contact:** vibesense@poczta.fm  
**Data ostatniej aktualizacji / Last updated:** 3 kwietnia 2026 / 3 April 2026

---

## Polityka prywatności (PL)- VibSense

### 1) Kto jest administratorem danych
Administratorem danych w rozumieniu przepisów o ochronie danych jest wydawca aplikacji VibSense.  
W sprawach prywatności skontaktuj się z nami pod adresem e-mail wskazanym powyżej.

### 2) Jakie dane przetwarzamy i dlaczego

#### A. Audio z mikrofonu / wejścia audio Bluetooth (funkcja nasłuchu)
Aplikacja może uzyskać dostęp do mikrofonu lub wejścia audio z zestawu słuchawkowego Bluetooth, aby wykrywać zdarzenia dźwiękowe (np. mowa/dzwonek/pies/klakson) i generować alerty (powiadomienia/wibracje). Nasłuch działa w usłudze pierwszoplanowej (foreground service).

**Sposób przetwarzania:** klasyfikacja dźwięku odbywa się na urządzeniu (model audio/TFLite), bez potrzeby zakładania konta.

**Przechowywanie audio:** nie zapisujemy surowych nagrań audio w aplikacji (audio jest przetwarzane strumieniowo w pamięci na potrzeby detekcji).

#### B. Rozpoznawanie mowy (Speech-to-Text)
Jeśli włączysz funkcję „Rozpoznaj mowę”, aplikacja użyje systemowego API Android SpeechRecognizer do zamiany mowy na tekst.

**Ważne:** rozpoznawanie mowy jest realizowane przez usługi rozpoznawania mowy dostępne na urządzeniu (np. dostawca systemowy). W zależności od konfiguracji urządzenia i dostawcy usługi, dane głosowe mogą być przetwarzane poza urządzeniem (np. w chmurze dostawcy) zgodnie z zasadami prywatności tego dostawcy. Aplikacja VibSense nie ma kontroli nad tym procesem po stronie dostawcy usługi.

Wynik rozpoznania (tekst) jest prezentowany w aplikacji i nie jest przez nas wysyłany na własne serwery.

#### C. Identyfikatory/parametry urządzeń audio (lokalnie)
Jeśli wybierzesz źródło audio Bluetooth, aplikacja może odczytywać listę urządzeń wejściowych audio i (jeśli dostępne) ich parametry techniczne, a także identyfikator urządzenia (np. adres lub identyfikator id:...) wyłącznie w celu umożliwienia wyboru wejścia i diagnostyki.

Aplikacja może też wyświetlać w ekranie diagnostyki nazwy i adresy zestawów Bluetooth podłączonych do profilu HEADSET.

#### D. Ustawienia aplikacji i liczniki użycia (lokalnie)
Aplikacja przechowuje lokalnie (w pamięci aplikacji / SharedPreferences) wybrane ustawienia (np. źródło audio, wybrane urządzenie BT, wyłączone urządzenia BT) oraz pomocnicze stany UI (np. ostatnie efektywne źródło i powód fallbacku).

Dodatkowo aplikacja zapisuje lokalne liczniki limitów dla wersji „FREE” (czas dzienny nasłuchu i STT oraz flagi, czy pokazano komunikat o limicie).

#### E. Ekran „YouTube channels” (linki zewnętrzne)
Aplikacja zawiera ekran z listą publicznych kanałów YouTube i otwiera je w oficjalnej aplikacji YouTube lub w przeglądarce.  
Jeśli w przyszłości włączysz pobieranie metadanych „najnowszego filmu”, może to wykorzystywać YouTube Data API (zapytania HTTP do domen Google APIs).

#### F. Czat tekstowy i komunikacja dla osób niesłyszących
Aplikacja zawiera funkcję czatu tekstowego wspierającą komunikację osób niesłyszących.

**Funkcja umożliwia:**
- wpisywanie wiadomości tekstowych przez użytkownika,
- wyświetlanie wyników rozpoznawania mowy jako wiadomości,
- odczytywanie wiadomości na głos (Text-to-Speech),
- korzystanie z szybkich komunikatów (np. „Nie słyszę”, „Mów wolniej”).

**Sposób przetwarzania:**
- wszystkie wiadomości czatu są przetwarzane i przechowywane wyłącznie lokalnie na urządzeniu (w pamięci aplikacji),
- aplikacja nie wysyła treści wiadomości na własne serwery,
- wiadomości nie są archiwizowane poza bieżącą sesją aplikacji.

**Integracja z innymi funkcjami:**
- wiadomości mogą pochodzić z funkcji rozpoznawania mowy (patrz sekcja B),
- funkcja odczytu (Text-to-Speech) wykorzystuje systemowe usługi Android.

**Ograniczenia (wersja FREE):**
- aplikacja może stosować lokalne limity liczby użyć funkcji czatu i rozpoznawania mowy dziennie.

### 3) Uprawnienia (permissions) i uzasadnienie
- Mikrofon (RECORD_AUDIO): wymagany do nasłuchu i rozpoznawania mowy  
- Powiadomienia (POST_NOTIFICATIONS, Android 13+): do alertów  
- Bluetooth (BLUETOOTH_CONNECT): do audio i diagnostyki  

### 4) Czy zbieramy dane na naszych serwerach?
Nie prowadzimy kont użytkowników i nie zbieramy danych na własnych serwerach.

Dotyczy to również funkcji czatu – wiadomości użytkownika nie są przesyłane ani przechowywane na naszych serwerach.

### 5) Udostępnianie danych podmiotom trzecim
Nie sprzedajemy danych.

### 6) Retencja danych
Ustawienia i liczniki przechowywane są lokalnie.  
Surowe audio nie jest archiwizowane.  
Wiadomości czatu nie są trwale przechowywane.

### 7) Bezpieczeństwo
Stosujemy standardowe mechanizmy Android.

### 8) Twoje wybory
Możesz cofnąć uprawnienia, zatrzymać aplikację lub usunąć dane.

### 9) Prywatność dzieci
Aplikacja nie jest kierowana do dzieci.

### 10) Zmiany w polityce
Polityka może być aktualizowana.

---

## Privacy Policy (EN)- VibSense

### 1) Who we are
This Privacy Policy explains how the VibSense app handles information.

### 2) What data we process and why

#### A. Microphone / Bluetooth audio input
Used for sound detection.  
Processed on-device.  
No raw audio stored.

#### B. Speech-to-text
Uses Android SpeechRecognizer.  
May be processed by external providers.

#### C. Audio device data
Stored locally for configuration.

#### D. App settings and usage counters
Stored locally.

#### E. YouTube
External links handled by YouTube.

#### F. Text chat and communication feature for deaf users
The app includes a text chat feature.

**Allows:**
- typing messages  
- displaying STT results  
- TTS playback  
- quick phrases  

**Processing:**
- local only  
- no server transmission  
- no permanent storage  

### 3) Permissions
- RECORD_AUDIO  
- POST_NOTIFICATIONS  
- BLUETOOTH_CONNECT  

### 4) Do we collect data on our servers?
No.  
This also applies to chat messages.

### 5) Sharing
Only via external services (STT, YouTube).

### 6) Data retention
Local only. No audio or chat storage.

### 7) Security
Standard Android protections.

### 8) Controls
You can revoke permissions or delete data.

### 9) Children
Not intended for children.

### 10) Changes
Policy may be updated.
