# ALCKioskElectronRelease

# Kiosk Side
### Step 1 - Install Required Drivers & Prerequistions
* Install Touch Screen Drivers
* Install Thermal Printer Drivers
* Install Set Default Printer to Thermal Printer
* Install Digital Persona Biometric Drivers
* Disable Windows Notifications & Popups
* Disable Windows Auto Updates & Popups
* Disable Antivirus Popups
##
### Step 2 - Install C# Biometric Windows Application for Biometric Integration.
##
### Step 3 - Install MongoDB
* https://www.mongodb.com/try/download/community?tck=docs_server
* https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/
##
### Step 4 - Access Github & Download Latest Release
* https://github.com/Aadhithya1718/ALCKioskElectronRelease
##
### Step 5 - Run EXE
* EXE will automatically update if any update is available in future. Therefore, no need to follow these steps for updates.
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
### Points to take care while kiosk setup
* 

