# vps-config

## What It Does

* Creates a new non-root user
* Adds the new user to the `sudo` group
* Applies basic SSH hardening
* Updates system packages
* Installs core utilities, including `htop`
* Enables unattended security updates
* Installs and starts Fail2Ban
* Configures UFW firewall rules
* Installs Docker
* Adds the new user to the `docker` group

## Quick Start

Run this as `root` on a fresh Ubuntu or Debian VPS:

```bash
curl -fsSL https://raw.githubusercontent.com/maksym-shunder/vps-config/main/setup.sh | bash
```
