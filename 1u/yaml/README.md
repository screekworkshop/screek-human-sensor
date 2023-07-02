This is a custom firmware for Human Presence Sensor 1U, you can get help for using the firmware and some FAQ on our website: https://screek.tech
- If you want to buy one of our DIY products, you can also find our eBay store on our homepage. 
- In order to adapt to work in a small space, we made some optimizations: including adjusting the WIFI transmit mode (we lowered it to 15dB), and downconverting the ESP32 to 80Mhz.
- Two of our modified libraries were used: the LD2410 modified the initialization mechanism based on the official one (thanks to @regevbr) (we abandoned setting it in the esphome and used the HLKRadarTool configuration instead), added the BLE switch, and added the resistance value to get the LDR; while the uart library, with some slight modifications, aims to make both uart work on s2 at the same time, so that we can keep the serial port support.

Thank you for your support! It's been a pleasure to share them.  
Have a great day.  