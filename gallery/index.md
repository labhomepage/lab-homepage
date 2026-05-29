---
title: Activity
nav:
  order: 6
---

# {% include icon.html icon="fa-regular fa-image" %} Activity

<style>
  .activity-list {
    display: flex;
    flex-direction: column;
    gap: 28px;
    margin-top: 24px;
  }

  .activity-row {
    display: flex;
    align-items: center;
    gap: 24px;
    background: #ffffff;
    border: 1px solid #eaeaea;
    border-radius: 12px;
    padding: 18px;
    box-shadow: 0 3px 8px rgba(0,0,0,0.05);
  }

  .activity-row img {
    width: 320px;
    flex: 0 0 320px;
    height: auto;
    border-radius: 8px;
    object-fit: cover;
  }

  .activity-text {
    flex: 1;
    text-align: left;
  }

  .activity-title {
    font-size: 1.3rem;
    font-weight: 700;
    margin: 0 0 8px 0;
    color: #111;
  }

  .activity-desc {
    font-size: 0.98rem;
    line-height: 1.6;
    color: #444;
    margin: 0;
  }

  @media (max-width: 700px) {
    .activity-row {
      flex-direction: column;
      align-items: flex-start;
    }
    .activity-row img {
      width: 100%;
      flex: none;
    }
  }
</style>

<div class="activity-list">

  <div class="activity-row">
    <img src="https://labhomepage.github.io/sassl/images/gallery1.png" alt="2025년 봄 학술대회">
    <div class="activity-text">
      <h3 class="activity-title">2025년 봄 학술대회</h3>
      <p class="activity-desc">설명을 여기에 입력하세요.</p>
    </div>
  </div>

  <div class="activity-row">
    <img src="https://labhomepage.github.io/sassl/images/gallery2.png" alt="2025년 가을 학술대회">
    <div class="activity-text">
      <h3 class="activity-title">2025년 가을 학술대회</h3>
      <p class="activity-desc">설명을 여기에 입력하세요.</p>
    </div>
  </div>

  <div class="activity-row">
    <img src="https://labhomepage.github.io/sassl/images/gallery3.png" alt="교내 캡스톤디자인 경진대회">
    <div class="activity-text">
      <h3 class="activity-title">교내 캡스톤디자인 경진대회</h3>
      <p class="activity-desc">설명을 여기에 입력하세요.</p>
    </div>
  </div>

  <div class="activity-row">
    <img src="https://labhomepage.github.io/sassl/images/gallery4.png" alt="구조물 내진설계경진대회">
    <div class="activity-text">
      <h3 class="activity-title">구조물 내진설계경진대회</h3>
      <p class="activity-desc">설명을 여기에 입력하세요.</p>
    </div>
  </div>

</div>
