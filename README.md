# LoRa shield for RPi

This is the most basic LoRa shield for the RPi using the SX1262 based module HT-RA62.

RXEN and TXEN are not connected, neither are DIO2 and DIO3

```
RST  --> GPIO18
DIO1 --> GPIO16
NSS  --> GPIO21
MOSI --> GPIO10
MISO --> GPIO9
SCK  --> GPIO11
BUSY --> GPIO20
```

Use this e.g. with pyMC and add

```
use_dio3_tcxo=true
use_dio2_rf=true
```


![shield](img/ht-ra62-shield.jpg)


