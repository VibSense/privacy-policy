# VibSense  
Polityka prywatności / Privacy Policy

**Kontakt / Contact:** vibesense@poczta.fm  
**Data ostatniej aktualizacji / Last updated:** 23 stycznia 2026 / 23 January 2026

---

## Polityka prywatności (PL)- VibSense

### 1) Kto jest administratorem danych
Administratorem danych w rozumieniu przepisów o ochronie danych jest wydawca aplikacji VibSense.  
W sprawach prywatności skontaktuj się z nami pod adresem e-mail wskazanym powyżej.

### 2) Jakie dane przetwarzamy i dlaczego

#### A. Audio z mikrofonu / wejścia audio Bluetooth (funkcja nasłuchu)
Aplikacja może uzyskać dostęp do mikrofonu lub wejścia audio z zestawu słuchawkowego Bluetooth, aby wykrywać zdarzenia dźwiękowe (np. mowa/dzwonek/pies/klakson) i generować alerty (powiadomienia/wibracje). Nasłuch działa w usłudze pierwszoplanowej (foreground service).

Sposób przetwarzania: klasyfikacja dźwięku odbywa się na urządzeniu (model audio/TFLite), bez potrzeby zakładania konta.

Przechowywanie audio: nie zapisujemy surowych nagrań audio w aplikacji (audio jest przetwarzane strumieniowo w pamięci na potrzeby detekcji).

#### B. Rozpoznawanie mowy (Speech-to-Text)
Jeśli włączysz funkcję „Rozpoznaj mowę”, aplikacja użyje systemowego API Android SpeechRecognizer do zamiany mowy na tekst.

Ważne: rozpoznawanie mowy jest realizowane przez usługi rozpoznawania mowy dostępne na urządzeniu (np. dostawca systemowy). W zależności od konfiguracji urządzenia i dostawcy usługi, dane głosowe mogą być przetwarzane poza urządzeniem (np. w chmurze dostawcy) zgodnie z zasadami prywatności tego dostawcy. Aplikacja VibSense nie ma kontroli nad tym procesem po stronie dostawcy usługi.

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

### 3) Uprawnienia (permissions) i uzasadnienie
Aplikacja może prosić o uprawnienia w czasie działania, w sposób stopniowy, w zależności od używanej funkcji.

- Mikrofon (RECORD_AUDIO): wymagany do nasłuchu i rozpoznawania mowy.
- Powiadomienia (POST_NOTIFICATIONS, Android 13+): do alertów o wykrytych zdarzeniach.
- Bluetooth (BLUETOOTH_CONNECT): do odczytu/wyboru wejścia audio Bluetooth i diagnostyki.

### 4) Czy zbieramy dane na naszych serwerach?
Nie prowadzimy kont użytkowników i nie zbieramy danych na własnych serwerach w ramach działania aplikacji opisanej w obecnym kodzie (ustawienia i liczniki są przechowywane lokalnie).

### 5) Udostępnianie danych podmiotom trzecim
Nie sprzedajemy danych. Możliwe udostępnienie danych wynika wyłącznie z użycia usług systemowych lub przejścia do aplikacji zewnętrznych:

- Dostawca rozpoznawania mowy (SpeechRecognizer): audio użyte do STT może zostać przekazane do dostawcy usługi rozpoznawania mowy zgodnie z jego polityką prywatności (zależnie od ustawień urządzenia).
- YouTube / przeglądarka: po kliknięciu kanału YouTube przechodzisz do aplikacji YouTube lub przeglądarki, które działają na własnych zasadach prywatności.
- YouTube Data API (opcjonalnie, jeśli aktywne w danej wersji): zapytania o publiczne metadane kanałów/filmów są realizowane do usług Google.

### 6) Retencja danych
Ustawienia i liczniki przechowywane są lokalnie na urządzeniu do czasu ich usunięcia (np. „Wyczyść dane aplikacji” w ustawieniach Androida) lub odinstalowania aplikacji.

Surowe audio nie jest archiwizowane przez aplikację.

### 7) Bezpieczeństwo
Stosujemy standardowe mechanizmy bezpieczeństwa platformy Android (piaskownica aplikacji, kontrola uprawnień). Pamiętaj, że żaden system nie gwarantuje 100% bezpieczeństwa.

### 8) Twoje wybory i kontrola
Możesz w każdej chwili:
- cofnąć uprawnienia (mikrofon/powiadomienia/bluetooth) w ustawieniach Androida,
- zatrzymać nasłuch w aplikacji,
- wyczyścić dane aplikacji lub ją odinstalować (usuwa lokalne ustawienia/liczniki).

### 9) Prywatność dzieci
Aplikacja nie jest projektowana jako usługa kierowana do dzieci i nie zakłada celowego gromadzenia danych dzieci.

### 10) Zmiany w polityce
Jeśli zmienimy sposób przetwarzania danych, zaktualizujemy treść polityki prywatności i wskażemy nową datę aktualizacji. Google Play wymaga, aby polityka prywatności była aktualna i zgodna z rzeczywistymi praktykami aplikacji.

---

## Privacy Policy (EN)- VibSense

### 1) Who we are
This Privacy Policy explains how the VibSense app handles information.  
If you have questions, contact us at the email above.

### 2) What data we process and why

#### A. Microphone / Bluetooth audio input (background sound monitoring)
VibSense can access the microphone or a Bluetooth headset input to detect sound events (e.g., speech/doorbell/dog/car horn) and provide alerts (notifications/vibration). Monitoring runs as a foreground service.

Processing: sound classification is performed on-device (TFLite audio model).

Audio storage: the app does not store raw audio recordings; audio is processed in-memory for detection.

#### B. Speech-to-text (SpeechRecognizer)
When you use the “Speech-to-text” feature, the app uses Android’s SpeechRecognizer API to convert speech into text.

Important: Speech recognition is provided by a system speech service on your device. Depending on your device/provider configuration, your speech audio may be processed off-device (e.g., in the provider’s cloud) under that provider’s privacy policy. VibSense does not control the provider-side processing.

Recognized text is shown in the app and is not sent to our servers.

#### C. Audio device identifiers/diagnostics (local)
If you enable Bluetooth as an audio source, the app may read available audio input devices and store a local identifier for your selected input (e.g., device address or an id:... value) to make routing/selection work.

The diagnostics screen may display Bluetooth headset names and addresses (when available and permitted) for troubleshooting.

#### D. App settings and usage counters (local)
The app stores local settings (audio source selection, chosen Bluetooth input, disabled BT inputs) and UI helper states (e.g., last effective source and fallback reason).

In the “FREE” version, the app stores local daily usage counters (listening time and STT time) and whether a limit message has already been shown.

#### E. “YouTube channels” screen (external links)
The app includes a list of public YouTube channels and opens them in the official YouTube app or a browser.  
If enabled in a given version, the app may fetch public channel/video metadata using the YouTube Data API (HTTP requests to Google APIs).

### 3) Permissions and why they are needed
The app requests runtime permissions as needed and for user-consented purposes.
- RECORD_AUDIO (Microphone): required for sound monitoring and speech-to-text.
- POST_NOTIFICATIONS (Android 13+): required to show alerts/notifications.
- BLUETOOTH_CONNECT: required to access/select Bluetooth audio inputs and show diagnostics.

### 4) Do we collect data on our servers?
We do not provide user accounts and we do not collect user data on our own servers based on the current implementation; settings and counters are stored locally on your device.

### 5) Sharing with third parties
We do not sell your data. Potential data sharing results only from using system services or opening external apps:

- Speech recognition provider (SpeechRecognizer): audio used for STT may be transmitted to the device’s speech service provider depending on your configuration, under that provider’s privacy policy.
- YouTube / browser: when you open a YouTube channel link, YouTube or your browser handles data under their own policies.
- YouTube Data API (optional): if enabled, the app requests public metadata from Google services.

### 6) Data retention
Local settings and counters remain until you clear app data or uninstall the app.

The app does not store raw audio recordings.

### 7) Security
We rely on standard Android security mechanisms (app sandboxing and permission controls). No method of storage is 100% secure.

### 8) Your controls
You can:
- revoke permissions at any time in Android settings,
- stop monitoring inside the app,
- clear app data or uninstall the app (removes locally stored settings/counters).

### 9) Children’s privacy
The app is not designed as a child-directed service and does not knowingly collect children’s personal data.

### 10) Changes to this policy
If we change how we process data, we will update this Privacy Policy and indicate a new “Last updated” date. Google Play requires the Privacy Policy to be up to date and consistent with the app’s actual practices.
