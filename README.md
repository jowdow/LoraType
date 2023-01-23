[![LoraType](https://raw.githubusercontent.com/AutomationArt/LoraType/main/Image/LoraType.png "LoraType")](https://raw.githubusercontent.com/AutomationArt/LoraType/main/Image/LoraType.png "LoraType")

### LoraType..|
First of all, our priority is to make the user experience as simple as possible. It only has an on/off button, a widespread QWERTY-keyboard and a cute e-ink display. That’s it. However, in spite of simplicity the Loratype can be used as a tiny PC with possibility for programming and adding new functions thanks to embedded wi-fi, bluetooth and esp32. Welcome on board and feel like home, dear like-minded fellows! There are some extra features: the LoRa-protocol is noise-resistant, and the communication range is about 1 km in a city and up to 7 km in line-of-sight coverage. And of course it is totally free of charge, Loratype has been created not by a Corporation for population, but by people for people . Thus, in any emergency condition we will honorably stay together!

### How Does it Work?
1. Turn on the device
2. Wait a moment (search for interlocutors in the mesh network)
3. Chat, stay in touch without paying for traffic!

### Device features
- FREE OF CHARGE (Lora user doesn't need to pay for the service)
- AUTONOMOUS DEVICE (I am developing LoraType to be completely autonomous)
- INDEPENDED OF INTERNET, 5G, GSM ETC. (Stay connected without Internet!)

### Use cases
- During disasters like earthquakes, floods, hurricanes, and fires among others
- Hiking or camping far away from cities, receptions etc
- In a war zone or mass protests (when government could shut down the internet)
- When you need free messaging (your plan is expired or you do not have a mobile data on your phone)

### Security
LoRa contains all the fundamental building blocks needed and used by any modern wireless technology, and it does so using the AES-128 standard. ([Lora Security](https://lora-alliance.org/wp-content/uploads/2020/11/lorawan_security_whitepaper.pdf "Lora Security"))

------------
### We have passed several important stages of product development, which is very important

[![LoraType](https://raw.githubusercontent.com/AutomationArt/LoraType/main/Image/LoraType_v1tov2.png "LoraTypePCB")](https://raw.githubusercontent.com/AutomationArt/LoraType/main/Image/LoraType_v1tov2.png "LoraTypePCB")

[![LoraType_Case](https://github.com/AutomationArt/LoraType/blob/main/3D%20model%20-%20Case/V1/LoraType_FirstCase.png "LoraTypePCB")](https://github.com/AutomationArt/LoraType/blob/main/3D%20model%20-%20Case/V1/LoraType_FirstCase.png "LoraTypePCB")

------------

### Current PCB release

[![LoraType](https://raw.githubusercontent.com/AutomationArt/LoraType/main/Image/LoraType_PCB.png "LoraTypePCB")](https://raw.githubusercontent.com/AutomationArt/LoraType/main/Image/LoraType_PCB.png "LoraTypePCB")

### Specifications

|   |   |
| ------------ | ------------ |
| **Display**  | Durable low power screen that can store information for up to 6 months without consuming power (1.54 inch e-paper display module partial refresh E-ink screen, [GDEH0154D67](https://www.good-display.com/product/1.54-inch-e-paper-display-module-partial-refresh-E-ink-screen,-GDEH0154D67-208.html "GDEH0154D67"))   |
| **Main controller ** | The [ESP32](https://www.espressif.com/sites/default/files/documentation/esp32-wroom-32e_esp32-wroom-32ue_datasheet_en.pdf "ESP32") module gives the device great advantages in development and functionality. You only need to replace the firmware over the air   |
| **Lora Module**  | The [E22](https://www.ebyte.com/en/product-view-news.aspx?id=437 "E22") series is the first wireless module in China to adopt Semtech's SX1262, SX1268 RF chip. This chip provides a variety of modulation methods, such as LoRaTM and traditional GFSK. Its special LoRaTM modulation method increases the communication distance.    |
| **Keyboard ** | [TCA8418RTWR](https://www.ti.com/product/TCA8418/part-details/TCA8418RTWR "TCA8418RTWR") Great built-in simultaneous click capabilities. Keyboard with built-in protection against electrostatic discharge.   |
| **Charger **| [TP4056](http://www.tp4056.com/datasheet/ "TP4056") Proven by time and many users. Has battery protection. Battery will last longer |
| **LDO regulator**  | [AP2112](https://www.digikey.com/en/products/detail/diodes-incorporated/AP2112K-3-3TRG1/4470746 "AP2112") is CMOS процес low dropout linear regulator with enable function  |

##### We used good solutions from Good Display, Espressif, Texas Instruments


### Additional features for the community

[![LoraTypeForDiy](https://raw.githubusercontent.com/AutomationArt/LoraType/main/Image/LoraType_ForDIY.png "LoraTypeForDiy")](https://raw.githubusercontent.com/AutomationArt/LoraType/main/Image/LoraType_ForDIY.png "LoraTypeForDiy")

For device owners, the ability to add DIY add-ons is available.
- Light firmware (UART)
- Adding your own sensors to the device (via I2C bus)
- Jtag debugging
- Lipo battery change
- Using integrated antenna
- Connection of external power generators

### Comparisons
|   #| LoraType  |  RippleQWERTY  |   ArmaChat | LoRa Msg  | ESPboy LORA  |
| ------------ | ------------ | ------------ | ------------ | ------------ | ------------ |
| **Open Source ** |  yes |  yes | yes |  yes | yes  |
|  **Battery** | Li-po  | It is not specified exactly  | 18650  | 1500mA Li-Po |   |
|  **Case** |  yes (choice is available+stl) |  yes (+stl)  |  pcb case  | yes (+stl) |  yes (+stl)  |
|  **Size** |  110mm*60mm | not specify |  76mm x 71mm | 70mm*105mm  |  90mm*50mm |     
|  **Price** |   |   |   |   |   |

### Funding goal

### Manufacturing Plan & Risks

### Mentions about LoraType

------------

### Support & Documentation
**This project is open source. We opened all circuits and software**

- [STL models for cases](https://github.com/AutomationArt/LoraType/tree/main/3D%20model%20-%20Case "STL models for cases") 
- [Component Documentation](https://github.com/AutomationArt/LoraType/tree/main/Documents "Component Documentation")
- [Software Example](https://github.com/AutomationArt/LoraType/tree/main/Software "Software Example")