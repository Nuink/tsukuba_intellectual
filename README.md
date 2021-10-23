# 知識人WEB

wip is here https://nuink.github.io/tsukuba.intellectual/

## changelog
### 10/23_4 css fixed
・h2のボーダー細くした<br>
### 10/23_3 various fix
・企画内ででた修正案を適用<br>
### 10/23_2 add gitignore
・TIGWEBのgitignoreをこちらに流用した<br>
### 10/23_1 remove "==", "var"
・==とvarを===とletに置き換えた<br>
### 10/23 for xss
・xss対策<br>
・文字置換で対応 <,>をそれぞれ全角＜,＞に置換するようにした<br>
・改行コード を br に置換するようにした<br>
### 10/19_2 css
・css調整した<br>
### 10/19 humberger-menu favicon
・スマホ用ハンバーガーメニューつくった<br>
・faviconつけた<br>
### 10/17 justify texts
・文面をきちんとしたものに置き換えた<br>
### 10/16 responsive_0.4 main content
・スマホ用にメインの写真表示部を変更した<br>
・PC版もアイコンなどデザインを変更した<br>
### 10/15 responsive_0.1~0.3
・iPhoneXを想定したレスポンシブデザインを実装した<br>
・一通りした<br>
・写真を実際にコンテンツに使用する写真に絞った<br>
・動画がスマホでも流れるようになった
### 10/04_3 scrollbar-cusomize
・スクロールバーをカスタマイズした　目立たないように<br>
### 10/04_2 twi-share
・miscボタン内にTwitter共有ボタンを追加した<br>
・見ている写真情報をもつメディアクエリを追加した　ロード時にその写真がスライドショーの初期写真になる<br>
・何個中何個見つけているかをツイート本文に記載する<br>
### 10/04 counter
・カウンターを追加した<br>
### 10/03_3 footer
・フッターをTIGと同じ内容にした<br>
### 10/03_2 close-button, misc-button, credit
・写真の閉じるボタン、詳細ボタンを追加した<br>
・撮影者(クレジット)を追加した<br>
### 10/03 resize slidshow, hover fx
・スライドショーを小さくした<br>
・左右の写真にホバー効果つけた
### 10/02_3 logo & responsive-preparing
・ヘッダーにあったtigテキストをtigロゴに置換した<br>
・レスポンシブの準備をした
### 10/02_2 triggers reposition
・トリガー表示中にウィンドウサイズ変更により写真サイズが変更されたとき、トリガーがずれるのを修正しました<br>
### 10/02 smoothscroll
・スムーズスクロールの実装<br>
・「スクロールして下へ」のアイコンをクリックしたら下にスクロールするようにしました
### 9/29 loading screen
・データベースにアクセスするまで閲覧できないようにするためのロード画面を実装した<br>
・90%になるまで200msごとに12%ずつ増やしていってデータベースにアクセスできたら100%にして表示します
#### 1.1, 1.2
・開発環境と実装時で見え方が違ったので調整した　まだ調整する必要あるかも<br>
### 9/27 slideshow
・整えたスライドショーを作成した Flickityを使用した<br>
### 9/20_1 how-to implemented
・「歩き方を見る」ボタンとその動作を概要下に追加<br>
### 9/20 made title-bg 'fixed' <br>
・TIGWEBの背景オブジェクトが固定されてるのが良さげだったのでこっちにも適用した<br>
### 9/19 new user comment implemented <br>
・一般の人の視点を投稿、表示できるように　教員のは紫色に対してこれはオレンジ色<br>
  -視点を表示する枠の最下部に投稿ボタンを表示->投稿フォームの表示->正常に入力されていれば確認画面->投稿完了<br>
・視点を表示する枠をスクロールするように　どんなに要素が長くなってもheightは一定にして画面からはみ出さないようにするため<br>
・視点を表示する枠の最上部にそのトリガーの名前を表示<br>
・1枚目の中央柱、左下自転車群にトリガーを設定<br>


## Todo
<s>like</s><br>
<s>comment</s><br>
more flexible for any window sizes<br>
for mobilephone<br>
もろもろ文の見直し<br>
視点ボックスを画面内に確定で収まるように表示させる<br>
<s>画像のプリロード<br>
データベースのロード後にページを表示する loading画面的なこと</s><br>
footer<br>



## 不具合
・Likeをつけたあと視点のボックス閉じてもう一回開くとLikeの状態が失われたまま数は増えてるよ<br>
<s>・DB(視点の情報)を読み込む前に写真を開いて視点を覗こうとできちゃう トリガーが失われてる　なんとなく解決できそう</s>
