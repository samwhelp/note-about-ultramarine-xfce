---
title: 輸入法
nav_order: 3030
has_children: true
---


# 輸入法


## 中文輸入法


## 主題

* [輸入法框架切換指令](#輸入法框架切換指令)
* [fcitx5](#fcitx5)
* [相關議題](#相關議題)




## 輸入法框架切換指令

| 輸入法框架 | 切換指令 | 設定檔路徑 |
| --- | --- | --- |
| [fcitx5](#fcitx5) | `imsettings-switch fcitx5` | ~/.config/imsettings/xinputrc |
| [ibus](#ibus) | `imsettings-switch ibus` | ~/.config/imsettings/xinputrc |
| [gcin](#gcin) | `imsettings-switch gcin` | ~/.config/imsettings/xinputrc |

執行

``` sh
imsettings-list
```

顯示

```
* 1: IBus[ibus.conf] (recommended)
  2: X compose table[xcompose.conf]
  3: fcitx5[fcitx5.conf]
  4: gcin[gcin.conf]
```

執行

``` sh
imsettings-switch fcitx5
```

執行

``` sh
file ~/.config/imsettings/xinputrc
```

顯示

```
/home/user/.config/imsettings/xinputrc: symbolic link to /etc/X11/xinit/xinput.d/fcitx5.conf
```



## fcitx5

| 模組 | 中文輸入法 |
| --- | --- |
| [fcitx5-chewing](https://samwhelp.github.io/note-about-ultramarine-xfce/read/subject/input-method/fcitx5/module/fcitx5-chewing.html) | 新酷音輸入法 |
| [fcitx5-table-boshiamy](https://samwhelp.github.io/note-about-ultramarine-xfce/read/subject/input-method/fcitx5/table/fcitx5-table-boshiamy.html) | 嘸蝦米輸入法 |
| [fcitx5-table-easy-large](https://samwhelp.github.io/note-about-ultramarine-xfce/read/subject/input-method/fcitx5/table/fcitx5-table-easy-large.html) | 輕鬆輸入法 |




## 相關議題

| 相關議題 |
| --- |
| [語系](https://samwhelp.github.io/note-about-ultramarine-xfce/read/subject/locale.html) |
| [字型](https://samwhelp.github.io/note-about-ultramarine-xfce/read/subject/font.html) |
