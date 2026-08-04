# Pixhawk Baseboard v1 Ports

{% hint style="info" %}
The Pixhawk Baseboard v1 has been replaced by the v2A & V2B. See the following change log for detail.&#x20;
{% endhint %}

{% content-ref url="/pages/zjEp4wewp27jR1NCTCvX" %}
[Baseboard Changelog](/autopilot/pixhawk-baseboards/baseboard-changelog.md)
{% endcontent-ref %}

![](/files/jhTDhBelpVY5XbaheAXL)

{% hint style="info" %}

* I/O PWM OUT = MAIN OUT
* FMU PWM OUT = AUX OUT
* Refer to this diagram for location of pin1. All connectors are JST GH 1.25 mm Pitch unless noted otherwise.&#x20;

![](/files/MyTeWlJug4RGPlgIU1H6)
{% endhint %}

### **Power1 (Main) & Power2 Port (Backup)** (2.00mm Pitch CLIK-Mate)

<table data-header-hidden data-search="false"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Pin</strong></td><td><strong>Signal</strong></td><td><strong>Volt</strong></td></tr><tr><td>1(red)</td><td>VDD5V_BRICK1/2</td><td>+5V</td></tr><tr><td>2(black)</td><td>VDD5V_BRICK1/2</td><td>+5V</td></tr><tr><td>3(black)</td><td>SCL1/2</td><td>+3.3V</td></tr><tr><td>4(black)</td><td>SDA1/2</td><td>+3.3V</td></tr><tr><td>5(black)</td><td>GND</td><td>GND</td></tr><tr><td>6(black)</td><td>GND</td><td>GND</td></tr></tbody></table>

### **Telem1, Telem2, Telem3 ports**

<table data-header-hidden data-search="false"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Pin</strong></td><td><strong>Signal</strong></td><td><strong>Volt</strong></td></tr><tr><td>1(red)</td><td>VCC</td><td>+5V</td></tr><tr><td>2(black)</td><td>TX7/5/2 (out)</td><td>+3.3V</td></tr><tr><td>3(black)</td><td>RX7/5/2 (in)</td><td>+3.3V</td></tr><tr><td>4(black)</td><td>CTS7/5/2 (in)</td><td>+3.3V</td></tr><tr><td>5(black)</td><td>RTS7/5/2 (out)</td><td>+3.3V</td></tr><tr><td>6(black)</td><td>GND</td><td>GND</td></tr></tbody></table>

### **GPS 1 Port**

<table data-header-hidden data-search="false"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Pin</strong></td><td><strong>Signal</strong></td><td><strong>Volt</strong></td></tr><tr><td>1(red)</td><td>VCC</td><td>+5V</td></tr><tr><td>2 black)</td><td>TX1(out)</td><td>+3.3V</td></tr><tr><td>3(black)</td><td>RX1(in)</td><td>+3.3V</td></tr><tr><td>4(black)</td><td>SCL1</td><td>+3.3V</td></tr><tr><td>5(black)</td><td>SDA1</td><td>+3.3V</td></tr><tr><td>6(black)</td><td>SAFETY_SWITCH</td><td>+3.3V</td></tr><tr><td>7(black)</td><td>SAFETY_SWITCH_LED</td><td>+3.3V</td></tr><tr><td>8(black)</td><td>VDD_3V3</td><td>+3.3V</td></tr><tr><td>9(black)</td><td>BUZZER-</td><td>0~5V</td></tr><tr><td>10(black)</td><td>GND</td><td>GND</td></tr></tbody></table>

### **GPS 2 Port**

<table data-header-hidden data-search="false"><thead><tr><th></th><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Pin</strong></td><td><strong>Signal</strong></td><td><strong>Volt</strong></td><td></td></tr><tr><td>1(red)</td><td>VCC</td><td>+5V</td><td></td></tr><tr><td>2 black)</td><td>TX8(out)</td><td>+3.3V</td><td></td></tr><tr><td>3(black)</td><td>RX8(in)</td><td>+3.3V</td><td></td></tr><tr><td>4(black)</td><td>SCL2</td><td>+3.3V</td><td></td></tr><tr><td>5(black)</td><td>SDA2</td><td>+3.3V</td><td></td></tr><tr><td>6(black)</td><td>GND</td><td>GND</td><td></td></tr></tbody></table>

### **CAN1, CAN2 ports**

| **Pin**  | **Signal** | **Volt** |
| -------- | ---------- | -------- |
| 1(red)   | VCC        | +5V      |
| 2(black) | CANH1/2    | +3.3V    |
| 3(black) | CANL1/2    | +3.3V    |
| 4(black) | GND        | GND      |

### **Uart4 & I2C port**

<table data-header-hidden data-search="false"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Pin</strong></td><td><strong>Signal</strong></td><td><strong>Volt</strong></td></tr><tr><td>1(red)</td><td>VCC</td><td>+5V</td></tr><tr><td>2(black)</td><td>TX4(out)</td><td>+3.3V</td></tr><tr><td>3(black)</td><td>RX4(in)</td><td>+3.3V</td></tr><tr><td>4(black)</td><td>SCL3</td><td>+3.3V</td></tr><tr><td>5(black)</td><td>SDA3</td><td>+3.3V</td></tr><tr><td>6(black)</td><td>NFC_GPIO</td><td>+3.3V</td></tr><tr><td>7(black)</td><td>GND</td><td>GND</td></tr></tbody></table>

### **SPI Port**

<table data-header-hidden data-search="false"><thead><tr><th></th><th></th><th></th></tr></thead><tbody><tr><td><strong>Pin</strong></td><td><strong>Signal</strong></td><td><strong>Volt</strong></td></tr><tr><td>1(red)</td><td>VCC</td><td>+5V</td></tr><tr><td>2 (black)</td><td>SPI6_SCK</td><td>+3.3V</td></tr><tr><td>3(black)</td><td>SPI6_MISO</td><td>+3.3V</td></tr><tr><td>4(black)</td><td>SPI6_MOSI</td><td>+3.3V</td></tr><tr><td>5(black)</td><td>SPI6_CS1</td><td>+3.3V</td></tr><tr><td>6(black)</td><td>SPI6_CS2</td><td>+3.3V</td></tr><tr><td>7(black)</td><td>SPIX_SYNC</td><td>+3.3V</td></tr><tr><td>8(black)</td><td>SPI6_DRDY1</td><td>+3.3V</td></tr><tr><td>9(black)</td><td>SPI6_DRDY2</td><td>+3.3V</td></tr><tr><td>10(black)</td><td>SPI6_nRESET</td><td>+3.3V</td></tr><tr><td>11(black)</td><td>GND</td><td>GND</td></tr></tbody></table>

### **USB Port**

| **Pin**  | **Signal** | **Volt** |
| -------- | ---------- | -------- |
| 1(red)   | VBUS       | +5V      |
| 2(black) | DM         | +3.3V    |
| 3(black) | DP         | +3.3V    |
| 4(black) | GND        | GND      |

### **I2C Port**

| **Pin**  | **Signal** | **Volt** |
| -------- | ---------- | -------- |
| 1(red)   | VCC        | +5V      |
| 2(black) | SCL3       | +3.3V    |
| 3(black) | SDA3       | +3.3V    |
| 4(black) | GND        | GND      |

### **ETH Port**

| **Pin**  | **Signal** | **Volt** |
| -------- | ---------- | -------- |
| 1(red)   | RXN        | +3.3V    |
| 2(black) | RXP        | +3.3V    |
| 3(black) | TXN        | +3.3V    |
| 4(black) | TXP        | +3.3V    |

### **AD\&IO Port**

| **Pin**  | **Signal**      | **Volt** |
| -------- | --------------- | -------- |
| 1(red)   | VCC             | +5V      |
| 2(black) | FMU\_CAP1       | +3.3V    |
| 3(black) | FMU\_BOOTLOADER | +3.3V    |
| 4(black) | FMU\_RST\_REQ   | +3.3V    |
| 5(black) | NARMED          | +3.3V    |
| 6(black) | ADC1\_3V3       | +3.3V    |
| 7(black) | ADC1\_6V6       | +6.6V    |
| 8(black) | GND             | GND      |

### **DSM RC Port** (JST-ZH 1.5mm Pitch)

| **Pin**   | **Signal**         | **Volt** |
| --------- | ------------------ | -------- |
| 1(yellow) | VDD\_3V3\_SPEKTRUM | +3.3V    |
| 2(black)  | GND                | GND      |
| 3(gray)   | DSM/SPEKTRUM IN    | +3.3V    |

### **RC IN Port**

| **Pin** | **Signal**   | **Volt** |
| ------- | ------------ | -------- |
| S       | SBUS/PPM in  | +3.3V    |
| +       | VDD\_5V \_RC | +5V      |
| -       | GND          | GND      |

### **IO Debug Port** (JST-SH 1mm Pitch)

| **Pin**   | **Signal**       | **Volt** |
| --------- | ---------------- | -------- |
| 1(red)    | IO\_VDD\_3V3     | +3.3V    |
| 2 black)  | IO\_USART1\_TX   | +3.3V    |
| 3(black)  | NC               | --       |
| 4(black)  | IO\_SWD\_IO      | +3.3V    |
| 5(black)  | IO\_SWD\_CK      | +3.3V    |
| 6(black)  | IO\_SWO          | +3.3V    |
| 7(black)  | IO\_SPARE\_GPIO1 | +3.3V    |
| 8(black)  | IO\_SPARE\_GPIO2 | +3.3V    |
| 9(black)  | IO\_nRST         | +3.3V    |
| 10(black) | GND              | GND      |

### **FMU Debug Port** (JST-SH 1mm Pitch)

| **Pin**   | **Signal**           | **Volt** |
| --------- | -------------------- | -------- |
| 1(red)    | FMU\_VDD\_3V3        | +3.3V    |
| 2 black)  | FMU\_USART3\_TX      | +3.3V    |
| 3(black)  | FMU\_USART3\_RX      | +3.3V    |
| 4(black)  | FMU\_SWD\_IO         | +3.3V    |
| 5(black)  | FMU\_SWD\_CK         | +3.3V    |
| 6(black)  | SPI6\_SCK\_EXTERNAL1 | +3.3V    |
| 7(black)  | NFC\_GPIO            | +3.3V    |
| 8(black)  | PH11                 | +3.3V    |
| 9(black)  | FMU\_nRST            | +3.3V    |
| 10(black) | GND                  | GND      |

### **RSSI Port**

| **Pin** | **Signal**         | **Volt** |
| ------- | ------------------ | -------- |
| S       | SBUS\_OUT/RSSI\_IN | +3.3V    |
| +       | VDD\_SERVO         | 0\~36V   |
| -       | GND                | GND      |

### **FMU PWM OUT  (AUX OUT)**

| **Pin** | **Signal**  | **Volt** |
| ------- | ----------- | -------- |
| S       | FMU\_CH1\~8 | +3.3V    |
| +       | VDD\_SERVO  | 0\~36V   |
| -       | GND         | GND      |

### **I/O PWM OUT (MAIN OUT)**

| **Pin** | **Signal** | **Volt** |
| ------- | ---------- | -------- |
| S       | IO\_CH1\~8 | +3.3V    |
| +       | VDD\_SERVO | 0\~36V   |
| -       | GND        | GND      |
