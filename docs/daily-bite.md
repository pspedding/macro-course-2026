# 🎮 Daily Bite

*One 10-minute macro workout: one concept, five quick questions, confidence check, and gentle XP/streak tracking.*

<div id="daily-bite-app" class="daily-bite-shell">
  <section class="db-hero">
    <div>
      <div class="db-kicker">Today's bite</div>
      <h2 id="db-title">Loading your bite…</h2>
      <p id="db-subtitle">Pulling a small practice set from the existing flashcard bank.</p>
    </div>
    <div class="db-stats-card">
      <div><span id="db-xp">0</span><small>XP</small></div>
      <div><span id="db-streak">0</span><small>day streak</small></div>
      <div><span id="db-ready">0%</span><small>mastery</small></div>
    </div>
  </section>

  <section class="db-controls">
    <label for="db-module">Focus:</label>
    <select id="db-module">
      <option value="daily">Daily recommended</option>
      <option value="weak">Weakest module</option>
      <option value="random">Random module</option>
    </select>
    <button id="db-new-bite" type="button">Generate bite</button>
    <button id="db-reset-today" type="button" class="secondary">Reset this bite</button>
  </section>

  <section class="db-card db-concept-card">
    <div class="db-label">1. Key concept</div>
    <div id="db-concept">Loading…</div>
  </section>

  <section class="db-card" id="db-visual-card" style="display:none;">
    <div class="db-label">2. Visual anchor</div>
    <div id="db-visual"></div>
  </section>

  <section class="db-card">
    <div class="db-label">3. Quick quiz</div>
    <div id="db-questions"></div>
    <div id="db-complete" class="db-complete" style="display:none;"></div>
  </section>

  <section class="db-card">
    <div class="db-label">4. Exam trap</div>
    <p id="db-trap">Answer first, then explain the economic mechanism. In exams, marks often sit in the “why”, not just the final number or letter.</p>
  </section>

  <section class="db-card db-mastery-card">
    <div class="db-label">Mastery map</div>
    <div id="db-mastery-map"></div>
  </section>
</div>

<style>
.daily-bite-shell { --db-primary:#5c6bc0; --db-ink:#1f2937; --db-muted:#667085; --db-soft:#f5f7ff; --db-border:#dbe1f3; }
.db-hero { display:flex; justify-content:space-between; gap:1rem; align-items:stretch; padding:1.2rem; border-radius:16px; background:linear-gradient(135deg,#eef2ff,#f8fafc); border:1px solid var(--db-border); margin:1rem 0; }
.db-kicker,.db-label { font-size:0.78rem; font-weight:700; letter-spacing:.08em; text-transform:uppercase; color:var(--db-primary); margin-bottom:.35rem; }
.db-hero h2 { margin:.1rem 0 .35rem; }
.db-hero p { margin:0; color:var(--db-muted); }
.db-stats-card { min-width:230px; display:grid; grid-template-columns:repeat(3,1fr); gap:.5rem; }
.db-stats-card div { background:white; border:1px solid var(--db-border); border-radius:12px; padding:.75rem; text-align:center; }
.db-stats-card span { display:block; font-weight:800; font-size:1.35rem; color:var(--db-ink); }
.db-stats-card small { color:var(--db-muted); font-size:.72rem; }
.db-controls { display:flex; flex-wrap:wrap; gap:.6rem; align-items:center; margin:1rem 0; }
.db-controls select,.db-controls button { padding:.48rem .75rem; border-radius:8px; border:1px solid var(--db-border); }
.db-controls button { background:var(--db-primary); color:white; cursor:pointer; font-weight:700; }
.db-controls button.secondary { background:#eef2f7; color:#344054; }
.db-card { background:white; border:1px solid var(--db-border); border-radius:14px; padding:1rem; margin:1rem 0; box-shadow:0 1px 2px rgba(16,24,40,.04); }
.db-concept-title { font-weight:800; font-size:1.1rem; margin-bottom:.35rem; }
.db-chip { display:inline-block; background:var(--db-soft); color:#3949ab; border:1px solid #c7d2fe; border-radius:999px; padding:.15rem .55rem; margin:.15rem .25rem .15rem 0; font-size:.78rem; font-weight:700; }
.db-question { border-top:1px solid #edf0f7; padding:1rem 0; }
.db-question:first-child { border-top:none; padding-top:.2rem; }
.db-q-meta { color:var(--db-muted); font-size:.78rem; margin-bottom:.35rem; }
.db-q-text { font-weight:700; margin-bottom:.6rem; }
.db-option { display:block; width:100%; text-align:left; background:#f8fafc; border:1px solid #d0d5dd; border-radius:9px; padding:.62rem .75rem; margin:.4rem 0; cursor:pointer; }
.db-option:hover { border-color:var(--db-primary); background:#f5f7ff; }
.db-option.correct { background:#ecfdf3; border-color:#12b76a; }
.db-option.incorrect { background:#fff1f3; border-color:#f04438; }
.db-feedback { margin-top:.65rem; padding:.7rem; border-radius:9px; background:#f8fafc; color:#344054; display:none; }
.db-confidence { display:flex; flex-wrap:wrap; gap:.4rem; margin-top:.65rem; }
.db-confidence button { border:1px solid #d0d5dd; background:white; border-radius:999px; padding:.35rem .6rem; cursor:pointer; font-size:.82rem; }
.db-confidence button.selected { background:#eef2ff; border-color:var(--db-primary); color:#3949ab; font-weight:700; }
.db-complete { margin-top:1rem; padding:.9rem; border-radius:12px; background:#ecfdf3; border:1px solid #12b76a; }
.db-mastery-row { display:flex; align-items:center; gap:.55rem; margin:.42rem 0; }
.db-mastery-row span { width:3.2rem; font-weight:700; font-size:.84rem; }
.db-bar { flex:1; height:.55rem; background:#eef2f7; border-radius:999px; overflow:hidden; }
.db-bar > div { height:100%; background:linear-gradient(90deg,#5c6bc0,#12b76a); }
.db-visual-img { max-width:100%; border-radius:12px; border:1px solid var(--db-border); background:white; }
@media (max-width: 720px) { .db-hero { flex-direction:column; } .db-stats-card { min-width:0; } }
</style>

<script>
(function() {
  const STORAGE_KEY = 'macro-daily-bite-v1';
  const todayKey = () => new Date().toISOString().slice(0, 10);
  const moduleNames = {
    M01:'Measurement & GDP', M02:'Inflation & wealth', M03:'Unemployment', M04:'Keynesian model',
    M05:'Fiscal, money & RBA', M06:'Monetary policy', M07:'AD-AS', M08:'Growth basics',
    M09:'Saving & Solow', M10:'Exchange rates', M11:'BOP & capital flows', M12:'Crises',
    M13:'National accounts+', M14:'IS-LM', M15:'Policy in IS-LM', M16:'Phillips curve',
    M17:'IS-LM-PC', M18:'Solow advanced', M19:'Endogenous growth', M20:'Mundell-Fleming', M21:'Open economy synthesis'
  };
  const diagramMap = {
    M01:['Production Possibilities Frontier','assets/diagrams/01-ppf.png'],
    M04:['Keynesian Cross','assets/diagrams/02-keynesian-cross.png'],
    M05:['Money Market','assets/diagrams/03-money-market.png'],
    M07:['AD-AS Model','assets/diagrams/04-ad-as.png'],
    M14:['IS-LM Model','assets/diagrams/05-is-lm.png'],
    M15:['IS-LM Model','assets/diagrams/05-is-lm.png'],
    M16:['Phillips Curve','assets/diagrams/06-phillips-curve.png'],
    M17:['Phillips Curve','assets/diagrams/06-phillips-curve.png'],
    M18:['Solow Growth Model','assets/diagrams/07-solow.png'],
    M20:['Mundell-Fleming Model','assets/diagrams/08-mundell-fleming.png'],
    M21:['Mundell-Fleming Model','assets/diagrams/08-mundell-fleming.png']
  };

  let allCards = [];
  let currentBite = [];
  let answers = {};
  let state = loadState();

  function loadState() {
    try { return JSON.parse(localStorage.getItem(STORAGE_KEY)) || { xp:0, streak:0, lastComplete:null, completed:{}, mastery:{} }; }
    catch(e) { return { xp:0, streak:0, lastComplete:null, completed:{}, mastery:{} }; }
  }
  function saveState() { localStorage.setItem(STORAGE_KEY, JSON.stringify(state)); }
  function hash(str) { let h = 2166136261; for (let i=0;i<str.length;i++) { h ^= str.charCodeAt(i); h += (h<<1)+(h<<4)+(h<<7)+(h<<8)+(h<<24); } return h >>> 0; }
  function rng(seed) { let x = seed || 123456789; return function() { x ^= x << 13; x ^= x >>> 17; x ^= x << 5; return ((x >>> 0) / 4294967296); }; }
  function shuffle(arr, rand) { for (let i=arr.length-1;i>0;i--) { const j=Math.floor(rand()*(i+1)); [arr[i],arr[j]]=[arr[j],arr[i]]; } return arr; }
  function strip(html) { const d=document.createElement('div'); d.innerHTML=html || ''; return d.textContent || d.innerText || ''; }
  function cleanTopic(t) { return (t || 'macro concept').replace(/[-_]/g,' ').replace(/\s+/g,' ').trim().replace(/^./, c => c.toUpperCase()).slice(0, 64); }
  function parseAnswerLetter(card) { const m = (card.back || '').match(/<strong>\s*([A-D])\)/i); return m ? m[1].toUpperCase() : null; }
  function parseMCQ(card) {
    const text = (card.front || '').replace(/<br\s*\/?>/gi, '\n');
    const optionMatches = [...text.matchAll(/(^|\n)\s*([A-D])\)\s*([^\n]+)/g)];
    const letter = parseAnswerLetter(card);
    if (!letter || optionMatches.length < 4) return null;
    const firstOpt = optionMatches[0].index;
    const q = strip(text.slice(0, firstOpt)).replace(/^\[.*?\]\s*/,'').trim();
    const options = optionMatches.slice(0, 4).map(m => ({ letter:m[2].toUpperCase(), text:m[3].trim() }));
    if (!q || options.some(o => !o.text)) return null;
    return { ...card, question:q, options, answerLetter:letter, answerHtml:card.back || '' };
  }
  function usableCards(cards) {
    return cards.map(parseMCQ).filter(Boolean).filter(c =>
      /^M\d\d$/.test(c.module || '') && c.question.length > 10 && c.question.length < 240 &&
      !/[{}]|undefined|null/.test(c.question) && strip(c.answerHtml).length > 15
    );
  }
  function flashcardUrls() {
    const here = new URL(window.location.href);
    const rootPath = here.pathname.replace(/\/daily-bite\/?$/, '/');
    const root = new URL(rootPath, here.origin);
    return [
      new URL('flashcards/', root).href,
      new URL('flashcards/index.html', root).href,
      new URL('../flashcards/', here).href,
      new URL('../flashcards/index.html', here).href
    ].filter((url, idx, arr) => arr.indexOf(url) === idx);
  }
  function extractCardsJson(html) {
    const marker = 'const ALL_CARDS';
    const markerIdx = html.indexOf(marker);
    if (markerIdx < 0) throw new Error('Could not find flashcard data marker');
    const start = html.indexOf('[', markerIdx);
    if (start < 0) throw new Error('Could not find flashcard data start');

    let depth = 0;
    let inString = false;
    let escaped = false;
    for (let i = start; i < html.length; i++) {
      const ch = html[i];
      if (inString) {
        if (escaped) escaped = false;
        else if (ch === '\\') escaped = true;
        else if (ch === '"') inString = false;
      } else {
        if (ch === '"') inString = true;
        else if (ch === '[') depth++;
        else if (ch === ']') {
          depth--;
          if (depth === 0) return html.slice(start, i + 1);
        }
      }
    }
    throw new Error('Could not find flashcard data end');
  }
  async function loadCards() {
    const candidates = flashcardUrls();
    let html = '';
    let lastError = null;

    for (const url of candidates) {
      try {
        const res = await fetch(url, { cache: 'no-store' });
        if (!res.ok) throw new Error(`Could not load ${url}`);
        html = await res.text();
        break;
      } catch (e) {
        lastError = e;
      }
    }

    if (!html) throw lastError || new Error('Could not load flashcard page');
    return usableCards(JSON.parse(extractCardsJson(html)));
  }
  function selectModule(mode) {
    const modules = [...new Set(allCards.map(c => c.module))].sort();
    if (mode === 'random') return modules[Math.floor(Math.random()*modules.length)];
    if (mode === 'weak') {
      return modules.map(m => {
        const s = state.mastery[m] || { attempts:0, correct:0 };
        const score = s.attempts ? s.correct / s.attempts : 0;
        return [m, score, s.attempts];
      }).sort((a,b) => (a[1]-b[1]) || (a[2]-b[2]))[0][0];
    }
    return modules[hash(todayKey()) % modules.length];
  }
  function generateBite() {
    const mode = document.getElementById('db-module').value;
    const module = selectModule(mode);
    const rand = rng(hash(todayKey() + '-' + mode + '-' + module));
    const moduleCards = allCards.filter(c => c.module === module);
    currentBite = shuffle(moduleCards.slice(), rand).slice(0, 5);
    if (currentBite.length < 5) currentBite = currentBite.concat(shuffle(allCards.slice(), rand).slice(0, 5-currentBite.length));
    answers = {};
    renderBite(module);
  }
  function renderStats() {
    document.getElementById('db-xp').textContent = state.xp || 0;
    document.getElementById('db-streak').textContent = state.streak || 0;
    const totals = Object.values(state.mastery || {}).reduce((a,m) => ({ attempts:a.attempts+(m.attempts||0), correct:a.correct+(m.correct||0) }), { attempts:0, correct:0 });
    document.getElementById('db-ready').textContent = totals.attempts ? Math.round((totals.correct/totals.attempts)*100) + '%' : '0%';
    renderMasteryMap();
  }
  function renderBite(module) {
    const anchor = currentBite[0];
    document.getElementById('db-title').textContent = `${module}: ${moduleNames[module] || 'Macro practice'}`;
    document.getElementById('db-subtitle').textContent = 'A bite-sized set from the existing macro flashcard bank.';
    document.getElementById('db-concept').innerHTML = `
      <div class="db-concept-title">${cleanTopic(anchor.topic)}</div>
      <span class="db-chip">${anchor.module}</span><span class="db-chip">${anchor.lesson || 'lesson'}</span><span class="db-chip">${anchor.type}</span>
      <p>${anchor.question}</p>
      <p style="color:#667085;margin-bottom:0;">Goal: answer the questions, then rate whether each answer was guessed, shaky, or confident.</p>`;
    const diag = diagramMap[module];
    const visualCard = document.getElementById('db-visual-card');
    if (diag) {
      visualCard.style.display = '';
      document.getElementById('db-visual').innerHTML = `<p><strong>${diag[0]}</strong></p><img class="db-visual-img" src="../${diag[1]}" alt="${diag[0]}">`;
    } else {
      visualCard.style.display = 'none';
    }
    document.getElementById('db-trap').textContent = makeTrap(anchor);
    renderQuestions();
    renderStats();
  }
  function makeTrap(card) {
    const topic = cleanTopic(card.topic).toLowerCase();
    if (/inflation|price/.test(topic)) return 'Exam trap: distinguish a movement along a curve from a shift in the whole curve. Inflation questions often hide that distinction.';
    if (/unemployment|labour/.test(topic)) return 'Exam trap: always identify who is in the labour force before calculating unemployment or participation rates.';
    if (/exchange|trade|current/.test(topic)) return 'Exam trap: keep the direction of the exchange rate clear — appreciation and depreciation flip export/import incentives.';
    if (/growth|solow|capital/.test(topic)) return 'Exam trap: separate level effects from growth-rate effects. More capital can raise output levels without permanently raising growth.';
    if (/fiscal|multiplier|keynesian/.test(topic)) return 'Exam trap: leakages matter. Taxes, imports, and saving usually make real-world multipliers smaller than the simple textbook case.';
    return 'Exam trap: do not stop at the answer letter. State the economic mechanism — that is usually where the marks are.';
  }
  function renderQuestions() {
    const container = document.getElementById('db-questions');
    container.innerHTML = '';
    currentBite.forEach((card, idx) => {
      const q = document.createElement('div');
      q.className = 'db-question';
      q.innerHTML = `
        <div class="db-q-meta">${card.module} / ${card.lesson || 'Lesson'} / ${cleanTopic(card.topic)}</div>
        <div class="db-q-text">Q${idx+1}. ${card.question}</div>
        <div class="db-options"></div>
        <div class="db-feedback" id="db-fb-${idx}"></div>
        <div class="db-confidence" id="db-conf-${idx}" style="display:none;">
          <button type="button" data-conf="guess">Guessed</button>
          <button type="button" data-conf="shaky">Shaky</button>
          <button type="button" data-conf="confident">Confident</button>
        </div>`;
      const opts = q.querySelector('.db-options');
      card.options.forEach(opt => {
        const b = document.createElement('button');
        b.type = 'button';
        b.className = 'db-option';
        b.textContent = `${opt.letter}) ${opt.text}`;
        b.addEventListener('click', () => answerQuestion(idx, opt.letter, b));
        opts.appendChild(b);
      });
      container.appendChild(q);
    });
    document.getElementById('db-complete').style.display = 'none';
  }
  function answerQuestion(idx, letter, btn) {
    if (answers[idx]) return;
    const card = currentBite[idx];
    const correct = letter === card.answerLetter;
    answers[idx] = { correct, confidence:null };
    const block = btn.closest('.db-question');
    block.querySelectorAll('.db-option').forEach(b => {
      if (b.textContent.startsWith(card.answerLetter + ')')) b.classList.add('correct');
      else if (b === btn) b.classList.add('incorrect');
      b.disabled = true;
    });
    const fb = document.getElementById(`db-fb-${idx}`);
    fb.style.display = 'block';
    fb.innerHTML = `<strong>${correct ? 'Correct.' : 'Not quite.'}</strong><br>${card.answerHtml}`;
    const conf = document.getElementById(`db-conf-${idx}`);
    conf.style.display = 'flex';
    conf.querySelectorAll('button').forEach(b => b.addEventListener('click', () => {
      answers[idx].confidence = b.dataset.conf;
      conf.querySelectorAll('button').forEach(x => x.classList.remove('selected'));
      b.classList.add('selected');
      maybeComplete();
    }));
    updateMastery(card.module, correct);
    state.xp += correct ? 10 : 2;
    saveState();
    renderStats();
    maybeComplete();
  }
  function updateMastery(module, correct) {
    if (!state.mastery[module]) state.mastery[module] = { attempts:0, correct:0 };
    state.mastery[module].attempts += 1;
    if (correct) state.mastery[module].correct += 1;
  }
  function maybeComplete() {
    if (Object.keys(answers).length < currentBite.length) return;
    const completed = document.getElementById('db-complete');
    const correct = Object.values(answers).filter(a => a.correct).length;
    const today = todayKey();
    if (!state.completed[today]) {
      const yesterday = new Date(Date.now() - 86400000).toISOString().slice(0, 10);
      state.streak = state.lastComplete === yesterday ? (state.streak || 0) + 1 : 1;
      state.lastComplete = today;
      state.completed[today] = true;
      state.xp += 20;
      saveState();
    }
    completed.style.display = 'block';
    completed.innerHTML = `<strong>Bite complete: ${correct}/${currentBite.length}.</strong> +20 completion XP ${correct >= 4 ? '— strong bite.' : '— review the feedback, then try another bite.'}`;
    renderStats();
  }
  function renderMasteryMap() {
    const el = document.getElementById('db-mastery-map');
    const modules = Object.keys(moduleNames).filter(m => (state.mastery && state.mastery[m]) || currentBite.some(c => c.module === m));
    if (!modules.length) { el.innerHTML = '<p style="color:#667085;">Answer a bite to start building your local mastery map.</p>'; return; }
    el.innerHTML = modules.map(m => {
      const s = state.mastery[m] || { attempts:0, correct:0 };
      const pct = s.attempts ? Math.round(100*s.correct/s.attempts) : 0;
      const label = s.attempts === 0 ? 'New' : pct >= 85 ? 'Exam-ready' : pct >= 65 ? 'Practised' : 'Needs work';
      return `<div class="db-mastery-row"><span>${m}</span><div class="db-bar"><div style="width:${pct}%"></div></div><small>${pct}% · ${label}</small></div>`;
    }).join('');
  }

  document.getElementById('db-new-bite').addEventListener('click', generateBite);
  document.getElementById('db-reset-today').addEventListener('click', () => { answers = {}; renderQuestions(); });

  loadCards().then(cards => {
    allCards = cards;
    generateBite();
  }).catch(err => {
    document.getElementById('db-title').textContent = 'Daily Bite could not load';
    document.getElementById('db-subtitle').textContent = err.message;
    document.getElementById('db-concept').textContent = 'Try reloading the page. If it persists, the flashcard data format may have changed.';
  });
})();
</script>
