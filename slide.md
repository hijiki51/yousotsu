---
marp: true
theme: default
---
<!--
headingDivider: 2
-->



# 教養卒論
理学院物理学系　関響

## 手続き型言語
```c
int main() {
  /* mesという変数に"Hello World"を格納 */
  const char *mes = "Hello World";
  /* mesを出力 */
  printf("%s\n", mes);
}
```
## 関数型言語

```haskell
main = fizzbuzz 100
fizzbuzz n = mapM_ (putStrLn . mes) [1..n]
mes n 
  | n `mod` 15 == 0 = "FizzBuzz"
  | n `mod` 3 == 0 = "Fizz"
  | n `mod` 5 == 0 = "Buzz"
  | otherwise = show n
```
## コンパイル言語

- コンパイル言語
  - 一度機械語に翻訳してから実行する
  - C,Rust,Goなど

## コンパイル言語/スクリプト言語

- スクリプト言語
  - ソースコードを逐次翻訳して実行する
  - JavaScript,Pythonなど
# 完
