# include
智能家居系列_四色灯

注：本项目只供学习和参考，请勿将本项目用于商业行为

本项目使用STM32F103系列芯片，软件为Keil5。

本项目是通过通用定时器TIM的4个通道进行PWM输出，控制灯光，可实现使用多个通用TIM驱动多个灯光，不局限于4个灯。

设有一个按钮（on/off/调色），灯具有记忆功能，可实现断电上电保留上一次灯的颜色。

灯除了单色调换外还有快闪模式和慢闪模式，快闪模式中每1.5s切换一次颜色，慢闪模式灯的颜色渐渐变换。

