# Step by Step after install FreeBSD 13 Release

# Upgrade Releaes to 13.2 (latest from 13 whichis still security support after 2026

## Update and Upgrade

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

## update to 13.2

```
freebsd-update -r 13.2-RELEASE upgrade
```

## Installing the downloaded 13.2 release updates

```
freebsd-update install
```

```
sudo /usr/sbin/sshd -t
```

```
freebsd-update install
```

```
pkg-static install -f pkg
```
