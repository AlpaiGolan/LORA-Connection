# LORA-Connection
LORA Connection between Arduino and Raspberry Pi

"Adjust the Raspberry Pi environment"


The Laura module connects to Raspberry Pi with the SPI protocol. Therefore, before installing the pylora package, it is necessary to turn SPI on enable on the Raspberry Pi board. Connect to Raspberry Pi with putty and enter the configuration window with the sudo raspi-config command.
Then select the " Interfacing option" and enable SPI. This activates the SPi interface on the Raspberry Pi board.
Save the changes and install the RPI GPIO package with the "pip install command RPi.GPIO".

pip install pyLoRa

With commands
"sudo apt-get install python-rpi.gpio python3-rpi.gpio"
"sudo apt-get install python-spidev python3-spidev"
  Download and install python rpi gpio and spidev packages.
