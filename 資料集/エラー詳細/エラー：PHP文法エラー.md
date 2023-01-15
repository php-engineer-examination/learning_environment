# エラー：PHP文法エラー

## エラーメッセージ例

**PHP 8 系**

```log
Parse error: syntax error, unexpected token ";" in /src/example.php on line 10
```

**PHP 7 系 / PHP 5.6 系**

```log
Parse error: syntax error, unexpected ';' in /src/example.php on line 10
```

## 原因

PHP コードの文法が間違っているため、パース（解析）に失敗した場合に発生するエラーメッセージです。  
公式ドキュメント: 定義済みの例外 [ParseError]

```php
// 例: 文末 ; の位置がおかしい
echo ('message';)
```

## 解決方法

エラーが発生した行を確認します。  
また、エラーが発生した行より上に問題があります。

```php
// 例: 文末の ) と ; の位置を入れ替える
echo ('message');
```

[ParseError]: <https://www.php.net/manual/ja/class.parseerror.php>