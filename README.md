# Packer Files for Ubuntu Server 18 LTS & VirtualBox
Automates the Installation of a VirtualBox Machine with Packer CLI.

## Run `ubuntu.json`
Will build a new machine "UbuntuServer v18 LTS".
https://www.packer.io/

## Run `server.json`
Will login to the new machine and run any provisions needed.
https://www.packer.io/

## Add VirtualBox NAT Forwarding Rules
```
SSH 127.0.0.1 2222 10.0.4.15 22
HTTP 127.0.0.1 8080 10.0.4.15 80
HTTP 127.0.0.1 8443 10.0.4.15 443
```