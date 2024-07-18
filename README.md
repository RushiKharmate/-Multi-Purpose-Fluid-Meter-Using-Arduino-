# Multi-Purpose Fluid Meter | Using Arduino

## Project Overview

This Arduino-based project aims to measure fluid flow accurately using the YF-S201 sensor. It displays real-time flow rate on an LCD and logs data to an SD card. Additionally, it controls a servo motor to close a valve after a specified volume of water passes through.

## Components Used
- **Arduino UNO**: Microcontroller board for program execution and sensor interfacing.
- **YF-S201 Flow Sensor**: Measures liquid flow rate.
- **Servo Motor**: Actuates the valve based on measured flow.
- **LM016L LCD**: Displays real-time flow rate and total flow.
- **MicroSD Card Module**: Stores flow data for logging.

## Project Details

The system operates by counting pulses from the YF-S201 flow sensor to calculate flow rate in liters per minute. It updates this data on the LCD and logs it to an SD card for historical tracking. The servo motor closes the valve when a specified amount of water, defined by `maxMilliLitres`, is reached.

## Usage
- Upload the `Multi-Purpose Fluid Meter.ino` sketch to your Arduino board.
- Use the Serial Monitor in the Arduino IDE for debugging and viewing flow data.
- Adjust `maxMilliLitres` in the code to set the volume at which the valve closes.
- The LCD displays real-time flow rate and total flow in milliliters.
- Data is logged to `flowData.txt` on the SD card for later analysis.

## Acknowledgments
- Thanks to the Arduino community for resources and inspiration.
- Acknowledge any contributors or resources used in developing the project.

## Contact

   - Author: [Rushi Kharmate]
   - Email: [rushirajekharmate@gmail.com]

