# Fox Transmitter and Receiver Hardware





## Bill Of Material



## Legal
- 433.92MHz [Page 94 of BIPT bandplan](https://www.bipt.be/file/cc73d96153bbd5448a56f19d925d05b1379c7f21/f05cbd16a076b4f72a4ea623a28cf4a6f8a84ff9/b24-en.pdf#page=94)
  - < 10mW e.r.p
  - < 10% duty cycle

## Interesting components
### Antenna's
- [433Mhz dipole antenna](https://www.bitsandparts.nl/RF-Antenne-Di-pole-433MHz-3dBi-male-SMA-p1106386)
- [433MHz antenna](https://www.tinytronics.nl/en/communication-and-signals/wireless/antennas/433mhz/433-mhz-antenna-with-sma-to-ufl-connector)
- [433MHz coil antenna](https://www.tinytronics.nl/en/communication-and-signals/wireless/antennas/433mhz/433mhz-antenna)
- [433MHz small 90 degrees antenna](https://www.tinytronics.nl/en/communication-and-signals/wireless/antennas/433mhz/433mhz-antenna-sma-small-90-degrees)
- [433MHz Yagi](https://www.ddselectronics.nl/webshop/antenne/antenne-toepassing-specifiek/antenne-toepassingspec-433mhz/3elem-400-470mhz-beam/)
- [433MHz Stubby](https://www.ddselectronics.nl/webshop/antenne/antenne-toepassing-specifiek/antenne-toepassingspec-433mhz/stubby-tqx400-433/)
- [Foldable UHF antenna](https://www.amazon.com/dp/B08FC7SQRN?ref_=pe_386300_442618370_TE_sc_as_ri_0)
- [433MHz Puck Antenna](https://www.ddselectronics.nl/webshop/puck-antenne-voor-433mhz/)


### Receivers
- [Aurel RX-4MM5](https://www.bitsandparts.nl/RF-Ontvanger-Aurel-RX-4MM5-F-433-92MHz-650201110G-p1063808)
- [Aurel 4M50RR30SF](https://www.bitsandparts.nl/RF-Ontvanger-Aurel-RX-4M50RR30SF-433-92MHz-650200527G-p1063795)
- [Aurel RX-4MM5](https://www.tinytronics.nl/en/communication-and-signals/wireless/rf/modules/aurel-rx-4mm5-f-433mhz-rf-receiver)

### Transmitters
- [Aurel TX-SAW-434-L](https://www.bitsandparts.nl/RF-Zender-Aurel-TX-SAW-434-L-433-92MHz-650201409G-p1922342)
  - Spurious emissions up to 4GHz (-40dBm) (might require a filter)
    -Bandpass filter: Taoglas DBP.433.T.A.30 (!! 3dB Loss)
- [HopeRf RFM85](https://www.tinytronics.nl/en/communication-and-signals/wireless/rf/modules/hoperf-rfm85w-433mhz-rf-transmitter)
  - 16dBm @ 5V  (~40mW)
  - 12dBm @ 3V3 (~16mW)
  - ASK/OOK

### Tranceivers
Aurel RTX-MID-5V
- [Aurel RTX-MID-5V](https://www.bitsandparts.nl/RF-Transceiver-Aurel-RTX-MID-5V-433-92MHz-650201044G-p1063809)
- [Aurel RTX-MID-5V](https://www.nodo-shop.nl/en/transmitters-and-receivers/41-aurel-tranceiver-rtx-mid-5v.html)
- [Datasheet](https://www.aurelwireless.com/wp-content/uploads/user-manual/650201033G_um.pdf)
  - 10mW
  - Has analog output (probably after AM peak detector) Making this a replacement.
- [RF Transceiver module HC12 SI4463 433MHz](https://www.bitsandparts.nl/RF-Transceiver-module-HC12-SI4463-433MHz-p1912071)
  - Board based on ST4463 tranceiver chip; with a moden build on top of it.
- [HopeRF RFM69HW](https://webshop.ideetron.nl/RFM69HW)
  - Also supports OOK mode
  -  +20 dBm (100mW)
  


### Enclosure
- [Drink bottle: 240mm x 75mm diameter](https://www.hema.com/nl-be/koken-tafelen/meenemen-bewaren/waterflessen-drinkbekers/waterfles-700ml-croissant-61110412.html)
- [Drink bottle: 147mm x 50mm diameter](https://www.action.com/nl-be/p/3013093/drinkbeker/)
- [Pelican case](https://amzn.eu/d/eDNpUkX)
  - [Original link with trace](https://www.amazon.com.be/-/nl/micro-beschermende-behuizing-gevoelige-waterdicht-transparant/dp/B002CM3ZU6/ref=sr_1_20?crid=2CJKDS4GZCZZ2&dib=eyJ2IjoiMSJ9.jSbVGTJEjEQ1gPS322DKIE5BbLCEVwCMBfLvMEBAmp6cMdRwYbB9iSHR8TaKx-T7w5n6qNiE0IXL7B85bTgG1ZvRvNJHpJcDkVHuXyHE_DgGXReHkE312KF2lz5GDpqqOCuJARLcPdWXDh4yFY01FuHalN4JIbGSoBtKr89HR_7rIwKk20SE4iEmzdn29xiOITuXsyrl3DXfVTXTlNjrCIhE43V3LJy6qEdbABM12aF-RYDJ3TvMMJnTT14Ob6N6nR4JR-y_4-6oUfMPR5Ym6yqBjc2K0DSHc5F3xidYuns.pYi-WWcLsJ2LM73WmBkXyXVmbORFwrCrMLrFrzVqD5k&dib_tag=se&keywords=pelican+case+waterproof&qid=1731163875&sprefix=pelican+case+waterproo%2Caps%2C76&sr=8-20)
  - PELI 1030 micro-beschermende behuizing voor kleine gevoelige apparaten, IP67
- [Pelican case](https://www.pelican.com/us/en/product/cases/micro/1040/)
  - [Amazon link](https://amzn.eu/d/aSuj9cq)

### Power supply
- [Traco 3V3](https://www.kiwi-electronics.com/nl/tsr-1-2433-3-3v-1a-switching-regulator-564?search=433)
- [Traco 5V](https://www.kiwi-electronics.com/nl/tsr-1-2450-5v-1a-switching-regulator-506?search=tsr)