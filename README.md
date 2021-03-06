# 卒論テンプレート for TeX
KCCT 電子工学科用の予稿および卒論 TeX スタイルファイルを置いています．

## 予稿用

1. [abstract.sty](https://raw.githubusercontent.com/kcct-fujimotolab/thesis-tex-template/master/interim/abstract.sty) をダウンロードします．

2. TeX ファイルに以下を追加することでスタイルが適用されます．
    ```tex
    \usepackage{abstract}
    ```

詳細は [interim/sample.tex](https://github.com/kcct-fujimotolab/thesis-tex-template/blob/master/interim/sample.tex) と [interim/sample.pdf](https://github.com/kcct-fujimotolab/thesis-tex-template/blob/master/interim/sample.pdf) を参考にしてください． 

## 卒論用

1. [paper.sty](https://raw.githubusercontent.com/kcct-fujimotolab/thesis-tex-template/master/thesis/paper.sty) をダウンロードします．

2. TeX ファイルに以下を追加することでスタイルが適用されます．
    ```tex
    \usepackage{paper}
    ```

詳細は [thesis/sample.tex](https://github.com/kcct-fujimotolab/thesis-tex-template/blob/master/thesis/sample.tex) と [thesis/sample.pdf](https://github.com/kcct-fujimotolab/thesis-tex-template/blob/master/thesis/sample.pdf) を参考にしてください． 

## 原稿を Git / GitHub で管理する場合
GitHub が公開している TeX 用 `.gitignore` の使用をオススメします．

https://github.com/github/gitignore/blob/master/TeX.gitignore
