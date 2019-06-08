# Hosts cop

If you have weak self-control.

Each time you try to remove blocked sites from `/etc/hosts` it will be restored to a previous version.

![notification](./screenshots/notification.png?raw=true)

Adding sites to `/etc/hosts` will not trigger a notification.

For macOS.

## Install

```
git clone https://github.com/agentcooper/hosts-cop
sudo ./hosts-cop/install
```

## Uninstall

```
# from hosts-cop directory
sudo ./uninstall
```

## Why `sudo`?

Script needs to run from `/Library/LaunchDaemons/` to be able to write to `/etc/hosts`.
