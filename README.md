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
- zabezpieczenie pomp. (anty stop)
- czujnik poziomu paliwa
- podanie początkowego IDX domoticz
- możliwość zmiany z menu konfiguracji sieci
- czas wyrzutu materiału ze slimaka po przekroczeniu temp. 


Zrobione 
- termometry dallas
- Układ wielomocy 
- sterowanie pompami
- połączenie z domoticz
- kontrola sprawności termometrów
- alarmy : 
-- termometrów
-- Slimaka
-- błedu odczytu pamięci eeprom
- nawigacja po menu



