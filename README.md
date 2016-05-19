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
| Pin        | Func         
| --- |-------------:|
| D0  | RX0 - TEL/OSD
| D1  | TX0 - TEL/OSD   
| D2  | PWM6 - CAM|  
| D3 | PWM5 - CAM|
| D4| BUZZER | 
| D5| PWM4 - LF |
| D6| PWM3-RR |
| D7| CH1 |
| D8| CH2|
| D9| PWM2-LR|
| D10| PWM1-RL |
| D11| TX1- GPS |
| D12| RX1-GPS|
| D13| LED |
| A0| CH3|
| A1| CH4
| A2| CH5
| A3| CH6
| A4| CH7
| A5| CH8
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
