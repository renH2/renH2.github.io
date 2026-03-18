---
permalink: /demo/
title: "Demo"
author_profile: false
redirect_from:
  - /demo.html
---

<span class='anchor' id='demo-section'></span>

## 我的 Demo

这里收录了我做的一些有趣的小网页：

<div class="demo-grid">
  <a href="{{ site.url }}{{ site.baseurl }}/demo/guess-riddle.html" class="demo-card" target="_blank">
    <div class="demo-icon">🔮</div>
    <div class="demo-info">
      <h3>猜字谜小游戏</h3>
      <p>点击卡片揭晓谜底，还有换题功能～</p>
    </div>
  </a>

  <a href="{{ site.url }}{{ site.baseurl }}/demo/xijing/index.html" class="demo-card" target="_blank">
    <div class="demo-icon">🗺️</div>
    <div class="demo-info">
      <h3>春日中国 · 各地风景</h3>
      <p>点击地图上的红点，探索各省春季美景</p>
    </div>
  </a>
</div>

<style>
.demo-grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
  gap: 1.5rem;
  margin-top: 1.5rem;
}

.demo-card {
  display: flex;
  align-items: center;
  gap: 1rem;
  padding: 1.5rem;
  background: var(--card-bg, #fff);
  border-radius: 12px;
  text-decoration: none;
  color: inherit;
  box-shadow: 0 2px 8px rgba(0,0,0,0.08);
  transition: transform 0.2s ease, box-shadow 0.2s ease;
  border: 1px solid rgba(0,0,0,0.06);
}

.demo-card:hover {
  transform: translateY(-2px);
  box-shadow: 0 4px 16px rgba(0,0,0,0.12);
}

.demo-icon {
  font-size: 2.5rem;
  flex-shrink: 0;
}

.demo-info h3 {
  margin: 0 0 0.5rem;
  font-size: 1.1rem;
  color: var(--text-color, #333);
}

.demo-info p {
  margin: 0;
  font-size: 0.9rem;
  color: var(--text-color-light, #666);
  line-height: 1.5;
}
</style>
