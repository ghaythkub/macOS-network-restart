# Read me
many times specially when changing wifi network or vpn connection the routing table and connection seems to be broken ,specially if the vpn client doesnt clean upon exit

this is a simple workflow for alfred to restart network

tested on macOS Venture and alfred 5

the command is simply : 

``` 
sudo launchctl kickstart -k system/com.apple.configd
```
