# Dokumentacja Wymagań

## Wymagania niefunkcjonalne
* Kontrola dostępu - system powinien ograniczać dostęp do funkcji na podstawie roli użytkownika
* Dostępność - system dostępny podczas codziennej pracy magazynu
* Wydajność - system ma działać szybko, niezauważalnie
* Sposób korzystania - system powinien umożliwiać szybkie wykonywanie podstawowych operacji magazynowych, takich jak wyszukiwanie, przyjmowanie i wydawanie towaru
* Bezpieczeństwo - indywidualne loginy i hasła dla użytkowników
* Kontrola stanów magazynowych - system powinien uniemożliwiać wydanie ilości przekraczającej aktualny stan
* Prostota - czytelny, prosty interfejs programu

## Aktorzy
* Administrator - zarządza kontami użytkowników, hasłami oraz uprawnieniami
* Magazynier - loguje się do systemu, wyszukuje produkty, sprawdza ich lokalizację, przyjmuje dostawy oraz wydaje towary
* Kierownik magazynu - ma dostęp do stanów magazynowych, zarządza produktami oraz przegląda historię i raporty magazynowe

## Wymagania funkcjonalne
* Zarządzanie użytkownikami - umożliwia tworzenie, edytowanie i usuwanie kont użytkowników oraz zmianę ich haseł i uprawnień
* Lokalizacja - przypisanie produktu do sektora, regału i półki
* Raporty magazynowe - generowanie i przeglądanie raportów dotyczących stanów oraz operacji magazynowych
* Logowanie - osobne konta dla każdego użytkownika
* Kontrola stanów - blokada wydania większej ilości niż dostępna
* Wydawanie towaru - rejestrowanie wydań i zmniejszanie stanu
* Produkty - dodawanie i wyszukiwanie po EAN, nazwie lub kategorii
* Historia operacji - zapis produktu, ilości, daty i użytkownika
* Przyjmowanie dostaw - rejestrowanie przyjęć i zwiększanie stanu
