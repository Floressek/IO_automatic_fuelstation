### LAB1 - contents: (pkt 1 i 2)

Zamawiający, czyli firma "PSO", będąca liderem w branży nowoczesnych technologii paliwowych, 
poszukuje wykonawcy do zaprojektowania i wdrożenia kompleksowego systemu informatycznego dla naszej nowej sieci bezobsługowych stacji paliw.
System ten ma na celu automatyzację wszystkich procesów związanych z obsługą klientów oraz zarządzaniem wewnętrznymi zasobami firmy.
Nasza wizja zakłada stworzenie nowej jakości usług w sektorze stacji paliw, gdzie klienci mogą korzystać z naszych usług w pełni automatycznie,
bez potrzeby interakcji z personelem.

### Moduł Obsługi Klienta (Wewnętrzne)
1. Aplikacja mobilna umożliwiająca lokalizowanie najbliższych stacji, rezerwację dystrybutorów i dokonywanie płatności.
2. System identyfikacji pojazdów przy użyciu technologii RFID oraz rozpoznawania tablic rejestracyjnych.
3. Automatyczne fakturowanie i cyfrowe paragony wysyłane bezpośrednio do aplikacji klienta.
4. Personalizacja usług poprzez analizę historii tankowań i preferencji użytkowników, oferowanie spersonalizowanych promocji.
5. Interaktywne kioski do samoobsługowej płatności dla klientów nieposiadających aplikacji.
6. System wsparcia klienta zintegrowany z aplikacją, umożliwiający szybkie rozwiązywanie problemów i pytania użytkowników.
7. Zaawansowane metody uwierzytelniania, Wprowadzenie biometrycznych metod uwierzytelniania
8. Możliwość oceniania usług przez użytkowników: Umożliwienie klientom oceniania jakości usług i poszczególnych stacji, co 
   może pomóc w poprawie standardów oraz zwiększyć zaufanie klientów poprzez transparentność.
9. Wirtualny asystent AI do wsparcia klienta: Integracja chatbota wykorzystującego sztuczną inteligencję, który 
   będzie w stanie na bieżąco odpowiadać na pytania użytkowników i pomagać w rozwiązywaniu problemów.
10. Funkcjonalność umożliwiającą użytkownikom wybór preferowanej metody tankowania: zautomatyzowanej, z użyciem robota do tankowania,
   lub tradycyjnej, gdzie klient samodzielnie tankuje pojazd.

### Moduł Zarządzania Stacją (Zewnętrzne)
1. Panel zarządzania dla operatorów stacji umożliwiający monitorowanie i kontrolę stanu dystrybutorów, poziomu paliw w zbiornikach i danych transakcyjnych.
2. Automatyczne generowanie raportów sprzedaży, analizy efektywności promocji i preferencji klientów.
3. System zarządzania zapasami i automatyczne zamawianie paliwa w oparciu o przewidywane zapotrzebowanie.
4. Moduł bezpieczeństwa monitorujący stacje pod kątem potencjalnych awarii, wycieków oraz nieautoryzowanego dostępu.
5. Integracja z systemami alarmowymi i powiadomieniami awaryjnymi, zapewniająca szybką reakcję na incydenty.
6. Zarządzanie zużyciem energii: Optymalizacja zużycia energii na stacjach poprzez inteligentne zarządzanie oświetleniem, pompami i innymi urządzeniami,
   co przyczynia się do obniżenia kosztów operacyjnych i wsparcia inicjatyw ekologicznych.
7. Integracja z Google Ads dla spersonalizowanych reklam: Wykorzystanie danych z Google Ads przy podjeździe klienta do stacji, umożliwiające 
   wyświetlanie spersonalizowanych reklam na ekranach stacji na podstawie historii wyszukiwania i preferencji, zwiększając skuteczność kampanii reklamowych.

### Wymagania Techniczne
1. System powinien być oparty na architekturze mikrousług, z wykorzystaniem najnowszych technologii cloud computing.
2. Wysoki poziom bezpieczeństwa danych, z zastosowaniem szyfrowania i zabezpieczeń przed nieautoryzowanym dostępem.
3. Elastyczność i skalowalność systemu, umożliwiająca łatwą rozbudowę o nowe stacje paliw oraz funkcjonalności.
4. Kompatybilność z różnymi systemami płatności elektronicznych i bankowości mobilnej.
5. Możliwość integracji systemu z zewnętrznymi dostawcami usług, np. systemami zarządzania flotą pojazdów.

### Przypadki Użycia (Use Cases)
1. Rezerwacja dystrybutora i tankowanie przez klienta.
2. Automatyczne rozliczenie transakcji i wysyłanie faktury do klienta.
3. Zarządzanie promocjami i ofertami specjalnymi dla zarejestrowanych użytkowników.
4. Monitorowanie stanu zbiorników paliw i automatyczne zamawianie dostaw.
5. Integracja z systemami alarmowymi i powiadomieniami awaryjnymi, zapewniająca szybką reakcję na incydenty.
6. Panel wystawiania faktur

### Dalsze Wymagania i Oczekiwania

6. **Optymalizacja procesu tankowania:** System powinien minimalizować czas potrzebny na tankowanie, oferując klientom możliwość szybkiego powrotu na drogę.
7. **Analiza danych i sztuczna inteligencja:** Wykorzystanie algorytmów AI do analizy danych zbieranych przez system, w celu optymalizacji procesów logistycznych i
   zapewnienia maksymalnej efektywności operacyjnej.
9. **Eko-inicjatywy:** Integracja funkcji wspierających ekologiczne inicjatywy, takich jak promowanie tankowania paliw alternatywnych oraz analiza śladu węglowego
    generowanego przez użytkowników stacji.
11. **Personalizacja doświadczeń klientów:** Rozwój funkcji personalizacji w aplikacji mobilnej, tak aby każdy klient czuł, że oferta "FuelFuture" jest dostosowana do
    jego indywidualnych potrzeb i preferencji.
13. **Zarządzanie awariami i utrzymanie:** Implementacja zaawansowanego systemu monitorowania urządzeń, który pozwoli na szybką diagnostykę i reakcję na ewentualne
    awarie lub potrzeby konserwacyjne, minimalizując przestoje w dostępności dystrybutorów.

### LAB2 - contents (pkt 3 i 4):

# Analiza czasownikowo-rzeczownikowa projektu

Analiza czasownikowo-rzeczownikowa jest techniką analityczną stosowaną w projektowaniu systemów informatycznych, która polega
na przeszukiwaniu dokumentacji(u nas zawartość lab1) projektu w celu znaleźenia czasownikow i rzeczowników. Czasowniki w tym 
kontekście pełnią rolę reprezentacji działania lub operacji, które użytkownik może wykonywać za pośrednictwem systemu, zaś rzeczowniki 
odnoszą się do obieków systemu, na których działania te są wykonywane. Proces ten umożliwia szybkie i jawne zidentyfikownie głowych 
funkcjonalności, które system ma oferować, oraz kluczowych elementów tegoż systemu tj. moduły, dane czy zasoby z którymi funkcje są związane. 
To sprawia, że analiza czasownikowo-rzeczownikowa jest cennym narzędziem na wczesnym etapie projektowania, pomagającym w strukturyzacji wymagań
i lepszym zrozumieniu zakresu projektu.


Oto szczegółowe podejście:

## Wyodrębnienie czasownikowo-rzeczownikowe:

### Projektowanie i wdrożenie systemu informatycznego dla sieci bezobsługowych stacji paliw:
- **Czasowniki**: "zaprojektowania" i "wdrożenia"
- **Rzeczowniki**: "systemu informatycznego", "sieci bezobsługowych stacji paliw"

### Automatyzacja procesów związanych z obsługą klientów oraz zarządzaniem wewnętrznymi zasobami firmy:
- **Czasownik**: "automatyzację"
- **Rzeczowniki**: "procesów związanych z obsługą klientów", "zarządzaniem wewnętrznymi zasobami firmy"

### Stworzenie nowej jakości usług w sektorze stacji paliw:
- **Czasownik**: "stworzenie"
- **Rzeczownik**: "nowej jakości usług", "sektorze stacji paliw"

## Moduł Obsługi Klienta:

- **Czasownik**: "umożliwiająca", "identyfikacji", "automatyczne fakturowanie", "wysyłane", "personalizacja", "umożliwienie", "integracja", "wybór"
- **Rzeczowniki**: "aplikacji mobilnej", "najbliższych stacji", "rezerwacji dystrybutorów", "dokonywania płatności", "pojazdów", "technologii RFID", "robot do tankowania",
  "metoda tankowania", "automatyczne tankowanie","tablic rejestracyjnych", "cyfrowe paragony", "aplikacji klienta", "analizę historii tankowań", "preferencji użytkowników", "spersonalizowanych promocji",
  "klientom oceniania", "usług", "poszczególnych stacji", "chatbota", "sztuczną inteligencję", "preferowanej metody tankowania", 
  "zautomatyzowanej", "tradycyjnej"

## Moduł Zarządzania Stacją:

- **Czasowniki**: "monitorowanie i kontrolę", "automatyczne generowanie", "zarządzanie", "automatyczne zamawianie", "optymalizacja"
- **Rzeczowniki**: "panelu zarządzania", "operatorów stacji", "raportów sprzedaży", "analiz", "promocji", "preferencji klientów", "zapasami",
  "paliwa", "zużycia energii", "inteligentne zarządzanie", "oświetleniem", "pompami"

## Wymagania Techniczne:

- **Rzeczowniki**: "architekturze mikrousług", "technologii cloud computing", "szyfrowanie", "zabezpieczenia", "nieautoryzowanym dostępem", "elastyczność i skalowalność"

## Przypadki Użycia:

- **Rzeczowniki**: "rezerwacja dystrybutora", "tankowanie", "automatyczne rozliczenie", "transakcji", "monitorowanie", "zbiorników paliw", "automatyczne zamawianie dostaw"

## Dalsze Wymagania i Oczekiwania:

- **Czasownik**: "optymalizacja", "wykorzystanie", "integracja"
- **Rzeczowniki**: "procesu tankowania", "algorytmów AI", "analizy danych", "ekologiczne inicjatywy"

Ta szczegółowa analiza pozwala zrozumieć, jak system ma integrować i automatyzować różnorodne funkcje.

## Lista wymagań funkcjonalnych:

### Funkcjonalności Aplikacji Mobilnej:
- Lokalizowanie najbliższych stacji paliw.
- Rezerwacja dystrybutorów paliw.
- Dokonywanie płatności za paliwo.

### System Identyfikacji i Autentykacji:
- Identyfikacja pojazdów przy użyciu technologii RFID.
- Rozpoznawanie tablic rejestracyjnych.
- Automatyczne fakturowanie i wysyłanie cyfrowych paragonów.
- Personalizacja usług na podstawie historii tankowań i preferencji użytkowników.

### Obsługa Klienta i Interaktywność:
- Interaktywne kioski do samoobsługowej płatności.
- Zintegrowany system wsparcia klienta w aplikacji mobilnej.
- Funkcja oceny jakości usług przez użytkowników.
- Wirtualny asystent AI do wsparcia klienta.

### Zarządzanie Stacją:
- Panel zarządzania dla operatorów stacji.
- Automatyczne generowanie raportów sprzedaży i analiz efektywności.
- System zarządzania zapasami i automatyczne zamawianie paliwa.
- Optymalizacja zużycia energii i zarządzanie zużyciem na stacji.

### Bezpieczeństwo i Monitoring:
- Monitorowanie stacji pod kątem potencjalnych awarii i wycieków.
- Integracja z systemami alarmowymi i powiadomieniami awaryjnymi.

### Integracja i Reklama:
- Integracja z Google Ads dla spersonalizowanych reklam.
- Możliwość wyświetlania reklam na ekranach stacji.

### Wymagania Techniczne Systemu:
- Architektura mikrousług i wykorzystanie cloud computing.
- Wysoki poziom bezpieczeństwa danych i szyfrowanie.
- Elastyczność i skalowalność systemu.
- Kompatybilność z różnymi systemami płatności elektronicznych.

## Lista Wymagań niefunkjonalnych:


### Dostępność/Niezawodność:
- aplikacja ma być dostępna dostępna przez 99.999% w roku
- aplikacja będzie dostępna przez określoną ilość lat

### Wydajność:
- maksymalna ilość użytkowników korzystających z aplikacji jednocześnie,
- maksymalna ilość czasu odpowiedzi aplikacji na zapytanie użytkownika,
- sposób, w jaki aplikacja korzysta z zasobów sprzętowych

### Wsparcie:
- maksymalny czas potrzebny do naprawienia błędów
- sposób testowania
- dostępność wsparcia techniczego i serwisowego

### Bezpieczeństwo:
- bezpieczeńśtwo przechowywania danych RODO
- pożądane sposoby zabezpieczenia aplikacji

### Użytecznośc aplikacji
- kolorystyka i design
- skalowaność wyglądu do rozmiaru ekranu
- kastominizacja wyglądu

### Zgodność prawna i regulacyjna:
- Spełnienie wszystkich obowiązujących wymogów prawnych i regulacyjnych 
związanych z działalnością stacji paliw oraz przetwarzaniem danych osobowych.

## Identyfikacja aktorów:
### Klient(Kluczowy Odbiorca)
Opis: 
Klienci stacji benzynowej bezdotykowej to osoby korzystające z pojazdów, które cenią sobie wygodę, 
szybkość i bezpieczeństwo przy tankowaniu. Mają kluczowe znaczenie dla projektu,
ponieważ sukces biznesowy zależy od ich zadowolenia i lojalności.
Są to osoby w różnym wieku, korzystające zarówno z pojazdów spalinowych, jak i elektrycznych, poszukujące efektywnych i nowoczesnych rozwiązań
Interakcje:
- Użycie Bezdotykowych Dystrybutorów Paliwa: Klienci korzystają z nowoczesnych, bezdotykowych dystrybutorów paliwa,
   które umożliwiają tankowanie bez konieczności fizycznego dotykania urządzenia.
  Interakcja odbywa się za pomocą aplikacji mobilnej lub systemów rozpoznawania pojazdów.
    Plan Zaangażowania Klienta:
-System feedbacku i ciągłej poprawy: Implementacja mechanizmu zbierania opinii od klientów po wizycie na stacji,
  co umożliwi bieżące dostosowywanie usług do ich potrzeb.
  
### Operator Stacji
Opis: 
Operatorzy są niezbędni do poprawnego funkjonowania stacji, ponieważ stacja musi być utrzymana w wysokim standardzie jakości
Interakcje:
- Utrzymanie Czystości i Bezpieczeństwa: Dbają o utrzymanie stacji w czystości i zgodności z normami bezpieczeństwa,
co jest kluczowe dla zapewnienia pozytywnego wrażenia klientów.
- Wsparcie Techniczne: Zapewnienie operatorom dostępu do wsparcia technicznego w przypadku problemów z systemem,
aby minimalizować przestoje i zakłócenia w dostępności usług.

### **System Zarządzania Flotą Pojazdów**
Opis: 
Zewnętrzny system używany przez firmy do monitorowania i zarządzania pojazdami,
mogący integrować się z systemem stacji    paliw w celu optymalizacji procesów tankowania i płatności.
Interakcje:
- Automatyczna identyfikacja pojazdów floty, rezerwacja dystrybutorów, automatyczne rozliczanie i fakturowanie.
  
### Administrator Systemu
Opis: 
Administrator Systemu jest odpowiedzialny za zarządzanie i konserwację infrastruktury IT stacji benzynowej,
w tym serwerów, oprogramowania oraz systemów bezpieczeństwa cyfrowego. 
Interakcje: 
- Reguralne łatki bezpieczeństwa, aby zapewnić niezawodność systemu.
  
### System Alarmowy
Opis: 
System bezpieczeństwa wykorzystywany do monitorowania stacji paliw
pod kątem potencjalnych awarii, wycieków paliwa lub nieautoryzowanego dostępu.
Interakcje:
- Generowanie alarmów i powiadomień dla operatorów stacji i administratorów systemu w przypadku wykrycia incydentów.

### Google Ads
Opis: 
Platforma reklamowa integrująca się z systemem stacji paliw w celu wyświetlania 
spersonalizowanych reklam klientom podczas korzystania ze stacji. Interakcje: 
- Dostarczanie danych dla spersonalizowanych kampanii reklamowych, analiza skuteczności reklam.

## Ustalanie priorytetów:

W celu ustalenia priorytetów zastosujemy metodę MoSCoW, dzieląc wymagania na:

### Must have (Musi posiadać):
- Lokalizowanie stacji i rezerwacja dystrybutorów.
- Dokonywanie płatności
- Funkcjonalność umożliwiająca użytkownikom wybór preferowanej metody tankowania, w tym
  automatycznego tankowania przy użyciu robotów. Jest to kluczowy element różnicujący usługę
  stacji paliw i odpowiada bezpośrednio na wizję stworzenia nowej jakości usług w sektorze.
- Identyfikacja pojazdów (RFID/tablice rejestracyjne).
- Automatyczne fakturowanie.
- Panel zarządzania dla operatorów stacji.
- Automatyczne generowanie raportów.
- System zarządzania zapasami.
- Bezpieczeństwo danych.

### Should have (Powinien posiadać):
- Personalizacja usług na podstawie historii użytkowników.
- Zintegrowany system wsparcia klienta.
- Optymalizacja zużycia energii.
- Monitorowanie stacji pod kątem awarii.

### Could have (Mógłby posiadać):
- Interaktywne kioski do płatności.
- Funkcja oceny usług przez użytkowników.
- Wirtualny asystent AI.
- Integracja z Google Ads i wyświetlanie reklam.

### Won't have (Nie będzie posiadać w tej wersji):
- Zaawansowane personalizacje i funkcje promocyjne.
- Niektóre funkcje integracyjne z zewnętrznymi usługami.


