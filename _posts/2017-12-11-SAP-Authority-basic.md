---
layout:     post
title:      "SAP オブジェクト命名ト権限"
subtitle:   "SAP豆知識"
date:       2017-12-11
author:     "Ding"
header-img: "img/aaron-burden-36113.jpg"
catalog: true
visible: 1
tags:
    - SAP
    - BASIS
---
# SAPのオブジェクト命名と権限

SAPのオブジェクトの命名と権限は知らない人が必ずぶつかる壁である。
汎用モジュールを作ろうとして、「TESTXXX」の名前で作ろうとしたら、いきなりアクセスキーが求められて、色々調べてもよくわからん！ という人は恐らくここに辿り着いたと思います。

実はZ＊とY＊以外のオブジェクト名は全部SAP社が標準オブジェクトとして抑えられています。（「今使用しなくても将来は使うから使っちゃダメ！」的な…わがまま…）

で、Z＊Y＊以外のオブジェクトは登録しようとしたら、オブジェクトキー(fn)が必要となります。オブジェクトキーはSSCR(fn)で申請する必要がある。一般的にプロジェクトのインフラチームに申請出します。出す単位は原則オブジェクト単位となります。


---- 
