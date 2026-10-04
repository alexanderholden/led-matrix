# LED matrix sign

## Key features
  - Multiplexed LED matrix
  - Adjustable brightness
  - Custom PCB and hardware design
  - WiFi enabled to allow for on-demand display changes
## System architecture
1. LED Matrix
   - LEDs arranged as an NxM grid
   - Rows and columns multiplexed reducing pin usage
  
2. Driver
   - 74HC595 attached to columns handle low side switching
   - CD4017 decade counters with transistors attached to rows handling scanning
  
3. Microcontroller
   - Generates clock signal
   - Updates frame buffer
   - Wi-Fi server

## Renders

- LED board
<img width="1083" height="604" alt="image" src="https://github.com/user-attachments/assets/1879126f-ccc4-4895-b11e-ca3bb9950995" />

- Driver board
<img width="921" height="645" alt="image" src="https://github.com/user-attachments/assets/e2e02210-4048-4e83-9937-bbd171bfc217" />


  
  
