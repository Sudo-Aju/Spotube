<div align="center">

# <img src="./media/logo.png" alt="spotube logo" width="100%" />

a physical spotify controller

<p>
<img src="https://img.shields.io/badge/status-in%20development-8A2BE2?style=for-the-badge">
<img src="https://img.shields.io/badge/open%20source-yes-00C853?style=for-the-badge">
<img src="https://img.shields.io/badge/powered%20by-esp32--s3-1E88E5?style=for-the-badge">
<img src="https://img.shields.io/badge/display-1.5%22%20ips-FF6D00?style=for-the-badge">
</p>

### *a dedicated physical interface for controlling spotify.*

<img src="./media/render1.png" width="85%">

</div>

---

# overview

**spotube** is a compact physical spotify controller built around an **esp32-s3**, 1.5" lcd, mechanical switches, and a rotary encoder.

it provides physical controls for spotify playback while displaying the current track.

---

# gallery

<div align="center">

<img src="./media/render1.png" width="90%">
<img src="./media/render2.png" width="90%">
<img src="./media/render3.png" width="90%">

</div>

---

# features

* spotify integration
* esp32-s3
* 1.5" ips display
* cherry mx switches
* ec11 rotary encoder
* wi-fi
* custom pcb
* custom enclosure
* physical playback controls

---

# hardware stack

| component    | description             |
| ------------ | ----------------------- |
| mcu          | waveshare esp32-s3 mini |
| display      | waveshare 1.5" ips lcd  |
| switches     | cherry mx               |
| encoder      | ec11                    |
| connectivity | wi-fi                   |
| pcb          | custom kiCad design     |
| case         | custom 3d printed       |

---

# assembly

## 1. order the pcb

generate gerbers from:

```bash
PCB/Spotube.kicad_pcb
```

and send them to your preferred manufacturer.

## 2. order components

all components are listed in:

```bash
BOM(6).csv
```

## 3. assemble

* solder the switches
* solder the ec11 encoder
* install the esp32-s3
* connect the display
* assemble the enclosure
* install the keycaps

---

# firmware

firmware is located in:

```bash
spotube.ino
```

the firmware handles:

* wi-fi
* spotify api
* display
* buttons
* rotary encoder

## setup

configure your:

```cpp
wifi ssid
wifi password
spotify client id
spotify client secret
```

then upload the firmware to the esp32-s3.

---

# pcb

designed in **kicad**.

```bash
PCB/
├── Spotube.kicad_pcb
├── Spotube.kicad_sch
├── Spotube.kicad_pro
└── Spotube.kicad_prl
```

---

# enclosure

the complete assembly is available as:

```bash
Assembly.step
```

designed around the custom pcb and components.

---

# bom

a

---

# repository

```text
Spotube/
├── PCB/
├── CAD/
├── media/
├── spotube.ino
├── BOM(6).csv
└── README.md
```

---

# current status

* [x] concept
* [x] pcb
* [x] schematic
* [x] enclosure
* [x] firmware
* [x] display
* [ ] final build
* [ ] complete spotify controls

---

# contributing

contributions and suggestions are welcome.

```bash
git clone https://github.com/Sudo-Aju/Spotube.git
cd Spotube
```

fork → modify → commit → pull request

---

# creator

### azmeer pirani

17 • india • @fallout

built with a love for:

* hardware
* pcb design
* music
* embedded systems
* experimental products

---

# license

this project is licensed under the **mit license**.

---

<div align="center">

# spotube

### *your music. your controls.*

</div>
