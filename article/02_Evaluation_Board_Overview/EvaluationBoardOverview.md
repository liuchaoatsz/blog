# IAR RISC-V GD32V EAL-board overview


> ![](.\boardoverview.png)<br/>
 
|Device|Ref. Peripheral|
|---|---|
|GigaDevice GD32V103RBT8
Osemi SPI Flash|SPI1|
Sensirion Temp/Humidity Sensor|I2C shared with [3]|
Nexperial Accelerometer|I2C shared with [2]|
Mic|ADC01_IN8(PB0)|
Earbud Jack|DAC_OUT0/DAC_OUT1/ADC01_IN0(PA0)|
Potentiometer|ADC01_IN1(PA1)|
Light Sensor|ADC01_IN11(PC1)|
Tri-Color LED|PWM|
USB Serial|UART|
32768Hz XTAL|RTC
Debug |JTAG|
Trace |NA|
<br/>

  This MCU(**GD32V103RBT8**) on the Eval-board is produced by **GigaDevice Semiconductor** .It's a 32-bit MCU based on __RISC-V__ Core.Benefit from adopting __Harvard structure__,128KB Code Flash and 32KB SRAM can be operated with separate buses .Both R/W operation  is at CPU clock(HCLK,**Up to 108MHz**) speed with zero wait states.<br/>
  As a general-purpose MCU , it is integrated with plentiful peripherals ,Including: **Timers**/**Watchdog**/**RTC**/**U(S)ART**/**I2C**/**SPI**/**I2S**/**CAN**/**USBFS**/**ADC**/**DAC**/**EXTI**.<br/>
  In the next serveral days , I will try to those peripherals one by one.  <br/>

- Reference Document:
   >- [GD32F103_Datasheet_Rev_1.2.pdf](GD32VF103_Datasheet_Rev_1.2.pdf)<br/>
   >- [Getting Started Guide IAR RISC-V GD32V Evaluation board.pdf](./Getting%20Started%20Guide%20IAR%20RISC-V%20GD32V%20Evaluation%20board.pdf)<br/>  
   >- [IAR RISC-V GD32V Eval Schematics.pdf](IAR%20RISC-V%20GD32V%20Eval%20Schematics.pdf)<br/>