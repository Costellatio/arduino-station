# arduino-station

### Software Requirements

- arduino-ide - [link](https://www.arduino.cc/en/software)
- gcc - [link](https://www.mingw-w64.org/downloads/)

### Hardware Requirements

- Arduino
- Sensors

### Project Setup / Updating Dependencies

```
  # Install / Update arduino-station
  ./install.sh
```

### Sensor Development Concepts

```
  # Define a Sensor Id and Sensor Pin/I2C Address
  # Implement the sensor logic in a timer task
  # Serialize the output and print to Serial
  # Wrap the sensor call in a toggle
```
