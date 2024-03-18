# Arduino Environment Monitoring

This Arduino project enables real-time monitoring of environmental parameters such as temperature and gas levels using sensors. The project is designed to provide continuous updates on the ambient temperature and gas concentration, with alerts triggered when predefined thresholds are exceeded.

## Components Used
- Gas sensor
- Temperature sensor
- Arduino board (e.g., Arduino Uno)
- LED
- Piezo buzzer

## Functionality
The Arduino sketch reads data from the gas sensor and temperature sensor, converting analog readings into meaningful measurements. When the gas concentration surpasses a set threshold, indicated by the gas sensor, an LED and a piezo buzzer alert the user. Additionally, the ambient temperature readings are displayed via the serial monitor.

## Usage
To use this project:
1. Connect the gas sensor, temperature sensor, LED, and piezo buzzer to the Arduino board following the circuit diagram.
2. Upload the provided Arduino sketch (`environment_monitoring.ino`) to the Arduino board.
3. Monitor the gas concentration and temperature readings through the serial monitor in the Arduino IDE.
4. Ensure proper ventilation if gas levels exceed the defined threshold.

## Contributing
Contributions are welcome! If you have suggestions for improvements or new features, feel free to open an issue or submit a pull request.


