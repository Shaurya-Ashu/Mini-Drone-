# About me 
Hi this is Shaurya a young innovator 
I like to make smart & cool project , and specially i am fascinated by flying things
So , today i am here try to make some things that can flys .
# Mini-Drone-
<img width="2880" height="1226" alt="Genrative Design Esp32S3 Drone Frame v1" src="https://github.com/user-attachments/assets/646cab87-198d-4727-b35b-26df0137da60" />

It's a mini quadcopter powered by 
- Xiao ESP32 S3 (FC)
- MPU 6050
- 8520 Coreless Motor 2xCW & 2xCCW
- 55mm Propeller 2xCW & 2xCCW
- Coustom motor drive:
    • SI2300 1N-MOSFET 4x
    • 1N4148 Diode 4x
    • 10k ohm Resistor 4X

- CRSF reciver (I will be using RadioMaster XR2 Nano )
- A transmitter supporting you Reciver ( I have an Radio Master Pocket)

# Frame
The frame is going to be 3D modeled and printed
<img width="2880" height="1226" alt="Genrative_Design_Esp32S3_Drone_Frame_2026-Feb-13_04-50-57PM-000_CustomizedView5716981986_png_alpha" src="https://github.com/user-attachments/assets/05ee573a-f5bd-402d-9845-75dec8c777a7" />


The housing is designed to fit all the component including battery, and the receiver is kept at the top with an open  antenna.
# Schematics
  <img width="1250" height="797" alt="Screenshot 2026-02-12 at 12 55 18 PM" src="https://github.com/user-attachments/assets/676e1280-840d-4f8f-a8bf-5772beac4310" />

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
The PCB is designed in Kicad V9 
top render
<img width="693" height="503" alt="Screenshot 2026-02-13 at 7 20 46 PM" src="https://github.com/user-attachments/assets/575b3a5d-e82b-4ef3-9a90-c41e48d989c1" />
bottom render
<img width="582" height="528" alt="Screenshot 2026-02-13 at 7 20 58 PM" src="https://github.com/user-attachments/assets/103c9156-ec4c-4be5-a81f-91b89ea15608" />
<img width="1440" height="900" alt="Screenshot 2026-02-13 at 7 21 10 PM" src="https://github.com/user-attachments/assets/551d1947-9b9d-499d-a6d9-300d3a31e879" />


The connection for the motors are on top
and for crsf at top , battry at bottom


<img width="523" height="604" alt="Screenshot 2025-12-14 at 10 42 23 PM" src="https://github.com/user-attachments/assets/bbc49268-90e9-41c4-b215-e9f22f6bebd6" />

# Assembly
  The whole thing is designed to be fitted into that frame , it's all going to be secured by a damping screw. A zip tie for battery just to be secured, and the below given image shows how each component is placed in their.
  <img width="767" height="491" alt="Screenshot 2026-02-14 at 9 21 31 AM" src="https://github.com/user-attachments/assets/0251026f-6a3b-4f96-b88f-ef9dbacae415" />


# Firmware

This project uses open-source flight controller firmware from the ESP-FC project,
developed by rtlopez.

- Original firmware repository:
  https://github.com/rtlopez/esp-fc

- My fork :
  https://github.com/Shaurya-Ashu/esp-fc-firmware-reference




