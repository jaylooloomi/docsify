# 知識聚合自動化

<div class="card-grid">

  <a class="card" href="#/markdowns/github/README">
    <div class="card-icon">🔥</div>
    <div class="card-title">GitHub 熱門熱點</div>
    <div class="card-desc">追蹤 GitHub 上最新最熱門的開源趨勢，掌握開發者社群動向。</div>
    <div class="card-link">→ 進入</div>
  </a>

  <a class="card" href="#/markdowns/japangirl/README">
    <div class="card-icon">🌸</div>
    <div class="card-title">日本暗黑行程</div>
    <div class="card-desc">推薦日本黑馬達人氣的神秘旅遊路線，帶你發現不一樣的日本。</div>
    <div class="card-link">→ 進入</div>
  </a>

  <a class="card" href="#/markdowns/worldnews/README">
    <div class="card-icon">🌍</div>
    <div class="card-title">世界熱門新聞</div>
    <div class="card-desc">匯集全球最新最熱門的新聞事件，快速掌握世界脈動。</div>
    <div class="card-link">→ 進入</div>
  </a>

  <a class="card" href="#/markdowns/makemoney/README">
    <div class="card-icon">💰</div>
    <div class="card-title">賺錢點子</div>
    <div class="card-desc">彙整各種副業感想、被動收入切入點及剝羊毛教學，探索財富自由的可能性。</div>
    <div class="card-link">→ 進入</div>
  </a>

  <a class="card" href="#/markdowns/serviceprovider/README">
    <div class="card-icon">🔧</div>
    <div class="card-title">服務供應商</div>
    <div class="card-desc">整理各項服務提供者接洽資訊，幫助你快速找到合適的合作方式。</div>
    <div class="card-link">→ 進入</div>
  </a>

  <a class="card" href="#/markdowns/sticker/README">
    <div class="card-icon">🎨</div>
    <div class="card-title">原創貼圖</div>
    <div class="card-desc">收錄原創 LINE 貼圖設計過程與發佈資訊，分享創作心得。</div>
    <div class="card-link">→ 進入</div>
  </a>

  <a class="card" href="#/markdowns/chromeextension/README">
    <div class="card-icon">🔩</div>
    <div class="card-title">Chrome 擴充套件</div>
    <div class="card-desc">精選提升生產力的 Chrome 擴充套件推薦與使用教學。</div>
    <div class="card-link">→ 進入</div>
  </a>

</div>

<style>
.card-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 24px;
  margin-top: 32px;
}

.card {
  display: block;
  background: #1a1a1a;
  border: 1px solid #2a2a2a;
  border-radius: 12px;
  padding: 32px 24px;
  text-align: center;
  text-decoration: none;
  color: inherit;
  transition: transform 0.2s, border-color 0.2s, box-shadow 0.2s;
}

.card:hover {
  transform: translateY(-4px);
  border-color: #00d4ff;
  box-shadow: 0 8px 24px rgba(0, 212, 255, 0.15);
  text-decoration: none;
}

.card-icon {
  font-size: 2.5rem;
  margin-bottom: 12px;
}

.card-title {
  font-size: 1.1rem;
  font-weight: bold;
  color: #00d4ff;
  margin-bottom: 12px;
}

.card-desc {
  font-size: 0.9rem;
  color: #a0a0a0;
  line-height: 1.5;
  margin-bottom: 16px;
}

.card-link {
  font-size: 0.9rem;
  color: #00d4ff;
  font-weight: 500;
}

@media (max-width: 768px) {
  .card-grid {
    grid-template-columns: 1fr;
    gap: 16px;
  }
}
</style>