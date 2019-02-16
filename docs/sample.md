# Markdown記法 サンプル集

## 見出し

# 見出し1
## 見出し2
### 見出し3
#### 見出し4
##### 見出し5
###### 見出し6

## 箇条書きkリスト
- リスト1
    - ネスト リスト1_1
        - ネスト リスト1_1_1
        - ネスト リスト1_1_2
    - ネスト リスト1_2
- リスト2
- リスト3

## 番号付きリスト
1. 番号付きリスト1
    1. 番号付きリスト1_1
    1. 番号付きリスト1_2
1. 番号付きリスト2
1. 番号付きリスト3

## 引用
> お世話になります。xxxです。
>
> ご連絡いただいた、バグの件ですが、仕様です。

## 二重引用
> お世話になります。xxxです。
>
> ご連絡いただいた、バグの件ですが、仕様です。
>> お世話になります。 yyyです。
>>
>> あの新機能バグってるっすね

## コードブロック
インストールコマンドは `gem install hoge` です

```
class Hoge
  def hoge
    print 'hoge'
  end
end
```

## 文字装飾
normal *italic* normal

normal _italic_ normal

normal **bold** normal

normal __bold__ normal

normal ***bold*** normal

normal ___bold___ normal

~~取り消し線~~

## 水平線
***

___

---

*    *    *

## リンク
[Google](https://www.google.co.jp/)

![Stormtroopocat](https://octodex.github.com/images/stormtroopocat.jpg "The Stormtroopocat")

## 表
|header1|header2|header3|
|:--|--:|:--:|
|align left|align right|align center|
|a|b|c|
