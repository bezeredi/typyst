Typyst
======
A service that allows your computer to sound like a keyboard without being
tied to a particular text editor or word processor.


#### Installing Dependencies ####
You will need python3, pip3, pynput, wave, glob

``` bash
#! For Ubuntu based systems
sudo apt-get install python3 pip3
sudo -H pip3 install pynput glob wave
```

#### Configuration ####
You need to change the location string for the .wav files in initialize()


#### Usage ####
./typyst.py

hit some keys (they echo back out)

hit ESC twice to quit (not sure why)
