# Linux Config (Tested on Pop!_OS 22.04 LTS)

1. Download https://docs.arduino.cc/software/ide-v1/tutorials/Linux
2. sudo apt remove brltty
3. sudo usermod -a -G dialout $USER
4. Log out and log back in. You __MUST__ do this, otherwise Arduino-ide won't be able to talk to the board(Needed for loading code).

# Board Config(Board)

![Board_Config](images/board_config_switches.png)


# To run:
1. Connect board
2. Click on Dropdown on top-left
3. Ensure `Arduino Mega or Mega 2560` is mapped(selected) to serial port.
    ![Arduino_Config](images/arduino_config.png)
4. Click "upload" on top-left

# Libraries used:

- https://github.com/thebigG/arduinoWebSockets