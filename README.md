
<p align="center">
  <img src="assets/MacropadV1_LOGO.png"
       alt="Macropad V1"
       width="700">
</p>

<h1 align="center">MACROPAD V1</h1>

<p align="center">
  <strong>
    A wireless Raspberry Pi Pico W macropad with RGB lighting,
    rotary encoders, an OLED display and haptic feedback!
  </strong>
</p>

<div align="center">

![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=for-the-badge&logo=kicad&logoColor=white)
![Raspberry Pi](https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white)
![Fusion 360](https://img.shields.io/badge/Fusion_360-FF6C00?style=for-the-badge&logo=autodesk&logoColor=white)

</div>

<img width="5443" height="3062" alt="IMG_0485" src="https://github.com/user-attachments/assets/1306d6c4-bb57-4d93-9579-427a55bfa642" />


I've made this as in my experience off the shelf macropads are way too expensive for the features they offer and are also very generic.
This is an alternative that is actually unique with multiple customizable switches, rotary encoders, a display, Wireless & Wired connectivity and insanely good haptics.


## Key Features

- **11 programmable keys** for custom shortcuts, macros, and commands
- **2 dedicated profile keys** for switching between profiles
- **Dual rotary encoders** for profile selection, volume, endless scrolling, and custom controls
- **OLED display** for showing the active profile and other information
- **Haptic feedback** for responsive physical feedback
- **QMK firmware** for controlling everything through the Pico
- **Vial configuration** for remapping keys and controls without reflashing firmware


## PCB 

Designed in KiCad!

### Schematic

### Front:

<img width="1019" height="729" alt="Screenshot 2026-09-03 at 1 07 09 PM" src="https://github.com/user-attachments/assets/cb8cc3bf-c179-4dec-89ae-4d0560963f74" />

### Back: 

<img width="1015" height="719" alt="Screenshot 2026-09-03 at 1 08 18 PM" src="https://github.com/user-attachments/assets/c384b454-e76a-47fe-bca7-3a87beef0cff" />




# Schematics
<img width="967" height="643" alt="Screenshot 2026-06-30 at 12 22 28 AM" src="https://github.com/user-attachments/assets/7fc7e8dc-42b9-428f-847a-203aa43e52eb" />


I am using the TP4056 module for charging the battery; MT3608 for boosting the single cell voltage; DRV2605l for accurately driving the haptics motors; Raspberry Pi Pico W for controlling everything, one more reason as to why I chose this MC is its amount of GPIO's and wireless connectivity.

# Bill Of Materials:

| SR. No: | Name:                     | Quantity: | Unit Price: (INR) | Total Price:(INR) | Unit Price: (USD) (Approx) | Total Price:(USD)(Approx) | Link:                                                                                                            |
|---------|---------------------------|-----------|-------------------|-------------------|----------------------------|---------------------------|------------------------------------------------------------------------------------------------------------------|
| 1       | Raspberry Pi Pico W       | 1         | ₹631.00           | ₹631.00           | $7.00                      | $7.00                     | https://robu.in/product/raspberry-pi-pico-w/                                                                     |
| 2       | EC11 Rotary Encoder       | 2         | ₹55.00            | ₹110.00           | $1.00                      | $2.00                     | https://robu.in/product/hongyan-ec11h-7ce20p1zy20-rotary-encoder-with-push-button-switch-vertical-plug-in-5-pin/ |
| 3       | Cherry MX Switch*35 pack  | 1         | ₹1,880.00         | ₹1,880.00         | $20.00                     | $20.00                    | https://keychron.in/product/cherry-mx-switch-set/                                                                |
| 4       | TP4056 Module             | 1         | ₹15.00            | ₹15.00            | $1.00                      | $1.00                     | https://robu.in/product/tp4056-1a-li-ion-lithium-battery-charging-module-mini-usb/                               |
| 5       | MT3608 Module             | 1         | ₹35.00            | ₹35.00            | $1.00                      | $1.00                     | https://robu.in/product/mt3608-2a-max-dc-dc-step-up-power-module-booster-power-module/                           |
| 6       | DRV2605L Module           | 1         | ₹1,200.00         | ₹1,200.00         | $13.00                     | $13.00                    | https://robu.in/product/adafruit-drv2605l-haptic-motor-controller-stemma-qt-qwiic/                               |
| 7       | OLED Display              | 1         | ₹600.00           | ₹600.00           | $7.00                      | $7.00                     | https://robu.in/product/waveshare-128x32-general-0-91inch-oled-display-module/                                   |
| 8       | SK6812 mini - e LEDS      |           | --                | --                | --                         | --                        | Sourced Locally                                                                                                  |
| 9       | Battery (3.7v)            | 1         | ₹500.00           | ₹500.00           | $6.00                      | $6.00                     | Sourced Locally                                                                                                  |
| 10      | SPDT Switch               | 1         | ₹600.00           | ₹600.00           | $7.00                      | $7.00                     | https://robu.in/product/1-month-warranty-261/                                                                    |
| 11      | JST Connectors (Assorted) | --        |                   |                   |                            |                           | Sourced Locally                                                                                                  |
| 12      | PCB Fabrication           | 1         | ₹1,700.00         | ₹1,700.00         | $17.00                     | $17.00                    | JLC PCB                                                                                                          |
|         |                           | TOTAL:    | ₹7,216.00         | ₹7,271.00         | $80.00                     | $81.00                    |                                                                                                                  |


