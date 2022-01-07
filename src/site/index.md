---
title: Pan Digital Wellness Association
subtitle: 디지털 웰니스 산업 진흥과 글로벌 생태계 조성을 통해 <br /> 건강하고 행복한 삶을 함께 만들어 갑니다.
layout: layouts/base.njk
---


## This site is a starting point

왜 PanDAW인가?

- 디지털 웰니스로 건강하고 행복한 삶을 함께 만들어 가는 Best Patner
- 디지털이 이어주는 건강한 일상과 행복한 삶
- Digital Wellness, Better Health, Better Life Together
- 디지털 포용, 건강격차 해소, 디지털 웰니스로 함께 누리는(성장하는) 건강하고 행복한 공동체(삶)
- 다양한 분야와 이해관계자간 협업과 융합, 협력을 통함 기업의 성장 지원과 더불어 사회공헌활동으로서 예술과 ICT, 헬스케어의 만남, 가교 역할


## Post pages

관련 페이지가 앞으로 추가될 예정입니다.

<ul class="listing">
{%- for page in collections.post -%}
  <li>
    <a href="{{ page.url }}">{{ page.data.title }}</a> -
    <time datetime="{{ page.date }}">{{ page.date | dateDisplay("LLLL d, y") }}</time>
  </li>
{%- endfor -%}
</ul>




