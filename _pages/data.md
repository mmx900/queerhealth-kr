---
title: 자료
author: Soyu Kim
date: 2023-05-15
category: Jekyll
layout: post
---

서적
----

{% for book in site.data.books %}
* [{{book.title}}]({{book.url}}) - {{book.date}} {{book.publisher}}
  > {{book.summary}} 
{% endfor %}

자료
----

* [트랜스섹슈얼·트랜스젠더·성별비순응자를 위한 건강관리실무표준 - 세계트랜스젠더보건의료전문가협회(WPATH)](https://rainbowfoundation.co.kr/intro_book/7315)


아카이브
----

* 코로나19 성소수자 긴급 대책본부
  * [코로나19 성소수자 긴급대책본부 활동백서](https://lgbtqact.org/queer-action-against-covid19/) - 2020.12.2
  * [웹사이트 (웹 아카이브)](http://web.archive.org/web/20220601000000*/https://www.queer-action-against-covid19.org/)
