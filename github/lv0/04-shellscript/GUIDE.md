# 04-shellscript

## 概要

アルゴ式のコンテンツを用いて、環境構築の基礎理解とshellscriptを用いた簡単な処理ができるようになりましょう。

このコースでは、アルゴ式 for business内で次の3つのパッケージに取り組みます。
各パッケージのすべての確認問題に正解することが目標となります。
理解度にあわせて、道中の問題は飛ばしても構いません。

-  OS とパス
  - OS とパスについて理解し、「パスを通す」という行為の意味と方法を理解する。
- ShellScript 初級
  - ShellScript(bash) の基本知識を習得し、簡単なファイル操作ができるようになる。
- ShellScript 中級
  - ShellScript(bash) を用いて、プログラムの実行をはじめとしたさまざまな操作が調べながらできるようになる。

各パッケージの確認問題の進捗状況は `PROGRESS_EXAMPLE.md` を参考にしながら、このディレクトリ内の `PROGRESS.md` にまとめましょう。
確認問題のタイトルと、それに対応する提出を順番に記述してください。
(確認問題以外の問題については記録する必要はありません。)

## チェックポイント

### 基本
- [ ] 「OS とパス」の全ての確認問題に正解する
- [ ] 「ShellScript 初級」の全ての確認問題に正解する
- [ ] 「ShellScript 中級」の全ての確認問題に正解する

### 発展
- [ ] アルゴ式のジャッジシステムをシンプルにしたものが作成できる。
  - 同じディレクトリ内に `input.txt`, `output.txt`, `main.py` がある
  - `input.txt` を標準入力として受け取り `main.py` を実行
    - この時点でエラーを吐いた場合は `Error` と出力し終了
  - 実行結果(標準出力) と `output.txt` を比較し、一致していれば `AC`、そうでなければ `WA` を出力