---
layout: page
permalink: /papers/
title: Papers
description:
nav: true
nav_order: 1
---

<style>
  /* 기본 페이지 제목 숨기고 직접 만든 제목 사용 */
  .post-header { display: none; }
  .pub-eyebrow { font-size: 0.85rem; font-weight: 700; letter-spacing: 0.18em; text-transform: uppercase; color: var(--global-theme-color); margin: 1rem 0 0.2rem; }
  .pub-page-title { font-size: 3rem; font-weight: 700; letter-spacing: -0.02em; margin: 0 0 0.6rem; }
  .pub-page-desc { color: var(--global-text-color-light); font-size: 1.05rem; margin-bottom: 1rem; }

  /* 대제목 / 중제목 */
  .pub-h2 { font-weight: 500 !important; font-size: 2rem; margin: 2.8rem 0 1.2rem; }
  .pub-h3 { font-weight: 300 !important; font-size: 1.4rem; margin: 2rem 0 1rem; }

  /* 논문 한 개 = 왼쪽 배지 + 오른쪽 내용 */
  .pub { display: grid; grid-template-columns: 150px 1fr; column-gap: 1.8rem; margin-bottom: 1.8rem; }
  .pub-left { padding-top: 0.15rem; }
  .badge { display: block; text-align: center; background: var(--global-theme-color); color: #fff !important; font-weight: 700; font-size: 0.85rem; padding: 0.25rem 0.4rem; border-radius: 5px; box-shadow: 0 2px 6px rgba(0,0,0,0.15); }
  .badge.review { font-size: 0.8rem; }
  .pub-title { font-weight: 600; font-size: 1.05rem; line-height: 1.45; }
  .pub-authors, .pub-venue, .pub-note { margin-top: 0.2rem; }
  .pub-authors .me { font-weight: 700; text-decoration: underline; text-underline-offset: 3px; }
  .pub-venue { font-style: italic; }
  .pub-note { font-size: 0.9rem; color: var(--global-text-color-light); }
  .pub-links { margin-top: 0.6rem; }
  .pub-btn, .pub-tag { display: inline-block; font-size: 0.78rem; text-transform: uppercase; letter-spacing: 0.05em; padding: 0.3rem 0.9rem; margin-right: 0.5rem; border-radius: 3px; }
  .pub-btn { border: 1px solid var(--global-text-color); color: var(--global-text-color) !important; text-decoration: none !important; }
  .pub-btn:hover { border-color: var(--global-theme-color); background: var(--global-theme-color); color: #fff !important; }
  .pub-tag { border: 1px solid var(--global-theme-color); color: var(--global-theme-color); font-weight: 600; }

  /* 폰: 배지를 위로, 내용은 아래로 */
  @media (max-width: 767px) {
    .pub { grid-template-columns: 1fr; row-gap: 0.6rem; }
    .badge { display: block; width: 100%; padding: 0.3rem 0.4rem; }
    .pub-page-title { font-size: 2.3rem; }
  }
</style>

<div class="pub-eyebrow">Research</div>
<h1 class="pub-page-title">Papers</h1>
<div class="pub-page-desc">Published work and manuscripts currently under review.</div>

<h2 class="pub-h2">Under Review</h2>
  <div class="pub">
    <div class="pub-left"><span class="badge review">Under Review</span></div>
    <div class="pub-right">
      <div class="pub-title">Learning a Unified Production and Charging Policy with Heterogeneous AGV Fleets in Manufacturing Systems</div>
      <div class="pub-authors">Seungkyu Yoon, <span class="me">Inguk Choi</span>, and Hyun-Jung Kim</div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge review">Under Review</span></div>
    <div class="pub-right">
      <div class="pub-title">Learning Generalizable Multi-Robot Scheduling from Local Observation in Conveyor-Based Robotic Workcells</div>
      <div class="pub-authors">Dong-Ha Lee, <span class="me">Inguk Choi</span>, Yuqian Lu, and Hyun-Jung Kim</div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge review">Under Review</span></div>
    <div class="pub-right">
      <div class="pub-title">Multi-Objective Photolithography Scheduling with Dual-Resource Constraints Using Graph-Based Reinforcement Learning</div>
      <div class="pub-authors">Sang-Hyun Cho, <span class="me">Inguk Choi</span>, Boyoon Choi, Paul Han, and Hyun-Jung Kim</div>
    </div>
  </div>
<h2 class="pub-h2">Publications</h2>
<h3 class="pub-h3">Journal Articles</h3>
  <div class="pub">
    <div class="pub-left"><span class="badge">EJOR</span></div>
    <div class="pub-right">
      <div class="pub-title">A Unified Learning Framework for the Block Relocation Problem: A New Performance Baseline</div>
      <div class="pub-authors">Woo-Jin Shin, Ji-Kang Jung, Sang-Hyun Cho, <span class="me">Inguk Choi</span>, Shunji Tanaka, and Hyun-Jung Kim</div>
      <div class="pub-venue">European Journal of Operational Research (EJOR), 2026. (SCIE, Q1)</div>
      <div class="pub-links"><a class="pub-btn" href="https://www.sciencedirect.com/science/article/pii/S0377221726007551" target="_blank">Paper</a></div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">TR-C</span></div>
    <div class="pub-right">
      <div class="pub-title">Learning to Retrieve Containers: A Scale-Diverse Deep Reinforcement Learning Approach for the Container Retrieval Problem</div>
      <div class="pub-authors">Woo-Jin Shin, <span class="me">Inguk Choi</span>, Sang-Hyun Cho, and Hyun-Jung Kim</div>
      <div class="pub-venue">Transportation Research Part C: Emerging Technologies (TR-C), vol. 183, article 105496, 2026. (SCIE, Q1)</div>
      <div class="pub-links"><a class="pub-btn" href="https://www.sciencedirect.com/science/article/pii/S0968090X25005005" target="_blank">Paper</a></div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">IEEE RA-L</span></div>
    <div class="pub-right">
      <div class="pub-title">A Multi-View Attention-Based Encoder-Decoder Framework for Clustered Traveling Salesman Problem</div>
      <div class="pub-authors">Jimin Park†, <span class="me">Inguk Choi†</span>, and Hyun-Jung Kim</div>
      <div class="pub-venue">IEEE Robotics and Automation Letters (IEEE RA-L), vol. 11, no. 1, pp. 137–144, 2026. (SCIE, Q1)</div>
      <div class="pub-note">†: Co-first authors</div>
      <div class="pub-links"><a class="pub-btn" href="https://ieeexplore.ieee.org/document/11248888" target="_blank">Paper</a></div>
    </div>
  </div>
<h3 class="pub-h3">AI/ML Conference Proceedings</h3>
  <div class="pub">
    <div class="pub-left"><span class="badge">NeurIPS 2026</span></div>
    <div class="pub-right">
      <div class="pub-title">Towards a Unified Model for Flexible Job Shop Scheduling with Diverse Constraints</div>
      <div class="pub-authors"><span class="me">Inguk Choi</span>, Woo-Jin Shin, Sang-Hyun Cho, and Hyun-Jung Kim</div>
      <div class="pub-venue">Advances in Neural Information Processing Systems (NeurIPS), Sydney, Australia, 2026. (A* Conference)</div>
      <div class="pub-links"><span class="pub-tag">Accepted</span></div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">NeurIPS 2026</span></div>
    <div class="pub-right">
      <div class="pub-title">SchedDiff: Diffusion-Based Priority Refinement for Job Shop Scheduling</div>
      <div class="pub-authors">Dong-Yoon Oh, Sang-Hyun Cho, <span class="me">Inguk Choi</span>, and Hyun-Jung Kim</div>
      <div class="pub-venue">Advances in Neural Information Processing Systems (NeurIPS), Sydney, Australia, 2026. (A* Conference)</div>
      <div class="pub-links"><span class="pub-tag">Accepted</span></div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">IJCAI 2026</span></div>
    <div class="pub-right">
      <div class="pub-title">Preference-Guided Multi-Policy Optimization for Flexible Job Shop Scheduling</div>
      <div class="pub-authors"><span class="me">Inguk Choi</span>, Woo-Jin Shin, Sang-Hyun Cho, and Hyun-Jung Kim</div>
      <div class="pub-venue">Proceedings of the Thirty-Fifth International Joint Conference on Artificial Intelligence (IJCAI), pp. 6156–6165, 2026. (A* Conference)</div>
      <div class="pub-links"><a class="pub-btn" href="https://www.ijcai.org/proceedings/2026/685" target="_blank">Paper</a></div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">NeurIPS 2025</span></div>
    <div class="pub-right">
      <div class="pub-title">Towards Generalizable Multi-Policy Optimization with Self-Evolution for Job Scheduling</div>
      <div class="pub-authors"><span class="me">Inguk Choi</span>, Woo-Jin Shin, Sang-Hyun Cho, and Hyun-Jung Kim</div>
      <div class="pub-venue">Advances in Neural Information Processing Systems (NeurIPS), vol. 38, pp. 24569–24616, 2025. (A* Conference)</div>
      <div class="pub-links"><a class="pub-btn" href="https://openreview.net/forum?id=VPm6afl0Sc" target="_blank">Paper</a></div>
    </div>
  </div>
<h2 class="pub-h2">Conference Presentations</h2>
<h3 class="pub-h3">International</h3>
  <div class="pub">
    <div class="pub-left"><span class="badge">APIEMS 2026</span></div>
    <div class="pub-right">
      <div class="pub-title">A Generalizable DRL Scheduler for the Job Shop Scheduling Problem with AGVs</div>
      <div class="pub-authors">S. Lee, <span class="me">I. Choi</span>, and H.-J. Kim</div>
      <div class="pub-venue">Asia-Pacific Industrial Engineering and Management Systems Conference (APIEMS), Busan, Korea, 2026.</div>
      <div class="pub-links"><span class="pub-tag">Accepted</span></div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">WSC 2026</span></div>
    <div class="pub-right">
      <div class="pub-title">RAG-enhanced Query Disambiguation in Spreadsheet-based Semiconductor Supply Chain Management</div>
      <div class="pub-authors">J. Park, <span class="me">I. Choi</span>, S. Joo, Y. Kim, G. Oh, Y. Song, and H.-J. Kim</div>
      <div class="pub-venue">Winter Simulation Conference (WSC), Glasgow, Scotland, 2026.</div>
      <div class="pub-note">Collaboration with Samsung Electronics</div>
      <div class="pub-links"><span class="pub-tag">Accepted</span></div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">CASE 2026</span></div>
    <div class="pub-right">
      <div class="pub-title">Real-Time Robotic Assembly Cell Scheduling via Generalizable Multi-Agent Reinforcement Learning</div>
      <div class="pub-authors">D.-H. Lee, <span class="me">I. Choi</span>, W.-J. Shin, Y. Lu, and H.-J. Kim</div>
      <div class="pub-venue">IEEE International Conference on Automation Science and Engineering (IEEE CASE), Shenyang, China, 2026.</div>
      <div class="pub-note">Collaboration with University of Auckland</div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">WSC 2025</span></div>
    <div class="pub-right">
      <div class="pub-title">Learning-based Scheduling for Stochastic Job Shop Scheduling with Mobile Robots</div>
      <div class="pub-authors">W.-J. Shin, D. Oh, <span class="me">I. Choi</span>, M. Wiktorsson, E. Florest-Garcia, Y. Jeong, and H.-J. Kim</div>
      <div class="pub-venue">Winter Simulation Conference (WSC), Seattle, USA, 2025.</div>
      <div class="pub-note">Collaboration with KTH Royal Institute of Technology</div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">WSC 2025</span></div>
    <div class="pub-right">
      <div class="pub-title">An Empirical Study on the Assessment of Demand Forecasting Reliability for Fabless Semiconductor Companies</div>
      <div class="pub-authors"><span class="me">I. Choi</span>, S.-Y. Hwang, J. Ahn, J. Lee, S. Joo, K. Kim, H. Lee, Y. Song, and H.-J. Kim</div>
      <div class="pub-venue">Winter Simulation Conference (WSC), Seattle, USA, 2025.</div>
      <div class="pub-note">Collaboration with Samsung Electronics</div>
      <div class="pub-links"><a class="pub-btn" href="https://ieeexplore.ieee.org/abstract/document/11338944" target="_blank">Paper</a></div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">CASE 2025</span></div>
    <div class="pub-right">
      <div class="pub-title">Adaptive Self-Supervised Learning for Solving Flow Shop Scheduling Problems</div>
      <div class="pub-authors"><span class="me">I. Choi</span> and H.-J. Kim</div>
      <div class="pub-venue">IEEE International Conference on Automation Science and Engineering (IEEE CASE), Los Angeles, USA, 2025.</div>
    </div>
  </div>
<h3 class="pub-h3">Domestic</h3>
  <div class="pub">
    <div class="pub-left"><span class="badge">KIIE 2026</span></div>
    <div class="pub-right">
      <div class="pub-title">Graph Reinforcement Learning-based Integrated Scheduling for OLED TFT Array Manufacturing</div>
      <div class="pub-authors">S.-H. Cho, S.-H. Jung, <span class="me">I. Choi</span>, B.-Y. Choi, B. Han, and H.-J. Kim</div>
      <div class="pub-venue">The Spring Conference of Korean Institute of Industrial Engineers (KIIE), Gyeongju, 2026.</div>
      <div class="pub-note">Collaboration with Samsung Display</div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">KIIE 2026</span></div>
    <div class="pub-right">
      <div class="pub-title">Natural Language-based Modification of Semiconductor Supply Management Spreadsheets using Retrieval-Augmented Generation</div>
      <div class="pub-authors">J. Park, <span class="me">I. Choi</span>, S. Joo, Y. Kim, G. Oh, Y. Song, and H.-J. Kim</div>
      <div class="pub-venue">The Spring Conference of Korean Institute of Industrial Engineers (KIIE), Gyeongju, 2026.</div>
      <div class="pub-note">Collaboration with Samsung Electronics</div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">KIIE 2026</span></div>
    <div class="pub-right">
      <div class="pub-title">A Learning Framework for the Container Relocation Problem in Container Yards</div>
      <div class="pub-authors">W.-J. Shin, J.-K. Jung, S.-H. Cho, <span class="me">I. Choi</span>, S. Tanaka, and H.-J. Kim</div>
      <div class="pub-venue">The Spring Conference of Korean Institute of Industrial Engineers (KIIE), Gyeongju, 2026.</div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">KIIE 2026</span></div>
    <div class="pub-right">
      <div class="pub-title">Learning-Based UAV Path Planning for Clustered Reconnaissance Targets</div>
      <div class="pub-authors">W.-J. Shin, <span class="me">I. Choi</span>, J.-Y. Shin, and H.-J. Kim</div>
      <div class="pub-venue">The Spring Conference of Korean Institute of Industrial Engineers (KIIE), Gyeongju, 2026.</div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">KIIE 2025</span></div>
    <div class="pub-right">
      <div class="pub-title">A Self-Imitation Learning Framework for Neural Dispatching Rule Optimization</div>
      <div class="pub-authors"><span class="me">I. Choi</span> and H.-J. Kim</div>
      <div class="pub-venue">The Spring Conference of Korean Institute of Industrial Engineers (KIIE), Jeju, 2025.</div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">KIIE 2025</span></div>
    <div class="pub-right">
      <div class="pub-title">Multi-objective Scheduling for Photo Process Using Reinforcement Learning</div>
      <div class="pub-authors">S.-H. Cho, S.-H. Jung, <span class="me">I. Choi</span>, B. Choi, B. Han, and H.-J. Kim</div>
      <div class="pub-venue">The Spring Conference of Korean Institute of Industrial Engineers (KIIE), Jeju, 2025.</div>
      <div class="pub-note">Collaboration with Samsung Display</div>
    </div>
  </div>
  <div class="pub">
    <div class="pub-left"><span class="badge">KIIE 2024</span></div>
    <div class="pub-right">
      <div class="pub-title">Deep Reinforcement Learning-based Encoder-Decoder Framework for The Clustered Traveling Salesman Problem</div>
      <div class="pub-authors">J. Park†, <span class="me">I. Choi†</span>, S.-H. Cho, and H.-J. Kim</div>
      <div class="pub-venue">The Autumn Conference of Korean Institute of Industrial Engineers (KIIE), Seoul, 2024.</div>
      <div class="pub-note">†: Co-first authors</div>
    </div>
  </div>
