---
layout: page
title: 小游戏
permalink: /games/
---

这里放我和朋友们做的小游戏。手机建议横屏游玩。

{% if site.data.games.size > 0 %}
{% include game-cards.html %}
{% else %}
<p>小游戏陆续添加中，敬请期待。</p>
{% endif %}
