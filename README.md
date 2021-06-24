# ALCKioskElectronRelease

# Kiosk Side
### Step 1 - Install MongoDB
* https://www.mongodb.com/try/download/community?tck=docs_server
* https://docs.mongodb.com/manual/tutorial/install-mongodb-on-windows/
##
### Step 2 - Access Github & Download Latest Release
* https://github.com/Aadhithya1718/ALCKioskElectronRelease
##
### Step 3 - Run EXE
#

#
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

