<!DOCTYPE html>
<html lang="ko">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>나의 공부 · 교육관 유형 테스트</title>
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Jua&family=Gowun+Dodum&display=swap" rel="stylesheet">
<style>
  :root {
    --paper: #F2F6FF;
    --line: #D6E0F5;
    --ink: #1B2B59;
    --ink-soft: #4A5A8A;
    --white: #FFFFFF;
    --hl: #FFE066;
    --blue: #3A6BFF;
    --good: #19B98B;
    --bad: #F2547D;
    --radius: 18px;
    --font-head: "Jua", "Apple SD Gothic Neo", "Malgun Gothic", sans-serif;
    --font-body: "Gowun Dodum", "Apple SD Gothic Neo", "Malgun Gothic", sans-serif;
  }
  * { box-sizing: border-box; }
  html, body { margin: 0; padding: 0; }
  body {
    font-family: var(--font-body);
    color: var(--ink);
    background-color: var(--paper);
    background-image: repeating-linear-gradient(to bottom, transparent 0, transparent 31px, var(--line) 31px, var(--line) 32px);
    min-height: 100vh;
    line-height: 1.7;
    font-size: 17px;
  }
  .app { max-width: 560px; margin: 0 auto; padding: 28px 18px 70px; }
  h1, h2, h3 { font-family: var(--font-head); font-weight: 400; margin: 0; line-height: 1.3; }
  button { font-family: inherit; font-size: inherit; color: inherit; cursor: pointer; }
  :focus-visible { outline: 3px solid var(--blue); outline-offset: 3px; }

  .screen { display: none; }
  .screen.active { display: block; }

  /* ---------- 인트로 ---------- */
  .intro { text-align: center; padding-top: 24px; }
  .intro .cast { display: flex; justify-content: center; gap: 8px; margin-bottom: 26px; flex-wrap: wrap; }
  .intro .cast .c {
    width: 74px; height: 74px; border-radius: 50%; position: relative;
    border: 3px solid var(--ink); box-shadow: 3px 3px 0 var(--ink);
  }
  .intro .cast .c svg { position: absolute; left: 50%; bottom: -3px; transform: translateX(-50%); width: 78px; height: auto; }
  .intro .cast .c:nth-child(even) { transform: translateY(8px); }
  .intro h1 {
    font-size: clamp(34px, 9vw, 46px); margin-bottom: 14px;
    background: linear-gradient(transparent 62%, var(--hl) 62%, var(--hl) 92%, transparent 92%);
    display: inline; padding: 0 6px;
    -webkit-box-decoration-break: clone; box-decoration-break: clone;
  }
  .intro p.lead { margin: 22px auto 28px; color: var(--ink-soft); max-width: 400px; word-break: keep-all; }
  .intro .stack { display: grid; gap: 14px; justify-items: center; }

  .btn {
    display: inline-block; background: var(--ink); color: var(--white);
    border: 3px solid var(--ink); border-radius: 999px; padding: 13px 30px;
    font-family: var(--font-head); font-size: 21px; box-shadow: 4px 4px 0 var(--blue);
    transition: transform .12s, box-shadow .12s;
  }
  .btn:hover { transform: translate(-1px, -1px); box-shadow: 6px 6px 0 var(--blue); }
  .btn:active { transform: translate(3px, 3px); box-shadow: 1px 1px 0 var(--blue); }
  .btn.ghost { background: var(--white); color: var(--ink); box-shadow: 4px 4px 0 var(--ink); }
  .btn.ghost:hover { box-shadow: 6px 6px 0 var(--ink); }
  .btn.ghost:active { box-shadow: 1px 1px 0 var(--ink); }
  .btn.small { font-size: 17px; padding: 8px 18px; box-shadow: 3px 3px 0 var(--ink); }
  .btn.small:hover { box-shadow: 5px 5px 0 var(--ink); }

  /* ---------- 질문 ---------- */
  .progress-wrap { display: flex; align-items: center; gap: 12px; margin-bottom: 26px; }
  .progress { flex: 1; height: 14px; background: var(--white); border: 2.5px solid var(--ink); border-radius: 999px; overflow: hidden; }
  .progress > div { height: 100%; width: 0; background: var(--hl); border-right: 2.5px solid var(--ink); transition: width .35s ease; }
  .progress-count { font-family: var(--font-head); font-size: 18px; min-width: 62px; text-align: right; }

  .question-card {
    background: var(--white); border: 3px solid var(--ink); border-radius: var(--radius);
    padding: 26px 22px 22px; box-shadow: 6px 6px 0 var(--ink);
  }
  .question-card h2 { font-size: clamp(23px, 6.2vw, 29px); margin-bottom: 20px; word-break: keep-all; }
  .options { display: grid; gap: 12px; }
  .option {
    display: flex; align-items: center; gap: 14px; text-align: left;
    background: var(--paper); border: 2.5px solid var(--ink); border-radius: 14px;
    padding: 14px 16px; line-height: 1.5; word-break: keep-all;
    transition: background .12s, transform .12s;
  }
  .option .emo { font-size: 26px; flex: none; }
  .option:hover { background: var(--hl); transform: translateX(3px); }
  .option.picked { background: var(--hl); }
  .back-row { margin-top: 22px; }
  .link-btn { background: none; border: none; padding: 4px 2px; color: var(--ink-soft); text-decoration: underline; text-underline-offset: 4px; }
  .link-btn[disabled] { visibility: hidden; }

  /* ---------- 결과 카드 ---------- */
  .result-wrap { perspective: 1200px; }
  .viewing {
    display: flex; align-items: center; justify-content: space-between; gap: 10px; flex-wrap: wrap;
    background: var(--hl); border: 2.5px solid var(--ink); border-radius: 14px;
    padding: 10px 14px; margin-bottom: 18px; font-size: 15px;
  }
  .card { background: var(--white); border: 3px solid var(--ink); border-radius: 24px; box-shadow: 8px 8px 0 var(--ink); overflow: hidden; }
  .card.flip-in { animation: flipIn .7s cubic-bezier(.2,.8,.2,1) both; }
  @keyframes flipIn {
    from { transform: rotateY(88deg) scale(.92); opacity: 0; }
    to   { transform: rotateY(0) scale(1); opacity: 1; }
  }
  .card-head { padding: 40px 22px 22px; text-align: center; border-bottom: 3px solid var(--ink); background: var(--tint); }
  .card-head .badge {
    position: relative; width: 150px; height: 150px; margin: 0 auto 16px; border-radius: 50%;
    background: var(--main); border: 3px solid var(--ink); box-shadow: 4px 4px 0 var(--ink);
  }
  .card-head .badge svg { position: absolute; left: 50%; bottom: -9px; transform: translateX(-50%); width: 172px; height: auto; }
  .card.flip-in .badge svg { animation: hop 1.1s .6s ease-out 1 both; }
  @keyframes hop { 0%,100% { transform: translateX(-50%) translateY(0); } 30% { transform: translateX(-50%) translateY(-14px); } 55% { transform: translateX(-50%) translateY(0); } 72% { transform: translateX(-50%) translateY(-6px); } }
  .card-head .pre { color: var(--ink-soft); margin-bottom: 2px; font-size: 15px; }
  .code {
    display: inline-block; font-family: var(--font-head); letter-spacing: .12em;
    background: var(--white); border: 2.5px solid var(--ink); border-radius: 999px;
    padding: 1px 14px; margin-bottom: 8px; font-size: 18px;
  }
  .card-head h2 { font-size: clamp(31px, 8.6vw, 40px); margin-bottom: 6px; }
  .card-head .tagline { font-size: 18px; word-break: keep-all; }
  .card-body { padding: 22px; display: grid; gap: 22px; }
  .card-body h3 { font-size: 21px; margin-bottom: 6px; }
  .card-body p { margin: 0; word-break: keep-all; }
  .philosophy { background: var(--tint); border-left: 6px solid var(--main); border-radius: 6px 14px 14px 6px; padding: 14px 16px; }
  .philosophy p { font-size: 18px; }
  .card-body ul { margin: 0; padding-left: 20px; }
  .card-body li { margin-bottom: 4px; word-break: keep-all; }
  .two-col { display: grid; gap: 22px; }
  @media (min-width: 520px) { .two-col { grid-template-columns: 1fr 1fr; } }

  .pair { display: grid; gap: 14px; }
  .match {
    display: grid; grid-template-columns: 64px 1fr; gap: 12px; align-items: start; text-align: left; width: 100%;
    background: var(--white); border: 3px solid var(--good); border-radius: 16px; padding: 12px 14px;
    transition: transform .12s;
  }
  .match.clash { border-color: var(--bad); border-style: dashed; }
  .match:hover { transform: translateY(-2px); }
  .match .m-emo { position: relative; width: 62px; height: 62px; border-radius: 50%; border: 2.5px solid var(--ink); display: block; }
  .match .m-emo svg { position: absolute; left: 50%; bottom: -3px; transform: translateX(-50%); width: 66px; height: auto; }
  .match .m-label { display: block; font-size: 14px; color: var(--ink-soft); }
  .match.clash .m-label { color: #C2294F; }
  .match .m-name { font-family: var(--font-head); font-size: 20px; line-height: 1.3; }
  .match .m-why { display: block; margin-top: 4px; font-size: 15.5px; line-height: 1.6; word-break: keep-all; }
  .match .m-more { display: block; margin-top: 4px; font-size: 14px; color: var(--ink-soft); text-decoration: underline; text-underline-offset: 3px; }

  .axes { display: grid; gap: 14px; }
  .axis .labels { display: flex; justify-content: space-between; font-size: 15px; margin-bottom: 3px; }
  .axis .labels b { font-family: var(--font-head); font-weight: 400; }
  .axis .labels .dim { color: var(--ink-soft); }
  .axis .track { height: 16px; background: #E3EAFB; border: 2.5px solid var(--ink); border-radius: 999px; overflow: hidden; }
  .axis .fill { height: 100%; width: 50%; background: var(--main); border-right: 2.5px solid var(--ink); transition: width .9s cubic-bezier(.2,.8,.2,1); }

  .gallery-title { margin: 38px 0 12px; font-size: 22px; text-align: center; }
  .gallery { display: grid; grid-template-columns: repeat(4, 1fr); gap: 10px; }
  .g-item {
    background: var(--white); border: 2.5px solid var(--ink); border-radius: 14px;
    padding: 8px 2px 7px; display: grid; justify-items: center; gap: 0; line-height: 1.3;
    transition: transform .12s, background .12s;
  }
  .g-item:hover { transform: translateY(-2px); background: var(--hl); }
  .g-item.mine { background: var(--hl); box-shadow: 3px 3px 0 var(--ink); }
  .g-item .g-emo { display: block; width: 100%; }
  .g-item .g-emo svg { width: 58px; height: auto; display: block; margin: 0 auto; }
  .g-item .g-name { font-size: 12.5px; word-break: keep-all; text-align: center; padding: 0 3px; }
  .g-item .g-code { font-size: 11.5px; color: var(--ink-soft); letter-spacing: .08em; }

  .actions { display: flex; gap: 12px; justify-content: center; flex-wrap: wrap; margin-top: 30px; }
  .toast {
    position: fixed; left: 50%; bottom: 28px; transform: translate(-50%, 30px);
    background: var(--ink); color: var(--white); padding: 11px 20px; border-radius: 999px;
    opacity: 0; pointer-events: none; transition: opacity .25s, transform .25s; z-index: 10;
  }
  .toast.show { opacity: 1; transform: translate(-50%, 0); }
  @media (max-width: 420px) {
    .gallery { grid-template-columns: repeat(4, 1fr); gap: 7px; }
    .g-item .g-name { font-size: 11.5px; }
  }
  @media (prefers-reduced-motion: reduce) { * { animation: none !important; transition: none !important; } }

  .hint { margin: -10px 0 16px; color: var(--ink-soft); font-size: 15px; }
</style>
</head>
<body>
<main class="app">

  <!-- 인트로 -->
  <section id="screen-intro" class="screen active intro">
    <div class="cast" id="cast" aria-hidden="true"></div>
    <h1>나는 어떤 선생님,<br>어떤 학생일까?</h1>
    <p class="lead">시험 전날부터 팀플 갈등까지, 20가지 질문(각 4가지 선택지)에 답하면 16마리 귀여운 캐릭터 중 나의 공부 스타일과 교육관을 알려드려요. 찰떡 궁합과 안 맞는 유형도 함께요. 3분이면 끝나요.</p>
    <div class="stack">
      <button class="btn" id="btn-start">테스트 시작하기</button>
      <button class="link-btn" id="btn-browse">16마리 캐릭터 먼저 구경하기</button>
    </div>
  </section>

  <!-- 질문 -->
  <section id="screen-quiz" class="screen">
    <div class="progress-wrap">
      <div class="progress" role="progressbar" aria-valuemin="0" aria-valuemax="20" aria-valuenow="0" id="progress"><div id="progress-bar"></div></div>
      <div class="progress-count" id="progress-count">1 / 20</div>
    </div>
    <div class="question-card">
      <h2 id="q-text"></h2>
      <p class="hint">나와 가장 가까운 답을 하나만 골라주세요.</p>
      <div class="options" id="q-options"></div>
    </div>
    <div class="back-row"><button class="link-btn" id="btn-back">이전 질문으로</button></div>
  </section>

  <!-- 결과 -->
  <section id="screen-result" class="screen">
    <div id="viewing-bar"></div>
    <div class="result-wrap" id="result-card"></div>
    <div class="actions" id="result-actions"></div>
    <h2 class="gallery-title">16마리 캐릭터 모두 보기</h2>
    <div class="gallery" id="gallery"></div>
  </section>

</main>
<div class="toast" id="toast" role="status" aria-live="polite"></div>

<script>
/* ===================== 귀여운 캐릭터 (인라인 SVG) ===================== */
const INK = "#1B2B59";
const SK = `stroke="${INK}" stroke-width="4" stroke-linejoin="round" stroke-linecap="round"`;
const ell = (cx, cy, rx, ry, fill, ex = "") => `<ellipse cx="${cx}" cy="${cy}" rx="${rx}" ry="${ry}" fill="${fill}" ${ex.includes("stroke") ? "" : SK} ${ex}/>`;
const circ = (cx, cy, r, fill, ex = "") => `<circle cx="${cx}" cy="${cy}" r="${r}" fill="${fill}" ${ex.includes("stroke") ? "" : SK} ${ex}/>`;
const pth = (d, fill, ex = "") => `<path d="${d}" fill="${fill}" ${ex.includes("stroke") ? "" : SK} ${ex}/>`;
const ln = (d, w = 3.5, c = INK) => `<path d="${d}" fill="none" stroke="${c}" stroke-width="${w}" stroke-linecap="round" stroke-linejoin="round"/>`;
const tailLine = (d, color, w) => ln(d, w + 8, INK) + ln(d, w, color);

function eyes(style, y = 100, dx = 24) {
  const xl = 100 - dx, xr = 100 + dx;
  if (style === "happy") return ln(`M${xl - 7} ${y + 3} Q${xl} ${y - 8} ${xl + 7} ${y + 3}`, 3.8) + ln(`M${xr - 7} ${y + 3} Q${xr} ${y - 8} ${xr + 7} ${y + 3}`, 3.8);
  if (style === "sleepy") return ln(`M${xl - 7} ${y - 2} Q${xl} ${y + 7} ${xl + 7} ${y - 2}`, 3.8) + ln(`M${xr - 7} ${y - 2} Q${xr} ${y + 7} ${xr + 7} ${y - 2}`, 3.8);
  const r = style === "sparkle" ? 8 : 6.5;
  const one = (x) => `<circle cx="${x}" cy="${y}" r="${r}" fill="${INK}"/><circle cx="${x + 2.4}" cy="${y - 2.6}" r="${r * 0.36}" fill="#fff"/>` +
    (style === "sparkle" ? `<circle cx="${x - 2.6}" cy="${y + 2.6}" r="1.6" fill="#fff"/>` : "");
  return one(xl) + one(xr);
}
const blush = (y = 114, dx = 38, c = "#FF8FA8") =>
  `<ellipse cx="${100 - dx}" cy="${y}" rx="9" ry="5.5" fill="${c}" opacity=".75"/><ellipse cx="${100 + dx}" cy="${y}" rx="9" ry="5.5" fill="${c}" opacity=".75"/>`;
function mouth(style, y = 116) {
  if (style === "w") return ln(`M92 ${y} Q96 ${y + 6} 100 ${y} Q104 ${y + 6} 108 ${y}`);
  if (style === "open") return `<path d="M90 ${y} Q100 ${y + 18} 110 ${y} Z" fill="#7A2B45" ${SK} stroke-width="3"/><ellipse cx="100" cy="${y + 9}" rx="6" ry="4" fill="#FF8FA8"/>`;
  return ln(`M91 ${y} Q100 ${y + 9} 109 ${y}`);
}
function torso({ fill, belly, arm = fill, foot = fill }) {
  return ell(78, 190, 15, 8, foot) + ell(122, 190, 15, 8, foot) +
    ell(100, 156, 42, 32, fill) + `<ellipse cx="100" cy="163" rx="26" ry="20" fill="${belly}"/>` +
    ell(60, 157, 11, 17, arm, 'transform="rotate(14 60 157)"') + ell(140, 157, 11, 17, arm, 'transform="rotate(-14 140 157)"');
}
const head = (fill) => ell(100, 96, 60, 50, fill);
function flower(x, y) {
  let p = "";
  for (let a = 0; a < 6; a++) p += `<ellipse cx="0" cy="-9" rx="5.5" ry="8" fill="#FFD84D" ${SK} stroke-width="2.5" transform="rotate(${a * 60})"/>`;
  return `<g transform="translate(${x} ${y})">${p}<circle r="6" fill="#B0702F" ${SK} stroke-width="2.5"/></g>`;
}

const DRAW = {
  penguin() {
    const navy = "#3E4E8C", beak = "#FFA94D";
    return torso({ fill: navy, belly: "#fff", foot: beak }) +
      ell(57, 155, 10, 21, navy, 'transform="rotate(20 57 155)"') + ell(143, 155, 10, 21, navy, 'transform="rotate(-20 143 155)"') +
      head(navy) + `<ellipse cx="100" cy="108" rx="44" ry="33" fill="#fff"/>` +
      eyes("dot", 99, 24) + blush(114, 40) +
      pth("M91 109 Q100 105 109 109 Q106 122 100 123 Q94 122 91 109Z", beak) +
      pth("M64 58 Q64 26 100 26 Q136 26 136 58 Z", "#fff") +
      `<rect x="58" y="52" width="84" height="14" rx="6" fill="#2B3A6E" ${SK}/>` +
      circ(100, 59, 5.5, "#FFC93C", 'stroke-width="2.5"') + ln("M84 30 Q100 22 116 30", 3, "#C8D4F5");
  },
  bear() {
    const br = "#BF8650", mz = "#F6DDBF";
    return circ(52, 56, 17, br) + circ(52, 56, 8, "#F4B5A3", 'stroke="none"') + circ(148, 56, 17, br) + circ(148, 56, 8, "#F4B5A3", 'stroke="none"') +
      torso({ fill: br, belly: mz }) + head(br) + ell(100, 117, 24, 17, mz, 'stroke="none"') +
      ell(100, 108, 8, 5.5, INK, 'stroke="none"') + ln("M100 113 V118") + mouth("w", 118) +
      eyes("dot", 92, 28) + blush(110, 44) +
      circ(72, 92, 15, "rgba(255,255,255,.35)", 'stroke-width="3.5"') + circ(128, 92, 15, "rgba(255,255,255,.35)", 'stroke-width="3.5"') + ln("M87 91 Q100 85 113 91", 3.5) +
      pth("M60 142 Q100 166 140 142 L142 158 Q100 182 58 158 Z", "#3DBE8B") + pth("M116 164 L134 166 L130 190 L112 186 Z", "#2FA777");
  },
  fox() {
    const o = "#FF9A4D", w = "#FFF6EA";
    return pth("M130 172 Q192 180 186 118 Q162 138 130 150 Z", o) + pth("M186 118 Q176 128 166 132 Q184 146 188 130 Z", w, 'stroke="none"') +
      pth("M46 76 L50 26 L88 54 Z", o) + pth("M56 66 L57 42 L74 54 Z", "#7A3E2A", 'stroke="none"') +
      pth("M154 76 L150 26 L112 54 Z", o) + pth("M144 66 L143 42 L126 54 Z", "#7A3E2A", 'stroke="none"') +
      torso({ fill: o, belly: w, arm: o, foot: "#7A3E2A" }) + head(o) +
      ell(72, 117, 24, 17, w, 'stroke="none"') + ell(128, 117, 24, 17, w, 'stroke="none"') +
      ell(100, 110, 7.5, 5.5, INK, 'stroke="none"') + mouth("smile", 118) + eyes("dot", 99, 26) + blush(112, 44, "#FFB08A") +
      `<g transform="translate(126 146) rotate(-8)"><rect y="-8" width="42" height="30" rx="3" fill="#fff" ${SK}/><rect y="-16" width="42" height="12" rx="2" fill="${INK}" ${SK} stroke-width="3"/>` +
      ln("M9 -16 L15 -4 M21 -16 L27 -4 M33 -16 L39 -4", 3, "#fff") + ln("M8 8 H34 M8 15 H26", 3) + `</g>`;
  },
  rabbit() {
    const w = "#FFF4F6", pk = "#FFB6C8";
    return ell(72, 30, 14, 36, w, 'transform="rotate(-8 72 30)"') + ell(72, 32, 7, 25, pk, 'stroke="none" transform="rotate(-8 72 32)"') +
      ell(128, 30, 14, 36, w, 'transform="rotate(8 128 30)"') + ell(128, 32, 7, 25, pk, 'stroke="none" transform="rotate(8 128 32)"') +
      torso({ fill: w, belly: "#FFE3EA", foot: w }) + head(w) +
      eyes("dot", 100, 24) + pth("M95 108 Q100 114 105 108 Q100 105 95 108Z", pk, 'stroke-width="2.5"') + mouth("w", 114) + blush(112, 40) + flower(134, 58);
  },
  tiger() {
    const o = "#FFB347", w = "#FFF6E6";
    return circ(54, 58, 15, o) + circ(54, 58, 7.5, "#FFD9B0", 'stroke="none"') + circ(146, 58, 15, o) + circ(146, 58, 7.5, "#FFD9B0", 'stroke="none"') +
      torso({ fill: o, belly: w }) + ln("M62 141 l10 5 M60 156 l11 2 M138 141 l-10 5 M140 156 l-11 2", 3.5) + head(o) +
      ln("M100 49 V61 M87 52 L90 63 M113 52 L110 63", 4) + ln("M42 98 L55 101 M42 112 L55 109 M158 98 L145 101 M158 112 L145 109", 3.5) +
      ell(100, 119, 26, 17, w, 'stroke="none"') + pth("M93 110 L107 110 L100 118 Z", "#F2547D", 'stroke-width="2.5"') +
      ln("M100 118 V122 M92 125 Q100 129 100 122 M100 122 Q100 129 108 125", 3) + eyes("dot", 99, 26) +
      pth("M42 80 Q100 62 158 80 L158 92 Q100 74 42 92 Z", "#F2547D") + pth("M158 82 L178 72 L174 90 Z", "#F2547D") + pth("M158 86 L176 98 L170 82 Z", "#D93A63");
  },
  owl() {
    const br = "#B07F52", cr = "#FFF1D6";
    return pth("M48 70 L44 28 L86 54 Z", br) + pth("M152 70 L156 28 L114 54 Z", br) +
      torso({ fill: br, belly: cr, arm: "#8F6139", foot: "#FFA94D" }) + ln("M88 154 q6 6 12 0 q6 6 12 0 M90 168 q5 5 10 0 q5 5 10 0", 3) +
      head(br) + circ(74, 99, 25, cr, 'stroke-width="3"') + circ(126, 99, 25, cr, 'stroke-width="3"') +
      circ(74, 99, 14, "#fff", 'stroke-width="3"') + circ(126, 99, 14, "#fff", 'stroke-width="3"') +
      `<circle cx="75" cy="100" r="8" fill="${INK}"/><circle cx="125" cy="100" r="8" fill="${INK}"/><circle cx="78" cy="96" r="3" fill="#fff"/><circle cx="128" cy="96" r="3" fill="#fff"/>` +
      pth("M93 112 L107 112 L100 126 Z", "#FFA94D", 'stroke-width="3"') +
      pth("M142 34 Q142 10 166 10 Q192 10 192 34 Q192 56 166 56 L156 56 L150 66 L150 54 Q142 48 142 34Z", "#fff") +
      `<text x="167" y="44" text-anchor="middle" font-family="Jua, sans-serif" font-size="32" fill="${INK}">?</text>`;
  },
  cat() {
    const c = "#C9B8FF", w = "#F4EFFF";
    return tailLine("M138 174 Q190 176 186 130", c, 12) +
      pth("M46 78 L52 30 L90 56 Z", c) + pth("M56 66 L58 44 L74 55 Z", "#FFB6C8", 'stroke="none"') +
      pth("M154 78 L148 30 L110 56 Z", c) + pth("M144 66 L142 44 L126 55 Z", "#FFB6C8", 'stroke="none"') +
      torso({ fill: c, belly: w }) + head(c) + ln("M100 49 V59 M89 51 L91 60 M111 51 L109 60", 3.5) +
      eyes("sparkle", 99, 26) + pth("M96 108 L104 108 L100 113 Z", "#FF8FA8", 'stroke-width="2.5"') + mouth("w", 115) + blush(112, 42) +
      ln("M28 104 L50 108 M28 116 L50 114 M172 104 L150 108 M172 116 L150 114", 3) +
      ln("M76 6 L68 0 M124 6 L132 0 M68 22 L58 22 M132 22 L142 22 M100 -2 V-8", 3.5, "#FFB300") +
      circ(100, 22, 15, "#FFE066") + `<rect x="92" y="36" width="16" height="9" rx="3" fill="#C7CFE8" ${SK} stroke-width="3"/>` + ln("M94 24 L100 31 L106 24", 3);
  },
  dog() {
    const g = "#F4C27E", br = "#C98E4A", w = "#FFF3DD";
    return ell(44, 96, 16, 32, br, 'transform="rotate(10 44 96)"') + ell(156, 96, 16, 32, br, 'transform="rotate(-10 156 96)"') +
      torso({ fill: g, belly: w }) + head(g) + ell(124, 92, 17, 16, br, 'stroke="none"') + ell(100, 120, 26, 18, w, 'stroke="none"') +
      ell(100, 109, 9, 6, INK, 'stroke="none"') + ln("M100 114 V121") + mouth("open", 121) + eyes("dot", 96, 26) + blush(112, 46) +
      pth("M100 8 L72 58 L128 58 Z", "#7C5CFF") + ln("M90 28 L112 36 M82 42 L120 50", 5, "#FFE066") + circ(100, 8, 7, "#FFE066", 'stroke-width="3"') +
      circ(40, 40, 4, "#F2547D", 'stroke-width="2"') + circ(164, 34, 4, "#3DD6B0", 'stroke-width="2"') + circ(180, 74, 3.5, "#FFE066", 'stroke-width="2"') + circ(22, 78, 3.5, "#7C5CFF", 'stroke-width="2"');
  },
  panda() {
    const k = "#3A3F5C";
    return circ(54, 56, 17, k) + circ(146, 56, 17, k) +
      torso({ fill: "#fff", belly: "#F1F4FF", arm: k, foot: k }) + head("#fff") +
      ell(76, 101, 15, 19, k, 'stroke="none" transform="rotate(20 76 101)"') + ell(124, 101, 15, 19, k, 'stroke="none" transform="rotate(-20 124 101)"') +
      `<circle cx="77" cy="100" r="6.5" fill="#fff"/><circle cx="123" cy="100" r="6.5" fill="#fff"/><circle cx="78" cy="100" r="3.6" fill="${INK}"/><circle cx="122" cy="100" r="3.6" fill="${INK}"/>` +
      ell(100, 113, 8, 5.5, k, 'stroke="none"') + mouth("w", 117) + blush(116, 48) +
      `<g transform="translate(130 136) rotate(10)"><rect width="38" height="46" rx="4" fill="#fff" ${SK}/>` +
      `<text x="19" y="30" text-anchor="middle" font-family="Jua, sans-serif" font-size="18" fill="#F2547D">100</text>` + ln("M7 11 H31", 3) + `</g>`;
  },
  koala() {
    const g = "#B5BDD8", w = "#EEF1FA";
    return circ(40, 68, 25, g) + circ(40, 68, 13, "#FFD3DC", 'stroke="none"') + circ(160, 68, 25, g) + circ(160, 68, 13, "#FFD3DC", 'stroke="none"') +
      torso({ fill: g, belly: w }) + head(g) + eyes("sleepy", 96, 26) + ell(100, 108, 11, 15, "#4A5272", 'stroke-width="3"') +
      ln("M92 127 Q100 133 108 127", 3.5) + blush(116, 44) +
      pth("M62 150 L100 158 L138 150 L138 184 L100 192 L62 184 Z", "#fff") + ln("M100 158 V192", 3) + ln("M70 162 L92 167 M70 172 L92 177 M108 167 L130 162 M108 177 L130 172", 2.5, "#9AA6D4");
  },
  hamster() {
    const c = "#FFDCA8", w = "#FFF7EA";
    return circ(56, 62, 13, c) + circ(56, 62, 6.5, "#FFC1CF", 'stroke="none"') + circ(144, 62, 13, c) + circ(144, 62, 6.5, "#FFC1CF", 'stroke="none"') +
      torso({ fill: c, belly: w }) + ell(100, 98, 62, 48, c) + ell(58, 117, 17, 12, "#FFC9A0", 'stroke="none"') + ell(142, 117, 17, 12, "#FFC9A0", 'stroke="none"') +
      eyes("dot", 100, 24) + ell(100, 109, 5, 4, "#FF8FA8", 'stroke="none"') + mouth("w", 114) +
      ell(98, 52, 46, 17, "#F2547D") + circ(100, 36, 4.5, "#F2547D", 'stroke-width="3"') + ln("M70 48 Q86 42 100 44", 3, "#FFB3C6") +
      `<g transform="translate(132 138) rotate(-28)">` +
      `<rect x="0" y="0" width="9" height="38" rx="3" fill="#3A6BFF" ${SK} stroke-width="3"/><rect x="11" y="0" width="9" height="38" rx="3" fill="#FFE066" ${SK} stroke-width="3"/><rect x="22" y="0" width="9" height="38" rx="3" fill="#3DD6B0" ${SK} stroke-width="3"/></g>`;
  },
  mouse() {
    const c = "#E4DBF7", pk = "#FFC3D3";
    return tailLine("M138 178 Q194 196 188 150", pk, 5) +
      circ(52, 60, 24, c) + circ(52, 60, 14, pk, 'stroke="none"') + circ(148, 60, 24, c) + circ(148, 60, 14, pk, 'stroke="none"') +
      torso({ fill: c, belly: "#F6F1FF" }) + head(c) + eyes("happy", 100, 24) + ell(100, 109, 5.5, 4.5, "#FF8FA8", 'stroke-width="2.5"') + mouth("smile", 114) + blush(113, 40) +
      ln("M34 106 L54 110 M34 118 L54 116 M166 106 L146 110 M166 118 L146 116", 3) +
      pth("M166 14 A24 24 0 1 0 190 52 A19 19 0 1 1 166 14 Z", "#FFE066", 'stroke-width="3.5"') +
      pth("M30 22 L33 30 L41 33 L33 36 L30 44 L27 36 L19 33 L27 30 Z", "#FFE066", 'stroke-width="2.5"') +
      `<g transform="translate(130 142) rotate(8)"><rect width="30" height="38" rx="4" fill="#FF9DB6" ${SK}/><rect x="4" width="4" height="38" fill="#FF7A9C" stroke="none"/>` +
      pth("M20 16 Q16 11 13 16 Q16 22 20 24 Q24 22 27 16 Q24 11 20 16Z", "#fff", 'stroke="none"') + `</g>`;
  },
  raccoon() {
    const g = "#A5AEC7", dk = "#45506E", w = "#F3F5FB";
    return pth("M130 172 Q194 180 186 124 Q162 148 130 150 Z", g) + ln("M164 166 L158 152 M178 156 L170 140", 5, dk) +
      circ(52, 56, 15, g) + circ(52, 56, 7, dk, 'stroke="none"') + circ(148, 56, 15, g) + circ(148, 56, 7, dk, 'stroke="none"') +
      torso({ fill: g, belly: w, arm: g, foot: dk }) + head(g) + ell(100, 121, 32, 22, w, 'stroke="none"') +
      pth("M42 98 Q70 78 100 94 Q130 78 158 98 Q150 124 124 116 Q106 112 100 106 Q94 112 76 116 Q50 124 42 98 Z", dk, 'stroke="none"') +
      `<circle cx="76" cy="100" r="8" fill="#fff"/><circle cx="124" cy="100" r="8" fill="#fff"/><circle cx="78" cy="101" r="4.6" fill="${INK}"/><circle cx="122" cy="101" r="4.6" fill="${INK}"/><circle cx="80" cy="99" r="1.6" fill="#fff"/><circle cx="124" cy="99" r="1.6" fill="#fff"/>` +
      ell(100, 114, 7, 5, INK, 'stroke="none"') + mouth("smile", 120) +
      `<g transform="translate(146 150)">` + circ(0, 0, 22, "#fff") + circ(0, 0, 15, "#F2547D", 'stroke-width="3"') + circ(0, 0, 8, "#fff", 'stroke-width="3"') + circ(0, 0, 3, "#F2547D", 'stroke="none"') +
      ln("M0 0 L26 -26", 4) + ln("M18 -18 L28 -18 M18 -18 L18 -28", 3.5) + `</g>`;
  },
  dino() {
    const g = "#7ED6A5", d = "#4FB483", w = "#E6FBF0", sp = "#FFB347";
    return tailLine("M138 178 Q190 188 188 148", g, 16) +
      pth("M64 56 L74 28 L90 50 Z", sp) + pth("M86 50 L100 20 L114 50 Z", sp) + pth("M110 50 L126 28 L136 56 Z", sp) +
      torso({ fill: g, belly: w }) + head(g) +
      ell(70, 66, 6, 4, d, 'stroke="none"') + ell(132, 70, 7, 5, d, 'stroke="none"') + ell(112, 60, 4, 3, d, 'stroke="none"') +
      eyes("dot", 96, 26) + `<circle cx="93" cy="111" r="2.2" fill="${INK}"/><circle cx="107" cy="111" r="2.2" fill="${INK}"/>` +
      ln("M82 122 Q100 138 118 122", 3.5) + blush(114, 46) +
      `<g transform="translate(142 148)"><circle r="17" fill="rgba(200,235,255,.6)" ${SK}/>` + ln("M12 12 L30 30", 10, INK) + ln("M12 12 L30 30", 5, sp) + ln("M-8 -5 Q-6 -10 -1 -11", 3, "#fff") + `</g>`;
  },
  monkey() {
    const b = "#A9744A", f = "#F7D9B6";
    return tailLine("M136 176 Q196 190 188 128", b, 8) +
      circ(40, 98, 15, b) + circ(40, 98, 8, f, 'stroke="none"') + circ(160, 98, 15, b) + circ(160, 98, 8, f, 'stroke="none"') +
      torso({ fill: b, belly: f }) + head(b) +
      circ(80, 98, 19, f, 'stroke="none"') + circ(120, 98, 19, f, 'stroke="none"') + ell(100, 119, 30, 20, f, 'stroke="none"') +
      eyes("dot", 99, 22) + `<circle cx="95" cy="112" r="2" fill="${INK}"/><circle cx="105" cy="112" r="2" fill="${INK}"/>` + mouth("open", 120) + blush(114, 48) +
      `<g transform="translate(100 168)"><rect x="-34" y="-14" width="68" height="28" rx="14" fill="#7C5CFF" ${SK}/>` +
      ln("M-24 0 H-12 M-18 -6 V6", 3.5, "#fff") + circ(14, -3, 3.8, "#FFE066", 'stroke-width="2"') + circ(23, 3, 3.8, "#3DD6B0", 'stroke-width="2"') + circ(14, 5, 3.8, "#FF8FA8", 'stroke-width="2"') +
      circ(-36, 2, 9, b) + circ(36, 2, 9, b) + `</g>`;
  },
  sheep() {
    const wl = "#FFFFFF", sk = "#FFE1CE";
    const puffs = [[48, 88, 22], [58, 58, 24], [86, 44, 25], [116, 44, 25], [144, 58, 24], [152, 88, 22], [56, 118, 20], [144, 118, 20]];
    return torso({ fill: wl, belly: "#F4F1FF", arm: sk, foot: "#5A4F85" }) +
      puffs.map(p => circ(p[0], p[1], p[2], wl)).join("") + puffs.map(p => circ(p[0], p[1], p[2] - 0.5, wl, 'stroke="none"')).join("") +
      ell(52, 108, 14, 8, "#FFD0BC", 'transform="rotate(25 52 108)"') + ell(148, 108, 14, 8, "#FFD0BC", 'transform="rotate(-25 148 108)"') +
      ell(100, 102, 40, 38, sk) + circ(86, 68, 14, wl) + circ(114, 68, 14, wl) + circ(86, 68, 13, wl, 'stroke="none"') + circ(114, 68, 13, wl, 'stroke="none"') +
      eyes("sleepy", 100, 18) + blush(113, 28) + mouth("smile", 112) +
      `<g transform="translate(160 30)">` + ell(-11, -6, 12, 9, "#FFB6C8", 'transform="rotate(-25)"') + ell(11, -6, 12, 9, "#C9B8FF", 'transform="rotate(25)"') +
      ell(-8, 8, 8, 6, "#FFB6C8", 'transform="rotate(25)"') + ell(8, 8, 8, 6, "#C9B8FF", 'transform="rotate(-25)"') + ln("M0 -10 V12", 4) + ln("M0 -10 L-5 -18 M0 -10 L5 -18", 2.5) + `</g>` +
      pth("M30 28 L33 36 L41 39 L33 42 L30 50 L27 42 L19 39 L27 36 Z", "#FFE066", 'stroke-width="2.5"');
  }
};

const ANIMAL = {
  TPLG: ["penguin", "🐧", "펭귄"], TPLH: ["bear", "🐻", "곰"], TPCG: ["fox", "🦊", "여우"], TPCH: ["rabbit", "🐰", "토끼"],
  TBLG: ["tiger", "🐯", "호랑이"], TBLH: ["owl", "🦉", "부엉이"], TBCG: ["cat", "🐱", "고양이"], TBCH: ["dog", "🐶", "강아지"],
  SPLG: ["panda", "🐼", "판다"], SPLH: ["koala", "🐨", "코알라"], SPCG: ["hamster", "🐹", "햄스터"], SPCH: ["mouse", "🐭", "생쥐"],
  SBLG: ["raccoon", "🦝", "너구리"], SBLH: ["dino", "🦖", "아기 공룡"], SBCG: ["monkey", "🐵", "원숭이"], SBCH: ["sheep", "🐑", "아기 양"]
};

function characterSVG(code, cls = "") {
  const a = ANIMAL[code];
  return `<svg class="${cls}" viewBox="-4 -12 208 214" xmlns="http://www.w3.org/2000/svg" role="img" aria-label="${a[2]} 캐릭터">${DRAW[a[0]]()}</svg>`;
}


/* ===================== 유형 데이터 ===================== */
const TYPES = {
  TPLG: { emoji: "🏛️", name: "스터디 사령관", tagline: "목표는 명확하게, 실행은 함께!",
    philosophy: "좋은 교육은 분명한 목표와 체계적인 로드맵, 그리고 함께 달리는 팀이 만든다고 믿어요.",
    style: "스터디 일정표를 짜고 역할을 나눠 진도를 관리해요. 근거 있는 계획으로 팀을 목표까지 이끄는 타입이에요.",
    strengths: ["팀 전체의 진도와 일정을 한눈에 관리해요", "논리적으로 우선순위를 정해요", "목표 달성률이 높아요"],
    caution: "효율을 따지다 팀원의 속도와 감정을 놓칠 수 있어요.",
    tip: "스터디 시작 5분은 진도 점검 대신 근황 나누기로 써보세요. 팀 집중력이 올라가요.",
    matchWhy: "같은 논리파라 말이 잘 통하고, 호기심 넘치는 질문으로 내 계획에 깊이를 더해줘요.",
    clashWhy: "혼자서 감성과 영감으로 움직이는 스타일이라 내 일정표가 답답하게 느껴질 수 있어요. 결과물 기준만 합의하고 과정은 맡겨보세요." },
  TPLH: { emoji: "🧭", name: "길잡이 멘토", tagline: "같이 걷는 길, 지도는 내가 그려줄게!",
    philosophy: "모든 학생에게는 맞는 속도와 방향이 있다고 믿고, 체계적이면서 다정하게 돕는 교육을 지향해요.",
    style: "친구의 공부를 도우며 개념을 차근차근 설명해줘요. 계획은 세우되 상대의 컨디션에 맞춰 유연하게 조정해요.",
    strengths: ["쉽고 차근차근한 설명", "팀원을 세심하게 챙겨요", "꾸준한 응원으로 동기를 지켜줘요"],
    caution: "남을 돕다가 내 공부 시간이 줄어들 수 있어요.",
    tip: "내 공부 시간을 캘린더에 먼저 확정하고, 남는 시간에 친구를 도와주세요.",
    matchWhy: "열정적인 승부욕이 내 따뜻한 설명과 만나 팀에 추진력을 만들어줘요.",
    clashWhy: "혼자서 파격적으로 도전하는 스타일이라 내 세심한 조언이 간섭처럼 들릴 수 있어요. 먼저 '도움이 필요하면 말해줘'라고 한 번만 말해보세요." },
  TPCG: { emoji: "🎬", name: "프로젝트 PD", tagline: "기획부터 발표까지, 내가 책임질게!",
    philosophy: "배움은 눈에 보이는 결과물로 완성된다고 믿고, 프로젝트형 수업을 가장 좋아해요.",
    style: "팀플이 생기면 기획안, 일정, 발표 연출까지 큰 그림을 먼저 그려요. 아이디어를 계획으로 바꾸는 데 강해요.",
    strengths: ["아이디어를 실행 계획으로 연결해요", "발표와 시각화 감각이 뛰어나요", "마감 관리가 철저해요"],
    caution: "완성도에 집착해 팀원의 부담이 커질 수 있어요.",
    tip: "'80% 완성 기준'을 정해두고, 나머지는 팀과 함께 다듬어보세요.",
    matchWhy: "아이디어에 열광해주는 에너지 덕분에 내 기획이 신나게 현실이 돼요.",
    clashWhy: "혼자 원리를 파고드는 스타일이라 마감과 연출보다 이해가 우선이에요. 속도가 엇갈릴 땐 '탐구 시간'을 일정에 미리 넣어주세요." },
  TPCH: { emoji: "🌻", name: "따뜻한 기획자", tagline: "모두가 즐거운 공부 시간을 설계해요!",
    philosophy: "즐겁고 안전한 분위기에서 배움이 오래 간다고 믿어요. 교실은 함께 만드는 놀이터예요.",
    style: "스터디 규칙, 간식 타임, 미니 퀴즈 같은 활동을 창의적으로 기획해요. 모두가 참여하는 분위기를 만드는 데 능해요.",
    strengths: ["팀 분위기를 설계하는 능력", "갈등을 부드럽게 풀어요", "소외되는 사람 없이 참여를 이끌어요"],
    caution: "즐거움에 집중하다 진도가 밀릴 수 있어요.",
    tip: "재미 요소 하나마다 학습 목표 하나를 짝지어 계획해보세요.",
    matchWhy: "번뜩이는 아이디어에 내 기획력이 더해지면 멋진 결과가 나와요.",
    clashWhy: "혼자 효율만 따지는 스타일이라 감정 교류가 부족하게 느껴질 수 있어요. 용건 위주의 대화도 애정 표현이라고 생각해보세요." },
  TBLG: { emoji: "⚔️", name: "토론 승부사", tagline: "논리로 붙어봐야 실력이 늘지!",
    philosophy: "치열한 토론과 건강한 경쟁이 사고력을 단련한다고 믿어요.",
    style: "평소엔 느긋하다가 토론, 퀴즈, 시험 직전에 집중력이 폭발해요. 친구와 문제 대결을 하며 공부할 때 가장 불타올라요.",
    strengths: ["빠른 판단과 날카로운 반박", "압박 속에서 살아나는 집중력", "뚜렷한 목표 의식"],
    caution: "이기려다 상대의 감정을 상하게 할 수 있어요.",
    tip: "토론이 끝나면 '좋은 지적이었어' 한마디를 습관으로 만들어보세요.",
    matchWhy: "차분한 설명과 응원이 내 승부욕을 지치지 않게 받쳐줘요.",
    clashWhy: "천천히 혼자 감성으로 정리하는 스타일이라 내 속도와 직설이 부담스러울 수 있어요. 결론부터 말하기 전에 의견을 한 번 물어봐주세요." },
  TBLH: { emoji: "🦉", name: "토론 올빼미", tagline: "같이 파고들면 더 재밌어!",
    philosophy: "질문과 대화 속에서 배움이 깊어진다고 믿어요. 정답보다 '왜?'를 나누는 교실이 좋은 교실이에요.",
    style: "밤늦게 친구와 '이건 왜 그럴까?'를 이야기하다가 개념이 정리되는 타입이에요. 설명하면서 이해가 깊어져요.",
    strengths: ["끝없는 호기심과 열린 대화", "설명하며 이해를 확장해요", "사람들에게 생각할 거리를 던져줘요"],
    caution: "대화가 길어져 정작 진도는 못 나갈 수 있어요.",
    tip: "토론을 시작하기 전에 타이머 30분을 맞춰두세요.",
    matchWhy: "내 호기심에 체계적인 일정이 붙으면 질문이 성과로 이어져요.",
    clashWhy: "혼자 계획대로 꾸준히 해나가는 스타일이라 내 즉흥적인 토론 제안이 흐름을 끊는 것처럼 느껴질 수 있어요. 대화 시간을 미리 약속해두면 좋아요." },
  TBCG: { emoji: "🚀", name: "아이디어 스파크", tagline: "일단 해보자, 답은 가면서 찾는 거야!",
    philosophy: "정답보다 새로운 도전을 존중하는 교실이 좋은 교육이라고 믿어요.",
    style: "마감이 다가오면 번뜩이는 아이디어와 추진력으로 결과를 만들어내요. 팀에서는 아이디어를 던지는 역할이에요.",
    strengths: ["발상 전환과 아이디어 뱅크", "도전정신과 추진력", "위기 상황에서의 순발력"],
    caution: "아이디어는 많은데 마무리가 약할 수 있어요.",
    tip: "아이디어 3개 중 1개만 골라서 끝까지 완성해보세요.",
    matchWhy: "내 아이디어를 차곡차곡 정리해주고 팀 분위기도 챙겨줘요.",
    clashWhy: "조용히 자기 계획대로 가는 스타일이라 내 즉흥적인 에너지가 소란스럽게 느껴질 수 있어요. 아이디어는 정리해서 한 번에 전달해보세요." },
  TBCH: { emoji: "🎈", name: "응원단장", tagline: "분위기가 좋으면 점수도 따라와!",
    philosophy: "즐거움과 응원이 학습 동기의 연료라고 믿어요. 웃으면서 배운 건 오래 남아요.",
    style: "친구들과 웃으며 공부하고, 하고 싶을 때 확 몰입해요. 모두를 신나게 만드는 에너지가 있어요.",
    strengths: ["친화력과 긍정 에너지", "분위기를 띄우는 능력", "친구의 동기부여를 도와줘요"],
    caution: "즐거움에 취해 중요한 일을 미룰 수 있어요.",
    tip: "응원받고 싶은 목표를 친구들 앞에서 공개 선언해보세요.",
    matchWhy: "내 에너지를 목표로 이끌어주는 사람이 있으면 분위기가 결과로 이어져요.",
    clashWhy: "혼자 계획대로 달리는 스타일이라 내 즉흥 수다가 방해처럼 느껴질 수 있어요. 공부 중에는 '쉬는 시간에 얘기하자'를 약속해보세요." },
  SPLG: { emoji: "📚", name: "만점 설계자", tagline: "계획대로, 목표대로, 정확하게!",
    philosophy: "체계와 꾸준함이 가장 공정한 실력이라고 믿어요. 노력은 계획 위에서 빛나요.",
    style: "혼자서 오답노트, 주간 계획, 목표 점수를 꼼꼼하게 관리해요. 흔들리지 않는 루틴이 최고의 무기예요.",
    strengths: ["철저한 자기관리", "정확한 분석과 오답 정리", "흔들리지 않는 꾸준함"],
    caution: "완벽주의 때문에 쉽게 지칠 수 있어요.",
    tip: "일주일에 한 번은 '계획 없는 시간'을 의도적으로 만들어보세요.",
    matchWhy: "같은 혼자파이면서 호기심으로 내 공부에 재미와 깊이를 더해줘요.",
    clashWhy: "시끌벅적한 즉흥 에너지가 내 계획된 리듬을 흔들 수 있어요. 함께할 땐 '함께하는 시간'을 미리 정해두면 편해요." },
  SPLH: { emoji: "🕯️", name: "도서관 지킴이", tagline: "천천히, 깊게, 내 페이스대로!",
    philosophy: "서두르지 않고 이해하는 깊이가 교육의 본질이라고 믿어요.",
    style: "조용한 공간에서 개념을 천천히 곱씹으며 정리해요. 안정적인 루틴 속에서 가장 편안해요.",
    strengths: ["깊이 있는 이해", "차분한 몰입", "안정적인 루틴"],
    caution: "혼자만의 공부가 길어져 교류가 부족해질 수 있어요.",
    tip: "한 달에 한 번, 배운 내용을 누군가에게 설명해보세요.",
    matchWhy: "짧고 강한 집중력이 차분한 내 공부에 추진력을 보태줘요.",
    clashWhy: "즉흥적이고 시끌벅적한 아이디어 폭풍에 에너지가 금방 소진될 수 있어요. 대화는 짧게, 정해진 시간에만 하는 걸 추천해요." },
  SPCG: { emoji: "🖍️", name: "컬러 노트 장인", tagline: "예쁘게 정리하면 머리에도 쏙!",
    philosophy: "자기만의 표현 방식을 존중하는 교육이 좋은 교육이라고 믿어요.",
    style: "색, 도식, 마인드맵으로 혼자 정리하고 계획대로 복습해요. 눈에 보이는 결과물이 곧 성취감이에요.",
    strengths: ["시각적 정리와 요약 능력", "꾸준한 복습 루틴", "완성도 높은 결과물"],
    caution: "꾸미기에 시간을 너무 많이 쓸 수 있어요.",
    tip: "내용을 먼저 채우고, 꾸미기는 나중에 하는 규칙을 만들어보세요.",
    matchWhy: "같은 감각파라 서로의 노트와 아이디어에서 영감을 주고받아요.",
    clashWhy: "즉흥적인 토론 요청이 내 정리 흐름을 끊는 것처럼 느껴질 수 있어요. 토론은 정리가 끝난 뒤로 약속해보세요." },
  SPCH: { emoji: "🌙", name: "감성 다이어리 학자", tagline: "나만의 속도로 의미를 모아가요.",
    philosophy: "배움은 삶의 의미와 연결될 때 오래 남는다고 믿어요.",
    style: "공부 일기를 쓰며 배운 것의 의미를 기록해요. 감정과 이해가 이어질 때 공부가 가장 잘돼요.",
    strengths: ["의미를 연결하는 힘", "섬세한 감수성", "꾸준한 기록 습관"],
    caution: "감정 상태에 따라 공부 효율의 기복이 있을 수 있어요.",
    tip: "기분이 좋든 나쁘든 '오늘 배운 것 한 줄 요약'은 꼭 남겨보세요.",
    matchWhy: "도전적인 시도로 내 안전지대 밖의 자극을 주고, 나는 그걸 차분히 기록해요.",
    clashWhy: "빠르고 직설적인 토론 속도에 마음이 지칠 수 있어요. 의견은 글이나 메시지로 나눠보는 것도 방법이에요." },
  SBLG: { emoji: "🎯", name: "벼락 저격수", tagline: "필요한 건 정확히, 한 방에!",
    philosophy: "효율과 집중이 핵심이라고 믿어요. 불필요한 것은 과감히 줄이는 교육이 좋아요.",
    style: "평소엔 에너지를 아끼다가 시험 직전 핵심만 뽑아 몰입해요. 짧은 시간에 큰 성과를 내는 타입이에요.",
    strengths: ["핵심을 꿰뚫는 판단력", "폭발적인 집중력", "효율적인 시간 활용"],
    caution: "기초 개념에 구멍이 생길 수 있어요.",
    tip: "하루 15분, 기초 개념 점검 시간을 고정해보세요.",
    matchWhy: "차분하게 기본기를 받쳐줘서 내 집중력이 헛돌지 않아요.",
    clashWhy: "감정과 과정을 세심하게 챙기는 스타일이라 내겐 느리게 느껴질 수 있어요. 상대의 방식에는 '결과보다 과정을 중시하는구나' 하고 이해해보세요." },
  SBLH: { emoji: "🔭", name: "호기심 탐험가", tagline: "궁금하면 끝까지 간다!",
    philosophy: "교육의 목적은 호기심을 지켜주는 것이라고 믿어요.",
    style: "흥미가 생기면 밤새 혼자 파고들고, 관심이 없으면 손이 안 가요. 스스로 의미를 찾을 때 가장 크게 성장해요.",
    strengths: ["깊이 있는 탐구", "자기주도 학습", "독창적인 연결과 통찰"],
    caution: "흥미 없는 과목을 방치하기 쉬워요.",
    tip: "싫어하는 과목을 내가 좋아하는 주제와 연결해서 공부해보세요.",
    matchWhy: "내 호기심을 성과로 이어주는 설계 감각을 빌릴 수 있어요.",
    clashWhy: "일정과 연출을 앞세우는 스타일이라 원리를 파고들 시간이 부족해질 수 있어요. '탐구 시간'을 먼저 확보해두면 갈등이 줄어요." },
  SBCG: { emoji: "🎮", name: "게임 체인저", tagline: "룰이 바뀌면 내가 먼저 뛰어든다!",
    philosophy: "정해진 길보다 새 길을 개척하는 학생을 키우는 교육이 좋다고 믿어요.",
    style: "도전 과제와 챌린지를 좋아하고, 남들과 다른 방법으로 짧게 몰입해서 성과를 내요.",
    strengths: ["도전정신", "독창적인 풀이", "승부처에서의 집중력"],
    caution: "혼자 밀어붙이다 협업 기회를 놓칠 수 있어요.",
    tip: "중요한 결정 전에 한 명에게라도 의견을 물어보세요.",
    matchWhy: "내 도전을 차분히 정리하고 기록해줘서 성과가 흩어지지 않아요.",
    clashWhy: "세심한 조언이 간섭으로 들릴 수 있어요. 도움이 필요할 땐 내가 먼저 요청하는 방식으로 선을 정해보세요." },
  SBCH: { emoji: "🦋", name: "자유로운 몽상가", tagline: "영감이 오는 순간이 공부 타임!",
    philosophy: "배움은 자유롭게 상상할 때 피어난다고 믿어요. 틀 없는 교실이 좋은 교실이에요.",
    style: "기분과 영감에 따라 몰입하고, 산책하다 떠오른 아이디어를 정리하면서 공부해요.",
    strengths: ["풍부한 상상력", "섬세한 감수성", "독창적인 표현력"],
    caution: "루틴이 부족해 마감에 쫓길 수 있어요.",
    tip: "영감 메모장을 만들고, 하루 한 번 고정된 공부 시간을 정해보세요.",
    matchWhy: "내 상상을 예쁘게 정리해서 결과물로 만들어줘요.",
    clashWhy: "일정표와 역할 분담 중심의 방식이 숨 막히게 느껴질 수 있어요. 마감일만 공유하고 과정은 서로 존중해보세요." }
};

/* ===================== 축 / 질문 ===================== */
/*
  4개의 축으로 16유형을 만들어요.
  1) 공부 방식  T 함께 / S 혼자
  2) 공부 리듬  P 계획 / B 몰입(몰아서)
  3) 이해 방식  L 논리 / C 창의
  4) 공부 동기  G 성취 / H 마음
  각 질문의 4가지 선택지는 두 축의 조합(2×2)이에요. 예) "TP" = 함께 + 계획
  모든 축의 투표 수가 홀수(11, 9, 11, 9)라서 동점이 나오지 않아요.
*/
const AXES = [
  { a: "T", b: "S", name: { T: "함께", S: "혼자" }, emo: { T: "🤝", S: "🧍" } },
  { a: "P", b: "B", name: { P: "계획", B: "몰입" }, emo: { P: "📅", B: "🔥" } },
  { a: "L", b: "C", name: { L: "논리", C: "창의" }, emo: { L: "📐", C: "🎨" } },
  { a: "G", b: "H", name: { G: "성취", H: "마음" }, emo: { G: "🏆", H: "🌱" } }
];
const FLIP = { T: "S", S: "T", P: "B", B: "P", L: "C", C: "L", G: "H", H: "G" };

// 선택지: [축 조합, 이모지, 문장]
const QUESTIONS = [
  { q: "시험 전날 밤, 당신의 공부법은?", o: [
    ["TP", "📞", "스터디 친구들과 정해둔 시간표대로 마지막 문제를 같이 점검한다"],
    ["TB", "🌙", "친구와 밤새 통화하며 핵심만 서로 문제 내준다"],
    ["SP", "📋", "혼자 체크리스트를 확인하며 계획대로 차분히 마무리한다"],
    ["SB", "⚡", "조용히 혼자 밤새 핵심만 골라 몰아서 집중한다"] ] },
  { q: "이해가 안 되는 단원을 만났을 때?", o: [
    ["TL", "🙋", "친구에게 물어서 개념과 풀이 과정을 같이 따져본다"],
    ["TC", "🗣️", "친구와 그림, 예시, 비유로 이야기하며 이해해본다"],
    ["SL", "📖", "혼자 교재를 읽으며 원리를 차근차근 따져본다"],
    ["SC", "✏️", "혼자 낙서와 마인드맵으로 그려가며 이해한다"] ] },
  { q: "내가 공부하는 가장 큰 이유는?", o: [
    ["LG", "🎓", "원하는 성적과 진학, 자격증을 얻기 위해서"],
    ["LH", "🌍", "세상의 원리를 알아가는 지적 즐거움을 위해서"],
    ["CG", "🚀", "내 아이디어를 인정받고 꿈을 이루기 위해서"],
    ["CH", "🎨", "상상하고 표현하는 즐거움을 위해서"] ] },
  { q: "팀플에서 갈등이 생겼을 때?", o: [
    ["TG", "📣", "다 같이 모여 결과물과 마감 기준을 확실히 정하고 정리한다"],
    ["TH", "☕", "다 같이 모여 서로의 속마음부터 이야기해본다"],
    ["SG", "🧩", "일단 각자 할 일을 나눠 맡고 결과물만 합친다"],
    ["SH", "💌", "따로 한 명씩 조용히 만나 마음을 풀어준다"] ] },
  { q: "공부 계획은 어떻게 세우나요?", o: [
    ["PL", "🗓️", "목표를 쪼개 정리한 체계적인 주간 계획표"],
    ["PC", "🌈", "색깔 스티커와 그림으로 꾸민 나만의 플래너"],
    ["BL", "🎛️", "큰 목표만 정해두고 상황에 맞춰 효율적으로 조정"],
    ["BC", "🌊", "그날 기분과 영감에 따라 자유롭게 정한다"] ] },
  { q: "과제 마감이 일주일 남았다면?", o: [
    ["TP", "👥", "팀원들과 일정표를 짜서 이미 절반쯤 진행해놨다"],
    ["TB", "🔥", "팀원들을 불러 모아 마감 직전에 다 같이 폭발적으로 끝낸다"],
    ["SP", "🐢", "혼자 미리 조금씩 해둬서 거의 끝나간다"],
    ["SB", "🦸", "아직 시작 전이지만 혼자 밤새 해치울 자신이 있다"] ] },
  { q: "시험 한 달 전, 나의 공부 방식은?", o: [
    ["PG", "🎯", "목표 점수를 정하고 매일 계획표대로 달성해간다"],
    ["PH", "🌱", "매일 조금씩 이해하는 즐거움을 느끼며 꾸준히 한다"],
    ["BG", "⏳", "평소엔 여유롭다가 마감 직전에 목표 점수를 위해 집중한다"],
    ["BH", "🔭", "호기심이 생길 때만 푹 빠져서 신나게 공부한다"] ] },
  { q: "배운 내용을 정리하는 방법은?", o: [
    ["TL", "🧑‍🏫", "친구에게 논리적으로 설명하면서 구조를 잡는다"],
    ["TC", "📚", "친구에게 이야기처럼 풀어서 설명하며 정리한다"],
    ["SL", "🗂️", "혼자 깔끔한 표와 개조식 노트로 정리한다"],
    ["SC", "🖍️", "혼자 색깔 펜과 그림으로 나만의 노트를 만든다"] ] },
  { q: "내가 존경하는 선생님은 어떤 분인가요?", o: [
    ["LG", "🧭", "체계적인 설명으로 목표까지 이끌어주는 선생님"],
    ["LH", "❓", "질문을 잘 받아주고 깊이 생각하게 해주는 선생님"],
    ["CG", "🎪", "창의적인 수업으로 도전과 성과를 끌어내는 선생님"],
    ["CH", "🤗", "학생의 마음과 개성을 소중히 대해주는 선생님"] ] },
  { q: "시험 결과를 받았을 때, 나는?", o: [
    ["TG", "🏁", "친구들과 점수를 비교하며 다음 목표를 세운다"],
    ["TH", "💬", "친구들과 어떤 부분이 이해됐는지 이야기를 나눈다"],
    ["SG", "📊", "혼자 점수를 분석해 목표 대비 부족한 부분을 확인한다"],
    ["SH", "🌤️", "혼자 오답을 보며 내가 얼마나 성장했는지 돌아본다"] ] },
  { q: "새 학기, 새 교과서를 받았다면?", o: [
    ["PL", "📑", "목차를 보고 전체 진도 계획부터 짠다"],
    ["PC", "🎀", "표지를 꾸미고 단원마다 색깔 인덱스를 붙인다"],
    ["BL", "⏩", "핵심 개념만 빠르게 훑고 시험 전에 몰입한다"],
    ["BC", "🧭", "끌리는 단원부터 마음 가는 대로 펼쳐본다"] ] },
  { q: "발표 수업이 있다면 어떤 방식이 좋아요?", o: [
    ["TL", "📈", "모둠이 근거와 데이터를 나눠 맡아 탄탄하게 발표한다"],
    ["TC", "🎭", "모둠이 연극이나 영상처럼 재미있게 연출해서 발표한다"],
    ["SL", "🔎", "혼자 자료를 꼼꼼히 조사해서 논리적으로 발표한다"],
    ["SC", "🖼️", "혼자 스토리와 시각 자료를 만들어 개성 있게 발표한다"] ] },
  { q: "방학 공부는 어떻게 하는 편인가요?", o: [
    ["TP", "🏫", "스터디 모임을 만들어 매주 같은 요일, 같은 시간에 한다"],
    ["TB", "🎉", "친구들과 꽂힐 때 몰아서 같이 하고, 쉴 땐 다 같이 논다"],
    ["SP", "⏰", "혼자 시간표를 짜서 매일 같은 시간에 꾸준히 한다"],
    ["SB", "🏖️", "혼자 몰입할 땐 몰아서, 쉴 땐 확실히 쉰다"] ] },
  { q: "도저히 공부가 안 되는 날, 나는?", o: [
    ["TG", "💪", "스터디 친구를 불러 같이 오늘 목표량을 채운다"],
    ["TH", "🫂", "친구에게 힘들다고 털어놓고 같이 쉰다"],
    ["SG", "😤", "혼자 이를 악물고 오늘 목표량은 끝낸다"],
    ["SH", "🛌", "혼자 컨디션부터 돌보며 잠시 쉬어간다"] ] },
  { q: "갑자기 시험 범위가 바뀌었다면?", o: [
    ["PL", "🧮", "침착하게 계획표를 논리적으로 다시 짠다"],
    ["PC", "🖊️", "새 계획표를 색깔별로 예쁘게 다시 만들며 마음을 가다듬는다"],
    ["BL", "🔬", "바뀐 범위의 핵심만 빠르게 분석해서 집중한다"],
    ["BC", "😎", "오히려 좋아! 새로운 방식으로 재미있게 공부해본다"] ] },
  { q: "내가 선생님이 된다면 어떤 수업을 하고 싶나요?", o: [
    ["LG", "📐", "명확한 목표와 평가 기준이 있는 체계적인 수업"],
    ["LH", "🔭", "원리를 함께 탐구하며 호기심을 키워주는 수업"],
    ["CG", "🏆", "프로젝트 결과물로 성취감을 느끼게 하는 수업"],
    ["CH", "🌻", "학생 한 명 한 명의 이야기를 존중하는 자유로운 수업"] ] },
  { q: "문제를 풀다가 막혔을 때?", o: [
    ["TL", "🧠", "친구와 풀이를 단계별로 되짚어본다"],
    ["TC", "💡", "친구와 엉뚱한 방법들을 던져가며 시도해본다"],
    ["SL", "🔙", "혼자 풀이를 거꾸로 추적하며 오류를 찾는다"],
    ["SC", "🌀", "혼자 완전히 다른 관점으로 새롭게 접근해본다"] ] },
  { q: "하루 공부를 끝낸 뒤 나의 모습은?", o: [
    ["PG", "✅", "오늘 계획한 분량을 채웠는지 체크하며 뿌듯해한다"],
    ["PH", "📔", "오늘 배운 것을 일기처럼 기록하며 하루를 정리한다"],
    ["BG", "🌟", "오늘 몰입해서 큰 성과를 낸 것에 만족한다"],
    ["BH", "😊", "재미있었던 순간을 떠올리며 흐뭇해한다"] ] },
  { q: "나의 노트 필기 스타일은?", o: [
    ["PL", "📏", "항상 같은 형식으로 깔끔하게 개조식으로 정리한다"],
    ["PC", "🧶", "매번 같은 색 규칙으로 마인드맵을 그린다"],
    ["BL", "⚡", "핵심 키워드만 빠르게 메모한다"],
    ["BC", "🎨", "그림, 화살표, 낙서가 자유롭게 섞여 있다"] ] },
  { q: "이상적인 학습 환경은?", o: [
    ["TG", "🏟️", "서로 경쟁하며 자극받는 스터디 모임"],
    ["TH", "🍪", "서로 응원해주는 따뜻한 스터디 모임"],
    ["SG", "🎧", "목표만 보고 집중할 수 있는 독서실"],
    ["SH", "🛋️", "나만의 속도로 편하게 할 수 있는 내 방"] ] }
];

/* ===================== 유형 / 캐릭터 ===================== */
const CODES = Object.keys(TYPES);
CODES.forEach((c, i) => {
  const h = Math.round(i * 22.5 + 215) % 360;
  TYPES[c].main = "hsl(" + h + ", 78%, 66%)";
  TYPES[c].tint = "hsl(" + h + ", 100%, 94%)";
  TYPES[c].emoji = ANIMAL[c][1];
  TYPES[c].animal = ANIMAL[c][2];
});

const bestOf = (c) => c[0] + FLIP[c[1]] + c[2] + FLIP[c[3]];     // 리듬·동기만 반대 = 서로 보완
const worstOf = (c) => c.split("").map(l => FLIP[l]).join("");   // 네 축이 모두 반대

/* ===================== 상태 ===================== */
const $ = (id) => document.getElementById(id);
const screens = { intro: $("screen-intro"), quiz: $("screen-quiz"), result: $("screen-result") };
let current = 0;
let answers = [];     // 문항별로 고른 선택지 index
let orders = [];      // 문항별 선택지 표시 순서(섞기)
let myCode = null;
let myCounts = null;
let viewCode = null;

function show(name) {
  Object.values(screens).forEach(s => s.classList.remove("active"));
  screens[name].classList.add("active");
  window.scrollTo({ top: 0, behavior: "smooth" });
}

function shuffle(arr) {
  const a = arr.slice();
  for (let i = a.length - 1; i > 0; i--) {
    const j = Math.floor(Math.random() * (i + 1));
    [a[i], a[j]] = [a[j], a[i]];
  }
  return a;
}

/* 인트로 캐릭터 */
$("cast").innerHTML = ["TPLG", "SBLG", "TBLH", "SBLH", "SPCG", "SBCH"].map(c =>
  '<div class="c" style="background:' + TYPES[c].main + '">' + characterSVG(c) + '</div>').join("");

/* ===================== 질문 ===================== */
function renderQuestion() {
  const total = QUESTIONS.length;
  const item = QUESTIONS[current];
  $("q-text").textContent = item.q;
  $("progress-count").textContent = (current + 1) + " / " + total;
  $("progress-bar").style.width = (current / total * 100) + "%";
  $("progress").setAttribute("aria-valuenow", current);
  $("btn-back").disabled = current === 0;

  const box = $("q-options");
  box.innerHTML = "";
  orders[current].forEach(idx => {
    const opt = item.o[idx];
    const btn = document.createElement("button");
    btn.type = "button";
    btn.className = "option" + (answers[current] === idx ? " picked" : "");
    btn.innerHTML = '<span class="emo" aria-hidden="true">' + opt[1] + '</span><span>' + opt[2] + '</span>';
    btn.addEventListener("click", () => choose(idx, btn));
    box.appendChild(btn);
  });
}

function choose(idx, btn) {
  answers[current] = idx;
  box_clear_picked();
  btn.classList.add("picked");
  setTimeout(() => {
    if (current < QUESTIONS.length - 1) {
      current++;
      renderQuestion();
    } else {
      $("progress-bar").style.width = "100%";
      finish();
    }
  }, 240);
}
function box_clear_picked() {
  document.querySelectorAll("#q-options .option").forEach(b => b.classList.remove("picked"));
}

function finish() {
  const counts = {};
  "TSPBLCGH".split("").forEach(l => counts[l] = 0);
  answers.forEach((idx, qi) => {
    QUESTIONS[qi].o[idx][0].split("").forEach(l => counts[l]++);
  });
  myCounts = counts;
  myCode = AXES.map(ax => counts[ax.a] >= counts[ax.b] ? ax.a : ax.b).join("");
  viewCode = myCode;
  renderResult(true);
}

/* ===================== 결과 ===================== */
function renderResult(animate) {
  const code = viewCode;
  const t = TYPES[code];
  const isMine = code === myCode;
  const best = bestOf(code), worst = worstOf(code);

  let bar = "";
  if (myCode && !isMine) {
    bar = '<div class="viewing"><span>지금은 다른 캐릭터를 보고 있어요</span>' +
          '<button class="btn small ghost" data-code="' + myCode + '">내 결과로 돌아가기</button></div>';
  } else if (!myCode) {
    bar = '<div class="viewing"><span>16마리 캐릭터 미리보기</span>' +
          '<button class="btn small" id="bar-start">테스트 시작하기</button></div>';
  }
  $("viewing-bar").innerHTML = bar;
  if ($("bar-start")) $("bar-start").addEventListener("click", startQuiz);

  const matchCard = (c, kind) => {
    const m = TYPES[c];
    const clash = kind === "clash";
    return '<button class="match' + (clash ? ' clash' : '') + '" data-code="' + c + '">' +
      '<span class="m-emo" style="background:' + m.main + '">' + characterSVG(c) + '</span>' +
      '<span><span class="m-label">' + (clash ? "안 맞는 유형" : "찰떡 궁합") + '</span>' +
      '<span class="m-name">' + m.name + ' (' + c + ')</span>' +
      '<span class="m-why">' + (clash ? t.clashWhy : t.matchWhy) + '</span>' +
      '<span class="m-more">이 캐릭터 카드 보기</span></span></button>';
  };

  let axesHtml = "";
  if (isMine) {
    axesHtml = '<div><h3>내 성향 분포</h3><div class="axes">' + AXES.map(ax => {
      const a = myCounts[ax.a], b = myCounts[ax.b];
      const pa = Math.round(a / (a + b) * 100), pb = 100 - pa;
      const winA = a >= b;
      return '<div class="axis"><div class="labels">' +
        '<span class="' + (winA ? "" : "dim") + '">' + (winA ? "<b>" : "") + ax.emo[ax.a] + " " + ax.name[ax.a] + " " + pa + "%" + (winA ? "</b>" : "") + '</span>' +
        '<span class="' + (winA ? "dim" : "") + '">' + (winA ? "" : "<b>") + pb + "% " + ax.name[ax.b] + " " + ax.emo[ax.b] + (winA ? "" : "</b>") + '</span></div>' +
        '<div class="track"><div class="fill" data-w="' + pa + '"></div></div></div>';
    }).join("") + '</div></div>';
  }

  const codeLabels = code.split("").map((l, i) => AXES[i].name[l]).join(" · ");

  $("result-card").innerHTML =
    '<article class="card' + (animate ? ' flip-in' : '') + '" style="--main:' + t.main + ';--tint:' + t.tint + '">' +
      '<div class="card-head">' +
        '<div class="badge">' + characterSVG(code) + '</div>' +
        '<div class="pre">' + (isMine ? "나의 공부 · 교육관 유형은" : "공부 · 교육관 유형") + '</div>' +
        '<div class="code">' + code + '</div>' +
        '<h2>' + t.name + '</h2>' +
        '<div class="tagline">' + t.tagline + '</div>' +
        '<div class="pre" style="margin-top:6px">' + t.emoji + ' ' + t.animal + ' 캐릭터 · ' + codeLabels + '</div>' +
      '</div>' +
      '<div class="card-body">' +
        '<div class="philosophy"><h3>나의 교육관</h3><p>' + t.philosophy + '</p></div>' +
        '<div><h3>공부 스타일</h3><p>' + t.style + '</p></div>' +
        '<div class="two-col">' +
          '<div><h3>강점</h3><ul>' + t.strengths.map(s => '<li>' + s + '</li>').join("") + '</ul></div>' +
          '<div><h3>조심할 점</h3><p>' + t.caution + '</p></div>' +
        '</div>' +
        '<div><h3>추천 공부 팁</h3><p>' + t.tip + '</p></div>' +
        '<div class="pair">' + matchCard(best, "match") + matchCard(worst, "clash") + '</div>' +
        axesHtml +
      '</div>' +
    '</article>';

  $("result-actions").innerHTML = myCode
    ? '<button class="btn small" id="btn-share">내 결과 복사하기</button><button class="btn small ghost" id="btn-retry">다시 테스트하기</button>'
    : '<button class="btn small" id="btn-start2">테스트 시작하기</button><button class="btn small ghost" id="btn-home">처음으로</button>';
  if ($("btn-share")) $("btn-share").addEventListener("click", copyShare);
  if ($("btn-retry")) $("btn-retry").addEventListener("click", restart);
  if ($("btn-start2")) $("btn-start2").addEventListener("click", startQuiz);
  if ($("btn-home")) $("btn-home").addEventListener("click", () => show("intro"));

  renderGallery();
  show("result");

  if (isMine) {
    requestAnimationFrame(() => setTimeout(() => {
      document.querySelectorAll(".axis .fill").forEach(el => { el.style.width = el.dataset.w + "%"; });
    }, 350));
  }
}

function renderGallery() {
  $("gallery").innerHTML = CODES.map(c => {
    const t = TYPES[c];
    return '<button class="g-item' + (c === myCode ? ' mine' : '') + '" data-code="' + c + '" aria-label="' + t.name + ' ' + c + '">' +
      '<span class="g-emo">' + characterSVG(c) + '</span>' +
      '<span class="g-name">' + t.name + '</span>' +
      '<span class="g-code">' + c + '</span></button>';
  }).join("");
}

/* ===================== 이벤트 ===================== */
document.addEventListener("click", (e) => {
  const el = e.target.closest("[data-code]");
  if (!el) return;
  viewCode = el.dataset.code;
  renderResult(true);
});

function toast(msg) {
  const el = $("toast");
  el.textContent = msg;
  el.classList.add("show");
  clearTimeout(toast._t);
  toast._t = setTimeout(() => el.classList.remove("show"), 2200);
}

function shareText() {
  const t = TYPES[myCode], b = TYPES[bestOf(myCode)], w = TYPES[worstOf(myCode)];
  return "나의 공부 · 교육관 유형은 " + t.emoji + " " + t.name + " (" + myCode + ")!\n" +
         t.tagline + "\n" +
         "찰떡 궁합: " + b.emoji + " " + b.name + " / 안 맞는 유형: " + w.emoji + " " + w.name + "\n" +
         "너는 어떤 유형일까? " + location.href;
}

async function copyShare() {
  const text = shareText();
  try {
    await navigator.clipboard.writeText(text);
    toast("결과가 복사되었어요!");
  } catch (err) {
    const ta = document.createElement("textarea");
    ta.value = text; document.body.appendChild(ta); ta.select();
    try { document.execCommand("copy"); toast("결과가 복사되었어요!"); }
    catch (e2) { toast("복사에 실패했어요. 직접 선택해서 복사해주세요."); }
    document.body.removeChild(ta);
  }
}

function startQuiz() {
  current = 0; answers = []; myCode = null; myCounts = null; viewCode = null;
  orders = QUESTIONS.map(() => shuffle([0, 1, 2, 3]));
  renderQuestion();
  show("quiz");
}

function restart() {
  current = 0; answers = []; myCode = null; myCounts = null; viewCode = null;
  show("intro");
}

$("btn-start").addEventListener("click", startQuiz);
$("btn-browse").addEventListener("click", () => { myCode = null; viewCode = CODES[0]; renderResult(false); });
$("btn-back").addEventListener("click", () => { if (current > 0) { current--; renderQuestion(); } });

</script>
</body>
</html>
