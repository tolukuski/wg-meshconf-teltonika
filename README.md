# wg-meshconf-teltonika

A quick and lazy fork of https://github.com/k4yt3x/wg-meshconf 

Config syntax edited to Teltonika format

```shell
# cloning the repository with git
git clone https://github.com/tolukuski/wg-meshconf-teltonika

# enter the directory
cd wg-meshconf-teltonika

# Make a venv and install the program with Pip
# Pip and PDM will take care of dependency installation
python3 -m venv venv/
source venv/bin/activate
pip install -U .
```

In database Name has to be "wgN" format ie wg15 and AllowedIP cant be empty

Apply config to a device by appending the generated lines to /etc/config/network and
```shell
#commit changes
uci commit
#restart networking
/etc/init.d/network restart
```
