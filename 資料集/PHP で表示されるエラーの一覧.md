# PHP で表示されるエラーの一覧

**目次**

1. [[#Fatal error:]]
1. [[#Parse error:]]
1. [[#Warning:]]

PHP で表示されるエラーメッセージの一覧です。  
エラーメッセージの読み方は、[[PHP エラーメッセージの読み方]] を参照してください。

## Fatal error:

`Fatal error:` で始まるメッセージは、致命的な場合に発生するエラーのメッセージです。  
公式ドキュメント: 定義済みの例外 [ParseError]

---

> **Fatal error: Uncaught DivisionByZeroError: Division by zero**

[[エラー：ゼロで除算]] を参照

---

> **Fatal error: Uncaught Error: Attempt to increment/decrement property "`{property_name}`" on `{var_type}`**

- `{property_name}` : エラーメッセージ内に書かれているプロパティ名
- `{var_type}` : エラーメッセージ内に書かれている変数の型

[[エラー：プロパティのインクリメント／デクリメント]] を参照

---

## Parse error:

`Parse error:` で始まるメッセージは、PHP コードのパース（解析）に失敗した場合に発生するエラーメッセージです。  
公式ドキュメント: 定義済みの例外 [ParseError]

---

> **Parse error: syntax error, unexpected token ";"**

> **Parse error: syntax error, unexpected ';'**

[[エラー：PHP文法エラー]] を参照

---

## Warning:

PHP の実行はできるが、警告として表示されているエラーの種類です。  
公式ドキュメント: 定義済みの例外 [E_WARNING]

---

> **Warning: Attempt to increment/decrement property '`{property_name}`' of non-object**

> **Warning: Attempt to increment/decrement property of non-object**  

- `{property_name}` : エラーメッセージ内に書かれているプロパティ名

[[エラー：プロパティのインクリメント／デクリメント]] を参照

---

> **Warning: Division by zero**

[[エラー：ゼロで除算]] を参照

[E_WARNING]: <https://www.php.net/manual/ja/errorfunc.constants.php>
[Error]: <https://www.php.net/manual/ja/class.error.php>
[ArgumentCountError]: <https://www.php.net/manual/ja/class.argumentcounterror.php>
[ArithmeticError]: <https://www.php.net/manual/ja/class.arithmeticerror.php>
[AssertionError]: <https://www.php.net/manual/ja/class.assertionerror.php>
[CompileError]: <https://www.php.net/manual/ja/class.compileerror.php>
[ParseError]: <https://www.php.net/manual/ja/class.parseerror.php>
[TypeError]: <https://www.php.net/manual/ja/class.typeerror.php>
[ValueError]: <https://www.php.net/manual/ja/class.valueerror.php>
[UnhandledMatchError]: <https://www.php.net/manual/ja/class.valueerror.php>
[FiberError]: <https://www.php.net/manual/ja/class.fibererror.php>
