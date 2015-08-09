# PHP-Tutorial

php初学者向けのチュートリアル

## 開発環境構築
VirtualBox, VagrantをインストールしてVM上でPHPを動かす。

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
