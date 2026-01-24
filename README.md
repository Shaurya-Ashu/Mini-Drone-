# About me 
Hi this is Shaurya a young innovator 
I like to make smart & cool project , and specially i am fascinated by flying things
So , today i am here try to make some things that can flys but also on a budget ~ $33
# Mini-Drone-

<img width="2880" height="1226" alt="Image" src="https://github.com/user-attachments/assets/6c468552-0975-4e9e-8316-51dba1fa7098" />
It's a mini quadcopter powered by 
- Xiao ESP32 S3 (FC)
- MPU 6050
- 8520 Coreless Motor 2xCW & 2xCCW
- 55mm Propeller 2xCW & 2xCCW
- Coustom motor drive:
    • SI2300 1N-MOSFET 4x
    • 1N4148 Diode 4x
    • 10k ohm Resistor 4X

- CRSF reciver ( I have an ER8G )
- A transmitter supporting you Reciver ( I have an Radio Master Pocket)

# Frame
The frame is going to be 3D model 
<img width="882" height="654" alt="Image" src="https://github.com/user-attachments/assets/64c97c8e-371e-471b-a67e-00e8dd91a03e" />
The housing is designed to fit all the component including battery, only the receiver is kept outside tied with a zip tie.
# Schematics
  <img width="1169" height="827" alt="Schematic_Mini-Drone_2025-12-14" src="https://github.com/user-attachments/assets/31eb330a-89d8-4b81-ad72-a2e1666bdc45" />
  Here is the break down of the connections 
  MOTORS-
  M1 --> A8
  M2 --> A3
  M3 --> A2
  M4 --> A0

  MPU6050-
  SDA --> A4
  SCL --> A5

  CRSF-
  RX --> D7
  TX --> D6

  Battery Voltage Telemetry-
  Vin --> A1
  

# PCB 
The PCB is designed for refrence and future usage 

TOP SIDE-
<img width="483" height="567" alt="Screenshot 2025-12-15 at 3 54 31 PM" src="https://github.com/user-attachments/assets/f39fb7e2-5632-46c8-97d1-43c2efea6e2c" />

BOTTOM SIDE-
<img width="491" height="561" alt="Screenshot 2025-12-15 at 3 54 56 PM" src="https://github.com/user-attachments/assets/ab290610-5290-4491-a23b-38bfa354ec23" />

The connection for the motors are on top
and for crsf , battry and MPU6050 are at bottom


<img width="523" height="604" alt="Screenshot 2025-12-14 at 10 42 23 PM" src="https://github.com/user-attachments/assets/bbc49268-90e9-41c4-b215-e9f22f6bebd6" />

# Firmware

This project uses open-source flight controller firmware from the ESP-FC project,
developed by rtlopez.

- Original firmware repository:
  https://github.com/rtlopez/esp-fc

- My fork :
  https://github.com/Shaurya-Ashu/esp-fc-firmware-reference




