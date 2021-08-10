# ***profilerWPA***

![IMG](.screenshots/sst.png)
## Purpose
It's intended to be used in a RaspberryPi 0W to change easily from stored profiles (AS IT IS!) inside the script itself. 

## Security 
This program stores the password strings as it is, it's one of the first bash programs I made. 
To avoid any security danger change permissions to only be executed and read :
```bash
chown root profilerWPA && chgrp root profilerWPA
chmod 700 ProfilerWPA
```
The file should look like this: 
![IMG2](.screenshots/sst2.png)

## Usage
