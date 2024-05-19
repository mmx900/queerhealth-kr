---
title: 병원 및 상담센터 정보
author: Soyu Kim
date: 2023-05-10
category: Jekyll
layout: post
---

* [성소수자알권리보장지원 노스웨스트 호](https://theshipnorthwest.tistory.com/notice/16)에서는 퀴어프렌들리 병원과 상담센터 정보 및 후기를 제보받아 정리하고 있습니다.
  > 현재 노스웨스트 호는 퀴어 관련 의료/상담/생활/복지 등의 정보를 정리하여 게시하는 활동을 주로 하고있습니다. - [성소수자알권리보장지원 노스웨스트 호란?](https://theshipnorthwest.tistory.com/entry/%EC%84%B1%EC%86%8C%EC%88%98%EC%9E%90%EC%95%8C%EA%B6%8C%EB%A6%AC%EB%B3%B4%EC%9E%A5%EC%A7%80%EC%9B%90-%EB%85%B8%EC%8A%A4%EC%9B%A8%EC%8A%A4%ED%8A%B8-%ED%98%B8%EB%8A%94)
* [성소수자와함께하는상담사모임, 다다름](https://linktr.ee/QALLY)에서는 퀴어프렌들리 상담사 리스트를 배포중입니다. 
* [트랜스로드맵](http://transroadmap.net/transgender-health/)에서는 트랜스젠더에 대한 이해가 있는 일반 병원의 목록을 게시중입니다.
* 다음은 홈페이지에서 명시적으로 성소수자(LGBTQIA+)를 명시하고 있는 병원들입니다.
  {% for hospital in site.data.hospitals %}
    * [{{ hospital.name }}]({{ hospital.url }}) - {{ hospital.location }}
    > {{ hospital.quote }}
    {% for review in hospital.reviews %}
      * [{{ review.title }}]({{ review.url }})
    {% endfor %}
  {% endfor %}
* [iSHAP](https://ishap.org/?c=2/62/65)에서는 PrEP 처방을 받을 수 있는 병원의 목록을 게시중입니다. 
  > PrEP은 HIV 치료가 가능한 병원(주로 감염내과) 등에서 처방받을 수 있습니다. iSHAP은 PrEP을 처방 받을 수 있는 병원과 함께 진료의뢰서 없이 편하게 방문할 수 있거나 원외처방을 통해 PrEP을 처방받을 수 있는 병원을 조사 하고 있습니다. 아래 명단 이외에 원외 처방이 가능한 병원을 알고 있다면 아이샵으로 제보 부탁드립니다. - [PrEP 병원안내](https://ishap.org/?c=2/62/65)
* [iSHAP](https://www.ishap.org/?c=67/68)에서는 또한 엠폭스(MPOX) 백신 접종 가능 병원과 다양한 정보를 제공합니다.

소식
----

[[모집] 부산지역 청소년 성소수자 정신의료 정보접근권 조사단을 찾습니다.](https://www.facebook.com/onlyasunaro/posts/pfbid035fKgfKFkZDhXkHe4zPXs3ifgubuhpg47UBVDWACGwsiXxDQQRvDyArATLAs1Tjd1l) - 부산어린이퀴어센터 2024.05.15
