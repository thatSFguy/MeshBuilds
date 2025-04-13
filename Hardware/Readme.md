Here are a couple builds

1. ProMicro + E22
![alt text](https://github.com/thatSFguy/MeshBuilds/blob/main/Hardware/Images/ProMicro%20NRF%20with%20E22%20900M30S.png?raw=true)
   
3. ProMicro + Seeed Wio SX1262
![alt text](https://github.com/thatSFguy/MeshBuilds/blob/main/Hardware/Images/ProMicro%20NRF%20with%20SEEED%20WIO%20SX1262.png?raw=true)
![alt text](https://github.com/thatSFguy/MeshBuilds/blob/main/Hardware/Images/Mounted%20PM%20and%20Seeed.jpg?raw=true)

4. Adding Battery voltage:
   - You need to add two 1M Ohm resistors power divider formation.
     - R1:  from B+ to 031 Pin
     - R2:  from B- to 031 Pin
   - Adjust the ADC in the Power setting to somewhere around 2.3, and use the calculator to get the correct setting.
