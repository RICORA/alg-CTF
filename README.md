# alg-CTF
## CTFのいろはを学べるリポジトリ
### 準備
- picoCTF(https://picoctf.org/)への登録
- Virtual BoxやWSLなどLinuxのコマンドが動かせる環境(Virtual Boxを使ったUbuntuの導入方法は後に追記)
### 使い方
1. このリポジトリをcloneしましょう。
```
git clone git@github.com:RICORA/alg-CTF.git
```
2. やりたい分野のファイルを開いて進めましょう
### 様々な分野の概要
- PWN
  - C言語などで作られたプログラムの脆弱性をついて権限を取得する分野
- REV
  - コンパイルされたプログラムを逆アセンブルして解読する
- WEB
  - 問題となるサイトにアクセスし、フラグを探しだす
  - SQLインジェクションやapiの悪用など
- FORENSICS
  - 与えられたデータからフラグを探す問題
  - ステガノグラフィーやメモリダンプなど様々なデータが対象となる