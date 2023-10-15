# Week-3-Homework
Week 3 Homework -Making Embedded  
BLinky LEDS:  
	HAL_GPIO_TogglePin(GPIOD, GPIO_PIN_13);  
	HAL_GPIO_TogglePin(GPIOD, GPIO_PIN_14|GPIO_PIN_15);  
	HAL_Delay(1000);  
Blink LED using the USER button:  
HAL_GPIO_WritePin(GPIOD, GPIO_PIN_12, myPushButton);  
	HAL_Delay(100);  

Questions:
What build environment are you using? 
I am using the  STM32CubeMxIDE

