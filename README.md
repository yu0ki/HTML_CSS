# HTML_CSS レポジトリの概要　

このレポジトリでは、DMM WEBCAMP の HTML・CSS について学ぶチャプターで作成したファイル群を,
章ごとにディレクトリに分けて管理している。

## chapter2 　　

この章では HTML・CSS の書式概要を学んだ。chapter2-exercise に演習として作成した DMM WEBCAMP のサービス紹介ページが保存されている。
chapter2-exercise などのディレクトリが、誤ってディレクトリ「chapter2」の外部と内部の両方に複製されてしまったが、これらの内容は同じものである。

## chapter3 　　

この章では入れ子構造について学んだ。<div>タグで箱を 2 つ作って入れ子構造にし、各箱に背景色を background-color を使って指定したり、padding,mergin を指定したりした。

## chapter4

4 章の練習問題、演習問題の解答。練習問題の解答は boxes に入っている。boxes.html は以下の条件を満たす。

1. \<div class="boxes">要素の中に\<div class="box1">要素と\<div class="box2">が存在するように HTML を作成する
2. .boxes：横幅 600px、背景色 yellow、.boxes クラスそのものと子要素を両方中央寄せにする
3. .box1：横幅 150px、高さ 400px、背景色 orange
4. .box2：横幅 250px、高さ 400px、背景色 red

演習問題は chapter4-exercise に入っている。箱をさらにたくさん並べて、簡易的なウェブページの枠組みを作成した。
flexbox を用いて箱を中央ぞろえにするのがポイントである。

## chapter5

5 章の練習問題、演習問題の解答を管理するディレクトリ。直下の example.html と style.css は練習問題（問 3）の解答であり、次の条件を満たす。

1. header タグ、h1 タグ、nav タグ、ol タグ、li タグを用いる
   　　 header タグの中に h1 タグと nav タグがあり、nav タグの中に ol タグ、
   　　 ol タグの中に li タグが 4 つある構成にする
2. h1 タグの中身は、EXAMPLE とする
3. li タグの中身は、それぞれ MENU1、MENU2、MENU3、MENU4 とする
4. class 名は、それぞれ"headline"、"nav"、"list"、"list-item"とする
5. header の width（横幅）は、10％にする
6. headline の font-size（文字の大きさ）は、22px にする
7. nav 内の文字を中央寄せ（text-align）にする
8. "list"クラスには css で padding-left: 40px;を適用させる

chapter5-exercise 内には演習問題の解答が含まれる。

## chapter6

6 章の演習問題を管理するディレクトリ。

## chapter7

7 章の演習問題を管理するディレクトリ。

## chapter8

8 章の演習問題を管理するディレクトリ。

## caravan

4 章以降での作成物はこのフォルダに入っている。4 章以降では、ウェブページ caravan の作成を行った。

### 4 章で学んだこと

- リセット CSS
- web ページの枠組みの作り方

### 5 章で学んだこと

- ヘッダーの作り方
- フッターの作り方
- 中央ぞろえの方法や、display で指定できる要素の表示形式など、本格的に css が活躍し始める。

### 6 章で学んだこと

- メインビジュアルの作り方
- 背景に画像または透過色を指定する方法

### 7 章で学んだこと

- main タグ、span 要素、section 要素などを使用した、ブログ部分の作り方

### 8 章で学んだこと

- サイドバーの作り方
- クラス名は一つのアイテムに複数つけることができる
- 疑似クラス
- pagenation の作り方
