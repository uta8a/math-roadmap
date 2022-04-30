---
layout: example
title: Exampleページ $f(\alpha)$
description: |
  これは見た目テスト用のサンプルページです。
  改行してみた

  空行で段落別にできる
  数学ブロック $\alpha + 1$
  小さなコードブロック `code`
draft: false # deploy時にtrueにしておくとよい
changelog:
  - summary: 見出し作成
    date: 2022-04-30T17:32:55+09:00
---

# これは `h1` 見出しです
## これは `h2` 見出しです
### これは `h3` 見出しです
#### これは `h4` 見出しです
##### これは `h5` 見出しです
###### これは `h6` 見出しです

これは一行。

空行を開けています。
これは空行を開けないで二行書いています。

これは数学 $f(x)$
複数行の数式は毎回 `$` で囲うことにする。

<hr>

↑htmlタグが書ける。ここでは `<hr>` を書いた

```none
$ git status
```

```c
#include <stdio.h>

int main(void) {
  int a = 1;
}
```
