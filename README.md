# Skynet Tracking API
- Return JSON formatted string of Skynet Tracking details
- I have been looking for Skynet API but I cannot find the one that actually work and easy to use, so, I developed my own.
- Can be use for tracking the Skynet parcel in your own project/system
- Note: 
  - This is not the official API, this is actually just a "hack", or workaround for obtaining the tracking data.
  - This API will fetch data directly from the Skynet Tracking website, so if there are any problem with the site, this API will also affected. 
  
# Created By
- Afif Zafri
- Date: 21/12/2016
- Contact: http://fb.me/afzafri

# Installation
- Drop all files into your server

# Usage
- ```http://site.com/api.php?trackingNo=CODE```
- where ```CODE``` is your parcel tracking number
- It will then return a JSON formatted string, you can parse the JSON string and do what you want with it.

# License
This library is under ```MIT license```, please look at the LICENSE file
