# Gentelella lite 

Bootstrap 3 ベースの管理画面テンプレート [Gentelella](https://github.com/puikinsh/gentelella) をより使いやすくエンジニア向けに改良しました。

Gentelella からJS周りのコンポーネントを取り除き、テンプレートをJade化しています。

多くのJSコンポーネントが動作しなくなっているので、HTMLテンプレートとしてPHPやフロントエンドのアプリケーションに取り込んで利用する人向けです。

https://chatbox-inc.github.io/gentelella/

## 導入

モックとしてHTMLのみ必要な場合、以下の形で取り込めます。

````
$ git clone https://github.com/chatbox-inc/gentelella.git -b gh-pages
````


## TASKS 

- [x] gentelellaのJSコンポーネントなどを全て削る
- [x] 再現可能なページの範囲をリストアップ
- [x] 各種ページのjade化
- [ ] コピペしなくていい導入フローを考える(フロント向け)
- [ ] jade mixin の導入
  
 