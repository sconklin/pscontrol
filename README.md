# Control analog interface

This board is designed to connect a programmable power supply with analog control inputs and outputs to a DAQPlate, to enable network control.

# Analog conversions

### Voltage Measurement
Input -5.0V to 0V input represents 600V to 0V
Output 0 to 4.096 to DAQPlate board
Gain = -0.8192
Gain Range .714 - .896

### Current Measurement
Input 0 to 100 mV represents 0 to 1M output
Output 4.096 Volts to DAQplate
Gain = 40.96
Gain Range 38.3 - 43.3

### Voltage Control
Input from DAQplate 0 to 4.096V
Output to Powr Supply 0 to 5 volts
Gain = 1.22
Gain Range 1.098 - 1.294

### Current Limiting Control
Input from DAQplate 0 to 4.096V
Output to Power Supply 0 to 100 mV
Gain = 0.024
Gain Range .0215 - .0261

