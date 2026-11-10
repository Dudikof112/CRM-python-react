# CRM — system zarządzania klientami

## Cel projektu

Celem projektu jest stworzenie aplikacji CRM (Customer Relationship Management), czyli systemu do zarządzania relacjami z klientami.

Aplikacja będzie przeznaczona dla małych i średnich firm, przedsiębiorców oraz osób zajmujących się obsługą klienta i sprzedażą.

System ma ułatwić przechowywanie informacji o klientach, zarządzanie kontaktami, kontrolowanie historii współpracy oraz organizowanie zadań związanych z obsługą klientów.

Głównym problemem, który rozwiązuje aplikacja, jest rozproszenie informacji o klientach w różnych dokumentach i arkuszach kalkulacyjnych. CRM pozwoli zebrać wszystkie najważniejsze dane w jednym miejscu.

## Planowane funkcjonalności

W przyszłości aplikacja będzie oferować następujące możliwości:

- **Rejestracja i logowanie użytkowników** – bezpieczny dostęp do systemu.
- **Zarządzanie klientami (CRUD)** – dodawanie, wyświetlanie, edytowanie i usuwanie klientów.
- **Wyszukiwanie klientów** – szybkie odnajdywanie klientów po nazwie, adresie e-mail lub numerze telefonu.
- **Zarządzanie kontaktami** – przechowywanie danych kontaktowych klientów.
- **Historia współpracy** – zapisywanie spotkań, rozmów i innych interakcji.
- **Zarządzanie zadaniami** – tworzenie zadań i przypisywanie terminów.
- **Dashboard** – panel główny prezentujący najważniejsze informacje i statystyki.
- **Filtrowanie i sortowanie** – łatwiejsze zarządzanie bazą klientów.
- **Responsywny interfejs** – możliwość korzystania z aplikacji na komputerach, tabletach i telefonach.

## Technologie docelowe

W projekcie planowane jest wykorzystanie następujących technologii:

**Backend:**
- Python – główny język programowania.
- FastAPI – tworzenie API i obsługa logiki aplikacji.
- SQLAlchemy – komunikacja z bazą danych.
- PostgreSQL – przechowywanie danych.
- JWT – uwierzytelnianie użytkowników.

**Frontend:**
- React.js – budowanie interfejsu użytkownika.
- JavaScript – logika aplikacji frontendowej.
- HTML5 – struktura stron.
- CSS3 – wygląd i stylowanie aplikacji.
- Axios – komunikacja z backendem.

**Narzędzia dodatkowe:**
- Git i GitHub – kontrola wersji projektu.
- Visual Studio Code – środowisko programistyczne.
- npm – zarządzanie zależnościami frontendu.
- Swagger – dokumentacja i testowanie API.

## Aktualny stan projektu

Projekt znajduje się na etapie planowania i przygotowania struktury aplikacji.

Na obecnym etapie:
- Określono główny cel aplikacji CRM.
- Zaplanowano podstawowe funkcjonalności systemu.
- Wybrano technologie do realizacji projektu.
- Określono podział aplikacji na frontend (React) i backend (Python).

**Do wykonania:**
- Przygotowanie struktury projektu.
- Konfiguracja środowiska Python i React.
- Utworzenie backendu i API.
- Konfiguracja bazy danych.
- Stworzenie interfejsu użytkownika.
- Implementacja poszczególnych funkcjonalności.
- Testowanie i poprawianie błędów.


## Uruchamianie

### Aktualny stan — P00

Aplikacja CRM nie jest jeszcze zaimplementowana.
Obecnie dostępne jest repozytorium Git oraz środowisko
programistyczne Python.

### Otwieranie projektu

1. Uruchom PyCharm.
2. Wybierz File > Open.
3. Otwórz katalog crm-python-react.
4. Ustaw interpreter projektu na:
   .venv\Scripts\python.exe

### Sprawdzenie interpretera

W terminalu PowerShell, w katalogu projektu, wykonaj:

    .\.venv\Scripts\python.exe --version

Oczekiwany rezultat: Python 3.12.x.

### Kolejne etapy

Backend FastAPI, baza PostgreSQL i frontend React
zostaną zaimplementowane podczas kolejnych bloków kursu.

Instrukcje uruchamiania aplikacji zostaną dodane
po wdrożeniu i przetestowaniu tych komponentów.


**1. Uruchomienie backendu (Python)**

Przejdź do folderu backend:

```bash
cd backend
```

Utwórz środowisko wirtualne:

```bash
python -m venv venv
```

Aktywuj środowisko:

Windows:
```bash
venv\Scripts\activate
```

Linux / macOS:
```bash
source venv/bin/activate
```

Zainstaluj zależności:

```bash
pip install -r requirements.txt
```

Uruchom serwer:

```bash
uvicorn main:app --reload
```

Backend będzie dostępny pod adresem:

`http://127.0.0.1:8000`

Dokumentacja API:

`http://127.0.0.1:8000/docs`

**2. Uruchomienie frontendu (React)**

Przej