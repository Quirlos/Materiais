# Materiais
Esse repositório PÚBLICO tem o objetivo de guardar datasheets importantes sobre os materiais que usamos.


# Lista de conexões dos componentes ![Última atualização](https://img.shields.io/github/last-commit/HumaMaquina/Materiais?label=Última%20atualização&style=flat&color=blue&labelColor=grey&logo=github&logoColor=white&date_format=DD%2FMM%2FYY%20-%20HH%3A%MM%20%28UTC%29)

Sujeita a mudanças:

|Quantidade|Componente|Conexão no Esp32|Portas(n°)|Descrição|
|:----|:----|:----|:----|:----|
|1|ESP32 DEVKIT V1 - DOIT|Motor|A01, A02, PGND1| |
| | | |B02, B01, PGND2| |
| | |Ponte H TB6612FNG|2 - VCC(20)| |
| | | |IO22 - PWMA(23)| |
| | | |IO23 - AIN1(21)| |
| | | |IO25 - AIN2(22)| |
| | | |IO26 - PWMB(15)| |
| | | |IO27 - BIN1(17)| |
| | | |IO32 - BIN2(16)| |
| | |NRF24L01|3.3V - VCC| |
| | | |GND - GND| |
| | | |IO5 - CSN| |
| | | |IO4 - CE| |
| | | |IO23 - MOSI| |
| | | |IO18 - SCK| |
| | | |IO19 - MISO| |
|2|Micro motor 6V 200 RPM Low Power|ESP32|A01, A02, PGND1| |
| | | |B02, B01, PGND2| |
|2|Par de Encoders Magnéticos com entrada lateral|ESP32|IO 14/15/16/17| |
|1|Ponte H TB6612FNG|ESP32|VCC(20) - 2| |
| | | |PWMA(23) - IO22| |
| | | |AIN1(21) - IO23| |
| | | |AIN2(22) - IO25| |
| | | |PWMB(15) - IO26| |
| | | |BIN1(17) - IO27| |
| | | |BIN2(16) - IO32| |
| | |TB6612FNG|VM2 (13) / STBY(19) - VCC (20)| |
| | |Regulador 7805|VM2(13) / VM3(14) - VO(3)| |
|1|Módulo de Rádio NFR24L01|ESP32|VCC - 3.3V
| | | |GND - GND| |
| | | |CSN - IO5| |
| | | |CE - IO4| |
| | | |MOSI - IO23| |
| | | |SCK - IO18| |
| | | |MISO - IO19| |
|1|Regulador Boost XL6009|Regulador 7805|SW(3) - VI(1)| |
| | |Bateria LiPo 7.4V|VIN(4) - Terminal Positivo| |
|1|Regulador 7805|XL6009|VI(1) - SW(3)| |
| | |TB6612FNG|VO(3) - VM2(13)| |
