# Wuxi i-core AiP31520 Demonstration Code
This is Arduino sample code for any display that uses the Wuxi i-core AiP31520 controller. The code has been written specifically for 122x32 size displays. 

These displays are a part of the CFAG graphics family and operate at 5V. Please refer the display datasheet before connection to a power source. Further, a variable resistor connection is required for contrast adjustment and its connection scheme has been outlined in the datasheet of the respective part.

## Connection Guide
```
//  ARD      | Port  | Display pin |  Function - 6800 Parallel                |
//-----------+-------+-------------+------------------------------------------+
// 3.3V/5V   |       |             |  POWER 3.3V/5V                           |
// GND       |       |             |  GROUND                                  |
//-----------+-------+-------------+------------------------------------------+
// D8        | PORTB |  05         |  Data/Instruction                (D/I)   |
// D9        | PORTB |  16         |  Read/Write                      (R/W)   |
// D10       | PORTB |  06         |  Column select 1/chip enable IC1 (CS1)   |
// D11       | PORTB |  07         |  Column select 2/chip enable IC2 (CS2)   |
//-----------+-------+-------------+------------------------------------------+
//Data Lines
//-----------+-------+-------------+------------------------------------------+
// D0        | PORTD |  08         |  DATA BUS LINE (DB0)                     |
// D1        | PORTD |  09         |  DATA BUS LINE (DB1)                     |
// D2        | PORTD |  10         |  DATA BUS LINE (DB2)                     |
// D3        | PORTD |  11         |  DATA BUS LINE (DB3)                     |
// D4        | PORTD |  12         |  DATA BUS LINE (DB4)                     |
// D5        | PORTD |  13         |  DATA BUS LINE (DB5)                     |
// D6        | PORTD |  14         |  DATA BUS LINE (DB6)                     |
// D7        | PORTD |  15         |  DATA BUS LINE (DB7)                     |
//-----------+-------+-------------+------------------------------------------+
```


Crystalfontz Part Numbers:\
[CFAG12232A-TMI-TA](https://www.crystalfontz.com/product/cfag12232atmita-graphical-display-module-lcd-122x32)\
[CFAG12232A-YYH-TA](https://www.crystalfontz.com/product/cfag12232ayyhta-122x32-graphical-lcd-display-module)\
[CFAG12232D1-NYG-VJ](https://www.crystalfontz.com/product/cfag12232d1nygvj)\
[CFAG12232D1-YYH-VJ](https://www.crystalfontz.com/product/cfag12232d1yyhvj-122x32-transflective-graphic-lcd-display)\
[CFAG12232J-TFH-TA](https://www.crystalfontz.com/product/cfag12232jtfhta-graphic-lcd-module-122x32)\
[CFAG12232J-TMI-TA](https://www.crystalfontz.com/product/cfag12232jtmita-lcd-module-122x32-graphic)\
[CFAG12232J-YYH-TA](https://www.crystalfontz.com/product/cfag12232jyyhta-graphic-lcd-122x32)\
[CFAG12232K-YYH-TA](https://www.crystalfontz.com/product/cfag12232kyyhta-graphical-lcd-module-122x32)
