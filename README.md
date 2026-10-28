# Tytuły Allegro — wydania Windows

[Pobierz najnowszy instalator](https://github.com/BlackCatV2/tytuly-allegro-releases/releases/latest)

Aplikacja Windows do tworzenia tytułów Allegro z list zastosowań świec zapłonowych. Dostęp do generowania wymaga osobnego tokenu aplikacji. Instalator nie zawiera tokenów ani klucza OpenAI.

Od wersji 0.4.0 zainstalowana aplikacja automatycznie sprawdza i pobiera nowe wydania. Instalacja wymaga kliknięcia „Zaktualizuj i uruchom ponownie”. Wersje 0.3.x i wcześniejsze wymagają jednorazowego uruchomienia nowego instalatora.

Repozytorium udostępnia pakiety aplikacji. Kod źródłowy jest prywatny. Instalatory nie mają obecnie podpisu cyfrowego.

## Publikacja przez właściciela

Workflow `release.yml` uruchamia się ręcznie dla zatwierdzonego numeru wersji z prywatnego repozytorium kodu. Buduje i testuje WPF, pakuje Velopack, tworzy robocze wydanie, przesyła komplet plików i dopiero potem udostępnia wydanie aplikacji. Nie wykonuje instalatora ani aktualizacji na komputerze użytkownika.
