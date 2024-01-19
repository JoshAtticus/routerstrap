# Optus AC800S
The dashboard for this router is currently WIP

## What's shown
- Battery Percentage & Charging status
- Registered Carrier name
- Signal Type & Strength
- Connected Devices
- Device & Battery Temperature (in celsius)
- Network connection status
- IPv4 address
- Unread messages count

## How to use
1. Install & Activate CORS Unblock: [Firefox](https://addons.mozilla.org/en-US/firefox/addon/cors-unblock/) [Chrome](https://chromewebstore.google.com/detail/cors-unblock/lfhmikememgdcahcdlaciloancbhjino) [Microsoft Edge](https://microsoftedge.microsoft.com/addons/detail/cors-unblock/hkjklmhkbkdhlgnnfbbcihcajofmjgbh)
2. Open routerstrap for this router

## Limitations
- This router's API has CORS, therefore CORS Unblock is required to function
- It is impossible to get a token for admin permissions without dev tools, so editing settings, viewing wifi details etc is not possible as of now
- API is known to randomly break, close the page, wait 30 seconds then re-open it if info is not loading
- Not possible to view, send, delete or reply to SMS messages
