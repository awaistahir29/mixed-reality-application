# Mixed-Reality-Application
This repository contains the procedure to make mixed reality application which will be developed on Unity Engine and would be deployed on HoloLens 2. 
## Connecting Camera to WSL2 subsystem 
Follow [This](https://learn.microsoft.com/en-us/windows/wsl/connect-usb) guide to see the camera connected to your Ubuntu which is running in WSL2.
Open the PowerShell as an administrator and follow the guide to connect the camera. Make sure that you are running the right distribution.
`usbipd wsl attach --busid 2-13 --distribution Ubuntu-20.04`
