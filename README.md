# Lucek
Sterownik Pieca z Ekranem Dotykowym 
przygotowywany do pieca z podajnikiem ślimakowym.

# Podzespoły główne:
- serce - Arduino Mega 
- ekran Nextion 4.3
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
- termometr spalin
- wykorzystanie opału w palenisku awaryjnym ( odpowiednie wyregulowanie mocy wentylatora w momencie kiedy wykryte zostanie za wysoka temp. w spalinach)




Zrobione 
- termometry dallas
- Układ wielomocy 
- sterowanie pompami wg. temperatury
- kontrola sprawności termometrów
- alarmy : 
-- termometrów
-- Slimaka
-- błedu odczytu pamięci eeprom (jeśli pusta lub brak zgłosi błąd )
- nawigacja po menu
- podanie początkowego IDX Domoticz 1 - 255 ( z powodu pamięci eeprom do 255 można więcej ale czy potrzeba)
- podanie portu Domoticza zakres od 80 - 90 i od 8080-8089
- zawór 4d współpracuje z wyjściem pompy CO2 kiedy pompa jest włączona to steuje jeśli wyączona to zamknie zawór. (czas zamykania 6*4 = 24 sekundy)
- obniżenie temeratury np. nocnej
-- zabezpieczenie pomp. (anty stop) aktywowany o 11:11 codziennie diagnozowane i aktywowane w miarę potrzeb. 

