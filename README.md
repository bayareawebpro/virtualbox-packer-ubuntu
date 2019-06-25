# Packer Files for Ubuntu Server 18 LTS & VirtualBox
Automates the Installation of a VirtualBox Machine with Packer CLI.

**Note:** Figuring out the boot key sequence was a pain the ass, so enjoy.

## Install Packer
https://www.packer.io/

### Run `ubuntu.json`
Will build a new machine "UbuntuServer v18 LTS".

### Run `server.json`
Will login to the new machine and run any provisions needed.

### Add VirtualBox NAT Forwarding Rules
```
SSH 127.0.0.1 2222 10.0.4.15 22
HTTP 127.0.0.1 8080 10.0.4.15 80
HTTP 127.0.0.1 8443 10.0.4.15 443
```

**Keywords for Google:** 

- Ubuntu Boot Key Sequence 2019
- Ubuntu Server Boot Key Sequence
- Ubuntu Server Boot Key Sequence 2019
- Ubuntu Server 18 LTS Boot Key Sequence
- Ubuntu Server 18 LTS Boot Key Sequence 2019