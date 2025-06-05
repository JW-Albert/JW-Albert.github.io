---
title: "短代碼範例"
date: 2020-06-08T08:06:25+06:00
description: 短代碼範例
menu:
  sidebar:
    name: 短代碼範例
    identifier: shortcodes
    weight: 40
---

這篇範例文章用於測試以下功能：

- 預設英雄圖片。
- 各種短代碼。

## 提示框

這個主題包含以下提示框：

{{< alert type="success" >}}
這是使用 `type="success"` 的範例提示框。
{{< /alert >}}

{{< alert type="danger" >}}
這是使用 `type="danger"` 的範例提示框。
{{< /alert >}}

{{< alert type="warning" >}}
這是使用 `type="warning"` 的範例提示框。
{{< /alert >}}

{{< alert type="info" >}}
這是使用 `type="info"` 的範例提示框。
{{< /alert >}}

{{< alert type="dark" >}}
這是使用 `type="dark"` 的範例提示框。
{{< /alert >}}

{{< alert type="primary" >}}
這是使用 `type="primary"` 的範例提示框。
{{< /alert >}}

{{< alert type="secondary" >}}
這是使用 `type="secondary"` 的範例提示框。
{{< /alert >}}

## 圖片

#### 不帶任何屬性的圖片範例。

{{< img src="/posts/shortcodes/boat.jpg" title="A boat at the sea" >}}

{{< vs 3 >}}

#### 帶有 `height` 和 `width` 屬性的圖片範例。

{{< img src="/posts/shortcodes/boat.jpg" height="400" width="600" title="A boat at the sea" >}}

{{< vs 3 >}}

#### 帶有 `height` 和 `width` 屬性且置中的圖片範例。

{{< img src="/posts/shortcodes/boat.jpg" height="400" width="600" align="center" title="A boat at the sea" >}}

{{< vs 3 >}}

#### 帶有 `float` 屬性的圖片範例。

{{< img src="/posts/shortcodes/boat.jpg" height="200" width="500" float="right" title="A boat at the sea" >}}

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras egestas lectus sed leo ultricies ultricies. Praesent tellus risus, eleifend vel efficitur ac, venenatis sit amet sem. Ut ut egestas erat. Fusce ut leo turpis. Morbi consectetur sed lacus vitae vehicula. Cras gravida turpis id eleifend volutpat. Suspendisse nec ipsum eu erat finibus dictum. Morbi volutpat nulla purus, vel maximus ex molestie id. Nullam posuere est urna, at fringilla eros venenatis quis.

Fusce vulputate dolor augue, ut porta sapien fringilla nec. Vivamus commodo erat felis, a sodales lectus finibus nec. In a pulvinar orci. Maecenas suscipit eget lorem non pretium. Nulla aliquam a augue nec blandit. Curabitur ac urna iaculis, ornare ligula nec, placerat nulla. Maecenas aliquam nisi vitae tempus vulputate.

## 分欄

這個主題支援將頁面分成任意數量的欄位。

#### 分成兩欄

{{< split 6 6>}}

##### 左欄

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras egestas lectus sed leo ultricies ultricies.

---

##### 右欄

Fusce ut leo turpis. Morbi consectetur sed lacus vitae vehicula. Cras gravida turpis id eleifend volutpat.

{{< /split >}}

#### 分成三欄

{{< split 4 4 4 >}}

##### 左欄

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Cras egestas lectus sed leo ultricies ultricies.

---

##### 中間欄

Aenean dignissim dictum ex. Donec a nunc vel nibh placerat interdum. 

---

##### 右欄

Fusce ut leo turpis. Morbi consectetur sed lacus vitae vehicula. Cras gravida turpis id eleifend volutpat.

{{< /split >}}

## 垂直間距

可以在兩行之間添加垂直間距。

這是第一行
{{< vs 4>}}
這是第二行。應該與第一行有 `4rem` 的垂直間距。