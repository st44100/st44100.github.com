---
layout: post
title: "PhoneGap + iOS Sim 4.2 + Plist Missing WARNING"
date: 2011-10-12 19:09
comments: true
categories: 
---


PhoneGap 1.0 + iOS simulator 4.2 のとき,PhoneGap.plistを多言語に対応させると

1. PhoneGapで多言語対応してplistが複数できているとき

    {% img http://f.cl.ly/items/1f3U342D3A3v1C161426/picture%EF%BC%882011-10-12%2019.15.31%EF%BC%89.png 'plistの多言語化' %}


2. iOS Simulator 4.2でエラー

    {% codeblock PhoneGap Error Message %}
    2011-10-12 19:17:27.423 PCORN[69605:207] WARNING: PhoneGap.plist is missing.
    {% endcodeblock %}



* iOS 4.2.1の実機だと動く。


