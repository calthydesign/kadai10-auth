# kadai10-auth
PHP4 - 管理画面（認証機能等）

# ①課題番号-プロダクト名
Conditon Record　日々の体調記録アプリ　ver.4

## ②課題内容（どんな作品か）
- 先週まで作っていた課題にログイン認証機能をつけました
- 管理者画面でのみ更新、削除ができるようにしました。
- SNS形式にしたくて一覧をタイムラインに変更しました（複数ユーザーの登録情報が見える）が、データベースの更新が間に合わず名前などが出ていません。
- 
  
## ③DEMO
https://calthy-design.sakura.ne.jp/kadai10-auth/login.php
アンケートアプリではないのですが修正間に合わず、indexはログインしなくても見れます。
シークレットモードでないと認証情報のリジェネレートがうまくいかないかもです。

## ④工夫した点・こだわった点
- ログイン機能が無事実装できました
- 
- 

## ④難しかった点・次回トライしたいこと(又は機能)
- SNS形式にするにはまずユーザー登録→ログインになると思うので、indexページをログインページにしたところログインができなくなりました。。とりあえず前バージョンを提出します。
- ユーザーごとにプロフィールページなどを表示する場合のやり方が知りたいです。
- 

## ⑤質問・疑問・感想、シェアしたいこと等なんでも
- [質問] ページ遷移でどのページがどの様につながって、と考えるのが頭が混乱するので、良いメモの仕方など知りたいです。（まずサイトマップを作るのか？）
- [疑問] データベースのテーブルで、行はどんどん追加しても問題ないのか気になります。
- [感想] 演習はなんとかクリアできて実装もスムーズかと思いきや、ページ遷移で混乱することになりました。アンケートアプリと個人の記録を取るアプリではページ遷移の順序が違うのでそこを考えるべきでした。
- [tips] 
- [参考記事] 
- ### スクリーンショット
![top page capture](top_image.png)
