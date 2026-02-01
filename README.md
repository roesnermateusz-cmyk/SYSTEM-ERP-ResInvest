# ResInvest ERP System - Magazyn Zrębki Pyskowice

Profesjonalny system ERP do zarządzania magazynem zrębki drzewnej klasy Comarch/LOMAG.

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-production-success.svg)

## 📋 Opis

System ERP do kompleksowego zarządzania magazynem zrębki drzewnej dla ResInvest Commodities w Pyskowicach. Aplikacja webowa działająca w przeglądarce, bez potrzeby instalacji serwera czy bazy danych.

## ✨ Główne Funkcje

### Zarządzanie Dokumentami
- Tworzenie dokumentów **PZ (Przyjęcie Zewnętrzne)** z automatyczną numeracją
- Tworzenie dokumentów **WZ (Wydanie Zewnętrzne)** z automatyczną numeracją
- Profesjonalne generowanie dokumentów gotowych do druku
- Eksport dokumentów do PDF
- Wysyłanie dokumentów przez email

### Stan Magazynu
- Monitoring aktualnego stanu zrębki w **metrach przestrzennych (mp)**
- Automatyczne obliczanie bilansu (PZ - WZ)
- Historia wszystkich operacji magazynowych
- Suma przyjęć i wydań w czasie rzeczywistym

### Elektrociepłownie
Dedykowane zakładki dla każdej elektrowni z pełnymi statystykami:
- **Elektrownia Trutnov** (Czechy)
- **Fortum Częstochowa** (Polska)
- **Elektrociepłownia Chorzów** (Polska)

Dla każdej elektrowni system wyświetla:
- Łączną objętość wydanej zrębki (mp)
- Liczbę dokumentów WZ
- Wydania w bieżącym miesiącu
- Pełną historię operacji

### Zarządzanie Pojazdami
- Rejestr floty transportowej
- Statystyki wykorzystania każdego pojazdu
- Łączna objętość przewieziona przez każdy pojazd
- Liczba operacji dla każdego pojazdu

### Raporty i Analizy
System generuje profesjonalne raporty Excel:
- **Raport Miesięczny** - wszystkie operacje PZ i WZ
- **Raport Elektrociepłowni** - zestawienie wydań dla każdej elektrowni
- **Raport Stanu Magazynu** - aktualny stan z historią
- **Raport Pojazdów** - statystyki wykorzystania floty

## 🚀 Instalacja i Uruchomienie

### Wymagania
- Nowoczesna przeglądarka internetowa (Chrome, Firefox, Edge, Safari)
- Włączona obsługa JavaScript
- Połączenie z internetem (do załadowania bibliotek CDN)

### Instalacja
1. Pobierz plik `resinvest-erp-system.html`
2. Otwórz plik w przeglądarce
3. System jest gotowy do użycia

**Brak wymagań serwerowych** - aplikacja działa w pełni po stronie przeglądarki.

## 📖 Instrukcja Użytkowania

### Pierwsze Kroki

1. **Dodaj pojazdy**
   - Przejdź do zakładki "🚛 Pojazdy"
   - Kliknij "➕ Dodaj Pojazd"
   - Wpisz numer rejestracyjny

2. **Utwórz pierwszy dokument PZ**
   - Kliknij "📥 Nowe PZ" na panelu głównym
   - Wypełnij formularz (data, dostawca, pojazd, objętość, osoba)
   - Kliknij "💾 Zapisz i Generuj Dokument"
   - System automatycznie pokaże podgląd dokumentu

3. **Utwórz dokument WZ**
   - Kliknij "📤 Nowe WZ"
   - Wypełnij formularz (wybierz elektrownię jako odbiorcę)
   - System wygeneruje profesjonalny dokument

### Nawigacja

System posiada 6 głównych zakładek:
- **📊 Panel Główny** - przegląd kluczowych wskaźników
- **📄 Dokumenty** - lista wszystkich dokumentów PZ i WZ
- **📦 Magazyn** - aktualny stan magazynu
- **⚡ Elektrownie** - statystyki dla każdej elektrociepłowni
- **🚛 Pojazdy** - zarządzanie flotą transportową
- **📈 Raporty** - generowanie raportów Excel

## 💾 Przechowywanie Danych

### Lokalne Przechowywanie
Dane zapisywane są w **localStorage** przeglądarki.

### Backup Danych
⚠️ **WAŻNE**: Regularnie twórz kopie zapasowe przez eksport raportów do Excel!

## 📄 Licencja

MIT License - Zobacz pełną treść w pliku

## 📞 Kontakt

**ResInvest Commodities**  
ul. Wiejska 26a  
44-120 Pyskowice  
Tel: 661 710 380  
Email: magazyn@resinvest.pl
