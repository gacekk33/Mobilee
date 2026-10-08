# LeafGPT Mobile (osobne repozytorium)

Mobilny interfejs oparty na działającym frontendzie LeafGPT. Zawiera czat, Supabase, historię, statystyki, panel admina, promocję i ustawienia. Dane i API są współdzielone z wersją PC.

## Publikacja z telefonu
1. Utwórz **nowe publiczne repozytorium** na GitHubie, np. `LeafGPT-Mobile`.
2. Wgraj pliki z ZIP do głównego katalogu repozytorium (nie cały ZIP jako jeden plik).
3. GitHub: Settings → Pages → Deploy from a branch → `main` / `(root)` → Save.
4. Po publikacji otwórz adres `https://TWOJ_LOGIN.github.io/LeafGPT-Mobile/`.

## Ważne: Supabase i API
Frontend używa tej samej konfiguracji Supabase i API co PC. Aby logowanie działało, dodaj nowy adres GitHub Pages w Supabase Auth → URL Configuration → Redirect URLs. W razie problemów z odpowiedziami AI sprawdź CORS endpointu `/api/chat` na Vercel i dodaj nowy origin (bez ukośnika na końcu). Nie publikuj kluczy service_role ani GEMINI_API_KEY.

## Brakujące logo partnera
W dostarczonym ZIP-ie nie było `valek-logo.png`. Dodaj je do głównego katalogu, jeśli chcesz wyświetlać logo VałekAI.

## APK
Po publikacji mobilnego adresu możesz go użyć w kreatorze APK/WebView. Wymagane połączenie internetowe.
