# Vehicle monitoring using CAN protocol
This project was done for the course Microcontroller Architecture and Organization (ECE5042) at Vellore Institute of Technology, Vellore to explore and learn the usage of Embedded C.

Authors

     DATTAKUMAR MALKHEDE    [20MES0051]
     PRABHLEEN KAUR CHAWLA  [20MES0041]
     MEERA S NAIR           [20MES0040]
    
Guide

     Dr. Gerardine Immaculate Mary
     Department of Embedded Technology
     
Components
    
    Keil uvision5 (Simulator + IDE)
    Two ARM Cortex-M3 based microcontrollers-STM32F103
    LCD Display(16X2)
    Buzzer
    Temperature Sensor
    Speed Sensor
    Fuel Sensor
    
Aim

    Present Automobiles are being developed by more of electronics parts for efficient operation. Generally a vehicle is built with an analog driver-vehicle interface for indicating various vehicle status like speed, fuel level, engine temperature etc.
    
    The aim of the project is to develop and implement a vehicle monitoring system to improve the driver-vehicle interface. It uses an ARM based data acquisition system that uses ADC to bring all data from analog to digital format and visualize through LCD.
    
    The communication protocol used in this project is embedded networking by CAN which has efficient data transfer. In this system, one node acquires the data via sensors (switches).Each sensed parameter sends signal to the main node through CAN Bus and gives the appropriate output through the LCD.
    The proposed system is a cost effective, fast and reliable system.
    

