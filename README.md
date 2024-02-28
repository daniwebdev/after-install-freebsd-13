# Step by Step after install FreeBSD 13 Release

## Update Package
```
pkg update
```

## Upgrade to freebsd 13.2 (latest from 13)

```
freebsd-update fetch
freebsd-update install
```

Reboot
```
reboot
```

Show detail current release version
```
cat /etc/os-release
```

## Update all package

```
pkg update
pkg upgrade
```
