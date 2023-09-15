# Samsung Galaxy S23 series debloater
This is a debloating script for Samsung Galaxy S23 series.
It doesn't uninstall apps but disables them so if you find any feature missing you can revert it by using

```bash
  adb shell pm enable <package-name>
```

Use at your own risk

## Windows
Double click the bat file

## Ubuntu
Install [Android Debug Bridge (adb)](https://developer.android.com/studio/command-line/adb):

```bash
  sudo apt install adb
```

Rename *s23-debloater.cmd* to *s23-debloater.sh* and run it:

```bash
  bash './s23-debloater.sh'
```