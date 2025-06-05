---
title: "Markdown 範例"
date: 2020-06-08T08:06:25+06:00
description: Markdown 渲染範例
menu:
  sidebar:
    name: Markdown 範例
    identifier: markdown
    weight: 30
author:
  name: Jessica Jonas
  image: /images/author/jessica.png
math: true
---

這篇範例文章用於測試以下功能：

- 不同的文章作者。
- 目錄。
- Markdown 內容渲染。
- 數學公式渲染。
- 表情符號渲染。

---
# Markdown 語法渲染

## 標題

以下 HTML `<h1>`—`<h6>` 元素代表六個層級的標題。`<h1>` 是最高層級，而 `<h6>` 是最低層級。

# H1
## H2
### H3
#### H4
##### H5
###### H6

## 段落

Xerum, quo qui aut unt expliquam qui dolut labo. Aque venitatiusda cum, voluptionse latur sitiae dolessi aut parist aut dollo enim qui voluptate ma dolestendit peritin re plis aut quas inctum laceat est volestemque commosa as cus endigna tectur, offic to cor sequas etum rerum idem sintibus eiur? Quianimin porecus evelectur, cum que nis nust voloribus ratem aut omnimi, sitatur? Quiatem. Nam, omnis sum am facea corem alique molestrunt et eos evelece arcillit ut aut eos eos nus, sin conecerem erum fuga. Ri oditatquam, ad quibus unda veliamenimin cusam et facea ipsamus es exerum sitate dolores editium rerore eost, temped molorro ratiae volorro te reribus dolorer sperchicium faceata tiustia prat.

Itatur? Quiatae cullecum rem ent aut odis in re eossequodi nonsequ idebis ne sapicia is sinveli squiatum, core et que aut hariosam ex eat.

## 引用區塊

引用區塊元素表示從其他來源引用的內容，可以選擇性地包含引用來源（必須在 `footer` 或 `cite` 元素中），也可以選擇性地包含註釋和縮寫等內聯更改。

#### 無來源的引用

> Tiam, ad mint andaepu dandae nostion secatur sequo quae.
> **注意** 你可以在引用區塊中使用 *Markdown 語法*。

#### 有來源的引用

> Don't communicate by sharing memory, share memory by communicating.</p>
> — <cite>Rob Pike[^1]</cite>


[^1]: 上述引用摘自 Rob Pike 在 2015 年 11 月 18 日 Gopherfest 期間的[演講](https://www.youtube.com/watch?v=PAAkCSZUG1c)。

## 表格

表格不是核心 Markdown 規範的一部分，但 Hugo 原生支援它們。

   | Name  | Age |
   | ----- | --- |
   | Bob   | 27  |
   | Alice | 23  |

#### 表格中的內聯 Markdown

| Inline&nbsp;&nbsp;&nbsp; | Markdown&nbsp;&nbsp;&nbsp; | In&nbsp;&nbsp;&nbsp;                | Table  |
| ------------------------ | -------------------------- | ----------------------------------- | ------ |
| *italics*                | **bold**                   | ~~strikethrough~~&nbsp;&nbsp;&nbsp; | `code` |

## 程式碼區塊

#### 使用反引號的程式碼區塊

```
html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
```
#### 使用四個空格縮排的程式碼區塊

    <!DOCTYPE html>
    <html lang="en">
    <head>
      <meta charset="UTF-8">
      <title>Example HTML5 Document</title>
    </head>
    <body>
      <p>Test</p>
    </body>
    </html>

#### 使用 Hugo 內部高亮短代碼的程式碼區塊
{{< highlight html >}}
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Example HTML5 Document</title>
</head>
<body>
  <p>Test</p>
</body>
</html>
{{< /highlight >}}

## 列表類型

#### 有序列表

1. 第一項
2. 第二項
3. 第三項

#### 無序列表

* 列表項目
* 另一個項目
* 再一個項目

#### 巢狀列表

* 水果
  * 蘋果
  * 橘子
  * 香蕉
* 乳製品
  * 牛奶
  * 起司

## 其他元素 — abbr, sub, sup, kbd, mark

<abbr title="Graphics Interchange Format">GIF</abbr> 是一種點陣圖影像格式。

H<sub>2</sub>O

X<sup>n</sup> + Y<sup>n</sup> = Z<sup>n</sup>

按下 <kbd><kbd>CTRL</kbd>+<kbd>ALT</kbd>+<kbd>Delete</kbd></kbd> 結束工作階段。

大多數 <mark>蠑螈</mark> 都是夜行性的，以昆蟲、蠕蟲和其他小型生物為食。

---

## 數學公式渲染

{{< math.inline >}}
<p>
內聯數學：\(\varphi = \dfrac{1+\sqrt5}{2}= 1.6180339887…\)
</p>
{{</ math.inline >}}

區塊數學：
$$
 \varphi = 1+\frac{1} {1+\frac{1} {1+\frac{1} {1+\cdots} } } 
$$

---

## 表情符號渲染

<p><span class="nowrap"><span class="emojify">🙈</span> <code>:see_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙉</span> <code>:hear_no_evil:</code></span>  <span class="nowrap"><span class="emojify">🙊</span> <code>:speak_no_evil:</code></span></p>
<br>