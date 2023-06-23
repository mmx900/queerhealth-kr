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
* [{{ book.title }}{% if book.subtitle %} - {{ book.subtitle }}{% endif %}]({{ book.url }}) - {{ book.date }} {% if book.author %}{{ book.author }} / {% endif %} {{ book.publisher }}
  > {{ book.summary }} 
{% endfor %}

자료
----

* [나, 그대로 괜찮은 상담실 - 2022 성소수자 대상 심리상담 경험 및 욕구 설문조사 보고서](https://www.instagram.com/p/Ctnbv8IJs2g/) - "성소수자와 함께하는 상담사 모임, 다다름", 2023.06.18
* [성적소수자의 노후인식조사 보고서](http://kscrc.org/xe/board_hWwy34/19728) - 한국성적소수자문화인권센터, 2021.11.29
* [혐오의 시대에 맞서는 성소수자에 대한 12가지 질문](https://lgbtstudies.or.kr/) - 한국성소수자연구회(준), 2016.06.11
* [트랜스섹슈얼·트랜스젠더·성별비순응자를 위한 건강관리실무표준 - 세계트랜스젠더보건의료전문가협회(WPATH)](https://rainbowfoundation.co.kr/intro_book/7315)


아카이브
----

* 코로나19 성소수자 긴급 대책본부
  * [코로나19 성소수자 긴급대책본부 활동백서](https://lgbtqact.org/queer-action-against-covid19/) - 2020.12.2
  * [웹사이트 (웹 아카이브)](http://web.archive.org/web/20220601000000*/https://www.queer-action-against-covid19.org/)
