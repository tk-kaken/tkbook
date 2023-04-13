# Welcome to bs4_book_template! ようこそ

## About This Template

This is a minimal example of a book based on R Markdown and **bookdown** (https://github.com/rstudio/bookdown) with bs4_book style. 

1. All original contents are collected in the last chapter bookdown so that you can keep them as you like. 

2. The line `output_dir: docs` is in the second line of bookdown.yml` so that you can easily publish your book on GitHub Pages.

3. Two lines in the preamble for a PDF output in Japanese. Delete them if the book is in English. 

This template provides a skeleton file structure you can edit to create your book. 

The contents inside the .Rmd files provide some pointers to help you get started, but feel free to delete the content in each file and create fresh ones

## 日本語版テンプレートについて

英語版は、いろいろと良いものがあるが、[bookdown site](https://bookdown.org/yihui/bookdown/) や、そのページから リンクのついている [arxive ページ](https://bookdown.org/home/archive/) においても、日本語のものは、非常に限られている。日本のデータサイエンスの学習者は、英語があまり得意ではないが、それが障害となってはいけないと常々考えていた。特に、R などを利用する場合は、日本語以外のコンテンツに慣れていくことが適切だと思うが、ある程度、日本語でのデジタルコンテンツが増えていくことは望ましいと思い、自分でも、日本語コンテンツを作成している。

このテンプレートは、日本語コンテンツを提供してくださる方の障害をいくらかでも、低減したちとの願いから、作成したものである。

## 使い方

これは、`bs4_book` スタイルでの、簡単な、日本語テンプレートです。

1. 自分の、GitHub アカウントに、ログインします。
2. [icu-hsuzuki/bs4_book_template](https://github.com/icu-hsuzuki/bs4_book_template) にアクセスし、Use this template から、create a new repository を選択します。
3. 自分のアカウントの中に、コピーされたリポジトリーがつくられます。
4. [データサイエンスを始めましょう：IT ツール](https://icu-hsuzuki.github.io/ds4aj/tools.html#tools) を参照してください。

もし、IPA フォントに関してインストールされていないと表示されたら、次のコードを、Console で実行してください。

```
# if error on ipa fonts
tinytex::tlmgr_install("ipaex")
```


## 参考文献 Additional resources:

* The **bookdown** book: https://bookdown.org/yihui/bookdown/
* The **bookdown** package reference site: https://pkgs.rstudio.com/bookdown
* R Markdown Cookbook: https://bookdown.org/yihui/rmarkdown-cookbook/
* R Markdown: The Definitive Guide: https://bookdown.org/yihui/rmarkdown/
* How to create a bookdown book in 5 minutes (YouTub Video):  https://www.youtube.com/watch?v=m5D-yoH416Y
* データサイエンスを始めましょう: https://icu-hsuzuki.github.io/ds4aj/
* データサイエンスを一緒に教えませんか：https://icu-hsuzuki.github.io/ds_education/
