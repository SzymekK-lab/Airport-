# ✈️ Airport Management System

### Kompleksowy system zarządzania portem lotniczym

![Status](https://img.shields.io/badge/Status-In%20Development-orange)
![Java](https://img.shields.io/badge/Java-21%2B-red)
![Spring Boot](https://img.shields.io/badge/Spring%20Boot-Backend-brightgreen)
!(https://img.shields.io/badge/React-Frontend-blue)[React]
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue)
![Team](https://img.shields.io/badge/Team-7%20Members-purple)

---

## 1. Opis projektu

**Airport Management System** to rozbudowany system informatyczny przeznaczony do kompleksowego zarządzania portem lotniczym. Projekt zakłada stworzenie zintegrowanego środowiska, które umożliwi obsługę pasażerów, zarządzanie operacjami lotniczymi oraz koordynowanie pracy wszystkich najważniejszych działów lotniska.

System będzie obejmował zarówno funkcjonalności dostępne dla klientów korzystających z usług lotniska, jak i rozbudowane panele przeznaczone dla pracowników, administratorów oraz kadry zarządzającej.

Głównym założeniem jest odwzorowanie funkcjonowania rzeczywistego portu lotniczego – od rezerwacji biletu i odprawy online, przez obsługę bagażu i operacje naziemne, aż po wieżę kontroli lotów, służby ratunkowe i zarządzanie infrastrukturą.

Projekt będzie rozwijany przez siedmioosobowy zespół, w którym każdy członek odpowiada za określony obszar funkcjonalny systemu.

## 2. Główne cele projektu

Najważniejsze cele przedsięwzięcia:

- Stworzenie kompleksowego systemu zarządzania portem lotniczym.
- Zapewnienie pasażerom możliwości samodzielnej obsługi podróży.
- Implementacja rezerwacji i zakupu biletów lotniczych.
- Zapewnienie pełnej obsługi odprawy online (Online Check-in).
- Wdrożenie elektronicznych kart pokładowych z kodami QR.
- Umożliwienie zarządzania lotami, samolotami i liniami lotniczymi.
- Odwzorowanie pracy wieży kontroli lotów.
- Zarządzanie personelem oraz harmonogramami pracy.
- Obsługa bagażu i operacji naziemnych.
- Zarządzanie bezpieczeństwem oraz służbami ratunkowymi.
- Integracja wszystkich modułów w jednym środowisku.
- Zapewnienie bezpieczeństwa, spójności i poprawności przetwarzanych danych.

## 3. Główne obszary systemu

System będzie składał się z dwóch podstawowych części.

### 3.1. System dla klientów lotniska

Część przeznaczona dla pasażerów korzystających z usług portu lotniczego.

Obejmuje:

**Konta pasażerów**
- Rejestracja i logowanie.
- Odzyskiwanie hasła.
- Edycja danych osobowych.
- Zarządzanie danymi kontaktowymi.
- Historia podróży.
- Zarządzanie profilami współpasażerów.

**Wyszukiwanie lotów**
- Wybór lotniska wylotu i przylotu.
- Wybór daty podróży.
- Określenie liczby pasażerów.
- Wyszukiwanie dostępnych połączeń.
- Filtrowanie i porównywanie lotów.
- Informacje o czasie podróży i przesiadkach.

**Rezerwacje i zakup biletów**
- Wybór połączenia.
- Wybór klasy podróży.
- Wybór taryfy.
- Wprowadzanie danych pasażerów.
- Wybór usług dodatkowych.
- Rezerwacja biletów.
- Generowanie numeru rezerwacji PNR.
- Symulacja płatności.
- Potwierdzenie zakupu.
- Zmiana i anulowanie rezerwacji.

**Online Check-in**
- Wyszukiwanie rezerwacji.
- Weryfikacja danych pasażera.
- Sprawdzanie dostępności odprawy.
- Wybór miejsc w samolocie.
- Interaktywna mapa miejsc.
- Blokowanie zajętych miejsc.
- Odprawa kilku pasażerów.
- Generowanie kart pokładowych.
- Generowanie kodów QR.
- Pobieranie kart pokładowych w PDF.
- Historia wykonanych odpraw.

**Obsługa bagażu**
- Informacje o limitach bagażowych.
- Bagaż podręczny i rejestrowany.
- Dokupowanie dodatkowego bagażu.
- Rejestrowanie bagażu.
- Nadawanie etykiet.
- Śledzenie statusu bagażu.
- Zgłaszanie zagubionego lub uszkodzonego bagażu.

**Informacje o podróży**
- Aktualny status lotu.
- Godziny przylotów i odlotów.
- Numer terminala i bramki.
- Status boardingu.
- Informacje o opóźnieniach i odwołaniach.
- Powiadomienia o zmianach.

**Usługi lotniskowe**
- Interaktywna mapa terminala.
- Informacje o punktach usługowych.
- Lokalizacja restauracji i sklepów.
- Rezerwacja parkingu.
- Informacje o transporcie.
- Dostęp do saloników VIP.
- Zamawianie asysty.
- Obsługa pasażerów o ograniczonej mobilności.

**Obsługa klienta**
- Formularz kontaktowy.
- Reklamacje.
- Zgłaszanie problemów.
- Status zgłoszenia.
- Historia korespondencji.
- FAQ.

### 3.2. System wewnętrzny lotniska

Część przeznaczona dla pracowników, kierowników, administratorów oraz służb operacyjnych.

Obejmuje:

**Operacje lotnicze i ATC**
- Zarządzanie liniami lotniczymi.
- Rejestracja samolotów.
- Zarządzanie flotą.
- Rozkłady lotów.
- Przyloty i odloty.
- Pasy startowe i drogi kołowania.
- Stanowiska postojowe.
- Opóźnienia i odwołania.
- Panel kontrolera ruchu lotniczego.
- Symulacja operacji ATC.

**Terminal i obsługa pasażerów**
- Stanowiska check-in.
- Obsługa odprawy na lotnisku.
- Weryfikacja kart pokładowych.
- Zarządzanie bramkami.
- Boarding.
- Listy pasażerów.
- Informowanie podróżnych.
- Tablice informacji lotniskowej FIDS.

**Obsługa naziemna**
- Załadunek i rozładunek bagażu.
- Sortownia bagażu.
- Transport bagażu.
- Tankowanie samolotów.
- Catering.
- Holowanie samolotów.
- Obsługa techniczna przed odlotem.
- Zarządzanie sprzętem naziemnym.

**Personel i administracja**
- Rejestracja pracowników.
- Struktura organizacyjna.
- Zarządzanie działami i stanowiskami.
- Grafiki i zmiany.
- Urlopy i nieobecności.
- Ewidencja czasu pracy.
- Uprawnienia i szkolenia.
- Przydzielanie zadań.

**Sprzątanie i utrzymanie infrastruktury**
- Harmonogramy sprzątania.
- Przydzielanie stref.
- Kontrola wykonania zadań.
- Zarządzanie środkami czystości.
- Zgłaszanie usterek.
- Przydzielanie techników.
- Naprawy i konserwacja.
- Ewidencja wyposażenia.
- Historia awarii.

**Bezpieczeństwo i ratownictwo**
- Ochrona lotniska.
- Kontrola dostępu.
- Przepustki.
- Strefy zastrzeżone.
- Rejestrowanie incydentów.
- Obsługa alarmów.
- Straż pożarna.
- Ratownictwo medyczne.
- Zespoły reagowania kryzysowego.
- Procedury ewakuacyjne.
- Raportowanie interwencji.

**Usługi i zarządzanie komercyjne**
- Restauracje i sklepy.
- Wynajem powierzchni.
- Parking.
- Usługi dodatkowe.
- Salony VIP.
- Przychody i koszty operacyjne.
- Raporty finansowe.

**Zarządzanie lotniskiem**
- Panel dyrektora.
- Statystyki lotów.
- Liczba pasażerów.
- Liczba operacji lotniczych.
- Liczba opóźnień.
- Obciążenie terminali.
- Wykorzystanie infrastruktury.
- Raporty poszczególnych działów.

---

# 4. Podział obowiązków w zespole

Projekt realizowany jest przez siedem osób. Każdy członek zespołu odpowiada za określony obszar funkcjonalny, jego analizę, projekt, implementację, testowanie oraz dokumentację.

## Osoba 1 – Loty, linie lotnicze i wieża kontroli lotów (ATC)

**Główny zakres odpowiedzialności:** zarządzanie operacjami lotniczymi oraz odwzorowanie pracy wieży kontroli lotów.

### Zadania funkcjonalne

1. Zarządzanie liniami lotniczymi.
2. Rejestracja samolotów i floty.
3. Przechowywanie parametrów technicznych samolotów.
4. Tworzenie i zarządzanie rozkładami lotów.
5. Zarządzanie przylotami.
6. Zarządzanie odlotami.
7. Przydzielanie pasów startowych.
8. Zarządzanie drogami kołowania.
9. Przydzielanie stanowisk postojowych.
10. Obsługa opóźnień.
11. Obsługa odwołanych lotów.
12. Panel kontrolera ruchu lotniczego.
13. Rejestrowanie komunikatów operacyjnych.
14. Symulacja operacji ATC.
15. Historia operacji lotniczych.

### Zadania projektowe i programistyczne

- Analiza procesów operacji lotniczych.
- Przygotowanie diagramów BPMN.
- Przygotowanie diagramów UML.
- Zaprojektowanie tabel i relacji modułu.
- Implementacja logiki biznesowej w Javie.
- Wykorzystanie Spring Boot.
- Przygotowanie interfejsów użytkownika.
- Integracja z pozostałymi modułami.
- Przygotowanie testów.
- Dokumentacja techniczna.

### Technologie

- Java
- Spring Boot
- SQL
- PostgreSQL
- React i TypeScript – w zakresie interfejsów modułu

---

## Osoba 2 – Klient, wyszukiwanie lotów, rezerwacje i płatności

**Główny zakres odpowiedzialności:** stworzenie systemu obsługi klienta od wejścia na stronę lotniska do zakupu biletu.

### Zadania funkcjonalne

1. Publiczna strona internetowa lotniska w części pasażerskiej.
2. Rejestracja klienta.
3. Logowanie i wylogowanie.
4. Odzyskiwanie hasła.
5. Profil pasażera.
6. Wyszukiwarka połączeń.
7. Filtrowanie lotów.
8. Wybór połączenia.
9. Wybór klasy podróży.
10. Wybór taryfy.
11. Wprowadzanie danych pasażerów.
12. Rezerwacja biletów.
13. Generowanie numeru PNR.
14. Symulacja płatności.
15. Potwierdzenie zakupu.
16. Zarządzanie rezerwacjami.
17. Anulowanie rezerwacji.
18. Zmiana rezerwacji.
19. Historia podróży.
20. Dokupowanie usług dodatkowych.

### Zadania projektowe i programistyczne

- Analiza procesów zakupowych.
- Przygotowanie diagramów BPMN i UML.
- Zaprojektowanie modelu danych klientów i rezerwacji.
- Przygotowanie interfejsu strony internetowej.
- Implementacja logiki biznesowej.
- Integracja z modułem lotów.
- Integracja z modułem online check-in.
- Przygotowanie testów.
- Dokumentacja techniczna.

### Technologie

- Java
- Spring Boot
- TypeScript
- React
- HTML5
- CSS3
- SQL
- PostgreSQL

---

## Osoba 3 – Online Check-in, terminal i boarding

**Główny zakres odpowiedzialności:** obsługa pasażera od momentu odprawy online aż do wejścia na pokład samolotu.

Jest to jeden z kluczowych modułów projektu, ze względu na wymaganie prowadzącego dotyczące pełnej możliwości odprawy online.

### Zadania funkcjonalne

1. Online check-in.
2. Weryfikacja rezerwacji.
3. Weryfikacja pasażera.
4. Sprawdzanie dostępności odprawy.
5. Wybór miejsca w samolocie.
6. Interaktywna mapa miejsc.
7. Blokowanie zajętych miejsc.
8. Odprawa wielu pasażerów.
9. Generowanie kart pokładowych.
10. Generowanie kodów QR.
11. Pobieranie kart pokładowych w PDF.
12. Obsługa odprawy na lotnisku.
13. Zarządzanie stanowiskami check-in.
14. Zarządzanie bramkami.
15. Weryfikacja kart pokładowych.
16. Obsługa boardingu.
17. Lista pasażerów na pokładzie.
18. Aktualizacja statusu wejścia na pokład.
19. Informacje o terminalach i bramkach.
20. Tablice przylotów i odlotów FIDS.
21. Interaktywna mapa terminala.
22. Informacje dla pasażerów.

### Zadania projektowe i programistyczne

- Analiza procesów odprawy i boardingu.
- Przygotowanie diagramów BPMN.
- Przygotowanie diagramów UML.
- Zaprojektowanie modelu danych miejsc i kart pokładowych.
- Przygotowanie interfejsu klienta i pracownika.
- Implementacja modułu.
- Integracja z rezerwacjami i lotami.
- Przygotowanie testów.
- Dokumentacja techniczna.

### Technologie

- Java
- Spring Boot
- TypeScript
- React
- HTML5
- CSS3
- SQL
- PostgreSQL

---

## Osoba 4 – Bagaż, transport i obsługa naziemna

**Główny zakres odpowiedzialności:** zarządzanie bagażem oraz wszystkimi najważniejszymi procesami związanymi z obsługą samolotów na ziemi.

### Zadania funkcjonalne

1. Obsługa bagażu podręcznego.
2. Obsługa bagażu rejestrowanego.
3. Zarządzanie limitami bagażowymi.
4. Nadawanie bagażu.
5. Generowanie etykiet bagażowych.
6. Zarządzanie sortownią bagażu.
7. Transport bagażu.
8. Śledzenie statusu bagażu.
9. Obsługa zagubionego bagażu.
10. Obsługa uszkodzonego bagażu.
11. Załadunek samolotu.
12. Rozładunek samolotu.
13. Tankowanie.
14. Catering.
15. Obsługa techniczna samolotu przed odlotem.
16. Holowanie samolotów.
17. Transport sprzętu naziemnego.
18. Ewidencja pojazdów.
19. Przydzielanie pracowników do operacji.
20. Harmonogram obsługi samolotów.

### Zadania projektowe i programistyczne

- Analiza procesów obsługi naziemnej.
- Przygotowanie diagramów BPMN i UML.
- Zaprojektowanie modelu danych bagażu i sprzętu.
- Przygotowanie interfejsu pracownika.
- Implementacja modułu.
- Integracja z lotami i odprawą.
- Przygotowanie testów.
- Dokumentacja techniczna.

### Technologie

- Java
- Spring Boot
- SQL
- PostgreSQL
- React i TypeScript – w zakresie interfejsów modułu

---

## Osoba 5 – Personel, sprzątanie i infrastruktura techniczna

**Główny zakres odpowiedzialności:** zarządzanie pracownikami lotniska, organizacją ich pracy oraz utrzymaniem czystości i sprawności technicznej obiektów.

### Zadania funkcjonalne

1. Struktura organizacyjna lotniska.
2. Rejestracja pracowników.
3. Profile pracowników.
4. Zarządzanie stanowiskami i działami.
5. Zarządzanie grafikami.
6. Zarządzanie zmianami pracowniczymi.
7. Urlopy i nieobecności.
8. Ewidencja czasu pracy.
9. Uprawnienia i szkolenia.
10. Pracownicy sprzątający.
11. Przydzielanie stref sprzątania.
12. Harmonogramy sprzątania.
13. Kontrola wykonania zadań.
14. Zarządzanie środkami czystości.
15. Pracownicy techniczni.
16. Zgłaszanie usterek.
17. Przydzielanie napraw.
18. Konserwacja urządzeń.
19. Historia awarii.
20. Ewidencja wyposażenia technicznego.

### Zadania projektowe i programistyczne

- Opracowanie struktury organizacyjnej.
- Analiza procesów HR i utrzymania lotniska.
- Przygotowanie diagramów BPMN i UML.
- Zaprojektowanie modelu danych pracowników i zadań.
- Przygotowanie interfejsu pracownika i kierownika.
- Implementacja modułu.
- Integracja z pozostałymi modułami.
- Przygotowanie testów.
- Dokumentacja techniczna.

### Technologie

- Java
- Spring Boot
- SQL
- PostgreSQL
- React i TypeScript – w zakresie interfejsów modułu

---

## Osoba 6 – Bezpieczeństwo, ratownictwo i usługi lotniskowe

**Główny zakres odpowiedzialności:** zapewnienie bezpieczeństwa lotniska, obsługa sytuacji awaryjnych oraz zarządzanie wybranymi usługami dostępnymi dla pasażerów.

### Zadania funkcjonalne

1. Zarządzanie ochroną lotniska.
2. Kontrola dostępu.
3. Przepustki pracownicze.
4. Zarządzanie strefami zastrzeżonymi.
5. Rejestrowanie incydentów.
6. Obsługa alarmów.
7. Straż pożarna lotniskowa.
8. Ratownictwo medyczne.
9. Zespoły reagowania kryzysowego.
10. Rejestrowanie interwencji.
11. Procedury ewakuacyjne.
12. Zgłoszenia zagrożeń.
13. Obsługa reklamacji pasażerów.
14. Formularze zgłoszeń i kontakt z klientem.
15. Punkt rzeczy znalezionych.
16. Asysta dla osób z niepełnosprawnościami.
17. Obsługa VIP.
18. Salony VIP.
19. Restauracje i sklepy.
20. Parking lotniskowy.
21. Rezerwacja miejsc parkingowych.
22. Wynajem powierzchni komercyjnych.

### Zadania projektowe i programistyczne

- Analiza procesów bezpieczeństwa i usług.
- Przygotowanie diagramów BPMN i UML.
- Zaprojektowanie modelu danych incydentów i usług.
- Przygotowanie interfejsów pracowników.
- Implementacja modułu.
- Integracja z pozostałymi modułami.
- Przygotowanie testów.
- Dokumentacja techniczna.

### Technologie

- Java
- Spring Boot
- SQL
- PostgreSQL
- Docker – w zakresie wspólnego środowiska technicznego
- React i TypeScript – w zakresie interfejsów modułu

Dodatkowo osoba 6 koordynuje uzgodnienia dotyczące wspólnej infrastruktury aplikacyjnej, bazy danych i mechanizmów logowania, we współpracy z pozostałymi członkami zespołu.

---

## Osoba 7 – Kierownik projektu

**Główny zakres odpowiedzialności:** organizacja pracy zespołu, kontrola postępów, spójność projektu oraz przygotowanie głównego panelu zarządzania lotniskiem.

Zakres programistyczny został celowo ograniczony, aby kierownik mógł skupić się na koordynacji całego przedsięwzięcia.

### Zadania organizacyjne

1. Przygotowanie głównego opisu projektu.
2. Określenie celu i zakresu systemu.
3. Przygotowanie ogólnego harmonogramu.
4. Przydzielanie i koordynowanie zadań.
5. Organizowanie spotkań zespołu.
6. Kontrolowanie postępów prac.
7. Zbieranie dokumentacji od poszczególnych osób.
8. Pilnowanie spójności dokumentacji.
9. Koordynowanie integracji modułów.
10. Przygotowanie końcowej prezentacji projektu.

### Zadania programistyczne

Przygotowanie prostego dashboardu dyrektora lotniska.

Dashboard będzie prezentował podstawowe informacje o funkcjonowaniu całego portu lotniczego:

- Liczbę dzisiejszych lotów.
- Liczbę pasażerów.
- Liczbę opóźnionych lotów.
- Liczbę aktywnych pracowników.
- Liczbę zgłoszonych incydentów.
- Podstawowe statystyki lotniska.

Dashboard będzie korzystał z danych udostępnianych przez pozostałe moduły.

### Technologie

- TypeScript
- React
- HTML5
- CSS3

---

# 5. Wspólne zadania techniczne

Aby uniknąć powstawania niezależnych i niekompatybilnych części systemu, wszystkie moduły będą rozwijane według wspólnych standardów.

| Zadanie | Odpowiedzialność |
|---|---|
| Projekt wspólnej bazy danych | Osoba 6 koordynuje, wszyscy projektują swoje tabele |
| Serwer aplikacyjny | Osoba 6 koordynuje, zespół uzgadnia wymagania |
| Logika backendu | Każdy odpowiada za swój moduł |
| REST API | Każdy odpowiada za swoje endpointy |
| Wspólne logowanie i role | Osoba 6 koordynuje |
| Projekt interfejsów | Każdy odpowiada za swój moduł |
| Implementacja modułów | Każdy odpowiada za swój moduł |
| Integracja | Wszyscy, pod nadzorem osoby 6 |
| Testy jednostkowe | Każdy odpowiada za swój moduł |
| Testy integracyjne | Cały zespół, koordynuje kierownik |
| Dokumentacja | Każdy dokumentuje swoją część |

---

# 6. Technologie wykorzystywane w projekcie

Projekt będzie realizowany z wykorzystaniem następującego stosu technologicznego.

| Technologia | Zastosowanie |
|---|---|
| Java 21 LTS | Główny język backendu |
| Spring Boot | Tworzenie backendu i REST API |
| TypeScript | Logika frontendowa |
| React | Interfejs użytkownika |
| HTML5 | Struktura stron internetowych |
| CSS3 | Stylowanie interfejsów |
| PostgreSQL | Relacyjna baza danych |
| SQL | Operacje na bazie danych |
| Docker | Konteneryzacja i wspólne środowisko |
| Git | Kontrola wersji |
| GitHub | Współpraca zespołowa i zarządzanie kodem |

### Założenia technologiczne

- Backend zostanie opracowany w Javie z wykorzystaniem Spring Boot.
- Frontend będzie oparty na React i TypeScript.
- Pasażerowie oraz pracownicy będą korzystać z interfejsów dostępnych przez przeglądarkę.
- PostgreSQL będzie wspólnym systemem zarządzania bazą danych.
- Komunikacja pomiędzy frontendem i backendem będzie realizowana przez REST API.
- System zostanie podzielony na logiczne moduły w ramach jednej aplikacji backendowej.
- Docker ułatwi uruchamianie wspólnego środowiska programistycznego.

---

# 7. Zasady współpracy zespołu

W celu zapewnienia sprawnej realizacji projektu obowiązują następujące zasady:

1. Każdy członek zespołu odpowiada za przydzielony mu obszar.
2. Każdy realizuje analizę, projekt, implementację, testy i dokumentację swojej części.
3. Wszystkie moduły muszą być zgodne ze wspólną architekturą systemu.
4. Nie tworzymy niezależnych aplikacji – rozwijamy jeden zintegrowany system.
5. Zmiany wpływające na inne moduły muszą być wcześniej uzgodnione.
6. Każdy członek zespołu regularnie aktualizuje postęp prac.
7. Kod źródłowy przechowujemy we wspólnym repozytorium GitHub.
8. Przed połączeniem zmian z główną gałęzią przeprowadzamy przegląd kodu.
9. Każdy moduł powinien być możliwy do samodzielnego przetestowania.
10. Integrację przeprowadzamy stopniowo, a nie dopiero na końcu projektu.

## 8. Wymagane rezultaty pracy każdego członka zespołu

Każda osoba odpowiedzialna za moduł (osoby 1–6) musi przygotować:

- Analizę swojego obszaru.
- Opis funkcjonalności.
- Wymagania funkcjonalne.
- Wymagania niefunkcjonalne.
- Diagramy BPMN.
- Odpowiednie diagramy UML.
- Projekt modelu danych.
- Projekt interfejsu użytkownika.
- Implementację modułu.
- Testy funkcjonalne i jednostkowe.
- Dokumentację techniczną.

Kierownik projektu odpowiada za dokumentację ogólną, harmonogram, integrację, kontrolę jakości i końcową prezentację.

---

# 9. Przykładowy scenariusz integracji systemu

Jednym z głównych założeń jest zapewnienie współpracy wszystkich modułów.

Przykładowy scenariusz przedstawia pełną podróż pasażera:

1. **Rezerwacja biletu – Osoba 2:** pasażer zakłada konto, wyszukuje połączenie i kupuje bilet.
2. **Zarządzanie lotem – Osoba 1:** system udostępnia informacje o locie, samolocie i harmonogramie.
3. **Online Check-in – Osoba 3:** pasażer odprawia się online, wybiera miejsce i otrzymuje kartę pokładową z kodem QR.
4. **Obsługa bagażu – Osoba 4:** bagaż zostaje zarejestrowany, oznaczony i przekazany do obsługi naziemnej.
5. **Personel – Osoba 5:** system zapewnia przydział pracowników do odpowiednich zadań.
6. **Bezpieczeństwo – Osoba 6:** system obsługuje zgłoszenia, kontrolę dostępu i ewentualne incydenty.
7. **Zarządzanie – Osoba 7:** kierownik ma możliwość obserwowania podstawowych statystyk i przebiegu działania lotniska.

---

# 10. Granice i założenia symulacji

Projekt ma odwzorowywać funkcjonowanie dużego portu lotniczego, jednak nie będzie rzeczywistym systemem certyfikowanym do prowadzenia operacji lotniczych.

Wybrane funkcjonalności zostaną zrealizowane jako symulacje, w szczególności:

- Płatności i zwroty środków.
- Operacje wieży kontroli lotów (ATC).
- Śledzenie bagażu.
- Komunikacja z liniami lotniczymi.
- Procedury ratunkowe.
- Niektóre usługi dodatkowe.

Dzięki temu możliwe będzie zaprezentowanie pełnych procesów biznesowych bez konieczności podłączania rzeczywistej infrastruktury lotniskowej.

---

# 11. Cel końcowy

Rezultatem projektu ma być jeden spójny, rozbudowany system informatyczny, który odwzorowuje funkcjonowanie dużego portu lotniczego.

System powinien umożliwiać zarówno samodzielną obsługę podróży przez pasażera, jak i zarządzanie wszystkimi najważniejszymi procesami wewnętrznymi lotniska.

**Naszym celem nie jest stworzenie kilku niezależnych formularzy, lecz zintegrowanego środowiska, w którym poszczególne działy lotniska współpracują ze sobą i wymieniają dane w ramach jednego systemu.**

---

*Projekt realizowany zespołowo przez 7 osób. Każdy członek zespołu odpowiada za określony obszar funkcjonalny, a kierownik projektu nadzoruje całość przedsięwzięcia.*
