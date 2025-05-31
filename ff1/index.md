---
layout: default
title: FF I
---

<style>
.section-images {
  max-width: 400px;
  position: relative;
}
.section-images img {
  width: 100%;
  height: auto;
  object-fit: contain;
  display: block;
}
.toggle-btn {
  position: absolute;
  left: 50%;
  bottom: 10px;
  transform: translateX(-50%);
  width: 48px;
  height: 48px;
  background: #fff;
  border: none;
  border-radius: 50%;
  box-shadow: 0 2px 8px rgba(0,0,0,0.15);
  display: flex;
  align-items: center;
  justify-content: center;
  cursor: pointer;
  z-index: 2;
  transition: box-shadow 0.2s;
}
.toggle-btn:hover {
  box-shadow: 0 4px 16px rgba(0,0,0,0.25);
  background: #f0f0f0;
}
.toggle-btn svg {
  width: 28px;
  height: 28px;
  fill: #888;
  transition: fill 0.2s;
}
.toggle-btn:hover svg {
  fill: #333;
}
</style>

<div style="margin: 1em 0;">
  <label>シリーズ:
    <select id="filter-series" onchange="filterSections()">
      <option value="">すべて</option>
      <option value="1">1</option>
    </select>
  </label>
  <label>色:
    <select id="filter-color" onchange="filterSections()">
      <option value="">すべて</option>
      <option value="白">白</option>
      <option value="青">青</option>
      <option value="黒">黒</option>
      <option value="赤">赤</option>
      <option value="緑">緑</option>
      <option value="マルチカラー">マルチカラー</option>
      <option value="無色">無色</option>
      <option value="アーティファクト">アーティファクト</option>
      <option value="土地">土地</option>
    </select>
  </label>
  <label>タイプ:
    <select id="filter-type" onchange="filterSections()">
      <option value="">すべて</option>
      <option value="クリーチャー">クリーチャー</option>
      <option value="アーティファクト">アーティファクト</option>
      <option value="紋章">紋章</option>
      <option value="インスタント">インスタント</option>
      <option value="ソーサリー">ソーサリー</option>
      <option value="エンチャント">エンチャント</option>
      <option value="土地">土地</option>
    </select>
  </label>
</div>

<div class="section-block" id="「戦士」の剣" data-series="1" data-color="赤" data-type="アーティファクト">
  <div class="section-title">「戦士」の剣</div>
  <div class="section-images">
    <img src="../assets/img/ff1/「戦士」の剣.webp" alt="「戦士」の剣">
  </div>
  <div class="section-comment">「戦士」の剣</div>
  <hr>
</div>

<div class="section-block" id="「白魔術士」の杖" data-series="1" data-color="白" data-type="アーティファクト">
  <div class="section-title">「白魔術士」の杖</div>
  <div class="section-images">
    <img src="../assets/img/ff1/「白魔術士」の杖.webp" alt="「白魔術士」の杖">
  </div>
  <div class="section-comment">「白魔術士」の杖</div>
  <hr>
</div>

<div class="section-block" id="「黒魔術士」の杖" data-series="1" data-color="黒" data-type="アーティファクト">
  <div class="section-title">「黒魔術士」の杖</div>
  <div class="section-images">
    <img src="../assets/img/ff1/「黒魔術士」の杖.webp" alt="「黒魔術士」の杖">
  </div>
  <div class="section-comment">「黒魔術士」の杖</div>
  <hr>
</div>

<div class="section-block" id="「シーフ」のナイフ" data-series="1" data-color="青" data-type="アーティファクト">
  <div class="section-title">「シーフ」のナイフ</div>
  <div class="section-images">
    <img src="../assets/img/ff1/「シーフ」のナイフ.webp" alt="「シーフ」のナイフ">
  </div>
  <div class="section-comment">「シーフ」のナイフ</div>
  <hr>
</div>

<div class="section-block" id="「モンク」の拳" data-series="1" data-color="アーティファクト" data-type="アーティファクト">
  <div class="section-title">「モンク」の拳</div>
  <div class="section-images">
    <img src="../assets/img/ff1/「モンク」の拳.webp" alt="「モンク」の拳">
  </div>
  <div class="section-comment">「モンク」の拳</div>
  <hr>
</div>

<div class="section-block" id="「赤魔術士」のレイピア" data-series="1" data-color="赤" data-type="アーティファクト">
  <div class="section-title">「赤魔術士」のレイピア</div>
  <div class="section-images">
    <img src="../assets/img/ff1/「赤魔術士」のレイピア.webp" alt="「赤魔術士」のレイピア">
  </div>
  <div class="section-comment">「赤魔術士」のレイピア</div>
  <hr>
</div>

<div class="section-block" id="冒険者の飛空艇" data-series="1" data-color="" data-type="">
  <div class="section-title">冒険者の飛空艇</div>
  <div class="section-images">
    <img src="../assets/img/ff1/冒険者の飛空艇.webp" alt="冒険者の飛空艇">
  </div>
  <div class="section-comment">冒険者の飛空艇</div>
  <hr>
</div>

<div class="section-block" id="グルグ火山の赤竜エインシャントカッパードラゴン" data-series="1" data-color="赤" data-type="クリーチャー">
  <div class="section-title">グルグ火山の赤竜(エインシャント・カッパー・ドラゴン)</div>
  <div class="section-images">
    <img src="../assets/img/ff1/グルグ火山の赤竜(エインシャント・カッパー・ドラゴン).webp" alt="グルグ火山の赤竜(エインシャント・カッパー・ドラゴン)">
  </div>
  <div class="section-comment">グルグ火山の赤竜(エインシャント・カッパー・ドラゴン)</div>
  <hr>
</div>

<div class="section-block" id="コーネリアの騎士ガーランド" data-series="1" data-color="マルチカラー" data-type="クリーチャー">
  <div class="section-title" data-alt="コーネリアの騎士、ガーランド">コーネリアの騎士、ガーランド</div>
  <div class="section-images">
    <img src="../assets/img/ff1/コーネリアの騎士、ガーランド.webp"
         alt="コーネリアの騎士、ガーランド"
         data-alt-src="../assets/img/ff1/コーネリアの騎士、ガーランド(時を超えしカオス).webp"
         data-alt-alt="時を超えしカオス">
    <button type="button" class="toggle-btn" onclick="toggleImage(this)" aria-label="画像切り替え">
      <svg viewBox="0 0 48 48">
        <circle cx="24" cy="24" r="20" stroke="#888" stroke-width="3" fill="none"/>
        <path d="M24 8 A16 16 0 1 1 8 24" stroke="#888" stroke-width="3" fill="none"/>
        <polygon points="24,4 28,14 20,14" fill="#888"/>
      </svg>
    </button>
  </div>
  <div class="section-comment" data-alt="コーネリアの騎士、ガーランド(時を超えしカオス)">コーネリアの騎士、ガーランド</div>
  <hr>
</div>

<div class="section-block" id="セーラ姫迷える探求者梓" data-series="1" data-color="緑" data-type="クリーチャー">
  <div class="section-title">セーラ姫(迷える探求者、梓)</div>
  <div class="section-images">
    <img src="../assets/img/ff1/セーラ姫(迷える探求者、梓).webp" alt="セーラ姫(迷える探求者、梓)">
  </div>
  <div class="section-comment">セーラ姫(迷える探求者、梓)</div>
  <hr>
</div>

<div class="section-block" id="フェニックスの尾" data-series="1" data-color="白" data-type="アーティファクト">
  <div class="section-title">フェニックスの尾</div>
  <div class="section-images">
    <img src="../assets/img/ff1/フェニックスの尾.webp" alt="フェニックスの尾">
  </div>
  <div class="section-comment">フェニックスの尾</div>
  <hr>
</div>

<div class="section-block" id="ワールドマップ" data-series="1" data-color="アーティファクト" data-type="アーティファクト">
  <div class="section-title">ワールドマップ</div>
  <div class="section-images">
    <img src="../assets/img/ff1/ワールドマップ.webp" alt="ワールドマップ">
  </div>
  <div class="section-comment">ワールドマップ</div>
  <hr>
</div>

<div class="section-block" id="光の一閃" data-series="1" data-color="白" data-type="インスタント">
  <div class="section-title">光の一閃</div>
  <div class="section-images">
    <img src="../assets/img/ff1/光の一閃.webp" alt="光の一閃">
  </div>
  <div class="section-comment">光の一閃</div>
  <hr>
</div>

<div class="section-block" id="光の戦士統べるものジョダー" data-series="1" data-color="マルチカラー" data-type="クリーチャー">
  <div class="section-title">光の戦士(統べるもの、ジョダー)</div>
  <div class="section-images">
    <img src="../assets/img/ff1/光の戦士(統べるもの、ジョダー).webp" alt="光の戦士(統べるもの、ジョダー)">
  </div>
  <div class="section-comment">光の戦士(統べるもの、ジョダー)</div>
  <hr>
</div>

<div class="section-block" id="始まりの町" data-series="1" data-color="土地" data-type="土地">
  <div class="section-title">始まりの町</div>
  <div class="section-images">
    <img src="../assets/img/ff1/始まりの町.webp" alt="始まりの町">
  </div>
  <div class="section-comment">始まりの町</div>
  <hr>
</div>

<div class="section-block" id="宝物" data-series="1" data-color="アーティファクト" data-type="アーティファクト">
  <div class="section-title">宝物</div>
  <div class="section-images">
    <img src="../assets/img/ff1/宝物.webp" alt="宝物">
  </div>
  <div class="section-comment">宝物</div>
  <hr>
</div>

<div class="section-block" id="宝物モーグリ" data-series="1" data-color="アーティファクト" data-type="クリーチャー">
  <div class="section-title">宝物(モーグリ)</div>
  <div class="section-images">
    <img src="../assets/img/ff1/宝物(モーグリ).webp" alt="宝物(モーグリ)">
  </div>
  <div class="section-comment">宝物(モーグリ)</div>
  <hr>
</div>

<div class="section-block" id="宝物手掛かり" data-series="1" data-color="アーティファクト" data-type="アーティファクト">
  <div class="section-title">宝物(手掛かり)</div>
  <div class="section-images">
    <img src="../assets/img/ff1/宝物(手掛かり).webp" alt="宝物(手掛かり)">
  </div>
  <div class="section-comment">宝物(手掛かり)</div>
  <hr>
</div>


<div class="section-block" id="山" data-series="1" data-color="土地" data-type="土地">
  <div class="section-title">山</div>
  <div class="section-images">
    <img src="../assets/img/ff1/山.webp" alt="山">
  </div>
  <div class="section-comment">山</div>
  <hr>
</div>

<div class="section-block" id="町の歓迎者" data-series="1" data-color="緑" data-type="クリーチャー">
  <div class="section-title">町の歓迎者</div>
  <div class="section-images">
    <img src="../assets/img/ff1/町の歓迎者.webp" alt="町の歓迎者">
  </div>
  <div class="section-comment">町の歓迎者</div>
  <hr>
</div>

<div class="section-block" id="雲海の魔人ニクス咲きの古きもの" data-series="1" data-color="緑" data-type="クリーチャー">
  <div class="section-title">雲海の魔人(ニクス咲きの古きもの)</div>
  <div class="section-images">
    <img src="../assets/img/ff1/雲海の魔人(ニクス咲きの古きもの).webp" alt="雲海の魔人(ニクス咲きの古きもの)">
  </div>
  <div class="section-comment">雲海の魔人(ニクス咲きの古きもの)</div>
  <hr>
</div>

<script>
function filterSections() {
  const series = document.getElementById('filter-series').value;
  const color = document.getElementById('filter-color').value;
  const type = document.getElementById('filter-type').value;
  document.querySelectorAll('.section-block').forEach(block => {
    const match =
      (!series || block.dataset.series === series) &&
      (!color || block.dataset.color === color) &&
      (!type || block.dataset.type === type);
    block.style.display = match ? '' : 'none';
  });
}

function toggleImage(btn) {
  const img = btn.parentElement.querySelector('img');
  const title = btn.closest('.section-block').querySelector('.section-title');
  const comment = btn.closest('.section-block').querySelector('.section-comment');

  // 画像srcとdata-alt-srcを入れ替え
  const tmpSrc = img.src;
  img.src = img.getAttribute('data-alt-src');
  img.setAttribute('data-alt-src', tmpSrc);

  // alt属性も入れ替え
  const tmpAlt = img.alt;
  img.alt = img.getAttribute('data-alt-alt');
  img.setAttribute('data-alt-alt', tmpAlt);

  // タイトルとコメントも入れ替え
  const tmpTitle = title.textContent;
  title.textContent = title.getAttribute('data-alt');
  title.setAttribute('data-alt', tmpTitle);

  const tmpComment = comment.textContent;
  comment.textContent = comment.getAttribute('data-alt');
  comment.setAttribute('data-alt', tmpComment);
}
</script>