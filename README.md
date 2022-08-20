# STM32_UART_dma
This code will transmit data (using SSCOM serial command software) to USART1 and STM32 blue pill will reply with the same data to USART1. DMA's Idle Interrupt is used to process the received data.

This project was developed with :-<br /> 
1. STM32CubeMX 6.0.1<br /> 
2. Keil uVision 5.32.0.0<br />

List of hardwares used :-<br />
1. STM32 blue pill 
2. DC-DC converter module
3. lithium polymer battery
4. ST-Link V2 programmer
5. CH340 USB to Serial-<br />

![My Image](images/testbed.jpg)

![My Image](images/sscom_Dma.png)

![My Image](images/dma_idle_interrupt.png)

Reference : <br />
1. https://blog.csdn.net/as480133937/article/details/104827639?utm_medium=distribute.pc_relevant.none-task-blog-2%7Edefault%7EBlogCommendFromBaidu%7Edefault-9.control&depth_1-utm_source=distribute.pc_relevant.none-task-blog-<br />
2. http://www.bepat.de/2020/12/02/stm32f103c8-uart-with-dma-buffer-and-idle-detection/
