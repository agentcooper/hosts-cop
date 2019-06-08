# Hosts cop

`/etc/hosts` file is pretty useful for blocking websites ([guide](https://www.wikihow.com/Block-and-Unblock-Internet-Sites-(On-a-Mac)#Blocking_Sites_with_the_Hosts_File_sub)). Once you learn how to do it, it is also easy to unblock them.

Hosts cop will restore `/etc/hosts` file each time you try to remove blocked sites from it.

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
