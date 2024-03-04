# wazo-provd-coredump-plugin

Allows wazo-provd to dump core when crashing, e.g. from SIGABRT

## Installation

```sh
wazo-plugind-cli -c "install git https://github.com/wazo-communication/wazo-provd-coredump-plugin"
```

Core dumps will be created in `/var/lib/wazo-provd`

## Uninstallation

```sh
wazo-plugind-cli -c "uninstall wazocommunication/wazo-provd-coredump"
```
