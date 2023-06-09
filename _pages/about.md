---
title: 전문가 및 병원
author: Soyu Kim
date: 2023-05-14
category: Jekyll
layout: post
---

청소년 상담
----

* [사단법인 청소년 성소수자 지원센터 띵동](https://www.ddingdong.kr/xe/counsel)
  > 띵동은 위기상황에 놓인 청소년 성소수자들에게 필요한 서비스를 제공하고 있습니다.
  > 도움이 필요한 청소년 성소수자들은 언제든지 띵동의 문을 두드릴 수 있습니다. - [위기상담 및 지원](https://www.ddingdong.kr/xe/counsel)

부모 상담
----

* [성소수자부모모임 상담신청](https://www.pflagkorea.org/%EC%83%81%EB%8B%B4%EC%8B%A0%EC%B2%AD)

정신 건강 관련 상담
-------------

* [성소수자알권리보장지원 노스웨스트 호](https://theshipnorthwest.tistory.com)
  > 현재 노스웨스트 호는 퀴어 관련 의료/상담/생활/복지 등의 정보를 정리하여 게시하는 활동을 주로 하고있습니다. - [성소수자알권리보장지원 노스웨스트 호란?](https://theshipnorthwest.tistory.com/entry/%EC%84%B1%EC%86%8C%EC%88%98%EC%9E%90%EC%95%8C%EA%B6%8C%EB%A6%AC%EB%B3%B4%EC%9E%A5%EC%A7%80%EC%9B%90-%EB%85%B8%EC%8A%A4%EC%9B%A8%EC%8A%A4%ED%8A%B8-%ED%98%B8%EB%8A%94)
* [성소수자 자살예방 프로젝트 마음연결](https://chingusai.net/xe/main_connect) - 전화 및 게시판 상담
  > 전화상담은 자살을 고민하는 성소수자와 그러한 성소수자를 돕고 싶어 하는 분들에게 도움을 드립니다. - [전화상담](https://chingusai.net/xe/quick)
* [성소수자와 함께하는 상담사 모임, 다다름](https://vigorous-queen-bc7.notion.site/bd98bf09262d405887286827bdb83fd5)


병원
-------------

* [트랜스젠더에 대한 이해가 있는 일반병원이 있나요? - TRANS·ROADMAP](http://transroadmap.net/transgender-health/)
* 홈페이지 등에서 성소수자를 명시적으로 언급하고 있는 병원들
  {% for hospital in site.data.hospitals %}
    * [{{ hospital.name }}]({{ hospital.url }}) - {{ hospital.location }}
    > {{ hospital.quote }}
    {% for review in hospital.reviews %}
      * [{{ review.title }}]({{ review.url }})
    {% endfor %}
  {% endfor %}
* [PrEP 병원안내 - iSHAP](https://ishap.org/?c=2/62/65) 
  > PrEP은 HIV 치료가 가능한 병원(주로 감염내과) 등에서 처방받을 수 있습니다. iSHAP은 PrEP을 처방 받을 수 있는 병원과 함께 진료의뢰서 없이 편하게 방문할 수 있거나 원외처방을 통해 PrEP을 처방받을 수 있는 병원을 조사 하고 있습니다. 아래 명단 이외에 원외 처방이 가능한 병원을 알고 있다면 아이샵으로 제보 부탁드립니다.

HIV/AIDS 관련 상담
----
* [iSHAP 상담실](https://www.ishap.org/?c=4/23)
* [사단법인 청소년 성소수자 지원센터 띵동](https://www.ddingdong.kr/xe/hiv)
* > HIV 확진 이후 삶을 어떻게 이어나갈지 고민이 된다면,
  > 가족과의 갈등이나 학교생활을 하는데 어려움을 겪고 있다면,
  > 병원진료 및 투약과 관련해서 궁금한 점이 있다면 띵동으로 연락주세요. - [HIV감염인 청소년 성소수자 지원](https://www.ddingdong.kr/xe/hiv)
* [한국청소년·청년감염인커뮤니티알](https://communityr.org/counsel/)
  > HIV/AIDS에 대한 혐오나 낙인으로 인해 병원에서의 진료거부, 일터에서의 부당대우 등 인권침해와 차별을 겪고 계시다면?
  > 에이즈예방법 제19조 전파매개행위금지조항으로 인해 힘든 상황을 겪고 계시다면?
  > 부담없이 아래의 연락처 혹은 이메일을 통해 상담문의주세요! - [상담안내](https://communityr.org/counsel/)
* [한국HIV/AIDS감염인연합회 KNP+](https://knpplus.org/counseling)
  > KNP+는 일상생활에서 어려움을 겪는 감염인 분들을 지원하고자 상담을 진행합니다.
  > 동료 감염인 상담을 기본으로 하여 확진 초기의 고민을 함께 풀어갑니다.
  > 일터와 병원에서 마주하는 인권침해에 대응하고, 전문적인 심리상담도 연계합니다. - [상담](https://knpplus.org/counseling)
