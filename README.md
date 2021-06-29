# ALCKioskElectronRelease

# Kiosk Side

### Step 1 - Prerequistions Installations
* Works in Windows 10 64-Bit CPU Only
* Install Touch Screen Drivers
* Install Thermal Printer Drivers
* Install Set Default Printer to Thermal Printer
* Disable Windows Notifications & Popups
* Disable Windows Auto Updates & Popups
* Disable Windows Auto Sleep & Display Auto-Off
* Disable Antivirus Popups
* Set Empty Password for Kiosk Login
* Enable Auto Login in Startup
##
### Step 2 - Install Correct FingerPrint DP Driver
* Below Link has the RTE Setup for Production Kiosk with 64-Bit Windows. This setup will not work for debug sdk.
* https://drive.google.com/drive/folders/1JZ4hLI8kYvR90qqHPZbKCPx5K7myLvzs?usp=sharing
##
### Step 3 - Install MongoDB
* https://www.mongodb.com/try/download/community?tck=docs_server
* https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/
##
### Step 4 - Access Github & Download Latest Release
* https://github.com/Aadhithya1718/ALCKioskElectronRelease
##
# Server Side
### Step 1 - Add kiosk_settings record for the kiosk ip in 11.8 mongoDB.
```
//Example Record
  {
    "FPDevice_id": 15,
    "theme": "#133951",
    "Division_id": 1,
    "ip": "192.168.1.207",
    "FPDeviceName": "Kiosk Live 1"
}
```
##
# Done ✌️
##
