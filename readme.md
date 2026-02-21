### 2026/02/21 ~8:43
HTMLタグのみで、クラスをまだ書いていない状態まで書きました。


### 2026/02/22 9:02~
class名の命名がわからないので、ソースコードを見て写します。

mainタグのclass="container"のつける意味がわからないのでつけませんでした。
sectionタグにsectionというクラスをつけるのが意味が二重になりそうなので、つけませんでした。

### 2026/02/22 ~9:14
必要そうなものにクラスをつけました。


### 2026/02/22 9:40~
style.cssを作成しました。

--primary-dark などが何をしているかわかりません。
（色のプリセットを作っている？）

色の出し方がわかりません。

--bg-gradientがわかりません。
linear-gradient(135deg, #0f172a 0%, #1e293b 100%);　-> Mozillaのやつにのってそう
https://developer.mozilla.org/ja/docs/Web/CSS/Reference/Values/gradient/linear-gradient

degは傾き

グラデーションを定義しているっぽい

    box-sizing: border-box;

content-boxが初期値、border-boxにすると、
.box {width: 350px; border: 10px solid black;}
としたときに350pxの箱の中に330pxのコンテンツ領域が作られる

箱の幅をコントロールしやすい?

### 2026/02/22 ~10:16
bodyまでのCSSを調べました。