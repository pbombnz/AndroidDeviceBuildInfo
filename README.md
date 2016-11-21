# AndroidDeviceBuildInfo
Contains build information of various Android devices in JSON form. 

This information can be used to correctly identify of a device which we are unsure of by comparing the information from the ```android.os.Build``` class with the device build JSON file in this repo. You could possibly use this information to spoof your current device with another device from the build information from one of the JSON files. 

Please note that some fields are not included from the original ```build.prop``` or a intialised as ```'unknown'``` as these are unique to each device or are device/ROM-specific.
