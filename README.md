# wg-meshconf-teltonika

A quick and lazy fork of https://github.com/k4yt3x/wg-meshconf 

Config syntax edited to Teltonika format

In database Name has to be "wgN" format ie wg15 and AllowedIP cant be empty

Apply config to a device by appending the generated lines to /etc/config/network, commit changes "uci commit" and restart networking "/etc/init.d/network restart"
