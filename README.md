# 日本国憲法

このレポジトリは、現在の日本国憲法、そして現在の日本国憲法に対して提案された日本国憲法改正案がどのような変更点を含むか理解するためのものです。


# 改正案 (あいうえお順)

## 伊勢崎賢治 憲法9条改正案

- 差分
  - https://github.com/northface/constitution-of-japan/pull/1/files
- データ
  - https://blogos.com/article/179470/?p=2

### 日米地位協定の改定
 > 日本の施政下のすべての在日米軍拠点（基地および空域）における日本の主権を回復する。具体的には、
 > - 地位協定の時限立法化（更新可）、もしくは、米軍の（段階的・完全）撤退時の状況をビジョン化（日本がすべての隣国との領土、領海問題の完全解決等）
 > - 在日米軍基地に米軍が持ち込むすべての兵器、軍事物資に対する日本政府の許可と随時の検閲権。
 > - 在日米軍基地が日本の施政下以外の他国、領域への武力行使に使われることの禁止。

### 参考
- 護憲か、改憲か？ ４人の論客の「憲法９条案」を比較する
　　https://blogos.com/article/179470/
  
- 日米地位協定関連
  - https://www.mofa.go.jp/mofaj/area/usa/sfa/kyoutei/index.html

## 自由民主党: 日本国憲法改正草案-2012-04-27

- 差分
  - https://github.com/atsuya/constitution-of-japan/pull/1/files
- データ
  - https://jimin.ncss.nifty.com/pdf/news/policy/130250_1.pdf

## 日本のこころ:（日本のこころ）日本国憲法草案-2017-04-27

- 差分
  - https://github.com/atsuya/constitution-of-japan/pull/6/files
- データ
  - http://nippon-kokoro.jp/news/policies/kenpo01.php
  
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
