# System zarządzania zadaniami

## Opis

System zarządzania zadaniami to aplikacja webowa umożliwiająca zarządzanie zadaniami oraz śledzenie stanu wykonania. Projekt został zrealizowany z wykorzystaniem frameworka Django.

## Funkcje

- **Autoryzacja użytkowników**: Rejestracja, logowanie i wylogowywanie użytkowników.
- **Zarządzanie zadaniami**: Dodawanie, edytowanie i usuwanie zadań.
- **Stylizacja**: Użycie css'a do stylizacji formularzy i przycisków.

## Instalacja

1. Sklonuj repozytorium lub wypakuj folder z projektem:

    ```bash
    git clone https://github.com/TwojeUzytkownik/System-Archiwizacji-Dokumentow.git
    cd System-Zadan
    ```

2. Utwórz i aktywuj wirtualne środowisko:
# na Windows przejść do folderu Scripts: .venv\Scripts\activate
    ```bash
    python -m venv .venv
    source .venv/bin/activate  
    ```

3. Zainstaluj wymagane pakiety:

    ```bash
    pip install -r requirements.txt
    ```

4. Wykonaj migracje bazy danych:

    ```bash
    python manage.py migrate
    ```

5. Uruchom serwer deweloperski:

    ```bash
    python manage.py runserver
    ```

6. Otwórz przeglądarkę i przejdź do `http://127.0.0.1:8000/`.

## Użycie

1. **Rejestracja**: Użytkownicy mogą się zarejestrować, klikając na link "Zarejestruj się" na stronie głównej.
2. **Logowanie**: Zalogowani użytkownicy mogą zarządzać zadaniami.
3. **Dodawanie zadań**: Można dodawać nowe zadanie, klikając na link "Dodaj Dokument".
4. **Edytowanie i usuwanie zadań**: Dokumenty mogą być edytowane lub usuwane z listy dokumentów przez zalogowanych użytkowników.

