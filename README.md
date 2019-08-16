# Overview
Script to install Aporeto apoctl, enforcerd and useful utilities

## Installation

### Basic
```
curl -L -o install https://raw.githubusercontent.com/aporeto-se/aporeto-installer/master/src/install
chmod +x install
sudo ./install
```

### Advanced
```
curl -L -o install https://raw.githubusercontent.com/aporeto-se/aporeto-installer/master/src/install
chmod +x install
export ENFORCERD_NAMESPACE=/abc/123
sudo ./install
```

### Aporeto Environment Variables
You can set any of these before executing the script and they will be included in the /etc/enforcerd.conf file. Note that you must send ENFORCERD_NAMESPACE or ENFORCERD_APPCREDS before starting the enforcerd service.

The environment variables are as follows
```
ENFORCERD_API=
ENFORCERD_API_CACERT=
ENFORCERD_NAMESPACE=
ENFORCERD_LOG_TO_CONSOLE=
ENFORCERD_LOG_FORMAT=
ENFORCERD_LOG_LEVEL=
ENFORCERD_APPCREDS=
ENFORCERD_OPTS=
```

## Tools that will be installed are
- Aporeto Enforcerd
- Aporeto apoctl utility
- jq (JSON CLI Parser)
- jwt (JSOWN web token parser)
- enforcer-watch (tails the enforcerd log by looking up active pid)
