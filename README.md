# Materiais
Esse repositório PÚBLICO tem o objetivo de guardar datasheets importantes sobre os materiais que usamos.

# Lista de conexões
Sujeita a mudanças:
| | | |
|-|-|-|
|Componente|Conexão|Portas|
|Motor|ESP32|IO 14/15/16/17|
|Encoder|TB6612FNG|A01, A02, PGND1|
| | |B02, B01, PGND2|
|TB6612FNG|ESP32|VCC(20) - 2|
| | |PWMA(23) - IO22|
| | |AIN1(21) - IO23|
| | |AIN2(22) - IO25|
| | |PWMB(15) - IO26|
| | |BIN1(17) - IO27|
| | |BIN2(16) - IO32|
| |TB6612FNG|VM2 (13) / STBY(19) - VCC (20)|
| |Regulador 7805|VM2(13) / VM3(14) - VO(3)|
|XL6009|Regulador 7805|SW(3) - VI(1)|
| |Bateria|VIN(4) - Terminal Positivo|
|Regulador 7805|XL6009|VI(1) - SW(3)|
| |TB6612FNG|VO(3) - VM2(13)|
