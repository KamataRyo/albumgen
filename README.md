# albumgen

[![Build status](https://ci.appveyor.com/api/projects/status/xeip7jp71bc509yc?svg=true)](https://ci.appveyor.com/project/kamataryo/albumgen)

Excel macro to generate photo album.

## open ssh for SSH

https://github.com/PowerShell/Win32-OpenSSH/releases/download/v0.0.4.0/OpenSSH-Win64.zip

### How To

https://blogs.msdn.microsoft.com/miyamam/2016/04/09/powershell%E3%81%A7ssh%E3%82%92%E5%88%A9%E7%94%A8%E3%81%97%E3%81%A6%E3%81%BF%E3%81%9F/

## Ariawase

https://github.com/vbaidiot/Ariawase.git


### How To

Run build.bat, you'll get office macro-enabled file in bin directory.

http://blog.clockahead.com/2012/11/vba-vbacwsf.html


## Project Management

### Reset deploy key

In UNIX shell, Run `./bin/keygen.sh` to generate new key pair.
Then encrypt `./id_ecdsa` in [AppVeyor Encrypt tool](https://ci.appveyor.com/tools/encrypt).

### install ariawase

Run `./bin/install-ariawase.ps`.

### Export VBA module

### Build VBA module

Run `./ariawase/build.bat`.
