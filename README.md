# stm32f10x-frame
This project is a fireware based on STM32F10x.

## Intro
  * Platform   : STM32F103ZTE6
  * Dev OS     : ARCHLinux
  * Toolchain  : arm-none-eabi-gcc + openocd

## Note
  - CMSIS core_m3.c "=r" modified to "=&r" according to arm-gcc compiler 
  - Bootstrap (startup file and link script) is a variant from ride7 of official files

## Versions
  - Ver1.0.0, Basis Project

## Bugs
  - System will step into inf loop after configuring TIM6 or FSMC

## TODO List
  - [x] Transplant STM32F10x FW. Based on official V3.5.0 (stsw-stm32054)
  - [x] Transplant uCOS-ii.
  - [ ] Makefile of this project. Reserved

