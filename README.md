# Lucek
Sterownik Pieca z Ekranem Dotykowym 
przygotowywany do pieca z podajnikiem ślimakowym.

# Podzespoły główne:
- serce - Arduino Mega 
- ekran Nextion 4.2
- Zegar czasu rzeczywistego z eeprom DS3231
- Płytka z triakami
- termometry dallas
 opcjonalnie:
 - Termopara termometr spalin
 - czujnik odległści MAX6675
  

!["Strona startowa"](https://github.com/sargus123/Lucek/blob/main/Ekran_NEXTION/piec1.jpg)

!["Strona główna "](https://github.com/sargus123/Lucek/blob/main/Ekran_NEXTION/piec2.jpg)

![Strona główna ](https://github.com/sargus123/Lucek/blob/main/Ekran_NEXTION/piec3.jpg)

![Strona główna ](https://github.com/sargus123/Lucek/blob/main/Ekran_NEXTION/piec4.jpg)


na 17.12.2020 w fazie testowej.

do zrobienia :
- poprawić sterowanie wentylatorem ac
- czujnik poziomu paliwa
- możliwość zmiany z menu konfiguracji sieci
- czas wyrzutu materiału ze slimaka po przekroczeniu temp. 
- sterowanie z poziomu domoticza pompami


Zrobione 
- termometry dallas
- Układ wielomocy 
- sterowanie pompami
- połączenie z domoticz Port zakres portów od 80 - 8099
- Domoticz ustawienie id domyślnie od 1 do 500 ( myślę że nikt niema więcej urządzeń niż te 500
- kontrola sprawności termometrów
- alarmy : 
-- termometrów
-- Slimaka
-- błedu odczytu pamięci eeprom
- nawigacja po menu
- podanie początkowego IDX domoticz
- podanie portu Domoticza zakres od 80 - 90 i od 8080-8089
-- zabezpieczenie pomp. (anty stop) aktywowany o 11:11 codzienni diagnozowane i aktywowane w miarę potrzeb. 

