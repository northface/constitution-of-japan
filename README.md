# 日本国憲法

このレポジトリは、現在の日本国憲法、そして現在の日本国憲法に対して提案された日本国憲法改正案がどのような変更点を含むか理解するためのものです。


# 改正案 (あいうえお順)

## 引用記事
https://blogos.com/article/179470/?p=2

## 同時に検討されるべき事項

- 日米地位協定関連
  - https://www.mofa.go.jp/mofaj/area/usa/sfa/kyoutei/index.html


# スタイルガイド

- markdownで記述する
  - TODO: 恐らく憲法そのもののファイルにヘッダーを持つ方が良い (データの元のURL、改正案の立案者/提出元、日付など)
- 日本語のみで記述する
  - つまり、それがmarkdownのsyntaxである場合を除き、半角文字列は使用しない
- [ヘッダーのスタイル](https://daringfireball.net/projects/markdown/syntax#header)は、Setextではなくatx
  - 章の中に含まれる条など、ヘッダーにレベルが必要な場合は、レベルを一つずつ下げていく (例えば、`###`を章に使っていてその中に条がある場合は、条に`####`を使う)
  - ヘッダー (markdownの文法としての) の後には半角の空白を入れる (例えば、`#[半角の空白]タイトル`の様にする)


# 改正案のコミットの方法

- masterブランチから新しいブランチを作成する
  - ブランチの名前は、``feature/{提案者の名前}-{提案の名前}-YYYY-MM-DD``に従う
- 作成した新しいブランチで、``日本国憲法.md``のみを提案の通りに編集する
- 作成した新しいブランチから、masterブランチに対してpull requestを作成する


# データ

## 日本国憲法

http://elaws.e-gov.go.jp/search/elawsSearch/elaws_search/lsg0500/detail?lawId=321CONSTITUTION
