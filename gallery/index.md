---
title: Activity
nav:
  order: 7
---

# {% include icon.html icon="fa-regular fa-image" %} Activity

<style>
.activity-list {
  display: flex;
  flex-direction: column;
  gap: 28px;
  margin-top: 24px;
}
.activity-item {
  position: relative;
  background: #ffffff;
  border: 1px solid #ececec;
  border-radius: 14px;
  padding: 20px;
  box-shadow: 0 2px 12px rgba(0, 0, 0, 0.08);
  transition: box-shadow 0.25s;
}
.activity-item:hover {
  box-shadow: 0 4px 18px rgba(0, 0, 0, 0.12);
}
.activity-row {
  display: flex;
  align-items: center;
  gap: 24px;
}
.activity-row > img {
  width: 280px;
  flex: 0 0 280px;
  aspect-ratio: 4 / 3;
  object-fit: cover;
  border-radius: 10px;
}
.activity-text {
  flex: 1;
  text-align: left;
}
.activity-year {
  display: inline-block;
  background: #eef2f8;
  color: #2f5d9e;
  font-size: 0.75rem;
  font-weight: 700;
  letter-spacing: 0.03em;
  padding: 3px 10px;
  border-radius: 12px;
  margin-bottom: 10px;
}
.activity-title {
  font-size: 1.3rem;
  font-weight: 700;
  margin: 0 0 6px 0;
  color: #111;
  line-height: 1.4;
}
.activity-date {
  font-size: 0.85rem;
  color: #888;
  margin: 0 0 8px 0;
}
.activity-desc {
  font-size: 0.98rem;
  line-height: 1.65;
  color: #444;
  margin: 0;
}
.more-photo-wrap {
  display: flex;
  justify-content: flex-end;
  margin-top: 14px;
}
.more-photo-btn {
  background: none;
  border: 1px solid #d5d5d5;
  border-radius: 20px;
  padding: 6px 16px;
  font-size: 0.9rem;
  color: #333;
  cursor: pointer;
  transition: background 0.2s, border-color 0.2s;
}
.more-photo-btn:hover {
  background: #f2f4f7;
  border-color: #b0b0b0;
}
.more-photo-btn .arrow {
  display: inline-block;
  margin-left: 6px;
  transition: transform 0.25s;
}
.more-photo-btn.open .arrow {
  transform: rotate(90deg);
}
.photo-grid {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  gap: 12px;
  margin-top: 16px;
  padding-top: 16px;
  border-top: 1px solid #eee;
}
.photo-grid[hidden] {
  display: none;
}
.photo-grid img,
.photo-grid video {
  width: 100%;
  aspect-ratio: 4 / 3;
  object-fit: cover;
  border-radius: 8px;
  background: #000;
  display: block;
}
.photo-grid img {
  cursor: zoom-in;
  transition: transform 0.2s;
}
.photo-grid img:hover {
  transform: scale(1.03);
}
@media (max-width: 700px) {
  .activity-row {
    flex-direction: column;
    align-items: flex-start;
  }
  .activity-row > img {
    width: 100%;
    flex: none;
  }
  .photo-grid {
    grid-template-columns: repeat(2, 1fr);
    gap: 8px;
  }
}
</style>

<div class="activity-list">
<div class="activity-item">
<div class="activity-row">
<img src="https://labhomepage.github.io/sassl/images/2026 봄 콘학.jpg" alt="2026 봄 콘학">
<div class="activity-text">
<span class="activity-year">2026</span>
<h3 class="activity-title">2026년 한국콘크리트학회 봄 학술대회</h3>
<p class="activity-date">2026.05.06(수) ~ 2026.05.08(금)</p>
<p class="activity-desc">연구실 인원들과 함께 2026년 콘크리트학회 봄 학술대회에 참석하였으며, 손동희 교수가 학술교류 활동 및 세션 좌장을 하였습니다.</p>
</div>
</div>
<div class="more-photo-wrap">
<button class="more-photo-btn" onclick="togglePhotos(this)">More photo <span class="arrow">→</span></button>
</div>
<div class="photo-grid" hidden>
<img src="https://labhomepage.github.io/sassl/images/2026 봄 콘학_1.jpg" alt="사진1">
<img src="https://labhomepage.github.io/sassl/images/2026 봄 콘학_2.jpg" alt="사진2">
<img src="https://labhomepage.github.io/sassl/images/2026 봄 콘학_3.jpg" alt="사진3">
<video src="https://labhomepage.github.io/sassl/videos/2026_kci_spring.mp4" poster="https://labhomepage.github.io/sassl/images/2026 봄 콘학_1.jpg" controls preload="metadata" muted playsinline></video>
<img src="https://labhomepage.github.io/sassl/images/2026 봄 콘학_4.jpg" alt="사진4">
<img src="https://labhomepage.github.io/sassl/images/2026 봄 콘학_5.jpg" alt="사진5">
</div>
</div>
<div class="activity-item">
<div class="activity-row">
<img src="https://labhomepage.github.io/sassl/images/2026 봄 진단학회.jpg" alt="2026 봄 진단학회">
<div class="activity-text">
<span class="activity-year">2026</span>
<h3 class="activity-title">2026년 한국구조물진단유지관리공학회 봄 학술대회</h3>
<p class="activity-date">2026.04.08(수) ~ 2026.04.10(금)</p>
<p class="activity-desc">2026년 한국구조물진단유지관리공학회 봄 학술대회 및 30주년 행사에 참석하였습니다.</p>
</div>
</div>
<div class="more-photo-wrap">
<button class="more-photo-btn" onclick="togglePhotos(this)">More photo <span class="arrow">→</span></button>
</div>
<div class="photo-grid" hidden>
<img src="https://labhomepage.github.io/sassl/images/2026 봄 진단학회_1.jpg" alt="사진1">
<img src="https://labhomepage.github.io/sassl/images/2026 봄 진단학회_2.jpg" alt="사진2">
<img src="https://labhomepage.github.io/sassl/images/2026 봄 진단학회_3.jpg" alt="사진3">
</div>
</div>
<div class="activity-item">
<div class="activity-row">
<img src="https://labhomepage.github.io/sassl/images/gallery2.png" alt="2025년 가을 학술대회">
<div class="activity-text">
<span class="activity-year">2025</span>
<h3 class="activity-title">2025년 한국콘크리트학회 가을 학술대회</h3>
<p class="activity-date">2025.11.05(수) ~ 2025.11.07(금)</p>
<p class="activity-desc">2025년 콘크리트학회 가을 학술대회에 참석하여 손동희 교수가 학술논문 발표를 하였습니다.<br>발표논문 : 데이터 필터링에 기반한 강섬유 보강 콘크리트 보의 크기효과 저감에 대한 통계적 분석</p>
</div>
</div>
<div class="more-photo-wrap">
<button class="more-photo-btn" onclick="togglePhotos(this)">More photo <span class="arrow">→</span></button>
</div>
<div class="photo-grid" hidden>
<img src="https://labhomepage.github.io/sassl/images/gallery2_1.jpg" alt="사진1">
<img src="https://labhomepage.github.io/sassl/images/gallery2_2.jpg" alt="사진2">
<img src="https://labhomepage.github.io/sassl/images/gallery2_3.jpg" alt="사진3">
</div>
</div>
<div class="activity-item">
<div class="activity-row">
<img src="https://labhomepage.github.io/sassl/images/gallery3.png" alt="교내 캡스톤디자인 경진대회">
<div class="activity-text">
<span class="activity-year">2025</span>
<h3 class="activity-title">「KNUT RISE Capstone X-Road 2025」참가</h3>
<p class="activity-date">2025.11.20(금)</p>
<p class="activity-desc">교내 캡스톤 디자인 경진대회 「KNUT RISE Capstone X-Road 2025」에서 박성진(팀장), 박성훈, 윤성수, 금승우, 백종우 학생이 우수상을 수상하였습니다.</p>
</div>
</div>
<div class="more-photo-wrap">
<button class="more-photo-btn" onclick="togglePhotos(this)">More photo <span class="arrow">→</span></button>
</div>
<div class="photo-grid" hidden>
<img src="https://labhomepage.github.io/sassl/images/gallery3_1.jpg" alt="사진1">
<img src="https://labhomepage.github.io/sassl/images/gallery3_2.jpg" alt="사진2">
<img src="https://labhomepage.github.io/sassl/images/gallery3_3.jpg" alt="사진3">
</div>
</div>
<div class="activity-item">
<div class="activity-row">
<img src="https://labhomepage.github.io/sassl/images/gallery4.png" alt="구조물 내진설계경진대회">
<div class="activity-text">
<span class="activity-year">2025</span>
<h3 class="activity-title">2025 구조물 내진설계 경진대회 참가</h3>
<p class="activity-date">2025.07.25(금)</p>
<p class="activity-desc">부산에서 개최된 2025 구조물 내진설계 경진대회에서 정성훈(팀장), 천우진, 김연우, 정원철 학생이 아이디어 우수상을 수상하였습니다.</p>
</div>
</div>
<div class="more-photo-wrap">
<button class="more-photo-btn" onclick="togglePhotos(this)">More photo <span class="arrow">→</span></button>
</div>
<div class="photo-grid" hidden>
<img src="https://labhomepage.github.io/sassl/images/gallery4_1.jpg" alt="사진1">
<img src="https://labhomepage.github.io/sassl/images/gallery4_2.jpg" alt="사진2">
<img src="https://labhomepage.github.io/sassl/images/gallery4_3.jpg" alt="사진3">
</div>
</div>
<div class="activity-item">
<div class="activity-row">
<img src="https://labhomepage.github.io/sassl/images/gallery1.png" alt="2025년 봄 학술대회">
<div class="activity-text">
<span class="activity-year">2025</span>
<h3 class="activity-title">2025년 한국콘크리트학회 봄 학술대회</h3>
<p class="activity-date">2025.05.07(수) ~ 2025.05.09(금)</p>
<p class="activity-desc">2025년 콘크리트학회 봄 학술대회에 참석하여 손동희 교수가 콘크리트연구회 특별세션 발표를 하였습니다.<br>발표주제 : 수직분할공법을 적용한 기존 철근콘크리트 벽식구조의 하중 재분배 효과</p>
</div>
</div>
<div class="more-photo-wrap">
<button class="more-photo-btn" onclick="togglePhotos(this)">More photo <span class="arrow">→</span></button>
</div>
<div class="photo-grid" hidden>
<img src="https://labhomepage.github.io/sassl/images/gallery1_1.jpg" alt="사진1">
<img src="https://labhomepage.github.io/sassl/images/gallery1_2.jpg" alt="사진2">
<img src="https://labhomepage.github.io/sassl/images/gallery1_3.jpg" alt="사진3">
</div>
</div>
</div>

<script>
function togglePhotos(btn) {
  var item = btn.closest('.activity-item');
  var grid = item.querySelector('.photo-grid');
  if (grid.hasAttribute('hidden')) {
    grid.removeAttribute('hidden');
    btn.classList.add('open');
    btn.innerHTML = 'Close <span class="arrow">→</span>';
  } else {
    grid.querySelectorAll('video').forEach(function (v) { v.pause(); });
    grid.setAttribute('hidden', '');
    btn.classList.remove('open');
    btn.innerHTML = 'More photo <span class="arrow">→</span>';
  }
}
</script>
