---
layout: default
title: 首頁
permalink: /
---

<section class="hero">
  <p class="eyebrow">PERSONAL AI FIELD NOTES</p>
  <h1>把 AI 開發經驗，<br>整理成下次用得上的知識。</h1>
  <p class="hero-copy">這裡記錄我對 AI Agent、LLM 與 LINE 會議助理的理解。每篇文章會區分概念、實作觀察與尚待確認的地方，讓知識可以持續更新。</p>
  <a class="button" href="{{ '/knowledge/agent-basics/' | relative_url }}">從 AI Agent 開始閱讀 <span aria-hidden="true">↗</span></a>
</section>

<section class="section-heading">
  <div>
    <p class="eyebrow">KNOWLEDGE MAP</p>
    <h2>知識地圖</h2>
  </div>
  <p>從基礎概念走到實際系統，循序整理。</p>
</section>

<section class="card-grid" aria-label="知識文章">
  <a class="knowledge-card" href="{{ '/knowledge/agent-basics/' | relative_url }}">
    <span class="card-number">01</span><span class="tag">基礎概念</span>
    <h3>認識 AI Agent</h3>
    <p>理解語言模型、工具與流程控制如何組成一個能完成任務的系統。</p>
    <span class="card-link">閱讀文章 <span aria-hidden="true">→</span></span>
  </a>
  <a class="knowledge-card" href="{{ '/knowledge/meeting-assistant/' | relative_url }}">
    <span class="card-number">02</span><span class="tag">實作案例</span>
    <h3>LINE 會議助理</h3>
    <p>用實際專案整理 LINE、LIFF、Cloudflare Workers 與 D1 的分工。</p>
    <span class="card-link">閱讀文章 <span aria-hidden="true">→</span></span>
  </a>
  <a class="knowledge-card" href="{{ '/knowledge/llm-intent-routing/' | relative_url }}">
    <span class="card-number">03</span><span class="tag">設計方法</span>
    <h3>LLM 意圖辨識與功能路由</h3>
    <p>整理如何把使用者說的話轉成系統能安全處理的功能指令。</p>
    <span class="card-link">閱讀文章 <span aria-hidden="true">→</span></span>
  </a>
  <a class="knowledge-card" href="{{ '/knowledge/development-notes/' | relative_url }}">
    <span class="card-number">04</span><span class="tag">開發紀錄</span>
    <h3>測試觀察與待確認事項</h3>
    <p>保留實作過程中的發現，並標示哪些結論還需要更多驗證。</p>
    <span class="card-link">閱讀文章 <span aria-hidden="true">→</span></span>
  </a>
</section>

<section class="note-panel">
  <span class="note-icon" aria-hidden="true">✳</span>
  <div><h2>這個知識庫怎麼使用？</h2><p><code>AGENTS.md</code> 說明 AI 如何維護專案；<code>knowledge/</code> 裡的文章則是可以持續閱讀與補充的知識。規則讓新內容維持一致，文章提供可查閱的專案脈絡。</p></div>
</section>
