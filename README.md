# GolangForStatement
for文

## 処理
1月から12月までを出力します。

## コード
```
package main

import "fmt"

func main() {
    for i := 1; i <= 12; i++ {
        fmt.Printf("%d月\n", i)
    }
}
```

## 出力結果  
```
1月
2月
3月
4月
5月
6月
7月
8月
9月
10月
11月
12月
```
  
## 開発環境
| 開発ツール |  |
|:-|:-|
| OS | Windows10 |
| 仮想化ソフト | Oracle VM VirtualBox 5.2 |
| 構築ソフト | Vagrant 2.0.2 |
| 仮想化上OS | CentOS 6.9 |
| SSHクライアント | PuTTY 0.6.8 |
| FTPクライアント | Cyberduck 6.3.5 |
| エディタ | Atom 1.24.0 |
| 開発言語 | Go言語 1.9.2 |
