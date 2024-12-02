# Readme

勉強会用に作成した、[Causal ML Book](https://causalml-book.org) の資料を置いておく場所

- コード等は全て、上記サイトのものを自身の理解のため、少し改変したものである

## Replication の方法

- ターミナル / コマンドプロンプトで、`git clone https://github.com/Ryukius/CausalML_Ch10.git` を実行
- `renv` による仮想環境を使うことで、パッケージのバージョン管理を行っている
  - `renv::restore()` を行うことで、このノートブックで使用しているパッケージをインストール可能
  - `renv` パッケージをダウンロードしていない人は、最初に `install.packages("renv")` を実行する必要がある
