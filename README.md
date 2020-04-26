

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

## URL
https://github.com/HariboteOS/tolenv/

https://github.com/HariboteOS/z_tools_osx

http://hrb.osask.jp/
