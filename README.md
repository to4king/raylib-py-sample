# raylib-py-sample

raylib とそのラッパーである raylib-py を使ったサンプルを作ってみる

# 顛末

Windows10 環境にて苦労して環境を構築した。
以下苦労した点

- Python
  - Microsoft Store 経由 or python.org 純正
- poetry
  - 1.1.11 にバグがあるらしくパスが上手く解決できず`poetry add`や`poetry install`でエラーになる問題
  - この変更参考にした
    - https://blog.panicblanket.com/archives/6329
    - https://qiita.com/radiol/items/a27530fd33b7e4758e6d
- PowerShell
  - PowerShell の実行ポリシーの問題でスクリプトが実行できない

致命的なもの

- Windows 環境向けには 32 ビットしか対応していないっぽい
- やるなら`.h`ファイルを修正するなどして 64 ビット対応させる？

疲れた...
