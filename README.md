﻿# ★markdown 整理

## テーブルの書き方
```
.1行: ヘッダを表示する行。ここでは「 ヘッダ行 」と呼ぶ。
.2行目: 列ごとのアラインメントを設定する行。ここでは「 アラインメント行 」と呼ぶ。
.3行目以降: データを表示する行。ここでは「 データ行 」と呼ぶ。好きなだけ追加可能。
test
```
|a  |b  |c  |
|---|---|---|
|1  |2  |3  |
|4  |5  |6  |
---
## header 見出し
```
# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6
```
# 見出し1
## 見出し2
### 見出し3
test
##### 見出し5
###### 見出し6
---
## block 段落
```
段落1
(空行)
段落2
```
段落1

段落2

---
## br　改行
　(改行の前に半角スペース を2つ記述します。)
```
hoge
fuga(スペース2つ)
piyo
```
test
fuga  
piyo

---
## Blockquotes 引用
　(先頭に>を記述します。ネストは>を多重に記述します。)
```
> 引用  
> 引用
>> 多重引用
```
> 引用  
> 引用
>> 多重引用
---
## Hr 水平線
　(アンダースコア_ 、ハイフン-アスタリスク*などを3つ以上連続して記述します)
```
hoge
***
hoge
___
hoge
---
```
hoge
***
hoge
___
hoge

---
## ul 箇条書き
ハイフン-、プラス+、アスタリスク*のいずれかを先頭に記述します。
ネストはタブで表現します。
```
- リスト1
    - リスト1_1
        - リスト1_1_1
        - リスト1_1_2
    - リスト1_2
- リスト2
- リスト3
```
- リスト1
    - リスト1_1
        - リスト1_1_1
        - リスト1_1_2
    - リスト1_2
- リスト2
test

---

## 強調
```
em (アスタリスク*もしくはアンダースコア_1個で文字列を囲みます。)

これは *イタリック* です
これは _イタリック_ です
これは イタリック です これは イタリック です

strong (アスタリスク*もしくはアンダースコア_2個で文字列を囲みます。)

これは **ボールド** です
これは __ボールド__ です
これは ボールド です これは ボールド です

em + strong (アスタリスク*もしくはアンダースコア_3個で文字列を囲みます。)

これは ***イタリック＆ボールド*** です
これは ___イタリック＆ボールド___ です
これは イタリック＆ボールド です これは イタリック＆ボールド です
```
これは *イタリック* です
これは _イタリック_ です

これは **ボールド** です
これは __ボールド__ です

これは ***イタリック＆ボールド*** です
これは ___イタリック＆ボールド___ です

---

## code記法
(バッククォートで文字列を囲むことでコードの一部を表示可能です。)

```
インストールコマンドは `gem install hoge` です
```
インストールコマンドは `gem install hoge` です

---

## GFM:取り消し線
(チルダ2個で文字列を囲むことで取り消し線を利用できます。)

```
~~取り消し線~~
```
~~取り消し線~~

---
