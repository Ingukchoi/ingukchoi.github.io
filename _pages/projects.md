---
layout: page
title: Projects
permalink: /projects/
description:
nav: true
nav_order: 3
---

<style>
  /* 기본 페이지 제목 숨기고 직접 만든 제목 사용 (Papers / Awards 와 동일) */
  .post-header { display: none; }
  .pub-eyebrow { font-size: 0.85rem; font-weight: 700; letter-spacing: 0.18em; text-transform: uppercase; color: var(--global-theme-color); margin: 1rem 0 0.2rem; }
  .pub-page-title { font-size: 3rem; font-weight: 700; letter-spacing: -0.02em; margin: 0 0 0.6rem; }
  .pub-page-desc { color: var(--global-text-color-light); font-size: 1.05rem; margin-bottom: 1rem; }

  /* 프로젝트 하나 */
  .pj-list { margin-top: 2rem; }
  .pj-item { border-top: 1px solid var(--global-divider-color); padding: 1.2rem 0 2rem; }
  .pj-year { text-align: right; font-size: 0.85rem; color: var(--global-text-color-light); margin-bottom: 0.6rem; }
  .pj-row { display: grid; grid-template-columns: 150px 1fr; column-gap: 1.8rem; }
  .badge { display: block; text-align: center; background: var(--global-theme-color); color: #fff !important; font-weight: 700; font-size: 0.85rem; padding: 0.25rem 0.4rem; border-radius: 5px; box-shadow: 0 2px 6px rgba(0,0,0,0.15); }
  .pj-left { padding-top: 0.15rem; display: flex; flex-direction: column; gap: 0.45rem; }
  .badge.outline { background: transparent; color: var(--global-theme-color) !important; border: 1px solid var(--global-theme-color); box-shadow: none; padding: calc(0.25rem - 1px) 0.4rem; }
  .pj-title { font-weight: 600; font-size: 1.05rem; line-height: 1.45; }
  .pj-ko { margin-top: 0.2rem; font-size: 0.92rem; color: var(--global-text-color-light); }
  .pj-partner { margin-top: 0.25rem; font-style: italic; }

  /* 폰 */
  @media (max-width: 767px) {
    .pub-page-title { font-size: 2.3rem; }
    .pj-row { grid-template-columns: 1fr; row-gap: 0.6rem; }
    .pj-left { flex-direction: column; }
    .badge { display: block; width: 100%; padding: 0.3rem 0.4rem; }
    .badge.outline { padding: calc(0.3rem - 1px) 0.4rem; }
  }
</style>

<div class="pub-eyebrow">Research</div>
<h1 class="pub-page-title">Projects</h1>
<div class="pub-page-desc">Research fellowships and industry collaborations.</div>

<div class="pj-list">
<div class="pj-item">
  <div class="pj-year">Sep. 2026 – Aug. 2028</div>
  <div class="pj-row">
    <div class="pj-left"><span class="badge">Fellowship</span></div>
    <div class="pj-right">
      <div class="pj-title">Ph.D Fellowship</div>
      <div class="pj-ko">박사과정생 연구장려금 지원사업</div>
      <div class="pj-partner">Funded by National Research Foundation of Korea</div>
    </div>
  </div>
</div>
<div class="pj-item">
  <div class="pj-year">Apr. 2025 – Mar. 2026</div>
  <div class="pj-row">
    <div class="pj-left"><span class="badge">Industry</span><span class="badge outline">Project Manager</span></div>
    <div class="pj-right">
      <div class="pj-title">Optimization of Supply Chain Network Operations with LLM</div>
      <div class="pj-ko">LLM 기반 공급사슬망 운영 최적화 방법론 개발</div>
      <div class="pj-partner">with Samsung Electronics</div>
    </div>
  </div>
</div>
<div class="pj-item">
  <div class="pj-year">Mar. 2025 – Feb. 2026</div>
  <div class="pj-row">
    <div class="pj-left"><span class="badge">Industry</span></div>
    <div class="pj-right">
      <div class="pj-title">Reinforcement Learning-based OLED FAB Multi-agent Scheduling</div>
      <div class="pj-ko">강화학습 기반 OLED FAB Multi-agent 생산스케줄링 연구</div>
      <div class="pj-partner">with Samsung Display</div>
    </div>
  </div>
</div>
<div class="pj-item">
  <div class="pj-year">Mar. 2024 – Feb. 2025</div>
  <div class="pj-row">
    <div class="pj-left"><span class="badge">Industry</span></div>
    <div class="pj-right">
      <div class="pj-title">AI-based Algorithm for Optimal Operation Plans for Various Scenarios</div>
      <div class="pj-ko">AI 기반 시나리오별 최적 운영계획 수립 알고리즘 개발</div>
      <div class="pj-partner">with Samsung Electronics</div>
    </div>
  </div>
</div>
</div>
