 Schematic files are in Mentor Graphics' (Siemens) PADS Logic format.

 You can get the free viewer at https://resources.sw.siemens.com/en-US/download-pads-standard-plus-viewer or simply use the converted schematic.pdf file.

 The excel file contains pin assignments, copied down below for convenience.

 | Interface   name           | modul   | Pin              | Whether to use   interrupt | interrupt   priority level  |
|----------------------------|---------|------------------|----------------------------|-----------------------------|
| WiFi status   light        |         | Wifi_status=PC13 | -                          |                             |
| USB status   light         |         | USB_status=PC14  | -                          |                             |
| USB                        | USB_OTG | USB_DM=PA11      | OTG_FS_IRQn                | (,)                         |
|                            |         | USB_DP=PA12      |                            |                             |
| WiFi   module interface    | USART1  | USART1_TX=PA10   | USART1_IRQ                 | (0,0)                       |
|                            |         | USART1_RX=PA9    |                            |                             |
| SD   card module interface | SPI     | SPI2_MISO=PB14   |                            |                             |
|                            |         | SPI2_NSS=PB12    |                            |                             |
|                            |         | SPI2_SCK=PB13    |                            |                             |
|                            |         | SPI2_MOSI=PB15   |                            |                             |
|                            |         | SD_CD=PC6        |                            |                             |
| WiFi mode   selection      |         | MODE_SELECT=PA8  |                            |                             |
 
