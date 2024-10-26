# JC2432W328

Working yaml settings snipits for ESPHOME

```
display:
  - platform: ili9xxx
    id: my_display
    model: ST7789V
    spi_id: tft
    cs_pin: GPIO15
    dc_pin: GPIO2
    invert_colors: false
    dimensions:
      width: 240
      height: 320
    rotation: 90
    data_rate: 80MHz
```
