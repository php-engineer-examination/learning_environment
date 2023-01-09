# PHP で表示されるエラーの一覧

**目次**

1. [[#Parse error:|Parse error:]]
	1. [[#Parse error:#syntax error,|syntax error,]]

PHP で表示されるエラーメッセージの一覧です。  
エラーメッセージの読み方は、[[PHP エラーメッセージの読み方]] を参照してください。

## Fatal error:

`Parse error:` で始まるメッセージは、致命的な場合に発生するエラーのメッセージです。  
公式ドキュメント: 定義済みの例外 [ParseError]

### Uncaught DivisionByZeroError:

`Uncaught DivisionByZeroError:` で始まるメッセージは、`0` で除算（割り算）をしたために発生しているエラーです。  
公式ドキュメント: 定義済みの例外 [DivisionByZeroError]

**PHP 7.0 以降**

```log
Fatal error: Uncaught DivisionByZeroError: Division by zero in /src/example.php on line 10
Stack trace:
#0 {main}
  thrown in /src/example.php on line 10
```

## Parse error:

`Parse error:` で始まるメッセージは、PHP コードのパース（解析）に失敗した場合に発生するエラーのメッセージです。  
公式ドキュメント: 定義済みの例外 [ParseError]

### syntax error,

`syntax error,` で始まるメッセージは、文法エラーです。

**PHP 8.0 以降**

```log
Parse error: syntax error, unexpected token ";" in /src/example.php on line 10
```

**PHP 7.4 以前**

```log
Parse error: syntax error, unexpected ';' in /src/example.php on line 10
```

## Warning:

PHP の実行はできるが、警告として表示されているエラーの種類です。

### Division by zero

**PHP 7.4 以前**

`Division by zero` で始まるメッセージは、`0` で `/` 除算（割り算）をしたために発生しているエラーです。

```log
Warning: Division by zero in /src/example.php on line 10
```

[ArgumentCountError]: <https://www.php.net/manual/ja/class.argumentcounterror.php>
[ArithmeticError]: <https://www.php.net/manual/ja/class.arithmeticerror.php>
[AssertionError]: <https://www.php.net/manual/ja/class.assertionerror.php>
[DivisionByZeroError]: <https://www.php.net/manual/ja/class.divisionbyzeroerror.php>
[CompileError]: <https://www.php.net/manual/ja/class.compileerror.php>
[ParseError]: <https://www.php.net/manual/ja/class.parseerror.php>
[TypeError]: <https://www.php.net/manual/ja/class.typeerror.php>
[ValueError]: <https://www.php.net/manual/ja/class.valueerror.php>
[UnhandledMatchError]: <https://www.php.net/manual/ja/class.valueerror.php>
[FiberError]: <https://www.php.net/manual/ja/class.fibererror.php>
