# DAB Labkit - Platform WebApp

Labkit - Platform Webapp was thought to enhancing your user experience, we have provided an unique visual performance called Web app, where it allows you to interact with device features through your browser 
running locally on your own Laptop, over a simple Tornado Web Server.


## Setup
Make sure you have ```python 3.9``` (or ```python 3.10 ```) and ```Python PiP``` installed.

You can download python directly from Pythoh webpage (https://www.python.org/downloads/), or alternatively you can use your OS Package Manager (APT, RPM, chocolatey...)

Exampple:
```
# Update packages references
apt update -y

#Installing Python and dependencies
apt install python3 python3-pip pipenv -y
```

### Install Locally

1) Extract the zip file content.
2) On command line, install the python modules required:

```
# Installing Tornado Web Server Module
pip install Tornado 
# Installing Regex Module
pip install regex 
# Installing Requests Module
pip install requests
```

*** On debian bases OS, you can run the install script directly:
```
sudo bash install.sh
```

### Start Application

After Python3 and modules installed, you can run your WebApp, according the follow examples:

```
# Running on default config
python3 webapp.py

# Running on verbose mode
python3 webapp.py -v

# Running on specific port
python3 webapp.py -p [PORT]

# Running on Help options
python3 webapp.py -h
```

After the startup, you can access the WebApp directly on your browser http://[HOST]:[PORT] (Default: http://localhost:8888).

***Access the Webapp from remote machine it's possible since the port is exposed to remote access.


### Confire your credentials

When you connect on your WebApp, it's necessary to configure the Access token and DAB Account to be used on DAB requets. 
You can to it access the "Authorize" button on the Top-Right corner. 
