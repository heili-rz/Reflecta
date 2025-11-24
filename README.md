<html lang="en-US"><head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">

<!-- Begin Jekyll SEO tag v2.8.0 -->
<title>reflecta</title>
<meta name="generator" content="Jekyll v3.10.0">
<meta property="og:title" content="reflecta">
<meta property="og:locale" content="en_US">
<link rel="canonical" href="https://heili-rz.github.io/reflectav2/">
<meta property="og:url" content="https://heili-rz.github.io/reflecta/">
<meta property="og:site_name" content="reflecta">
<meta property="og:type" content="website">
<meta name="twitter:card" content="summary">
<meta property="twitter:title" content="reflecta">
<script type="application/ld+json">
{"@context":"https://schema.org","@type":"WebSite","headline":"reflecta","name":"reflecta","url":"https://heili-rz.github.io/reflecta/"}</script>
<!-- End Jekyll SEO tag -->

    <style class="anchorjs"></style><link rel="stylesheet" href="/reflectav2/assets/css/style.css?v=62060f95711d18a82df10536762545051d8d41c4">
    <!-- start custom head snippets, customize with your own _includes/head-custom.html file -->

<!-- Setup Google Analytics -->



<!-- You can set your favicon here -->
<!-- link rel="shortcut icon" type="image/x-icon" href="/reflectav2/favicon.ico" -->

<!-- end custom head snippets -->

  </head>
  <body>
    <div class="container-lg px-3 my-5 markdown-body">
      
      <h1><a href="https://heili-rz.github.io/reflectav2/">Reflecta</a></h1>
      

      

<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Reflecta Toolkit — Practical, Anonymous Tools</title>
<!-- Optionally keep your globals.css if you have it -->


<style>

:root {
    --bg: #f5f8fa;
    --card: #ffffff;
    --accent: #2b9fda;
    --accent-light: #eaf6ff;
    --muted: #6b7280;
    --text: #0f172a;
    --radius: 14px;
    --shadow-sm: 0 4px 12px rgba(15,23,42,0.05);
    --shadow-md: 0 8px 22px rgba(15,23,42,0.08);
}

* {
    box-sizing: border-box;
    -webkit-tap-highlight-color: transparent;
}

body {
    margin: 0;
    background: var(--bg);
    color: var(--text);
    font-family: Inter, system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    line-height: 1.55;
}

header {
    background: linear-gradient(90deg, #e8f6ff, transparent);
    padding: 20px 0 16px;
    border-bottom: 1px solid #e3edf7;
}

.container {
    max-width: 900px;
    margin: auto;
    padding: 0 18px;
}

.branding { display:flex; gap:12px; align-items:center; }
.branding h1 {
    margin: 0;
    font-size: 1.6rem;
    font-weight: 700;
}
.branding small {
    color: var(--muted);
    font-size: 0.92rem;
}

.nav-list {
    list-style: none;
    padding: 0;
    margin: 12px 0 0;
    display: flex;
    gap: 10px;
    flex-wrap: wrap;
}

.nav-list a {
    display: inline-block;
    padding: 8px 14px;
    border-radius: 12px;
    text-decoration: none;
    color: var(--accent);
    font-weight: 600;
    background: transparent;
    transition: 0.18s;
    border: 1px solid transparent;
}

.nav-list a:hover {
    background: var(--accent-light);
    border-color: rgba(43,159,218,0.18);
}

.card {
    background: var(--card);
    border-radius: var(--radius);
    padding: 20px 22px;
    margin-bottom: 20px;
    box-shadow: var(--shadow-sm);
    transition: box-shadow .2s ease, transform .08s ease;
}

.card:hover { box-shadow: var(--shadow-md); }

button {
    cursor: pointer;
    border: 0;
    border-radius: 10px;
    padding: 10px 16px;
    font-weight: 600;
    transition: 0.16s;
    font-family: inherit;
}

button:not(.ghost) {
    background: var(--accent);
    color: #fff;
}

button:not(.ghost):hover { opacity: 0.95; }

button.ghost {
    background: #fff;
    border: 1px solid rgba(43,159,218,0.22);
    color: var(--accent);
}

button.ghost:hover { background: var(--accent-light); }

.emoji-btn {
    font-size: 16px;
    padding: 10px 12px;
    background: #fff;
    border-radius: 12px;
    border: 1px solid #eef6ff;
    transition: 0.16s;
}

.emoji-btn:hover { background: var(--accent-light); }
.emoji-btn.selected { outline: 3px solid rgba(43,159,218,0.28); }

#breath-circle {
    width: 130px;
    height: 130px;
    border-radius: 50%;
    display: flex;
    align-items: center;
    justify-content: center;
    background: var(--accent-light);
    margin: 16px auto;
    font-weight: 700;
    transition: transform 1.2s ease, box-shadow .2s;
}

input, textarea, select {
    width: 100%;
    font-family: inherit;
    padding: 10px 12px;
    border-radius: 12px;
    border: 1px solid #dbe7f3;
    background: #fff;
    transition: 0.12s;
}

input:focus, textarea:focus, select:focus {
    border-color: var(--accent);
    outline: 3px solid rgba(43,159,218,0.14);
}

.tool-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(240px, 1fr));
    gap: 18px;
}

.prompt {
    background: #f0fbff;
    padding: 12px;
    border-radius: 12px;
    border: 1px solid #d3ecf8;
}

.result {
    margin-top: 14px;
    background: #fff9d6;
    border: 1px solid #f1e6a3;
    border-radius: 12px;
    padding: 12px;
}

footer {
    max-width: 900px;
    margin: 50px auto 80px;
    padding: 0 18px;
    color: var(--muted);
    font-size: 0.9rem;
}

.overlay {
    position: fixed; inset: 0;
    background: rgba(0,0,0,0.45);
    display: none;
    align-items: center;
    justify-content: center;
}

.overlay[open] { display: flex; }

.modal {
    background: #fff;
    border-radius: 14px;
    padding: 24px;
    max-width: 520px;
    width: calc(100% - 40px);
    box-shadow: var(--shadow-md);
}

.post {
    background: #fbfdff;
    border: 1px solid #e2eef7;
    padding: 14px;
    border-radius: 12px;
    margin-bottom: 14px;
}

.post .meta {
    color: var(--muted);
    font-size: 0.85rem;
    margin-bottom: 6px;
}

.sr-only{position:absolute;width:1px;height:1px;padding:0;margin:-1px;overflow:hidden;clip:rect(0,0,0,0);white-space:nowrap;border:0}

@media (max-width: 640px) {
    #breath-circle { width: 110px; height: 110px; }
}
</style>


    <header>
        <div class="container" role="banner">
            <div class="branding">
                <div>
                    <h1>Reflecta Toolkit</h1>
                    <div style="color:var(--muted);font-size:0.9rem">Practical, anonymous tools to reflect and cope</div>
                </div>
            </div>

            <nav aria-label="Main menu">
                <ul class="nav-list">
                    <li><a href="#about">About</a></li>
                    <li><a href="#toolkit">Toolkit</a></li>
                    <li><a href="#test">Wellness check</a></li>
                    <li><a href="#forum">Open forum</a></li>
                    <li><a href="#mood">Mood picker</a></li>
                    <li><a href="#What is SDG 3?">What is SDG 3?</a></li>
                    <li><a href="#resources">Resources</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <main class="container" role="main">
        <section id="about" style="margin-top:18px">
            <div class="card" aria-labelledby="about-title">
                <h2 id="about-title">What is Reflecta Toolkit?<a class="anchorjs-link " href="#about-title" aria-label="Anchor" data-anchorjs-icon="?" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
                <p class="lead">A local-first collection of short, evidence-informed exercises and anonymous spaces to help reduce distress and build small, repeatable habits. Not a replacement for professional care.</p>
            </div>
        </section>

        <!-- Toolkit section -->
        <section id="toolkit" style="margin-top:12px">
            <div class="card" aria-labelledby="toolkit-title">
                <h2 id="toolkit-title">Toolkit — quick practice tools<a class="anchorjs-link " href="#toolkit-title" aria-label="Anchor" data-anchorjs-icon="?" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
                <p class="lead">Short exercises you can try now. Results stay on your device.</p>

                <div class="tool-grid" role="list">
                    <!-- Breathing trainer -->
                    <div class="card" style="padding:12px">
                        <h3 id="2-4-breathing">2:4 Breathing<a class="anchorjs-link " href="#2-4-breathing" aria-label="Anchor" data-anchorjs-icon="?" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h3>
                        <div id="breath-circle">Breathe</div>
                        <div style="text-align:center">
                            <button id="start-breath" type="button">Start 1 cycle</button>
                            <button id="stop-breath" class="ghost" type="button">Stop</button>
                        </div>
                        <p style="margin-top:8px;color:var(--muted)">Inhale 2s — exhale 4s. One minute can calm the nervous system.</p>
                    </div>

                    <!-- Guided journaling -->
                    <div class="card" style="padding:12px">
                        <h3 id="guided-journaling">Guided journaling<a class="anchorjs-link " href="#guided-journaling" aria-label="Anchor" data-anchorjs-icon="?" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h3>
                        <div id="prompt" class="prompt">Click "New prompt" for a short writing cue.</div>
                        <div style="display:flex;gap:8px;margin-top:8px">
                            <button id="new-prompt">New prompt</button>
                            <button id="save-journal" class="ghost">Save (local)</button>
                        </div>
                        <textarea id="journal" rows="4" placeholder="Write a few lines..." style="width:100%;margin-top:8px;padding:8px;border-radius:8px;border:1px solid #e6eef6"></textarea>
                        <small style="color:var(--muted)">Saved entries are stored locally and anonymous.</small>
                    </div>

                    <!-- CBT thought record -->
                    <div class="card" style="padding:12px">
                        <h3 id="simple-thought-record">Simple thought record<a class="anchorjs-link " href="#simple-thought-record" aria-label="Anchor" data-anchorjs-icon="?" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h3>
                        <label class="sr-only">Situation</label>
                        <input id="situation" placeholder="Situation (short)" style="width:100%;padding:8px;border-radius:8px;border:1px solid #e6eef6">
                        <label class="sr-only">Automatic thought</label>
                        <input id="thought" placeholder="Automatic thought" style="width:100%;padding:8px;border-radius:8px;border:1px solid #e6eef6;margin-top:8px">
                        <label class="sr-only">Alternative</label>
                        <input id="alternative" placeholder="Alternative balanced thought" style="width:100%;padding:8px;border-radius:8px;border:1px solid #e6eef6;margin-top:8px">
                        <div style="display:flex;gap:8px;margin-top:8px">
                            <button id="save-thought">Save</button>
                            <button id="clear-thought" class="ghost">Clear</button>
                        </div>
                        <div id="thought-list" style="margin-top:8px;color:var(--muted)">No saved thought records.</div>
                    </div>

                    <!-- Micro-actions -->
                    <div class="card" style="padding:12px">
                        <h3 id="micro-actions">Micro-actions<a class="anchorjs-link " href="#micro-actions" aria-label="Anchor" data-anchorjs-icon="?" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h3>
                        <div id="micro" class="prompt">Name 3 things you can see right now</div>
                        <div style="display:flex;gap:8px;margin-top:8px">
                            <button id="next-micro">Next</button>
                            <button id="done-micro" class="ghost">Mark done</button>
                        </div>
                        <small style="color:var(--muted);display:block;margin-top:8px">Small, concrete steps that are easy to complete.</small>
                    </div>
                </div>
            </div>
        </section>

        <!-- Wellness check -->
        <section id="test" style="margin-top:12px">
            <div class="card" aria-labelledby="test-title">
                <h2 id="test-title">Free anonymous wellness check<a class="anchorjs-link " href="#test-title" aria-label="Anchor" data-anchorjs-icon="?" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
                <p class="lead">A short, anonymous self-check to reflect on recent weeks. Non-diagnostic.</p>
                <form id="wellness-form" onsubmit="return false;">
                    <div class="q"><label>1. Felt down or hopeless?</label><select data-q="0" class="qsel"><option value="0">Not at all</option><option value="1">Several days</option><option value="2">More than half the days</option><option value="3">Nearly every day</option></select></div>
                    <div class="q"><label>2. Little interest or pleasure?</label><select data-q="1" class="qsel"><option value="0">Not at all</option><option value="1">Several days</option><option value="2">More than half the days</option><option value="3">Nearly every day</option></select></div>
                    <div style="display:flex;gap:8px;align-items:center;margin-top:8px"><button id="test-run" type="button">Run check</button><button id="test-clear" class="ghost" type="button">Clear</button></div>
                    <div id="test-result" aria-live="polite"></div>
                </form>
            </div>
        </section>

        <!-- Forum -->
        <section id="forum" style="margin-top:12px">
            <div class="card" aria-labelledby="forum-title">
                <h2 id="forum-title">Open anonymous forum<a class="anchorjs-link " href="#forum-title" aria-label="Anchor" data-anchorjs-icon="?" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
                <p class="lead">Write freely. Posts are anonymous and local to your device.</p>
                <form id="post-form" onsubmit="return false;">
                    <textarea id="post-text" rows="4" maxlength="500" placeholder="Share how you're feeling..." style="width:100%;padding:10px;border-radius:8px;border:1px solid #e6eef6"></textarea>
                    <div style="display:flex;justify-content:space-between;align-items:center;margin-top:8px"><small id="char-count">0/500</small><div><button id="post-btn">Post anonymously</button><button id="clear-btn" class="ghost">Clear</button></div></div>
                </form>
                <div id="posts" style="margin-top:12px" aria-live="polite"><div class="empty">No posts yet — be the first to share.</div></div>
            </div>
        </section>

        <!-- Mood picker -->
        <section id="mood" style="margin-top:12px">
            <div class="card" aria-labelledby="mood-title">
                <h2 id="mood-title">What is your mood today?<a class="anchorjs-link " href="#mood-title" aria-label="Anchor" data-anchorjs-icon="?" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
                <p class="lead">Choose an emoji. A motivational quote will appear.</p>
                <div class="buttons" role="list" id="mood-picker">
                    <button class="emoji-btn" data-mood="happy">🙂 Happy</button>
                    <button class="emoji-btn" data-mood="sad">😢 Sad</button>
                    <button class="emoji-btn" data-mood="confuse">😕 Confuse</button>
                    <button class="emoji-btn" data-mood="afraid">😨 Afraid</button>
                    <button class="emoji-btn" data-mood="mad">😡 Mad</button>
                </div>
            </div>
        </section>

         <!-- What iS SDG 3? -->
        <section id="What is SDG 3?" style="margin-top:12px">
            <div class="card" aria-labelledby="What is SDG 3?-title">
                <h2 id="What is SDG 3?-title">What is SDG 3?<a class="anchorjs-link " href="#What is SDG 3?-title" aria-label="Anchor" data-anchorjs-icon="?" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
                <p class="lead">SDG 3 aims to ensure healthy lives and promote well-being for all people at all ages.
It focuses on making the world a place where everyone can live longer, safer, and healthier.</p>
                <ul><li><a href="#" onclick="openModal('What iS SDG 3?','List of links');return false;" aria-label="What iS SDG 3? link"><u>For more details.(demo)</u></a></li></ul>
            </div>
        </section>

        <!-- Resources -->
        <section id="resources" style="margin-top:12px">
            <div class="card" aria-labelledby="resources-title">
                <h2 id="resources-title">Resources<a class="anchorjs-link " href="#resources-title" aria-label="Anchor" data-anchorjs-icon="?" style="font: 1em / 1 anchorjs-icons; padding-left: 0.375em;"></a></h2>
                <p class="lead">If in crisis, contact local emergency services or a crisis line. This toolkit is a demo and not crisis care.</p>
                <ul><li><a href="#" onclick="openModal('Resources','In production, list trusted hotlines and local services.');return false;" aria-label="Resources link">Sample resources (demo)</a></li></ul>
            </div>
        </section>
    </main>

    <footer>
        <div class="container">© 2025 Reflecta — Find your calm. </div>
    </footer>

    <div id="overlay" class="overlay" role="dialog" aria-modal="true" aria-hidden="true">
        <div class="modal" role="document">
            <button id="close" aria-label="Close" style="float:right;background:transparent;border:0;font-size:18px;cursor:pointer">?</button>
            <h3 id="modal-title">What iS SDG 3?</h3>
            <p id="modal-body">List of links</p>
            <div class="actions" style="text-align:right"><button id="modal-ok">Okay</button></div>
        </div>
    </div>

<script>
const overlay = document.getElementById('overlay'),
      modalTitle = document.getElementById('modal-title'),
      modalBody = document.getElementById('modal-body');

function openModal(t, m) {
    modalTitle.textContent = t;
    modalBody.innerHTML = (m || '');
    overlay.setAttribute('open', '');
    overlay.setAttribute('aria-hidden', 'false');
}

function closeModal() {
    overlay.removeAttribute('open');
    overlay.setAttribute('aria-hidden', 'true');
}

document.getElementById('close').addEventListener('click', closeModal);
document.getElementById('modal-ok').addEventListener('click', closeModal);
overlay.addEventListener('click', (e) => { if (e.target === overlay) closeModal(); });
document.addEventListener('keydown', (e) => { if (e.key === 'Escape') closeModal(); });

const moodButtons = document.querySelectorAll('.emoji-btn');
const moodTag = { happy:'happiness', sad:'hope', confuse:'wisdom', afraid:'courage', mad:'anger' };
const fallback = {
    happy:["Keep shining — your joy matters. — Reflecta"],
    sad:["Small steps matter. — Reflecta"],
    confuse:["Clarity comes with time. — Reflecta"],
    afraid:["Courage is small steps forward. — Reflecta"],
    mad:["Feelings pass — tend to them safely. — Reflecta"]
};

async function fetchQuoteForMood(mood) {
    const tag = moodTag[mood] || 'inspirational';
    openModal('Finding a quote...', '<span class="spinner" aria-hidden="true"></span> Finding an uplifting quote...');
    try {
        
        const res = await fetch(`https://api.quotable.io/random?tags=${encodeURIComponent(tag)}`);
        if (!res.ok) throw new Error('no-res');
        const data = await res.json();
        openModal('Here is a quote for you', `${data.content}${data.author ? ` — ${data.author}` : ''}`);
    } catch (e) {
        const list = fallback[mood] || ["You are not alone. — Reflecta"];
        openModal('Here is a quote for you', list[Math.floor(Math.random() * list.length)]);
    }
}

moodButtons.forEach(btn => btn.addEventListener('click', () => {
    document.querySelectorAll('.emoji-btn').forEach(b => b.classList.remove('selected'));
    btn.classList.add('selected');
    fetchQuoteForMood(btn.getAttribute('data-mood'));
}));

const postText = document.getElementById('post-text'),
      postBtn = document.getElementById('post-btn'),
      clearBtn = document.getElementById('clear-btn'),
      postsContainer = document.getElementById('posts'),
      charCount = document.getElementById('char-count');

function updateCharCount() { if (!postText) return; charCount.textContent = `${postText.value.length}/500`; }
postText && postText.addEventListener('input', updateCharCount);

function loadPosts() {
    postsContainer.innerHTML = '';
    let stored = [];
    try { stored = JSON.parse(localStorage.getItem('forum_posts') || '[]'); } catch (e) { stored = []; }
    if (!stored.length) {
        const e = document.createElement('div'); e.className = 'empty'; e.textContent = 'No posts yet — be the first to share.'; postsContainer.appendChild(e); return;
    }
    stored.slice().reverse().forEach(p => renderPost(p));
}

function renderPost(post) {
    const div = document.createElement('div'); div.className = 'post';
    const meta = document.createElement('div'); meta.className = 'meta';
    let timeLabel = '';
    try { timeLabel = new Date(post.createdAt).toLocaleString(); } catch (e) { timeLabel = ''; }
    meta.textContent = `Anonymous ? ${timeLabel}`;
    const content = document.createElement('div'); content.className = 'content';
    content.textContent = post.text;
    div.appendChild(meta); div.appendChild(content); postsContainer.appendChild(div);
}

function savePost(text) {
    let arr = [];
    try { arr = JSON.parse(localStorage.getItem('forum_posts') || '[]'); } catch (e) { arr = []; }
    arr.push({ text, createdAt: new Date().toISOString() });
    try { localStorage.setItem('forum_posts', JSON.stringify(arr)); } catch (e) {}
}

if (postBtn) {
    postBtn.addEventListener('click', () => {
        const text = postText.value.trim();
        if (!text) { openModal('Post is empty', 'Please write something before posting.'); return; }
        savePost(text);
        postsContainer.querySelectorAll('.empty').forEach(n => n.remove());
        renderPost({ text, createdAt: new Date().toISOString() });
        postText.value = '';
        updateCharCount();
        openModal('Post successful', 'Your post has been added anonymously and is visible on this device.');
    });
}

clearBtn && clearBtn.addEventListener('click', () => { postText.value = ''; updateCharCount(); });
loadPosts();

let breathTimer = null;
const circle = document.getElementById('breath-circle'),
      startBreath = document.getElementById('start-breath'),
      stopBreath = document.getElementById('stop-breath');

function animateBreathOnce() {
    // simple rhythm: inhale 2s -> exhale 4s -> done
    circle.style.transform = 'scale(1.15)';
    circle.textContent = 'Inhale';
    setTimeout(() => {
        circle.style.transform = 'scale(0.9)';
        circle.textContent = 'Exhale';
        setTimeout(() => {
            circle.style.transform = 'scale(1)';
            circle.textContent = 'Done';
            setTimeout(() => { circle.textContent = 'Breathe'; }, 800);
        }, 4000);
    }, 2000);
}

startBreath && startBreath.addEventListener('click', () => { animateBreathOnce(); });
stopBreath && stopBreath.addEventListener('click', () => { circle.style.transform = ''; circle.textContent = 'Breathe'; if (breathTimer) { clearInterval(breathTimer); breathTimer = null; } });

const prompts = [
    "Name one thing you can be kind to yourself for today.",
    "Describe a small moment that felt okay recently.",
    "What is one small thing you can do right now to feel a bit better?",
    "Write a short message to your future self in two sentences."
];
const promptEl = document.getElementById('prompt'),
      newPrompt = document.getElementById('new-prompt'),
      journal = document.getElementById('journal'),
      saveJournal = document.getElementById('save-journal');

function setRandomPrompt() { if (!promptEl) return; promptEl.textContent = prompts[Math.floor(Math.random() * prompts.length)]; }
newPrompt && newPrompt.addEventListener('click', setRandomPrompt);

saveJournal && saveJournal.addEventListener('click', () => {
    const text = (journal && journal.value.trim()) || '';
    if (!text) { openModal('Empty', 'Write something before saving.'); return; }
    let arr = [];
    try { arr = JSON.parse(localStorage.getItem('journals') || '[]'); } catch (e) { arr = []; }
    arr.push({ text, ts: new Date().toISOString() });
    try { localStorage.setItem('journals', JSON.stringify(arr)); if (journal) journal.value = ''; openModal('Saved', 'Journal entry saved locally.'); } catch (e) { openModal('Error', 'Unable to save locally.'); }
});

const sit = document.getElementById('situation'),
      thought = document.getElementById('thought'),
      alt = document.getElementById('alternative'),
      saveThought = document.getElementById('save-thought'),
      clearThought = document.getElementById('clear-thought'),
      thoughtList = document.getElementById('thought-list');

function loadThoughts() {
    let arr = [];
    try { arr = JSON.parse(localStorage.getItem('thoughts') || '[]'); } catch (e) { arr = []; }
    if (!arr.length) { thoughtList && (thoughtList.textContent = 'No saved thought records.'); return; }
    thoughtList.innerHTML = '';
    arr.slice().reverse().forEach(t => {
        const d = document.createElement('div');
        d.style.padding = '8px';
        d.style.borderRadius = '8px';
        d.style.background = '#fff';
        d.style.marginBottom = '8px';
        d.textContent = `${new Date(t.ts).toLocaleString()} — ${t.situation} ? ${t.thought} ? ${t.alternative}`;
        thoughtList.appendChild(d);
    });
}

saveThought && saveThought.addEventListener('click', () => {
    const s = (sit && sit.value.trim()) || '';
    const th = (thought && thought.value.trim()) || '';
    const al = (alt && alt.value.trim()) || '';
    if (!s || !th || !al) { openModal('Missing', 'Fill all fields before saving.'); return; }
    let arr = [];
    try { arr = JSON.parse(localStorage.getItem('thoughts') || '[]'); } catch (e) { arr = []; }
    arr.push({ situation: s, thought: th, alternative: al, ts: new Date().toISOString() });
    try { localStorage.setItem('thoughts', JSON.stringify(arr)); sit.value = ''; thought.value = ''; alt.value = ''; loadThoughts(); openModal('Saved', 'Thought record saved locally.'); } catch (e) { openModal('Error', 'Unable to save locally.'); }
});

clearThought && clearThought.addEventListener('click', () => { if (sit) sit.value = ''; if (thought) thought.value = ''; if (alt) alt.value = ''; });
loadThoughts();

const microList = ["Stand up and stretch for 30s","Drink a glass of water","Step outside for 1 minute of fresh air","Send a short message to a friend","Name 3 things you can see right now"];
const microEl = document.getElementById('micro'),
      nextMicro = document.getElementById('next-micro'),
      doneMicro = document.getElementById('done-micro');

function setMicro() { if (!microEl) return; microEl.textContent = microList[Math.floor(Math.random() * microList.length)]; }
nextMicro && nextMicro.addEventListener('click', setMicro);
doneMicro && doneMicro.addEventListener('click', () => { openModal('Nice work', 'Small actions add up.'); setMicro(); });
setMicro();

const runBtn = document.getElementById('test-run'),
      clearTestBtn = document.getElementById('test-clear'),
      resultEl = document.getElementById('test-result');

function computeScore() {
    const sels = Array.from(document.querySelectorAll('.qsel'));
    let sum = 0;
    sels.forEach(s => sum += Number(s.value || 0));
    return sum;
}

function interpretScore(score) {
    if (score <= 1) return { level: 'Low', msg: 'Mild/low responses.' };
    if (score <= 3) return { level: 'Moderate', msg: 'Some symptoms — consider support.' };
    return { level: 'Elevated', msg: 'Notable distress — consider contacting a professional.' };
}

runBtn && runBtn.addEventListener('click', () => {
    const score = computeScore();
    const i = interpretScore(score);
    if (resultEl) resultEl.innerHTML = `<div class="result"><strong>Score: ${score}</strong> — ${i.level}<div style="margin-top:8px;color:var(--muted)">${i.msg}</div></div>`;
    try { localStorage.setItem('last_wellness_check', JSON.stringify({ score, ts: new Date().toISOString() })); } catch (e) {}
});

clearTestBtn && clearTestBtn.addEventListener('click', () => {
    document.querySelectorAll('.qsel').forEach(s => s.selectedIndex = 0);
    if (resultEl) resultEl.innerHTML = '';
});

document.querySelectorAll('a[href="#resources"]').forEach(a => a.addEventListener('click', () => {}));
</script>





      
    </div>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/anchor-js/4.1.0/anchor.min.js" integrity="sha256-lZaRhKri35AyJSypXXs4o6OPFTbTmUoltBbDCbdzegg=" crossorigin="anonymous"></script>
    <script>anchors.add();</script>
  

</body></html>
