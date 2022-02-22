---
layout: page
title: About
permalink: /about/
weight: 1
---

# **About Me**

반갑습니다. **{{ site.author.name }}** 라고 합니다. :wave:,<br>
제 개발 능력이 좋은지는 아직 잘 모르겠습니다.<br>
하지만 발전하는 좋은 사람은 되고싶기에 끊임없이 학습하고, 경험하려 노력합니다.<br>
모쪼록 찾아와주셔서 감사합니다.

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
