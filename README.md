INSTALLATION:

Import the .json to your node-red instance.

Make a folder located at:  ```/home/pi/AHT10```
Copy the file ```aht10.py``` to that folder.

You may need to update the location if you are not on a raspberry pi.

Should be straight forward.

You may need to install ```python3-smbus``` library via pip3:   ```pip3 install python3-smbus```

Don't forget to ```sudo raspi-config``` -> Interfaces ->  Enable I2C  ->  SAVE  ->  Reboot
