# UwUSounds v1.1.0 (PRO Version) 🐱✨

> Słodkie UwU dźwięki dla Discorda, które zostały pomyślnie zrekonstruowane od fundamentów dla absolutnej wydajności i niezawodności! **Żadnego generowania dźwięków na bieżąco, zero psujących się syntezatorów i przerywających pisków.** Przeszliśmy na czyste zewnętrzne zasoby audio i bezinwazyjne API Vencorda!

Dumnie stworzone i zaprojektowane przez zespół **VibeoDevelopers**.

---

## 🚀 Główne Funkcje (PRO Features)

| Funkcja | Opis |
|-----------|------|
| 🎨 **Motywy Dźwiękowe** | Zamiast jednego nudnego UwU, możesz w locie zmieniać całe paczki dźwięków (UwU Classic, Anime Girl, Lofi Beats, Minimalist). |
| 🎛️ **React Admin Panel** | Przepiękny, w pełni autorski graficzny interfejs ustawień (z logo!), wbudowanym **Soundboardem** do testowania dźwięków "na sucho". |
| 🕹️ **Konami Code** | Wciśnij na klawiaturze sekwencję `u` `w` `u`, aby odblokować ukryty Easter Egg, odtworzyć epicką fanfarę i wywołać na ekranie powiadomienie! |
| 💬 **Ping Words** | Powiadomienia dźwiękowe na Słowa Kluczowe. Gdy ktoś napisze na czacie np. Twój nick, wtyczka ostrzeże Cię dźwiękiem nawet bez oficjalnego `@pingu`! |
| 🌙 **Tryb Nocny (Chill Mode)** | Zarywasz nockę? Po godzinie 22:00 wtyczka automatycznie redukuje głośność i lekko modyfikuje Pitch dźwięków na spokojniejszy Lofi vibe. |
| 🤫 **Mute/Deafen Sync** | Złota funkcja dla zapominalskich: wtyczka powiadomi Cię, gdy zaczniesz mówić, a masz włączone wyciszenie mikrofonu na Discordzie! |
| 🔗 **Niestandardowe Linki** | Znalazłeś fajny dźwięk w internecie? Wklej jego adres bezpośrednio w ustawieniach wtyczki i nadpisz domyślne powiadomienia! |

---

## 🛠️ 6. Funkcje Administracyjne i Zarządzanie (Dla Profesjonalistów)
Wtyczka otrzymała potężne dedykowane narzędzia do pełnej, granularnej kontroli nad jej zachowaniem – zaprojektowane z myślą o inżynierach i zaawansowanych użytkownikach.

1. **Dostęp do Konsoli Wtyczki (Admin Console):** 
   Prawdziwy game-changer do debugowania. Po włączeniu tego przełącznika w panelu, wtyczka aktywuje szczegółowe raportowanie do Konsoli Deweloperskiej Discorda (`F12`). Każde przechwycone zdarzenie audio z silnika Discorda, każde użyte Słowo Kluczowe (Ping Word) i każdy błąd wejścia na stream jest dokładnie logowany z podaniem źródła, głośności i statusu. Idealne narzędzie do monitorowania infrastruktury Vencorda i diagnostyki przepływu zdarzeń.

2. **Zarządzanie Zewnętrzne (Import & Eksport Profili):** 
   Wypracowałeś swój idealny układ głośności, własnych linków URL i słów kluczowych? Specjalny, wyróżniony na zielono przycisk **"Eksportuj Profil 📥"** wygeneruje kompletny snapshot (zrzut stanu) Twoich konfiguracji i po cichu umieści go w Twoim schowku. Możesz natychmiast podzielić się swoją idealną konfiguracją ze znajomymi lub bezpiecznie zarchiwizować profil wtyczki. 

---

## 🎥 Prezentacja z testów (Video Demo)

Oto krótki materiał wideo prezentujący w akcji nasz najnowszy interfejs administracyjny UwUSounds v1.1.0

![Panel Administracyjny UwUSounds](uwu_sounds_demo.webp)

---

## 📦 Instalacja

1. Sklonuj najnowszą wersję repozytorium **Vencord** lub przejdź do swojego lokalnego folderu z Vencordem.
2. Skopiuj plik `index.tsx` (oraz cały ten kod) do folderu wtyczek: `src/plugins/uwuSounds/index.tsx`.
3. Wykonaj pełną budowę projektu używając komendy:
   ```bash
   pnpm build
   ```
4. Zrestartuj Discorda, wejdź w `Ustawienia -> Plugins`, wyszukaj **UwUSounds** i skonfiguruj wtyczkę!

---
*Powered by Webpack & FluxDispatcher. VibeoDevelopers © 2026*
