<!-- MDTOC maxdepth:6 firsth1:1 numbering:1 flatten:0 bullets:0 updateOnSave:1 -->

1. [This is an H1 Features](#this-is-an-h1-features)   
2. [This is an H1](#this-is-an-h1)   
&emsp;2.1. [This is an H2](#this-is-an-h2)   
&emsp;2.2. [This is an H2](#this-is-an-h2-1)   
&emsp;&emsp;2.2.1. [This is an H3](#this-is-an-h3)   
3. [This is an H1 Features](#this-is-an-h1-features-1)   
&emsp;&emsp;3.0.1. [中文標題](#中文標題)   
&emsp;3.1. [Not Use](#not-use)   
&emsp;3.2. [Not support](#not-support)   

<!-- /MDTOC -->
# This is an H1 Features

# This is an H1 #

This is an H2
----

## This is an H2 ##

### This is an H3 ######

----
# This is an H1 Features

由於計劃於本月底到東京自由行，又為了減輕行李負擔，這次希望不要攜帶筆記型電腦，雖說我的Think Pad X61「只有」1.5公斤，但開關機緩慢的速度經常會打消我使用的欲望，因此這次就評估看看iPad是否會是旅行的好伴侶。為了達成攜帶iPad旅行運用，我事先做了下列的硬體與軟體準備︰

* 硬體
    1. iPad、連接線與充電器
    1. Apple Camera Connection Kit
    1. [AluPen][]觸控筆
    1. [JustMobile Encore][] iPad折疊式鋁質置放架
    1. 藍牙無線鍵盤+備用電池一顆
    1. 日本國內的3G SIM卡 (尚未備妥)

    △代辦事項

▼預備中的「武器」

![iPad-devices][]

Here's an example:
``` c++
function test() {
  console.log("notice the blank line before this function?");
}
```
``` ruby
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
```
First Header  | Second Header
------------- | -------------
Content Cell  | Content Cell
Content Cell  | Content Cell

| Function name | Description                    |
| ------------- | ------------------------------ |
| `help()`      | Display the help window.       |
| `destroy()`   | **Destroy your computer!**     |

| Left-Aligned  | Center Aligned  | Right Aligned |
| :------------ |:---------------:| -----:|
| col 3 is      | some wordy text | $1600 |
| col 2 is      | centered        |   $12 |
| zebra stripes | are neat        |    $1 |

---------------------------------------------------------------------------

* iPad專屬軟體
  1. GPS軟體 (還在Survey，[MotionX GPS HD][]似乎不錯)
    1. 東京旅遊的相關電子書
    1. Skype (已購買點數)
    1. [WordPress for iPad][] (更新部落格用的AutoMattic官方軟體)
    1. 支援[Markdown][]語法的編輯器，看了幾套但似乎都不太理想，條件如下:
        * 要支援雲端儲存 (例如能同步文章到Dropbox)
        * 必須支援[TextExpander Touch][]，以能快速輸入、；常用詞彙
    1. 圖片處理軟體 (已購買[Photogene][]，希望足敷使用)

請點擊[此處連結](http://jdev.tw/files/Blog-Markdown.txt)開新分頁檢視。

[AluPen]: http://www.ipevo.com/prods/Just_Mobile_AluPen_iPad_iPhone4
[JustMobile Encore]: http://www.ipevo.com/prods/Just_Mobile_Encore_iPad_Silver_black
[iPad-devices]: http://www.artronix.net/upload/9440452999312Programing.jpg
[Markdown]: http://daringfireball.net/projects/markdown/syntax
[Markdown 說明]: http://dgta.hopto.org/wiki/Markdown%20%E8%AA%AA%E6%98%8E
[PHP Markdown Extra]: http://michelf.com/projects/php-markdown/extra
[Markdown Extra]: http://michelf.com/projects/php-markdown/extra
[TextExpander Touch]: http://jdev.tw/blog/2390#header-7
[Photogene]: http://itunes.apple.com/us/app/photogene-for-ipad/id363448251?mt=8

\#\#

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.





### 中文標題


## Not Use

----------------------------------------------------------------------

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__

Not support
----------------------------------------------------------------------

That's some text with a footnote.[^1]

[^1]: And that's the footnote.


``` diff
-         <td> <%= post.content %> </td>
+         <td> <%= simple_format(post.content) %> </td>
...
```

``` c++ test.cpp
function test() {
  console.log("notice the blank line before this function?");
}
```

{% blockquote Author Name %}
Flying is learning how to throw yourself at the ground and miss.
{% endblockquote %}

{% blockquote Author Name https://example.com/quotation/source/link %}
Over the past 24 hours I've been reflecting on my life & I've realized only one thing. I need a medieval battle axe.
{% endblockquote %}
