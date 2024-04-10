###  DATE: 13.03.24

###  NAME: KEERTHIKA.S
###  ROLL NO :212223040093
###  DEPARTMENT: CSE



# EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD

## Aim: To Interface a Digital output (LED) to ARM IOT development board and write a  program to blink an led 
## Components required: STM32 CUBE IDE, ARM IOT development board,  STM programmer tool.
## Theory 
The full form of an ARM is an advanced reduced instruction set computer (RISC) machine, and it is a 32-bit processor architecture expanded by ARM holdings. The applications of an ARM processor include several microcontrollers as well as processors. The architecture of an ARM processor was licensed by many corporations for designing ARM processor-based SoC products and CPUs. This allows the corporations to manufacture their products using ARM architecture. Likewise, all main semiconductor companies will make ARM-based SOCs such as Samsung, Atmel, TI etc.

What is an ARM7 Processor?
ARM7 processor is commonly used in embedded system applications. Also, it is a balance among classic as well as new-Cortex sequence. This processor is tremendous in finding the resources existing on the internet with excellence documentation offered by NXP Semiconductors. It suits completely for an apprentice to obtain in detail hardware & software design implementation.
LPC2148 Microcontroller
 The LPC2148 microcontroller is designed by Philips (NXP Semiconductor) with several in-built features & peripherals. Due to these reasons, it will make more reliable as well as the efficient option for an application developer. LPC2148 is a 16-bit or 32-bit microcontroller based on ARM7 family.
Features of LPC2148
The main features of LPC2148 include the following.
•	The LPC2148 is a 16 bit or 32 bit ARM7 family based microcontroller and available in a small LQFP64 package.
•	ISP (in system programming) or IAP (in application programming) using on-chip boot loader software.
•	On-chip static RAM is 8 kB-40 kB, on-chip flash memory is 32 kB-512 kB, the wide interface is 128 bit, or accelerator allows 60 MHz high-speed operation.
•	It takes 400 milliseconds time for erasing the data in full chip and 1 millisecond time for 256 bytes of programming.
•	Embedded Trace interfaces and Embedded ICE RT offers real-time debugging with high-speed tracing of instruction execution and on-chip Real Monitor software.
•	It has 2 kB of endpoint RAM and USB 2.0 full speed device controller. Furthermore, this microcontroller offers 8kB on-chip RAM nearby to USB with DMA.
•	One or two 10-bit ADCs offer 6 or 14 analogs i/ps with low conversion time as 2.44 μs/ channel.
•	Only 10 bit DAC offers changeable analog o/p.
•	External event counter/32 bit timers-2, PWM unit, & watchdog.
•	Low power RTC (real time clock) & 32 kHz clock input.
•	Several serial interfaces like two 16C550 UARTs, two I2C-buses with 400 kbit/s speed.
•	5 volts tolerant quick general purpose Input/output pins in a small LQFP64 package.
•	Outside interrupt pins-21.
•	60 MHz of utmost CPU CLK-clock obtainable from the programmable-on-chip phase locked loop by resolving time is 100 μs.
•	The incorporated oscillator on the chip will work by an exterior crystal that ranges from 1 MHz-25 MHz
•	The modes for power-conserving mainly comprise idle & power down.
•	For extra power optimization, there are individual enable or disable of peripheral functions and peripheral CLK scaling.
 
 

## Procedure:
 1. click on STM 32 CUBE IDE, the following screen will appear 
 ![226189166-ac10578c-c059-40e7-8b80-9f84f64bf088](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/9e2da654-a495-42d7-a8c1-ebf8c692d4d3)

 2. click on FILE, click on new stm 32 project 
![226189215-2d13ebfb-507f-44fc-b772-02232e97c0e3](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/f2f244ef-797b-4ee1-bf59-d3ff580baaf3)
![226189230-bf2d90dd-9695-4aaf-b2a6-6d66454e81fc](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/47867535-dcca-4124-b97a-44b65d01e797)

3. select the target to be programmed  as shown below and click on next 
![226189280-ed5dcf1d-dd8d-43ae-815d-491085f4863b](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/f099901b-8559-446b-84cd-9a647167377f)



4.select the program name 
![226189316-09832a30-4d1a-4d4f-b8ad-2dc28f137711](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/cad29090-50be-471c-a33d-2366680d905c)


5. corresponding ioc file will be generated automatically 
![226189378-3abbdee2-0df6-470f-a3cd-79c74e3d3ad8](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/5bfaedd9-995c-4e1e-ad70-8918bc380f8a)

6.select the appropriate pins as gipo, in or out, USART or required options and configure 
![226189403-f7179f1a-3eae-4637-826b-ab4ec35ba1e1](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/347941a6-2d8b-487a-af42-ea22449aeb5a)


![226189425-2b2414ce-49b3-4b61-a260-c658cb2e4152](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/b023db03-4ea8-4929-81eb-f5fe48b50baa)


7.click on cntrl+S , automaticall C program will be generated 
![226189443-8b43451d-0b14-47e4-a20b-cc09c6ad8458](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/3d1968b6-7768-42d7-9391-22cf683eebfd)

![226189450-85ffa969-2ffb-4788-81e5-72d60fdda0f1](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/58cb6f84-176a-49c3-aeaa-6bfe6c1ac021)

8. edit the program and as per required
![226189461-a573e62f-a109-4631-a250-a20925758fe0](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/4248efac-4350-42a9-bb8f-d1453861f40a)


9. use project and build all 
![226189554-3f7101ac-3f41-48fc-abc7-480bd6218dec](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/cd7b4ece-3e26-4dd6-b8b8-6f95c3c3d179)


10. once the project is bulild 
![226189577-c61cc1eb-3990-4968-8aa6-aefffc766b70](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/755b862b-6a99-4867-94a2-7c121d5f4cc4)

11. click on debug option 
![226189625-37daa9a3-62e9-42b5-a5ce-2ac63345905b](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/67e2cfbf-74f3-45a7-95ee-aeee179b1eee)

12. connect the stm nucleo board and click on run 

![226189649-b5dff389-91df-4eca-b84a-1127c6562637](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/8c4b0067-9367-4b07-9295-b2d4fa42592d)





## STM 32 CUBE PROGRAM :

```
#include "main.h"
void SystemClock_Config(void);
static void MX_GPIO_Init(void);
int main(void)
{
    SystemClock_Config();

    MX_GPIO_Init();
    while (1)
  {
    	  HAL_GPIO_WritePin(GPIOA, GPIO_PIN_0, GPIO_PIN_SET);
	  	  	  HAL_Delay(500);
	  HAL_GPIO_WritePin(GPIOA, GPIO_PIN_0, GPIO_PIN_RESET);
	  	  	  HAL_Delay(500);
   
  }
 }


```

## OUTPUT  :
![310564033-8ac5345e-d2d4-41b8-89e4-0c6b7e09f005](https://github.com/keerthigasudhagar/EXPERIMENT-01-INTERFACING-A-DIGITAL-OUTPUT-TO-IOT-DEVELOPMENT-BOARD-/assets/163229129/2fd98fa3-43bc-410f-a90e-419e07c73e74)
![Uploading 310564080-9413927e-e517-4946-a3d9-4f1591186e71.jpg…]()


 

 
## Result :
Interfacing a digital output with ARM microcontroller based IOT development is executed and the results are verified.
