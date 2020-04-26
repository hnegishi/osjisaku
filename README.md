## install

- qemu インストール ...🍺

https://www.qemu.org/
```bash
$ brew install qemu

# version 2020/4/26
$ qemu-system-i386 -version
QEMU emulator version 4.2.0
```

- bochs インストール ...🍺

http://bochs.sourceforge.net/doc/docbook/user/compiling.html

OSXの場合は必要。brewで導入すると正常に動作しないため手動で入れる。

参考：https://github.com/HariboteOS/z_tools_osx

- その他

環境毎にMakefile内の`z_tools`を切り替える必要あり。

## 実行

example
```bash
$ cd osjisaku/01/helloos0
$ make run
```

🎉🎉🎉
![image](https://user-images.githubusercontent.com/30515665/80303198-a98de580-87e9-11ea-9fe3-6d94cf65fcfe.png)



## 開発環境(必要に応じて)

### docker image pull
```bash
$ make pull
```

### container up
```bash
$ make up
```

### container down
```bash
$ make down
```

## localで使ってるバイナリエディタ
[Hex Fiend](https://apps.apple.com/jp/app/hex-fiend/id1342896380?l=en&mt=12)

特に拘りはない。

## URL
https://github.com/HariboteOS/tolenv/

https://github.com/HariboteOS/z_tools_osx

http://hrb.osask.jp/
