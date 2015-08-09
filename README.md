# PHP-Tutorial

php初学者向けのチュートリアル

## Hello World!
```php
<?php 
echo "Hello World";
```
## htmlを表示してみる
### その１ - ひたすら出力
```php
<?php
$hello = "Hello World!";
echo "<html>";
echo "<body>";
echo "<h1>{$hello}</h1>";
echo "</body>";
echo "</html>";
```

### その２ - ヒアドキュメント使ってみる
```php
<?php
$hello = "Hello World!";
echo <<< __HTML__
<html>
  <body>
    <h1>{$hello}</h1>
  </body>
</html>
__HTML__;
```

### その３ - HTMLにphpのコードを埋め込む
```php
<?php
$hello = "Hello World";
?>

<html>
  <body>
    <h1><?php echo $hello; ?></h1>
  </body>
</html>

```

### 配列の宣言

```php
$array = [];
$array = array();
```

## ブログを作ってみる

* ブログ一覧ページ
* ブログ詳細ページ
* 新規ブログ作成ページ

### ブログ一覧ページ(TOPページ)
今までに投稿したブログの記事一覧が閲覧できる

### ブログ詳細ページ
ブログ一覧ページのブログの詳細ボタンを押すことで遷移できるページ
実際に書かれたブログの内容を閲覧、修正、更新することができる

### 新規ブログ作成ページ
ブログ一覧ページから遷移することができる


### ページを表示してみる
### formからのリクエストを取得する
### エラーチェックする
### 
