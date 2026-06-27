========================
Rozdział 1: Wprowadzenie
========================

**Autor:** Daniel Szokało

Rozdział ten pełni funkcję wstępu do ostatecznego sprawozdania z przedmiotu Bazy Danych. Prace nad projektem odbywały się w semestrze letnim (rok akademicki 2025/2026) na kierunku informatyka techniczna.

Wprowadzenie tematyczne
-----------------------

Dokumentacja ta przedstawia krok po kroku proces tworzenia systemu bazodanowego – od podstaw teoretycznych, przez projektowanie architektury, aż po wdrożenie i testy. W części przeglądowej zebrano najważniejsze informacje o systemach zarządzania bazami danych (DBMS), zasadach normalizacji i języku SQL, co ułatwiło późniejsze podejmowanie decyzji projektowych.

Część praktyczna projektu polegała na stworzeniu własnego systemu transakcyjnego dla sklepu internetowego z elektroniką. Przeanalizowano w niej kluczowe procesy e-commerce, takie jak: zarządzanie kontami klientów, katalogowanie produktów, obsługa zamówień, płatności oraz recenzji. Projektowanie rozpoczęto od modelu konceptualnego, który następnie przekształcono w model logiczny zgodny z trzecią postacią normalną (3NF). Wymagało to zastosowania konkretnych rozwiązań, takich jak tabele łącznikowe dla koszyka zamówień czy mechanizmy zapamiętywania cen z momentu zakupu. Na koniec opracowano dwa niezależne modele fizyczne, dostosowane do specyfiki silników PostgreSQL oraz SQLite.

Ostatnie części raportu opisują wdrożenie struktur bazodanowych w środowiskach docelowych (lokalny i chmurowy PostgreSQL oraz platforma JupyterHub). Istotnym elementem była optymalizacja ładowania danych testowych. Posłużyły do tego autorskie skrypty w języku Python, wykorzystujące wsadowe wprowadzanie danych (*batch insert*). Stabilność systemu potwierdzono za pomocą złożonych zapytań SQL, zawierających wielokrotne złączenia, grupowania, podzapytania i funkcje agregujące. Kod skryptów zintegrowano z narzędziem Sphinx, co pozwoliło na automatyczne wygenerowanie tej dokumentacji technicznej.


Spis wszystkich użytych w raporcie repozytoriów
-----------------------------------------------

Repozytoria tematyczne
~~~~~~~~~~~~~~~~~~~~~~

* `Sprzęt dla bazy danych <https://github.com/karaskamil/Sprzet-dla-bazy-danych.git>`_
* `Konfiguracja bazy danych PostgreSQL <https://github.com/Youarecheck/Bazy_Danych_Tematyczne_Repo_MK.git>`_
* `Kontrola i konserwacja bazy danych <https://github.com/pawlos1337/Bazy-danych-temat.git>`_
* `Monitorowanie i diagnostyka <https://github.com/OskarProgrammer/monitorowanie_i_diagnostyka.git>`_
* `Wydajność, skalowanie i replikacja danych <https://github.com/KMachoK/Tematyczne.git>`_
* `Partycjonowanie danych <https://github.com/domino0472/Partycjonowani-Danych.git>`_
* `Bezpieczeństwo baz danych <https://github.com/oski486/BazyDanych-Subject.git>`_
* `Kopie zapasowe i odzyskiwanie danych <https://github.com/Koko9077/Kopie-zapasowe-i-odzyskiwanie-danych.git>`_

Repozytorium główne
~~~~~~~~~~~~~~~~~~~

* `Repozytorium główne <https://github.com/danszo1/Bazy-Danych-Main.git>`_