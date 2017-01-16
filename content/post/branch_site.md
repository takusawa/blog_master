+++
date = "2017-01-08T18:14:33+09:00"
draft = false
title = "サイト立ち上げについて"
isCJKLanguage = true
+++

静的サイトジェネレータhugoを用いたWEBサイトの構築にあたっては結構苦労しましたね。。  

・公式リファレンスが英語で書かれていること  
・github pagesへのホスティングの仕方  

の２点が非常に難しいかと思います。プログラミング未経験、Githubの知識が無いとなかなかとっつきにくいのかもしれません。  

自分も英語のリファレンスを読んでスラスラ理解出来るわけでも、Githubホスティングの知識が無いので
日本語でやり方を書いてる人はいないだろうかとひたすらネットサーフィンしてましたね。。  

ネットサーフィンする中で思ったことは、hugo+githubホスティングについて大きく  


<a href="http://blog.syati.info/post/create_hugo_2/" target="_blank">Hugo Part 2 - Hugo で github にブログを立ち上げる</a>  
<a href="http://qiita.com/eichann/items/4fe61b8b9bbafcfbe847" target="_blank">Hugo + Github Pagesでブログを公開してみた</a>  


２パターンあるのかなと思いました。  

リポジトリを２つ作ってソースファイル用リポジトリ、WEBページの管理用のリポジトリに分けるパターンと、  
１つのリポジトリの中にsubTreeとして別のブランチ上に公開WEBページを置いておくリポジトリを設置するパターンが
あるかなと思いました。


