# **Dokumentacja LLD**

Dokument ten jest prostym szablonem, zawierającym listę informacji, jakie powinny znleźć się w dokumentacji wdrożeniowej LLD. Dokładne omówienie go znajduje się w filmie [Co powinna zawierać dokumentacja HLD](https://youtu.be/v9rmFCi3SFc) na kanale YT [Nowoczesny Sieciowiec](https://www.youtube.com/channel/UCRsGDPGN4KlTNJOKcbnM_Cw)

Kolejność rozdziałów i ich zakres są przykładowe, można dostosować do własnych wymagań

- [**Dokumentacja LLD**](#dokumentacja-lld)
  - [**Część formalna**](#część-formalna)
    - [i. Strona tytułowa](#i-strona-tytułowa)
    - [ii. Informacje formalne](#ii-informacje-formalne)
    - [iii. Spisy treści](#iii-spisy-treści)
  - [**1. Wstęp**](#1-wstęp)
  - [**3. Wymagania środowiskowe**](#3-wymagania-środowiskowe)
  - [**4. Zestawienia**](#4-zestawienia)
  - [**5. Opis aktualnego środowiska**](#5-opis-aktualnego-środowiska)
  - [**6. Instalacja fizyczna**](#6-instalacja-fizyczna)
  - [**7. Proces wdrożenia**](#7-proces-wdrożenia)
  - [**8. Automatyzacja**](#8-automatyzacja)
  - [**9. Zabezpieczanie środowiska**](#9-zabezpieczanie-środowiska)
  - [**10. Zarządzanie**](#10-zarządzanie)
  - [**11. Obsługa serwisowa**](#11-obsługa-serwisowa)
  - [**12. Testy akceptacyjne**](#12-testy-akceptacyjne)
  - [**13. Opisy technologiczne**](#13-opisy-technologiczne)
  - [**14. Dodatki**](#14-dodatki)

## **Część formalna**

### i. Strona tytułowa

- Tytuł
- Odbiorca
- Autor
- Data publikacji
- Nagłówek
  - Nazwa aktualnego rozdziału
- Stopka
  - Nazwa dokumentu
  - Informacje prawne
  - Numer strony

### ii. Informacje formalne

- Historia dokumentu
- Zastrzeżenia, nota prawna
- Stosowane oznaczenia
  - Ikony
  - Uzyte kroje fontów
- Akcptacja klienta i wykonawcy

### iii. Spisy treści

- Spis treści
- Spis tabel
- Spis rysunków

## **1. Wstęp**

- Executive Summary
- Inwestor
- Osoby kontaktowe
- Lokalizacje
- Cel projektu
- Co nie jest celem projektu
- Wymgania i założenia
  - Odpowiedzialność klienta i dostawcy (kto, co dostarcza)
- Dokumenty zależne
- Przebieg projektu
- Wstępnie oszacowane ryzyka
- Odbiorcy dokumentu

## **3. Wymagania środowiskowe**

- Gabaryty
- Zapas na kable
- Pobór mocy
- Sposób podłączenia zasilania
- Przepływ powietrza
- Podsumowanie
- Ograniczenia sprzętu

## **4. Zestawienia**

- Fizyczne
  - Schemat nazewnictwa
  - Wersje oprogramowania
  - Lista urządzeń fizycznych (hostname, adres IP, model, przeznaczenie)
  - Diagram połączeń fizycznych
  - Zestawienie połączeń fizycznych (A, B, wkładka, typ kabla, długość)
  - Rozmieszczenie urządzeń w szafie
- Logiczne
  - VLAN, VRF, IP, L2/L3
  - QoS (wymagania, markowanie, kolejki, wyliczenia pasma)
  - Lista urządzeń logicznych
  - Diagram połączeń logicznych i przepływów
  - Globalne parametry systeowe (DNS, NTP, domena, SMTP, syslog, netflow)
  - Użytkownicy i konta systemowe
  - Wymagana komunikacja sieciowa
  - Wzorce konfiguracji

## **5. Opis aktualnego środowiska**

- Elementy mające wpływ na obecny projekt
- Utylizacja zasobów
- Opis migrowanych środowisk

## **6. Instalacja fizyczna**

- Narzędzia i materiały
- Szczególne elementy instalacji
- Pierwsze uruchomienie
- Czynności weryfikujące

## **7. Proces wdrożenia**

- Wytyczne konfiguracji i ich uzasadnienie
- Przepływy danych
- Inżynieria routingu
- Proces migracji usług
- Proces cofnięcia zmian

## **8. Automatyzacja**

- Jakie narzędzia
- API
- Przechowywanie skryptów
- Proces CICD
- Proces zatwierdzania zmian

## **9. Zabezpieczanie środowiska**

- Uwierzytelnianie dostępu (tacacs+, radius)
- Integracja (AD)
- Przdzielane profile
- Uwierzytelnianie protokołów routingu
- Szyfrowanie połączeń
- Szyfrowanie dysków
- Zasady zdalnego dostępu
- Hardening

## **10. Zarządzanie**

- Monitoring (konfiguracje, syslog, trap, SNMP)
- Kopie zapasowe i ich odtwarzanie
- Procedury operacyjne
- Proces wyłączania całego środowiska

## **11. Obsługa serwisowa**

- Jak zgłaszać, co zawierać w zgłoszeniu, gdzie wysyłać
- Tryby serwisowania urządzeń, numery kontraktów serwisowych
- Scenariusze awaryjne
  - Czynności weryfikujące, odtworzeniowe
  - Wpływ na pozostałe środowisko

## **12. Testy akceptacyjne**

- Ogólne założenia
- Lista urządzeń
- Dokładny opis testu
  - Data
  - Kto wykonał
  - Opis
  - Wykonywane polecenia
  - Wynik oczekiwany i obserwowany
  - Czasy przełączenia
  - Rezultat
  - Uwagi

## **13. Opisy technologiczne**

- Uzasadnienie użycia danej technologii

## **14. Dodatki**

- Spis urządzeń z numerami seryjnymi
- Spis licencji
- Słownik skrótów
- Bibliografia
