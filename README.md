# SPOTUBE

SPOTUBE is a compact, DIY desktop media station designed to provide a tactile and visual interface for your favorite streaming services (I MOSTLY USE SPOTIFY so ill use for that 😁).
<img width="1415" height="1321" alt="Screenshot 2026-03-19 at 23 48 43" src="https://github.com/user-attachments/assets/be9196ed-3878-4711-a151-355ebeb05ba1" />


## What does the project do?
The SPOTUBE device acts as a dedicated hardware controller and display for media playback. By leveraging the ESP32-C3's Wi-Fi capabilities, it communicates with APIs (like Spotify or YouTube) to:
* **Display Real-time Data:** Show current song titles, artists, and album art on the 1.8" TFT screen.
* **Tactile Control:** Use mechanical Cherry MX switches to play/pause, skip tracks, or toggle playlists.
* **Portable Design:** Housed in a custom 3D-printed shell, it sits perfectly on a desk as a functional piece of tech art.

## Bill of Materials
| Name                                                         | Purpose         | Cost Per Item (USD) | Quantity | Total (USD) | Link | Distributor        |
|:-------------------------------------------------------------|:----------------|--------------------:|---------:|------------:|:-----|:-------------------|
| 3D print model                                               | Shell           |                   5 |        1 |           5 | [Link](https://github.com/hackclub/print-legion) | Hack Club          |
| Cherry MX Keycaps                                            | Keycaps         |                   6 |        1 |           6 | [Link](https://www.amazon.in/STYLEHEAVEN-Transparent-Keycaps-Cherry-Switches/dp/B0GFP1XJ9Z/ref=sr_1_3?crid=DYB9DOR1TQBR&dib=eyJ2IjoiMSJ9.kKc3HdH17AhE-nTQrQ1SxfVaJhYmeFbPm0835eVz_-jbeImT-htLy8qY5z9y7LFMVcU5GMdK1seMkgmHiR4wWpi1BgtYqCacbU8EvAMouMm7CIndQuxGhQM03HZ5q1YC1rxEzez9aDCuzcTNcX6JDWGt8_kTfs1JOH-BJ0gKga4v_X3wMwq5lh2IEx95DAljB56USbKK-cMQQL0NlOBpbdPy96U8AAuc-0rmg1aAkgo.8iI3E4B-61cjV9iN_8wTP24XBDafzPccAuC3eiihFm8&dib_tag=se&keywords=cherry+mx+keycaps&nsdOptOutParam=true&qid=1773942374&sprefix=cherry+mx+keyca%2Caps%2C375&sr=8-3) | Amazon             |
| Cherry MX Switches                                           | Switches        |                   4 |        1 |           4 | [Link](https://neomacro.in/products/cherry-mx-switches?srsltid=AfmBOopQB-NQ1BO0dVkkvkxVeaQVPTGoN2zvkJHoIvh3QNb6hdRFlXtS) | Neo Macro          |
| M3X4 mm Brass Heat Set Threaded Round Insert Nut - Pack of 6 | Heatset Inserts |                   1 |        1 |           1 | [Link](https://www.amazon.in/M3X4-Brass-Threaded-Round-Insert/dp/B0B9NL8F74/ref=sr_1_6?crid=4XHSG7DE82FX&dib=eyJ2IjoiMSJ9.jSf9pEXSTtLSBrCZPvV8rjy5sJiwLvEN3PXR5QozJPsAiY0a3zu6d2eMFlCtvwc3lazSN3qwL78W-59c-F2lxC8eSm_g7yI2pQcVhqhLF0ZTlcaxr_mBZh80dUTecpa2n2oi8dVloWKQzb8cnK1K6XzuL9LXztnVKEaTjiPcTQCJJVEKcjAfRsyneHSKDAbe3HTdYqj45szwxJxZ59RBY0f4fnIMMKMSxA-nZUmDnciH63nYQ_eTNyiBXuaOVkBy9CxHedxJKnfBrpx4WTrILm3y449EAYZIIWevf4pucFc.ck8xHBHMe4U-TGfCyeApORo9GM7ryFF2eu3gQ-_vovg&dib_tag=se&keywords=M3+Heatset+inserts&qid=1773942041&sprefix=m3+heatset+inserts%2Caps%2C364&sr=8-6) | Amazon             |
| 1.8 inch SPI 128×160 TFT LCD Display Module                  | Screen          |                   6 |        1 |           6 | [Link](https://sharvielectronics.com/product/1-8-inch-spi-128x160-tft-lcd-display-module/?srsltid=AfmBOoqvsdgEor-hkL68La2pkhxe0j9GbAir5gN_4rwcEZz7Ym8qhYRu) | Sharvi Electronics |
| ESP32-C3 Mini                                                | Dev Board       |                   6 |        1 |           6 | [Link](https://www.amazon.in/OceanLabz-ESP32-C3-Super-Development-Bluetooth/dp/B0D2DM322M?s=bazaar&th=1) | Amazon             |

**Total Project Cost: $28.00**

## Components Overview
- **Shell**: 3D printed model.
- **Input**: Cherry MX Switches and Keycaps.
- **Assembly**: M3 Heatset Inserts.
- **Display**: 1.8 inch SPI TFT LCD.
- **Controller**: ESP32-C3 Mini.
