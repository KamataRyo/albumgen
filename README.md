# albumgen

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

バイナリファイルからVBAコードをエクスポートする場合
binフォルダに、バイナリファイルを配置
debuild.batファイルを実行
（→ src フォルダ内にVBAコードがエクスポートされる。
例: test.xls に含まれるVBAコードは、src/test.xls/ にエクスポートされる）
VBAコードをバイナリファイルにインポートする場合
srcフォルダ下のバイナリファイル名のフォルダ内に、VBAコードを配置
（例: test.xls にインポートしたいVBAコードは、src/test.xls/ に配置）
標準添付のbuild.batを実行
（→ binフォルダ内のバイナリファイルのVBAコードがクリアされた後、srcフォルダ内のVBAコードがインポートされる。）
