# MW328PB
This is a quadcopter based on the ATMEGA328PB IC. It is intended to have specific hardware support only with an emphasis on fast/simple code. MWPB is named such to pay homage its multiwii roots.

# Features
- **2 Serials:** Serial0 = D0-RX0 D1-TX0 (TEL/OSD), Serial1 = D12-RX1 D11-TX1 (GPS)
- **1 I2C:** I2C1 PE0(SDA1) PE1(SCL1)
- **8 Channels In:** D7-CH1 D8-CH2 A0-CHS A1-CH4 A2-CH5 A3-CH6 A4-CH7 A5-CH8
- **6 PWMS Out:** D10-PWM1 D9-PMW2 D6-PWM3 D5-PWM4 D3-PWM5 D2-PWM6
- **1 LED:** D13
- **1 BUZZER:** D4
- **1 VBAT:** A6
- **1 CUR:** A7
 
# Pin outs
| Pin        | Func  | Port | P#        
| --- |-------------:|---| ---|
| D0  | RX0 - TEL/OSD
| D1  | TX0 - TEL/OSD   
| D2  | CH1-PPM|  
| D3 | CH2|
| D4| CH3 | 
| D5| PWM4 - LF |
| D6| PWM3-RR |
| D7| CH4 |
| D8| BUZZER|
| D9| PWM2-LR|
| D10| PWM1-RL |
| D11| TX1- GPS |
| D12| RX1-GPS|
| D13| LED |
| A0| CH5|
| A1| CH6
| A2| CH7
| A3| CH8
| A4| PWM5/SERVO1
| A5| PWM6/SERVO2
| A6| Bat
| A7| Cur
| PE0| SCL1
| PE1| SDA1

#Hardware
W | C | P
--- | --- | ---
IC  | Atmega328PB | MCU
IC | MPU6050| GYRO/ACC
IC |HMC5883| MAG
IC |BMP180 | BARO
IC |UBLOX7 | GPS

Pin|User|Port
--- | --- | ---
D0	|	RX0 - TEL/OSD	|	PORTD
D1	|	TX0 - TEL/OSD	|	PORTD
D2	|	PWM6 - CAM	|	PORTD
D3	|	PWM5 - CAM	|	PORTD
D4	|	BUZZER	|	PORTD
D5	|	PWM4 - LF	|	PORTD
D6	|	PWM3-RR	|	PORTD
D7	|	CH1	|	PORTD
D8	|	CH2	|	PORTB
D9	|	PWM2-LR	|	PORTB
D10	|	PWM1-RL	|	PORTB
D11	|	TX1- GPS	|	PORTB
D12	|	RX1-GPS	|	PORTB
D13	|	LED	|	PORTB
A0	|	CH3	|	PORTC
A1	|	CH4	|	PORTC
A2	|	CH5	|	PORTC
A3	|	CH6	|	PORTC
A4	|	CH7	|	PORTC
A5	|	CH8	|	PORTC
A6	|	Bat	|	PORTC
A7	|	Cur	|	PORTC
PE0	|	SCL1	|	
PE1	|	SDA1	|	
