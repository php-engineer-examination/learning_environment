# PHP で使用する記号の一覧

PHP 言語ではいろいろな記号を使用します。  
記号は検索がしにくいため、こちらに一覧でまとめます。  
ブラウザのWeb ページ内検索を利用すると、より簡単に記号が検索できます。

## 記号

| 記号         | 記号の意味                                                                                                                                                                                                        |
| ------------ | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| `!`          | [論理演算子](https://www.php.net/manual/ja/language.operators.logical.php) 否定                                                                                                                                   |
| `!=`         | [比較演算子](https://www.php.net/manual/ja/language.operators.comparison.php) 等しくない<br>[配列演算子](https://www.php.net/manual/ja/language.operators.array.php) 等しくない                                   |
| `!==`        | [比較演算子](https://www.php.net/manual/ja/language.operators.comparison.php) 等しくない<br>[配列演算子](https://www.php.net/manual/ja/language.operators.array.php) 同一でない                                   |
| `#`          | 行コメント                                                                                                                                                                                                        |
| `#[ ]`       | アトリビュート構文                                                                                                                                                                                                |
| `$`          | 変数                                                                                                                                                                                                              |
| `$$`         | 可変変数                                                                                                                                                                                                          |
| `%`          | [算術演算子](https://www.php.net/manual/ja/language.operators.assignment.php#language.operators.assignment.arithmetic) 剰余                                                                                       |
| `%=`         | [算術代入演算子](https://www.php.net/manual/ja/language.operators.assignment.php) 剰余                                                                                                                            |
| `^`          | [ビット演算子](https://www.php.net/manual/ja/language.operators.bitwise.php) 排他的論理和(XOR)                                                                                                                    |
| `^=`         | [ビット代入演算子](https://www.php.net/manual/ja/language.operators.assignment.php#language.operators.assignment.bitwise) 排他的論理和(XOR)                                                                       |
| `&`          | [ビット演算子](https://www.php.net/manual/ja/language.operators.bitwise.php) ビット積(AND)<br>リファレンス                                                                                                        |
| `&=`         | [ビット代入演算子](https://www.php.net/manual/ja/language.operators.assignment.php#language.operators.assignment.bitwise) ビット積(AND)                                                                           |
| `&&`         | [論理演算子](https://www.php.net/manual/ja/language.operators.logical.php) 論理積(AND)                                                                                                                            |
| `*`          | [算術演算子](https://www.php.net/manual/ja/language.operators.assignment.php#language.operators.assignment.arithmetic) 乗算                                                                                       |
| `*=`         | [算術代入演算子](https://www.php.net/manual/ja/language.operators.assignment.php) 乗算                                                                                                                            |
| `**`         | [算術演算子](https://www.php.net/manual/ja/language.operators.assignment.php#language.operators.assignment.arithmetic) 累乗                                                                                       |
| `**=`        | [算術代入演算子](https://www.php.net/manual/ja/language.operators.assignment.php) 累乗                                                                                                                            |
| `+`          | [算術演算子](https://www.php.net/manual/ja/language.operators.assignment.php#language.operators.assignment.arithmetic) 同一 加算<br>[配列演算子](https://www.php.net/manual/ja/language.operators.array.php) 結合 |
| `++`         | [加算子](https://www.php.net/manual/ja/language.operators.increment.php)                                                                                                                                          |
| `+=`         | [算術代入演算子](https://www.php.net/manual/ja/language.operators.assignment.php) 加算                                                                                                                            |
| `,`          | 関数引数                                                                                                                                                                                                          |
| `-`          | [算術演算子](https://www.php.net/manual/ja/language.operators.assignment.php#language.operators.assignment.arithmetic) 負にする 減算                                                                              |
| `--`         | [減算子](https://www.php.net/manual/ja/language.operators.increment.php)                                                                                                                                          |
| `-=`         | [算術代入演算子](https://www.php.net/manual/ja/language.operators.assignment.php) 減算                                                                                                                            |
| `->`         | クラスとオブジェクト                                                                                                                                                                                              |
| `.`          | [文字列演算子](https://www.php.net/manual/ja/language.operators.string.php)                                                                                                                                       |
| `...`        | 可変長引数                                                                                                                                                                                                        |
| `.=`         | [その他の代入演算子](https://www.php.net/manual/ja/language.operators.assignment.php#language.operators.assignment.other) 文字列の結合                                                                            |
| `:`          | ラベル<br>制御構造<br>三項演算子<br>SQL プリペアドステートメント プレースホルダ                                                                                                                                   |
| `::`         | スコープ定義演算子                                                                                                                                                                                                |
| `<`          | [比較演算子](https://www.php.net/manual/ja/language.operators.comparison.php) より少ない                                                                                                                          |
| `<=`         | [比較演算子](https://www.php.net/manual/ja/language.operators.comparison.php) より少ないか等しい                                                                                                                  |
| `<<`         | [ビット演算子](https://www.php.net/manual/ja/language.operators.bitwise.php) 左シフト                                                                                                                             |
| `<<=`        | [ビット代入演算子](https://www.php.net/manual/ja/language.operators.assignment.php#language.operators.assignment.bitwise) 左シフト                                                                                |
| `<<<`        | 文字列 ヒアドキュメント                                                                                                                                                                                           |
| `<<<' '`     | 文字列 ヒアドキュメント構文                                                                                                                                                                                       |
| `<<<" "`     | 文字列 Nowdoc構文                                                                                                                                                                                                 |
| `<>`         | [比較演算子](https://www.php.net/manual/ja/language.operators.comparison.php) 等しくない<br>[配列演算子](https://www.php.net/manual/ja/language.operators.array.php) 等しくない                                   |
| `<=>`        | [比較演算子](https://www.php.net/manual/ja/language.operators.comparison.php) 宇宙船演算子                                                                                                                        |
| `<?`         | `<?php` 開始タグの短縮型                                                                                                                                                                                          |
| `<?=`        | `<?php echo` 開始タグの短縮型                                                                                                                                                                                     |
| `<?php`      | 開始タグ                                                                                                                                                                                                          |
| `>`          | [比較演算子](https://www.php.net/manual/ja/language.operators.comparison.php) より多い                                                                                                                            |
| `>=`         | [比較演算子](https://www.php.net/manual/ja/language.operators.comparison.php) より多いか等しい                                                                                                                    |
| `>>`         | [ビット演算子](https://www.php.net/manual/ja/language.operators.bitwise.php) 右シフト                                                                                                                             |
| `>>=`        | [ビット代入演算子](https://www.php.net/manual/ja/language.operators.assignment.php#language.operators.assignment.bitwise) 右シフト                                                                                |
| `=`          | [代入演算子](https://www.php.net/manual/ja/language.operators.assignment.php) 代入                                                                                                                                |
| `=&`         | リファレンス                                                                                                                                                                                                      |
| `==`         | [比較演算子](https://www.php.net/manual/ja/language.operators.comparison.php) 等しい<br>[配列演算子](https://www.php.net/manual/ja/language.operators.array.php) 同等                                             |
| `===`        | [比較演算子](https://www.php.net/manual/ja/language.operators.comparison.php) 等しい<br>[配列演算子](https://www.php.net/manual/ja/language.operators.array.php) 同一                                             |
| `=>`         | 配列                                                                                                                                                                                                              |
| `/`          | [算術演算子](https://www.php.net/manual/ja/language.operators.assignment.php#language.operators.assignment.arithmetic) 除算                                                                                       |
| `/=`         | [算術代入演算子](https://www.php.net/manual/ja/language.operators.assignment.php) 除算                                                                                                                            |
| `/*`<br>`*/` | ブロックコメント                                                                                                                                                                                                  |
| `//`         | 行コメント                                                                                                                                                                                                        |
| `?`          | [三項演算子](https://www.php.net/manual/ja/language.operators.comparison.php#language.operators.comparison.ternary)<br>Nullable型<br>glob ワイルドカード<br>SQL プリペアドステートメント プレースホルダ           |
| `?:`         | [エルビス演算子](https://www.php.net/manual/ja/language.operators.comparison.php#language.operators.comparison.ternary)                                                                                           |
| `?>`         | 終了タグ                                                                                                                                                                                                          |
| `??`         | [Null合体演算子](https://www.php.net/manual/ja/language.operators.comparison.php#language.operators.comparison.coalesce)                                                                                          |
| `??=`        | [Null合体代入演算子](https://www.php.net/manual/ja/language.operators.assignment.php#language.operators.assignment.other)                                                                                         |
| `?->`        | Nullsafe演算子                                                                                                                                                                                                    |
| `@`          | [エラー制御演算子](https://www.php.net/manual/ja/language.operators.errorcontrol.php)                                                                                                                             |
| `[]`         | 配列 (`array()`と同等)                                                                                                                                                                                            |
| `\`          | 名前空間                                                                                                                                                                                                          |
| `^`          | ビット演算子                                                                                                                                                                                                      |
| `` ` ``      | [実行演算子](https://www.php.net/manual/ja/language.operators.execution.php)                                                                                                                                      |
| \|           | [ビット演算子](https://www.php.net/manual/ja/language.operators.bitwise.php) ビット和(OR)                                                                                                                         |
| \|=          | [ビット代入演算子](https://www.php.net/manual/ja/language.operators.assignment.php#language.operators.assignment.bitwise) ビット和(OR)                                                                            |
| \|\|         | [論理演算子](https://www.php.net/manual/ja/language.operators.logical.php) 論理和(OR)                                                                                                                             |
| `~`          | [ビット演算子](https://www.php.net/manual/ja/language.operators.bitwise.php) 否定(NOT)                                                                                                                            |
| `_()`        | `gettext()` 関数の別の表記                                                                                                                                                                                        |

## 文字列内の記号が組み込まれているケース

記号が文字列内に書かれているときに、別途特別な意味を持つことがあります。  
有名なものは「SQL プリペアドステートメント プレースホルダ」などです。  
他にも、他のプログラミング言語の記号が組み込まれているケースもあるので、下記の内容も把握しておくことが望ましいです。

* ファイルパスや glob パターン
* 正規表現
* SQL
* その他のプログラミング言語