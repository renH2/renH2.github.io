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
    <div class="demo-card-inner">
      <div class="demo-icon">🔮</div>
      <div class="demo-info">
        <h3>猜字谜小游戏</h3>
        <p>点击卡片揭晓谜底，还有换题功能～</p>
      </div>
    </div>
  </a>

  <a href="{{ site.url }}{{ site.baseurl }}/demo/xijing/index.html" class="demo-card" target="_blank">
    <div class="demo-card-inner">
      <div class="demo-icon">🗺️</div>
      <div class="demo-info">
        <h3>春日中国 · 各地风景</h3>
        <p>点击地图上的红点，探索各省春季美景</p>
      </div>
    </div>
  </a>
</div>

<style>
.demo-grid {
  display: flex;
  flex-direction: column;
  gap: 1.25rem;
  margin-top: 1.5rem;
  max-width: 600px;
}

.demo-card {
  display: block;
  text-decoration: none;
  color: inherit;
  border-radius: 16px;
  overflow: hidden;
  transition: all 0.25s ease;
  border: 1px solid rgba(0,0,0,0.08);
  box-shadow: 0 2px 8px rgba(0,0,0,0.04);
}

.demo-card:hover {
  transform: translateY(-3px);
  box-shadow: 0 8px 24px rgba(0,0,0,0.1);
  border-color: rgba(0,0,0,0.12);
}

.demo-card-inner {
  display: flex;
  align-items: center;
  gap: 1.25rem;
  padding: 1.25rem;
  background: linear-gradient(135deg, #fefefe 0%, #fafafa 100%);
}

.demo-icon {
  font-size: 2.2rem;
  flex-shrink: 0;
  width: 56px;
  height: 56px;
  display: flex;
  align-items: center;
  justify-content: center;
  background: linear-gradient(135deg, #f0f4ff 0%, #e8f4f8 100%);
  border-radius: 14px;
}

.demo-info h3 {
  margin: 0 0 0.35rem;
  font-size: 1.05rem;
  font-weight: 600;
  color: #2d3748;
}

.demo-info p {
  margin: 0;
  font-size: 0.85rem;
  color: #718096;
  line-height: 1.5;
}
</style>
