# Formularz rejestracyjny – jQuery Validate

## Opis
Projekt zawiera formularz rejestracyjny z walidacją po stronie klienta
z wykorzystaniem wtyczki **jQuery Validate**.

## Użyte reguły walidacji

### Imię
- wymagane
- minimum 2 znaki

### Email
- wymagany
- poprawny format email

### Nazwa użytkownika
- wymagana
- minimum 3 znaki
- sprawdzana AJAX-em (czy nie istnieje w pliku JSON)

### Hasło
- wymagane
- minimum 6 znaków

### Powtórz hasło
- wymagane
- musi być identyczne jak pierwsze hasło

### Wiek
- wymagany
- tylko cyfry
- minimum 18 lat
