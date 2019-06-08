# Hosts cop

For macOS.

Restore `/etc/hosts` if modified while hosts-cop is running.

## Install

```
sudo ./install
```

## Uninstall

```
sudo ./uninstall
```

## Why `sudo`?

Script needs to run from `/Library/LaunchDaemons/` to be able to write to `/etc/hosts`.
