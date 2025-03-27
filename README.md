---
layout: home
title: Jekyll Gitbook Theme
permalink: /
cover: https://sighingnow.github.io/jekyll-gitbook/assets/dinosaur.gif #导入动画
---
- 这是我的博客网站（TZC）。
- 你可以在左上角点击“A”来调节字体大小和字体样式（White白色、Sepia暖色、Night黑色）。

- 更新了这些：
  1. 首页（README.md）没有“下一篇”按钮：我们需要确保 README.md 被正确识别并显示“下一篇”按钮。
  2. 实现所需的跳转顺序：确保“下一篇”和“上一篇”按钮按 README.md → _posts → _pages → _others 的顺序跳转（“上一篇”反向）。
  3. 导航栏（toc-date.html）顺序：将 _posts、_pages 和 _others 在导航栏中按日期从新到旧排列。
