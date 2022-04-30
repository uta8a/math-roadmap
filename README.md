# 数理メモ

ここにアルゴリズム/数学/暗号関連のドキュメントを置く。

# `content/` の説明

archetypesとしてテンプレートが `algorithm`, `cryptography`, `math`, `writeup` が存在している。

- `algorithm`: 競技プログラミングやアルゴリズム関連
- `cryptography`: 暗号やCTFのCrypto関連
- `math`: 数学関連
- `writeup`: 競技プログラミングやCTFや数学の問題の自分の解答置き場

# 記事を書くときの流れ

## 初回

hugo(extended): `hugo v0.92.2+extended darwin/arm64 BuildDate=unknown` 以降

```sh
# hugo new {template}/{topic_name}/_index.md
$ hugo new cryptography/differential-cryptoanalysis/_index.md
```

- `content/{template}/{topic_name}/` の中にその記事で使用する画像などを置く。
- frontmatterのtitle, descriptionに書き込む。このdescriptionはlistで使われる。
- frontmatterのdraftをfalseにすると公開

## 編集

- 編集したらfrontmatterのchangelogを書き換えておく

# その他

changelogをfrontmatterに置く発想は [ア辞典](https://github.com/noshi91/algorithm-encyclopedia) を参考にしました

style resetに、The New CSS Reset: https://github.com/elad2412/the-new-css-reset を使用しています。(MIT license)

syntax highlightに、prism.js: https://prismjs.com/ を使用しています。(MIT license)
