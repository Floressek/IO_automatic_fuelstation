# LAB1 - contents: (pkt 1 i 2)

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

# LAB2 - contents (pkt 3 i 4):

# Analiza czasownikowo-rzeczownikowa projektu

Analiza czasownikowo-rzeczownikowa jest techniką analityczną stosowaną w projektowaniu systemów informatycznych, która polega
na przeszukiwaniu dokumentacji(u nas zawartość lab1) projektu w celu znaleźenia czasownikow i rzeczowników. Czasowniki w tym 
kontekście pełnią rolę reprezentacji działania lub operacji, które użytkownik może wykonywać za pośrednictwem systemu, zaś rzeczowniki 
odnoszą się do obieków systemu, na których działania te są wykonywane. Proces ten umożliwia szybkie i jawne zidentyfikownie głowych 
funkcjonalności, które system ma oferować, oraz kluczowych elementów tegoż systemu tj. moduły, dane czy zasoby z którymi funkcje są związane. 
To sprawia, że analiza czasownikowo-rzeczownikowa jest cennym narzędziem na wczesnym etapie projektowania, pomagającym w strukturyzacji wymagań
i lepszym zrozumieniu zakresu projektu.


# Oto szczegółowe podejście:
## Wyodrębnienie czasownikowo-rzeczownikowe:

**Moduł Obsługi Klienta (Wewnętrzne)**
- ***Aplikacja mobilna umożliwiająca*** ***lokalizowanie*** najbliższych stacji, ***rezerwowanie*** dystrybutorów i ***dokonywanie*** płatności.
- ***System identyfikacji*** pojazdów przy ***użyciu*** technologii RFID oraz ***rozpoznawania*** tablic rejestracyjnych.
- ***Automatyczne fakturowanie*** i ***cyfrowe paragony wysyłane*** bezpośrednio do aplikacji klienta.
- ***Personalizacja usług*** poprzez ***analizowanie*** historii tankowań i ***preferencji*** użytkowników, ***oferowanie*** spersonalizowanych promocji.
- ***Interaktywne kioski do samoobsługowej płatności*** dla klientów nieposiadających aplikacji.
- ***System wsparcia klienta zintegrowany*** z aplikacją, ***umożliwiający*** ***szybkie rozwiązywanie*** problemów i ***pytania*** użytkowników.
- ***Zaawansowane metody uwierzytelniania***, ***wprowadzenie*** biometrycznych metod uwierzytelniania
- ***Możliwość oceniania usług przez użytkowników***: ***Umożliwienie*** klientom ***oceniania*** jakości usług i poszczególnych stacji, co ***może pomóc*** w ***poprawie*** standardów oraz ***zwiększyć*** zaufanie klientów poprzez transparentność.
- ***Wirtualny asystent AI do wsparcia klienta***: ***Integracja*** chatbota ***wykorzystującego*** sztuczną inteligencję, który ***będzie w stanie*** ***na bieżąco odpowiadać*** na pytania użytkowników i ***pomagać*** w ***rozwiązywaniu*** problemów.
- ***Funkcjonalność umożliwiająca*** użytkownikom ***wybór*** preferowanej metody tankowania: zautomatyzowanej, z ***użyciem*** robota do tankowania, lub tradycyjnej, gdzie klient ***samodzielnie tankuje*** pojazd.

**Moduł Zarządzania Stacją (Zewnętrzne)**
- ***Panel zarządzania dla operatorów stacji umożliwiający*** ***monitorowanie*** i ***kontrolę*** stanu dystrybutorów, ***poziomu paliw*** w zbiornikach i ***danych transakcyjnych***.
- ***Automatyczne generowanie raportów*** sprzedaży, ***analizy efektywności*** promocji i ***preferencji*** klientów.
- ***System zarządzania zapasami*** i ***automatyczne zamawianie*** paliwa w ***oparciu*** o ***przewidywane zapotrzebowanie***.
- ***Moduł bezpieczeństwa monitorujący*** stacje pod kątem potencjalnych awarii, wycieków oraz nieautoryzowanego dostępu.
- ***Integracja*** z ***systemami alarmowymi*** i ***powiadomieniami awaryjnymi***, ***zapewniająca*** ***szybką reakcję*** na incydenty.
- ***Zarządzanie zużyciem energii***: ***Optymalizacja*** zużycia energii na stacjach poprzez ***inteligentne zarządzanie*** oświetleniem, pompami i innymi urządzeniami, co ***przyczynia się*** do ***obniżenia*** kosztów operacyjnych i ***wsparcia*** inicjatyw ekologicznych.
- ***Integracja*** z Google Ads dla ***spersonalizowanych reklam***: ***Wykorzystanie*** danych z Google Ads przy ***podjeździe*** klienta do stacji, ***umożliwiające*** ***wyświetlanie*** spersonalizowanych reklam na ekranach stacji na ***podstawie*** historii wyszukiwania i ***preferencji***, ***zwiększając*** skuteczność kampanii reklamowych.

**Wymagania Techniczne**
- System ***powinien być oparty*** na ***architekturze mikrousług***, z ***wykorzystaniem*** najnowszych technologii cloud computing.
- ***Wysoki poziom bezpieczeństwa danych***, z ***zastosowaniem*** szyfrowania i ***zabezpieczeń*** przed nieautoryzowanym dostępem.
- ***Elastyczność i skalowalność*** systemu, ***umożliwiająca*** łatwą ***rozbudowę*** o nowe stacje paliw oraz ***funkcjonalności***.
- ***Kompatybilność*** z różnymi ***systemami płatności*** elektronicznych i bankowości mobilnej.
- ***Możliwość integracji*** systemu z ***zewnętrznymi dostawcami*** usług, np. ***systemami zarządzania*** flotą pojazdów.

**Przypadki Użycia (Use Cases)**
- ***Rezerwacja dystrybutora*** i ***tankowanie*** przez klienta.
- ***Automatyczne rozliczenie transakcji*** i ***wysyłanie faktury*** do klienta.
- ***Zarządzanie promocjami*** i ***oferami specjalnymi*** dla ***zarejestrowanych użytkowników***.
- ***Monitorowanie stanu zbiorników paliw*** i ***automatyczne zamawianie dostaw***.
- ***Integracja*** z ***systemami alarmowymi*** i ***powiadomieniami awaryjnymi***, ***zapewniająca*** ***szybką reakcję*** na incydenty.

**Dalsze Wymagania i Oczekiwania**
- ***Optymalizacja procesu tankowania***: System ***powinien minimalizować*** czas ***potrzebny*** na tankowanie, ***oferując*** klientom ***możliwość szybkiego powrotu*** na drogę.
- ***Analiza danych*** i ***sztuczna inteligencja***: ***Wykorzystanie*** algorytmów AI do ***analizy danych*** zbieranych przez system, w ***celu optymalizacji*** procesów logistycznych i ***zapewnienia*** maksymalnej efektywności operacyjnej.
- ***Eko-inicjatywy***: ***Integracja funkcji*** wspierających ekologiczne inicjatywy, takich jak ***promowanie*** tankowania paliw alternatywnych oraz ***analiza śladu węglowego*** generowanego przez użytkowników stacji.
- ***Personalizacja doświadczeń*** klientów: ***Rozwój funkcji personalizacji*** w aplikacji mobilnej, tak aby każdy klient ***czuł***, że oferta "FuelFuture" jest ***dostosowana*** do jego ***indywidualnych potrzeb*** i ***preferencji***.
- ***Zarządzanie awariami*** i ***utrzymanie***: ***Implementacja zaawansowanego systemu monitorowania*** urządzeń, który ***pozwoli na szybką diagnostykę*** i ***reakcję*** na ewentualne awarie lub potrzeby konserwacyjne, ***minimalizując przestoje*** w dostępności dystrybutorów.
## Wydzielenie czasowników i rzeczowników:

### Projektowanie i wdrożenie systemu informatycznego dla sieci bezobsługowych stacji paliw:
- **Czasowniki**: "zaprojektowania" i "wdrożenia"
- **Rzeczowniki**: "systemu informatycznego", "sieci bezobsługowych stacji paliw"

### Automatyzacja procesów związanych z obsługą klientów oraz zarządzaniem wewnętrznymi zasobami firmy:
- **Czasownik**: "automatyzację"
- **Rzeczowniki**: "procesów związanych z obsługą klientów", "zarządzaniem wewnętrznymi zasobami firmy"

### Stworzenie nowej jakości usług w sektorze stacji paliw:
- **Czasownik**: "stworzenie"
- **Rzeczownik**: "nowej jakości usług", "sektorze stacji paliw"

**Moduł Obsługi Klienta (Wewnętrzne)**

**Czasowniki:**
- "umożliwiająca", "identyfikacji", "automatyczne fakturowanie", "wysyłane", "personalizacja", "oferowanie", "integracja", "wybór", "lokalizowanie", "rezerwowanie", "dokonywanie", "analizowanie", "rozwiązywanie", "wprowadzenie", "oceniania", "pomagać", "umożliwiająca", "samodzielnie tankuje"

**Rzeczowniki:**
- "Aplikacja mobilna", "najbliższe stacje", "rezerwacja dystrybutorów", "dokonywanie płatności", "system identyfikacji pojazdów", "technologia RFID", "rozpoznawanie tablic rejestracyjnych", "cyfrowe paragony", "aplikacja klienta", "historia tankowań", "preferencje użytkowników", "spersonalizowane promocje", "interaktywne kioski", "samoobsługowa płatność", "system wsparcia klienta", "zaawansowane metody uwierzytelniania", "biometryczne metody uwierzytelniania", "ocenianie usług", "wirtualny asystent AI", "chatbot", "sztuczna inteligencja", "preferowana metoda tankowania", "robot do tankowania", "zautomatyzowane tankowanie", "tradycyjne tankowanie"

**Moduł Zarządzania Stacją (Zewnętrzne)**

**Czasowniki:**
- "umożliwiający", "monitorowanie", "kontrola", "automatyczne generowanie", "zarządzanie", "automatyczne zamawianie", "monitorujący", "zapewniająca", "optymalizacja", "wykorzystanie"

**Rzeczowniki:**
- "Panel zarządzania", "operatorzy stacji", "stan dystrybutorów", "poziom paliw", "dane transakcyjne", "raporty sprzedaży", "efektywność promocji", "preferencje klientów", "system zarządzania zapasami", "paliwo", "moduł bezpieczeństwa", "awarie", "wycieki", "nieautoryzowany dostęp", "systemy alarmowe", "powiadomienia awaryjne", "zużycie energii", "inteligentne zarządzanie", "oświetlenie", "pompy", "Google Ads", "spersonalizowane reklamy"

**Wymagania Techniczne**

**Czasowniki:**
- "oparty", "wykorzystanie", "zastosowanie", "umożliwiająca", "integracja"

**Rzeczowniki:**
- "architektura mikrousług", "technologie cloud computing", "bezpieczeństwo danych", "szyfrowanie", "zabezpieczenia przed nieautoryzowanym dostępem", "elastyczność systemu", "skalowalność systemu", "kompatybilność", "systemy płatności elektronicznych", "bankowość mobilna", "zewnętrzni dostawcy usług", "systemy zarządzania flotą pojazdów"

**Przypadki Użycia (Use Cases)**

**Czasowniki:**
- "rezerwacja", "tankowanie", "automatyczne rozliczenie", "wysyłanie", "zarządzanie", "monitorowanie", "automatyczne zamawianie", "integracja", "zapewniająca"

**Rzeczowniki:**
- "dystrybutor", "transakcje", "faktury", "promocje", "oferty specjalne", "zarejestrowani użytkownicy", "stan zbiorników paliw", "dostawy", "systemy alarmowe", "powiadomienia awaryjne"

**Dalsze Wymagania i Oczekiwania**

**Czasowniki:**
- "minimalizować", "oferować", "wykorzystanie", "integracja", "rozwój", "implementacja", "pozwoli na", "diagnostyka", "reakcja", "minimalizowanie"

**Rzeczowniki:**
- "proces tankowania", "powrót na drogę", "algorytmy AI", "analiza danych", "ekologiczne inicjatywy", "tankowanie paliw alternatywnych", "ślad węglowy", "personalizacja doświadczeń klientów", "oferta 'FuelFuture'", "system monitorowania urządzeń", "awarie", "potrzeby konserwacyjne", "przestoje w dostępności dystrybutorów"

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
- Zautomatyzowany system tankowania (automatyzacja przy użyciu robotow firmy BostonDinamics)
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

## Lista Wymagań niefunkcjonalnych:

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

## Identyfikacja aktorów: (7)
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
  
## User - Story (10):

## Poziom Klienta

### Initiative: Udoskonalenie Doświadczenia Użytkownika

#### Epic: Logowanie i Bezpieczeństwo
- **US1**: (Logowanie) Jako klient, chcę, by aplikacja prosiła mnie o wprowadzenie adresu e-mail jako loginu, co umożliwi mi bezpieczne logowanie się do konta.
- **US2**: (Bezpieczeństwo) Jako klient, chcę, by aplikacja prosiła o wprowadzenie hasła, dla dodatkowego zabezpieczenia, zapewniając, że dostęp do mojego konta mają tylko upoważnione osoby.
- **US3**: (Ułatwienie Dostępu) Jako klient, chcę móc nacisnąć przycisk "Zaloguj się", aby po potwierdzeniu moich danych przejść do głównego menu aplikacji, co zapewni mi szybki dostęp do wszystkich funkcji.
- **US4**: (Odzyskiwanie Konta) Jako klient, oczekuję możliwości odzyskania hasła lub stworzenia nowego konta bezpośrednio z ekranu logowania, co zapewni mi łatwy dostęp do aplikacji nawet w przypadku zapomnienia hasła.

#### Epic: Komunikacja z Klientem
- **US5**: (Personalizowane Powiadomienia) Jako klient, chcę otrzymywać spersonalizowane powiadomienia push o lokalizacji stacji, promocjach czy zmianach cen, aby być na bieżąco z ofertami, które mogą mnie interesować.

#### Epic: Dostęp do Usług
- **US6**: (Znajdowanie Stacji) Jako klient, chcę wyszukiwać stacje na mapie, znać ilość kolejki i mieć możliwość nawigacji, co umożliwi mi szybkie znalezienie najbliższej stacji i ocenę, czy warto do niej podjechać.
- **US7**: (Wybór Paliwa) Jako klient, chcę widzieć listę paliw wraz z ich cenami i korzyściami z wyboru paliw premium, aby móc świadomie zdecydować, jakie paliwo tankować.
- **US8**: (Sposób Tankowania) Jako klient, chcę wybrać sposób tankowania (automatyczny czy manualny) z dostępnymi instrukcjami, aby proces tankowania był jak najbardziej komfortowy i dostosowany do moich potrzeb.

#### Epic: Zarządzanie Finansami
- **US9**: (Historia Płatności) Jako klient, chcę mieć dostęp do historii płatności, w tym daty i kwot transakcji oraz rodzaju zatankowanego paliwa, co pozwoli mi lepiej kontrolować wydatki.
- **US10**: (Opcje Płatności) Jako klient, chcę mieć różne opcje płatności, w tym możliwość przerwania transakcji, płatności opóźnione, płatności mobilne oraz używania kart lojalnościowych, co da mi swobodę wyboru najwygodniejszej metody płatności.

#### Epic: Korzystanie z Promocji
- **US11**: (Aktywacja Kuponów) Jako klient, chcę wprowadzać kody kuponów przed dokonaniem płatności, co umożliwi automatyczne odjęcie ich wartości od sumy do zapłaty, zapewniając mi korzystanie z dostępnych promocji.

#### Epic: Informacje o Produktach
- **US12**: (Informacje o Paliwie) Jako klient, chcę mieć możliwość sprawdzenia składu chemicznego paliw oraz ich pochodzenia, aby dokonać bardziej świadomego wyboru paliwa zgodnego z moimi wartościami ekologicznymi i potrzebami pojazdu.

#### Epic: Personalizacja Doświadczenia
- **US13**: (Ulubione Stacje) Jako klient, chcę móc zapisywać ulubione stacje paliw, aby szybko do nich nawigować w przyszłości, co ułatwi mi planowanie podróży i tankowanie na zaufanych stacjach.
- **US14**: (Zgłaszanie Problemów) Jako klient, chcę mieć możliwość zgłaszania problemów związanych ze stacjami paliw bezpośrednio przez aplikację, np. nieprawidłowe działanie dystrybutora, co pozwoli na szybką reakcję obsługi i podniesienie jakości usług.
- **US15**: (Recenzje i Opinie) Jako klient, chcę czytać oraz dodawać recenzje i opinie na temat stacji paliw, co pozwoli mi na podjęcie lepszej decyzji, gdzie tankować, oraz podzielenie się moimi doświadczeniami z innymi użytkownikami aplikacji.


## Poziom Operatora

### Initiative: Ulepszenie Procesów Wewnętrznych

#### Epic: Usprawnienie Fakturowania
- **US16**: (Generowanie Faktur) Jako operator, chcę mieć możliwość przeglądania wszystkich transakcji w danym okresie czasu i generowania z nich faktur, co umożliwi mi szybkie i efektywne zarządzanie dokumentacją sprzedażową.
- **US17**: (Automatyzacja Fakturowania) Oczekuję funkcjonalności automatycznego wysyłania faktur do klientów poprzez media takie jak e-mail lub fax, co zminimalizuje potrzebę manualnej interwencji i usprawni proces obsługi klienta.
- **US18**: (Zarządzanie Fakturami) Chcę mieć opcję ręcznego tworzenia oraz edytowania faktur, aby móc dokonywać korekt i dostosowań faktur zgodnie z wymaganiami klientów i sytuacją faktyczną.

#### Epic: Monitoring i Analiza Zapasów Paliw
- **US19**: (Wgląd w Zapasy Paliw) Chcę mieć wgląd w stan zbiorników paliwa, możliwość wyświetlenia listy zmian ilości paliwa, dostęp do wykresów tendencji spadkowej/wzrostowej oraz wgląd w godzinowe zapotrzebowanie na paliwo, co pozwoli mi na lepsze planowanie zakupów paliwa i zarządzanie zapasami.
- **US20**: (Analiza Danych Sprzedażowych) Oczekuję możliwości podglądu statystyk rocznych dotyczących sprzedaży i zapotrzebowania, co pomoże mi w analizie trendów i optymalizacji działalności.

### Initiative: Poprawa Bezpieczeństwa i Utrzymania Stacji

#### Epic: Zarządzanie Przeglądami i Konserwacją
- **US21**: (Przypomnienia Konserwacyjne) Chcę mieć możliwość ustawienia przypomnień o rutynowych czynnościach konserwacyjnych i przeglądach stacji, aby zapewnić ciągłą sprawność urządzeń i infrastruktury, co przyczyni się do podniesienia bezpieczeństwa i jakości obsługi klienta.
- **US22**: (System Alerty) Oczekuję, że system będzie wysyłał powiadomienia o nadchodzących terminach płatności, ważnych datach dotyczących umów z dostawcami i innych krytycznych wydarzeniach operacyjnych, co pozwoli mi na lepsze zarządzanie zobowiązaniami i relacjami biznesowymi.
- **US23**: (Reagowanie na Awaryjne Sytuacje) Potrzebuję funkcji aktywnego wykrywania zdarzeń na stacji, takich jak zderzenia, wypadki, automatyczne wykrywanie wycieków lub zabrudzeń na nawierzchni, oraz automatycznego wzywania służb ratunkowych po wykryciu zagrożenia pożarowego, co zapewni szybką reakcję w sytuacjach awaryjnych i zwiększy bezpieczeństwo użytkowników stacji.

### Initiative: Rozwój i Zarządzanie Ofertą Stacji

#### Epic: Promocje i Lojalność Klientów
- **US24**: (Zarządzanie Promocjami) Jako operator, chcę mieć możliwość szybkiego dodawania, modyfikacji oraz usuwania promocji i rabatów oferowanych klientom, aby zachęcić ich do częstszych wizyt i zwiększyć lojalność.

#### Epic: Utrzymanie i Rozwój Infrastruktury
- **US25**: (Zarządzanie Zasobami Stacji) Chcę mieć możliwość monitorowania i zarządzania zasobami stacji, takimi jak dostępność myjni, stan techniczny urządzeń, czy dostępność poszczególnych typów paliw, aby zapewnić ciągłość i jakość świadczonych usług.

#### Epic: Szkolenie i Rozwój Personelu
- **US26**: (Programy Szkoleniowe dla Personelu) Oczekuję dostępu do platformy szkoleniowej dla personelu, aby mogli oni regularnie podnosić swoje kwalifikacje i zapewniać klientom profesjonalną obsługę zgodną z aktualnymi standardami bezpieczeństwa i obsługi klienta.

#### Epic: Analityka Biznesowa i Optymalizacja Oferty
- **US27**: (Narzędzia Raportowania i Analiz) Chcę mieć dostęp do zaawansowanych narzędzi raportowania i analiz, które umożliwią mi szczegółowe śledzenie wyników sprzedaży, efektywności promocji, oraz zrozumienie zachowań i preferencji klientów, co pozwoli mi na lepsze dostosowanie oferty do ich potrzeb.

## Sprawdzenie czy wszystkie user story pokrywają wymagania funkcjonalne (np. w formie tabelki - macierzy śledzenia) (11)

Sprawdziłem, czy wszystkie Historie Użytkowników (User Stories) pokrywają wymagania funkcjonalne, i rzeczywiście tak jest. Oto podsumowanie, jak każda Historia Użytkownika (User Story) jest zgodna z danymi wymaganiami dla systemu zarządzania stacją benzynową:

| Epik | Historia Użytkownika | Wymaganie Funkcjonalne |
| --- | --- | --- |
| Lokalizacja i Rezerwacja Stacji | US01: Geolokalizacja i Wyszukiwanie Stacji | Użytkownicy mogą znaleźć pobliskie stacje benzynowe korzystając z usług lokalizacyjnych. |
|  | US02: Rezerwacje | Użytkownicy mogą zarezerwować określony dystrybutor lub stację, aby zapewnić preferencyjną obsługę i skrócić czas oczekiwania. |
| Płatność i Tankowanie | US03: Metody Płatności | Dostępne są różne opcje płatności, w tym karty kredytowe/debetowe, portfele mobilne i gotówka. |
|  | US04: Wybór Paliwa | Użytkownicy mogą wybrać preferowany rodzaj paliwa, metodę tankowania i format dyszy. |
|  | US05: Identyfikacja Pojazdu | Systemy identyfikacji pojazdów (RFID/tablice rejestracyjne) są obsługiwane dla szybszej i spersonalizowanej obsługi. |
|  | US06: Automatyczne Fakturowanie | Zapewnione jest automatyczne fakturowanie dla płynniejszych transakcji i poprawy satysfakcji klienta. |
| Panel Operatora i Raportowanie | US11: Panel Operatora | Intuicyjny panel operatora zarządza wieloma stacjami, w tym real-time statusami zbiorników, informacjami o użytkownikach, danymi płatności i analizami stacji. |
|  | US15: Monitorowanie Stacji | Monitorowanie stacji benzynowych w czasie rzeczywistym pod kątem problemów z wysyłaniem alertów do operatorów, gdy jest to konieczne. |
| Personalizacja i Wsparcie Klienta | US12: Profile Użytkowników | Kompleksowe profile użytkowników wspierają preferencje i historię klientów. |
|  | US13: Zintegrowany System Wsparcia | Dostępne jest bezproblemowe wsparcie klienta, w tym czat, email, telefon lub pomoc osobista. |
|  | US14: Optymalizacja Energetyczna | Zaawansowane funkcje optymalizacji energetycznej mogą minimalizować marnotrawstwo i zwiększać efektywność zarówno dla stacji benzynowych, jak i pojazdów użytkowników (Opcjonalnie). |
|  | US15: Monitorowanie Stacji | Monitorowanie stacji benzynowych w czasie rzeczywistym pod kątem problemów z wysyłaniem alertów do operatorów, gdy jest to konieczne. |
| Personalizacja i Marketing | US16: Spersonalizowane Promocje | Dostępne są spersonalizowane promocje oparte na zachowaniach użytkowników, preferencjach i historii transakcji (Opcjonalnie). |
|  | US17: Integracja z Google Ads | Wspierana jest integracja z Google Ads dla ukierunkowanej reklamy w ramach platformy (Opcjonalnie). |
| Wirtualny Asystent i AI | US18: Wirtualny Asystent | Wirtualny asystent lub chatbot AI może poprawić interakcje z klientami i usprawnić komunikację między nimi a Twoim biznesem (Opcjonalnie). |
| Analityka Biznesowa i Optymalizacja Oferty | US19: Szczegółowe Raportowanie | Dostępne są zaawansowane narzędzia raportowania, w tym trendy sprzedażowe, demografia użytkowników, wzorce zużycia paliwa

 i wydajność stacji, aby optymalizować ofertę i poprawić ogólną wydajność. |
| Zaawansowane Personalizacje i Funkcje Promocyjne | US20: Zaawansowana Personalizacja | Dynamiczne ustalanie cen, spersonalizowane oferty i ukierunkowany marketing nie są dostępne, ale zapewniona jest solidna podstawa dla przyszłych usprawnień (Opcjonalnie). |
| Integracja z zewnętrznymi usługami | US21: Integracje z Stronami Trzecimi | Zaawansowane integracje z zewnętrznymi usługami (Google Maps, Google Analytics) nie są włączone w tej wersji, ale platforma pozostaje elastyczna na przyszłe dodatki. |

## Ustalanie priorytetów: (12) - MoSCoW

### Must have (Musi posiadać):

#### Epic: Lokalizacja i Rezerwacja Stacji
- US01: (Geolocation and Station Search) Must have location services for users to find nearby gas stations.
- US02: (Reservations) Must have the ability for users to reserve a specific tank or station, ensuring preferred service and reducing wait times.

#### Epic: Płatnosć i Tankowanie
- US03: (Payment Methods) Must have multiple payment options, including credit/debit cards, mobile wallets, and cash.
- US04: (Fuel Selection) Must have the ability for users to choose their preferred fuel type (e.g., diesel or ethanol), tank method (automatic or manual), and nozzle format (handheld or robotic).
- US05: (Vehicle Identification) Must have vehicle identification systems, like RFID/plates, to streamline the tanking experience by granting customers faster and more customized services.
- US06: (Automated Facturing) Must include automated billing for smoother transactions and improved customer satisfaction.

#### Epic: Panel Operatora i Raportowanie
- US11: (Operator Dashboard) Must have an intuitive operator panel for managing multiple stations, including real-time tank statuses, user information, payment data, and station analytics.

### Should have (Powinien posiadać):

#### Epic: Personalizacja i Wspieranie Klienta
- US12: (User Profiles) Should support a comprehensive profile system for customers to access their own preferences and history with the service.
- US13: (Integrated Support System) Should provide seamless customer support, including chat, email, phone, or even in-person assistance if needed.
- US14: (Energy Optimization) Could have advanced energy optimization features to minimize waste and increase efficiency for both gas stations and users' vehicles.
- US15: (Station Monitoring) Should include real-time monitoring of gas stations for issues, with alerts sent directly to operators when necessary.

### Could have (Mógłby posiadać w tej wersji):

#### Epic: Personalizacja i Marketing
- US16: (Personalized Promotions) Could include personalized promotions based on user behavior, preferences, and transaction history to increase engagement and retention.
- US17: (Google Ads Integration) Could support integration with Google Ads, allowing targeted advertising within the platform.

#### Epic: Wirtualny Asystent i AI
- US18: (Virtual Assistant) Could introduce a virtual assistant or AI chatbot to improve customer interactions and streamline communication between them and your business.

#### Epic: Analytika Biznesowa i Optymalizacja Oferty
- US19: (Detailed Reporting) Could have detailed reporting tools, including sales trends, user demographics, fuel usage patterns, and station performance to optimize offerings and enhance overall performance.

### Won't have (Nie będzie posiadać w tej wersji):

#### Epic: Zaawansowane Personalizacje i Funkcje Promocyjne
- US20: (Advanced Personalization) Won't include advanced personalization features, such as dynamic pricing, tailored offers, and targeted marketing, but will provide a solid foundation for further enhancements in future versions.

#### Epic: Integracja z zewnętrznymi usługami
- US21: (Third Party Integrations) Won't have advanced third-party integrations, such as Google Maps, Google Analytics, or other external systems to support a more comprehensive vision and value proposition. However, the platform will remain flexible enough for future additions.


