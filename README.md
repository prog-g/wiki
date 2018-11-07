# 岐阜大学プログラミングサークルに関する一連の規約

岐阜大学プログラミングサークルの構成員は、このリポジトリの全ての規約を守る義務があります。
これら規約に疑問が生じた場合は [issue](https://github.com/prog-g/wiki/issues/new) を、改定の必要が生じた場合は [Pull Request](https://github.com/prog-g/wiki/pulls) を送ってください。

## 規約一覧

- [サークル規約](サークル規約.md)  
  大学に提出している規約の写し
- [サークルの目的と方針](サークルの目的と方針.md)  
  サークルの目的と構成員の義務について
- [サークルロゴの使用規約](logo/サークルロゴの紹介と使用規約.md)  
  サークルロゴとその使用規約について

## その他

サークルの活動について、より具体的なガイドや tips は [prog-g/wiki/wiki](https://github.com/prog-g/wiki/wiki) で扱っています。
こちらは自由に編集してもらって構いません。

全ての Markdown は [Pandoc](https://pandoc.org) で PDF に変換できます。

```sh
git clone https://github.com/prog-g/wiki.git
cd wiki
sudo apt install -y texlive-full
pandoc -o サークル規約.pdf --pdf-engine=lualatex -V documentclass=ltjsarticle サークル規約.md
```
