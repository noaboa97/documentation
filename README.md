# Documentation
Documentation for my HomeLab

## UDM Pro

### Fan ramping up 
https://github.com/renedis/ubnt-auto-fan-speed <br/>
https://www.reddit.com/r/UNIFI/comments/nzzu99/udmpro_fans_spinning_up_in_tiny_bursts_59c_cpu/
# VPN
## MacOS VPN - Check if VPN should be established
### Run upon login (second solution)
https://stackoverflow.com/questions/6442364/running-script-upon-login-in-mac-os-x
### Run osascript to control tunnelblick
https://tunnelblick.net/cAppleScriptSupport.html
```
osascript -e "tell application \"/Applications/Tunnelblick.app\"" -e "connect \"configuration-name\"" -e "end tell"
```
Example:
```
osascript -e 'tell application \"Tunnelblick\"' -e 'connect \"All_traffic_home\"' -e 'end tell'
```

## MacOs VPN - Run scripts while a connection is up 
https://tunnelblick.net/cUsingScripts.html

## Windows
https://stackoverflow.com/questions/61456939/how-can-one-use-the-command-line-to-use-openvpn-on-windows
