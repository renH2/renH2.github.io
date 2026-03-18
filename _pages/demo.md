---
permalink: /demo/
title: "Demo"
author_profile: false
redirect_from:
  - /demo.html
---

<span class='anchor' id='demo-section'></span>

## Demo

一些有趣的小实验。

<div class="demo-list">
  <a href="{{ site.url }}{{ site.baseurl }}/demo/guess-riddle.html" class="demo-item" target="_blank">
    <span class="demo-num">01</span>
    <div class="demo-content">
      <h3>猜字谜小游戏</h3>
      <p>点击卡片揭晓谜底</p>
    </div>
    <span class="demo-arrow">→</span>
  </a>

  <a href="{{ site.url }}{{ site.baseurl }}/demo/xijing/index.html" class="demo-item" target="_blank">
    <span class="demo-num">02</span>
    <div class="demo-content">
      <h3>春日中国 · 各地风景</h3>
      <p>点击地图探索各省春景</p>
    </div>
    <span class="demo-arrow">→</span>
  </a>
</div>

<style>
.demo-list {
  margin-top: 3rem;
}

.demo-item {
  display: flex;
  align-items: baseline;
  gap: 2rem;
  padding: 1.5rem 0;
  border-bottom: 1px solid #eee;
  text-decoration: none;
  color: inherit;
  transition: opacity 0.2s ease;
}

.demo-item:hover {
  opacity: 0.6;
}

.demo-item:first-child {
  padding-top: 0;
}

.demo-num {
  font-size: 0.8rem;
  font-weight: 400;
  color: #999;
  font-family: monospace;
  flex-shrink: 0;
}

.demo-content {
  flex: 1;
}

.demo-content h3 {
  margin: 0 0 0.25rem;
  font-size: 1rem;
  font-weight: 500;
  color: #111;
}

.demo-content p {
  margin: 0;
  font-size: 0.85rem;
  color: #888;
}

.demo-arrow {
  color: #ccc;
  font-size: 1rem;
  transition: transform 0.2s ease;
}

.demo-item:hover .demo-arrow {
  transform: translateX(4px);
}
</style>
