# Firewalls

WAF:  
Analizuje dane wejściowe, takie jak nagłówki, URL, parametry zapytań, dane formularzy, aby wykryć podejrzane wzorce.


Analiza ruchu:

WAF monitoruje każdy przychodzący i wychodzący ruch HTTP/S.
Analizuje dane wejściowe, takie jak nagłówki, URL, parametry zapytań, dane formularzy, aby wykryć podejrzane wzorce.

Wykrywanie i blokowanie ataków:

WAF porównuje przychodzące żądania do bazy reguł, które mogą identyfikować znane ataki, np. SQLi, XSS, CSRF.
Jeśli ruch jest uznany za złośliwy (np. zawiera kod SQL w formularzu), WAF blokuje to żądanie, zapobiegając jego przetworzeniu przez aplikację.

Podstawowe techniki WAF:

Filtrowanie bazujące na sygnaturach: Wykrywanie znanych wzorców ataków (np. ciągi znaków używane w SQL Injection).
Filtrowanie na podstawie heurystyki: Analiza niestandardowych lub nietypowych wzorców ruchu, które mogą wskazywać na atak.
Biała lista (whitelisting): Dopasowanie do zaufanych źródeł, blokowanie wszystkiego, co pochodzi z niezaufanych adresów IP.
Ochrona przed botami: Wykrywanie i blokowanie ruchu pochodzącego od botów, które mogą wykonywać ataki, np. brute-force.

Reakcja na wykryty atak:

WAF może zastosować różne reakcje w zależności od konfiguracji:

Zablokowanie – blokuje niepożądane żądanie.
Przekierowanie – np. na stronę ostrzeżenia.
Logowanie – zapisuje dane o próbie ataku do logów w celu późniejszej analizy.
