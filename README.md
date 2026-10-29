# Tytuły Allegro — wydania Windows

[Pobierz najnowszy instalator](https://github.com/BlackCatV2/tytuly-allegro-releases/releases/latest)

Aplikacja Windows do tworzenia tytułów Allegro z list zastosowań świec zapłonowych. Dostęp do generowania wymaga połączenia komputera z prywatnym serwerem właściciela i aktywnej konfiguracji generowania. W wersji 0.6 nowy komputer łączy się jednorazowym kodem od administratora; dotychczasowy zapis dostępu migruje automatycznie. Instalator nie zawiera poświadczeń ani klucza OpenAI.

Od wersji 0.4.1 zainstalowana aplikacja automatycznie sprawdza i pobiera nowe wydania. Instalacja wymaga kliknięcia „Zaktualizuj i uruchom ponownie”. Wersje 0.3.x i wcześniejsze wymagają jednorazowego uruchomienia nowego instalatora.

Od wersji 0.6 ustawienia rozdzielają Dostęp, Aktualizacje i Wytyczne. Potwierdzony dostęp nie oznacza jeszcze gotowości AI. Pobranie instalatora z tego publicznego repozytorium nie przyznaje dostępu do serwera.

Repozytorium udostępnia pakiety aplikacji. Kod źródłowy jest prywatny. Instalatory nie mają obecnie podpisu cyfrowego.

## Publikacja przez właściciela

Workflow `release.yml` uruchamia się ręcznie dla zatwierdzonego numeru wersji z prywatnego repozytorium kodu. Buduje i testuje WPF, pakuje Velopack, tworzy robocze wydanie, przesyła komplet plików i dopiero potem udostępnia wydanie aplikacji. Nie wykonuje instalatora ani aktualizacji na komputerze użytkownika.
