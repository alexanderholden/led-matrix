# LED matrix sign

# Key features
  - Multiplexed LED matrix
  - Adjustable brightness
  - Custom PCB and hardware design
  - WiFi enabled to allow for on-demand display changes
# System architecture
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
