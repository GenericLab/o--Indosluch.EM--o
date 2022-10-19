![IndoSluch Logo by Helmi](https://github.com/GenericLab/o--Indosluch.EM--o/raw/main/Indosluch_Logo_color.jpg)

# o--Indosluch.EM--o
New pisibi and circuit for EM-sniffer, inspired by LOM's Elektrosluch (Error Static Zapper too), SOMA Ether, 1010 Detektor and Franzis' Bat-Detector and many others...

Goal: Make an affordable new and kinda modified / improved version of an EM sniffer in Yoygakarta, Indonesia. Use mainly parts that can be sourced locally on the common online shops or local stores.

Ideas:
* runs on 3V, LiPo, USB charging and / or powerbank
* single input / mono (mbe switched plug, to insert self-made antennas/coils)
* internal small speaker
* Volume knob
* Frequency shifting / demoluation of higher bandwidths to the audio range (with a knob to select bands)
* output mini-jack, 3.5mm
* beautifully crafted local teakwood casing
* ...

# Collaborators
* dusjagr
* Fiky
* Ucok

## Counselors
* Uwe, the Opa Master
* Ralf, another Opa Master

# Case study and mock-ups

![IndoSluch Logo by Helmi](https://github.com/GenericLab/o--Indosluch.EM--o/raw/main/photos/Indosluch_engraved_mockup.jpg)

# Reworking the Bat-Detector

![3 PCBs version](https://github.com/GenericLab/o--Indosluch.EM--o/raw/main/Indosluch_AM/Indosluch_AM_PCB.3d.jpg)

Kicad version of the Fledermaus Detektor (bat-detector): https://www.elektronik-labor.de/Lernpakete/Fledermaus.html

![3 PCBs version](https://github.com/GenericLab/o--Indosluch.EM--o/raw/main/Indosluch_AM/Indosluch_AM_schematic.jpg)

# Inspriational Sources

## LOM's Elektrosluch (open Source)

Based on a single chip dual channel bi-polar Audio Operational Amplifier, opa1612, can be replaced by cheaper more noisier TL074  (suchas the Error Zapper). Runs on 9V. 

https://github.com/LOM-instruments/Elektrosluch-3-plus

## ERROR Zapper

Seems to be a clone, cheaper version of the Elektrosluch. No credits given :-(
Runs on 9V.

https://www.errorinstruments.com/a-60734445/new-synthe-noise-instruments-for-sale/error-zapper/#description

## SOMA Ether (everything is waves)

Based on a fist stage transistor amplification, and some kinda extra antenna on the board for higher frequency bands and a potentiomter for atenuation. Second stage with SSM2211 audio amplifier. Runs on 3V.

https://somasynths.com/ether/

## 1010 Detektor by Martin Howse (open Source)

Based on AD8313 HF-detektor (kinda expensive) and fist stage amplification with LM358, second LM386. Runs on 4.5V.

http://www.1010.co.uk/org/detektor.html

## Elektronik-Labor |  Bat-Detector (open Source) in german

Based on a first stage single transistor amplification, and a radio AM/FM chip CD2003 for high-frequency demodulation, frequency is adjusted with 555 timer. Final amplification stage with LM386. Original design runs on 9V, but lower voltage should work.

https://www.elektronik-labor.de/Lernpakete/Fledermaus.html
