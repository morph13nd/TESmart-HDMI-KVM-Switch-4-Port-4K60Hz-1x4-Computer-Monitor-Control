# TESmart-HDMI-KVM-Switch-4-Port-4K60Hz-1x4-Computer-Monitor-Control

For https://www.amazon.com/dp/B08124CPLM/?th=1

## Overview
IR backup file for TESmart 4-Port HDMI KVM Switch remote control. This file contains cloned IR signals that replicate the original remote's functionality. 

## Features
- Complete IR signal set for TESmart 4-Port KVM Switch
- Compatible with Flipper Zero
- Tested with 4K@60Hz model

## Prerequisites
- Flipper Zero device
- IR transmitter module (built into Flipper Zero)

## Installation Instructions
1. Download the `tesmart_kvm_4port.ir` file
2. Copy to your Flipper Zero's SD card under `/infrared/`
3. Navigate to **Infrared** app on your Flipper Zero
4. Load the file from the saved remotes list

## Usage
- Point Flipper Zero's IR transmitter toward KVM switch
- Select desired command from the menu:
  - Power On/Off
  - Input 1-4 Selection
  - Next Input
  - Previous Input

## Testing
Before relying on this backup:
1. Test all functions while original remote is still available
2. Verify switching response time
3. Confirm signal works at various angles

## Troubleshooting
If switching fails:
- Ensure direct line of sight
- Keep within 10ft/3m range
- Check Flipper Zero's battery level
- Try adjusting IR transmitter angle

## Disclaimer
This is a backup solution. Keep original remote in a safe place as primary control method.

## Contributing
Found improvements? Open an issue or submit a pull request.

## License
MIT License - Feel free to use and modify
