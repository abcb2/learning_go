# Go言語のおべんきょ
この辺をやる
http://kakakakakku.hatenablog.com/entry/2017/10/16/081755

# インストール
https://golang.org/dl/

## Linux用のものをダウンロードし解凍

doc/install.htmlを読んだところ、解凍先を指定して解凍し、PATHを通すのみだった。

```
# tar -C /usr/local -xzf go1.9.1.linux-amd64.tar.gz
# echo 'export PATH=$PATH:/usr/local/go/bin' >> /etc/bashrc
```

ログインしなおして確認

```
$ go version
go version go1.9.1 linux/amd64
```
