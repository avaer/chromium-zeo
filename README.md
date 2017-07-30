# Multi-OS Chromium build

## Windows

- Download from https://chromium.woolyss.com/
- Run `chlauncher`
- Rename `bin` to `windows`

## Linux

```
aptitude download chromium
ar x *.deb
tar -xf data.tar.gz
mkdir -p linux
mv usr etc linux
```
