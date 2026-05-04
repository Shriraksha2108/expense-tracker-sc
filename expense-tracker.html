<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Expenzo – Smart Expense Tracker</title>
<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Sans:wght@300;400;500;600&display=swap" rel="stylesheet"/>
<style>
  :root {
    --bg: #0f0e17;
    --surface: #1a1928;
    --surface2: #242337;
    --border: #2e2d45;
    --accent: #e8c547;
    --accent2: #ff6b6b;
    --accent3: #6bffc8;
    --accent4: #a78bfa;
    --text: #f0eff8;
    --muted: #7a798f;
    --font-display: 'DM Serif Display', serif;
    --font-body: 'DM Sans', sans-serif;
    --radius: 16px;
    --radius-sm: 8px;
  }

  * { margin: 0; padding: 0; box-sizing: border-box; }

  body {
    background: var(--bg);
    color: var(--text);
    font-family: var(--font-body);
    min-height: 100vh;
    overflow-x: hidden;
  }

  /* Background mesh */
  body::before {
    content: '';
    position: fixed;
    top: -30%;
    right: -20%;
    width: 700px;
    height: 700px;
    background: radial-gradient(circle, rgba(232,197,71,0.07) 0%, transparent 70%);
    pointer-events: none;
    z-index: 0;
  }
  body::after {
    content: '';
    position: fixed;
    bottom: -20%;
    left: -15%;
    width: 600px;
    height: 600px;
    background: radial-gradient(circle, rgba(107,255,200,0.05) 0%, transparent 70%);
    pointer-events: none;
    z-index: 0;
  }

  .app { position: relative; z-index: 1; max-width: 1100px; margin: 0 auto; padding: 2rem 1.5rem 4rem; }

  /* Header */
  header {
    display: flex;
    align-items: center;
    justify-content: space-between;
    margin-bottom: 3rem;
    flex-wrap: wrap;
    gap: 1rem;
  }
  .logo { font-family: var(--font-display); font-size: 2rem; letter-spacing: -0.02em; }
  .logo span { color: var(--accent); }
  .tagline { color: var(--muted); font-size: 0.85rem; font-weight: 300; margin-top: 2px; }

  /* Summary Cards */
  .summary-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1rem;
    margin-bottom: 2.5rem;
  }
  .summary-card {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 1.4rem 1.5rem;
    position: relative;
    overflow: hidden;
    transition: transform 0.2s;
  }
  .summary-card:hover { transform: translateY(-2px); }
  .summary-card::before {
    content: '';
    position: absolute;
    top: 0; left: 0; right: 0;
    height: 3px;
  }
  .summary-card.total::before { background: var(--accent); }
  .summary-card.period::before { background: var(--accent4); }
  .summary-card.top-cat::before { background: var(--accent3); }
  .summary-card.count::before { background: var(--accent2); }
  .card-label { font-size: 0.75rem; color: var(--muted); text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 0.5rem; }
  .card-value { font-family: var(--font-display); font-size: 2rem; }
  .card-value.total { color: var(--accent); }
  .card-value.period { color: var(--accent4); }
  .card-value.top-cat { color: var(--accent3); font-size: 1.4rem; }
  .card-value.count { color: var(--accent2); }
  .card-sub { font-size: 0.78rem; color: var(--muted); margin-top: 4px; }

  /* Main Layout */
  .main-grid {
    display: grid;
    grid-template-columns: 1fr 1.5fr;
    gap: 1.5rem;
    align-items: start;
  }
  @media (max-width: 750px) { .main-grid { grid-template-columns: 1fr; } }

  /* Panel */
  .panel {
    background: var(--surface);
    border: 1px solid var(--border);
    border-radius: var(--radius);
    padding: 1.6rem;
  }
  .panel-title {
    font-family: var(--font-display);
    font-size: 1.2rem;
    margin-bottom: 1.4rem;
    display: flex;
    align-items: center;
    gap: 0.5rem;
  }
  .panel-title .dot {
    width: 8px; height: 8px;
    border-radius: 50%;
    background: var(--accent);
  }

  /* Form */
  .form-group { margin-bottom: 1rem; }
  label { display: block; font-size: 0.78rem; color: var(--muted); margin-bottom: 0.4rem; text-transform: uppercase; letter-spacing: 0.06em; }

  input, select, textarea {
    width: 100%;
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    color: var(--text);
    font-family: var(--font-body);
    font-size: 0.95rem;
    padding: 0.65rem 0.9rem;
    outline: none;
    transition: border-color 0.2s;
  }
  input:focus, select:focus, textarea:focus { border-color: var(--accent); }
  select option { background: var(--surface2); }

  .form-row { display: grid; grid-template-columns: 1fr 1fr; gap: 0.8rem; }

  .btn {
    display: inline-flex;
    align-items: center;
    justify-content: center;
    gap: 0.4rem;
    padding: 0.7rem 1.4rem;
    border-radius: var(--radius-sm);
    border: none;
    cursor: pointer;
    font-family: var(--font-body);
    font-size: 0.9rem;
    font-weight: 500;
    transition: all 0.2s;
  }
  .btn-primary {
    background: var(--accent);
    color: #0f0e17;
    width: 100%;
    margin-top: 0.5rem;
    font-weight: 600;
    letter-spacing: 0.03em;
  }
  .btn-primary:hover { background: #f5d46a; transform: translateY(-1px); box-shadow: 0 6px 20px rgba(232,197,71,0.25); }
  .btn-sm {
    padding: 0.35rem 0.7rem;
    font-size: 0.78rem;
    border-radius: 6px;
  }
  .btn-danger { background: rgba(255,107,107,0.15); color: var(--accent2); border: 1px solid rgba(255,107,107,0.25); }
  .btn-danger:hover { background: rgba(255,107,107,0.25); }

  /* Filter bar */
  .filter-bar {
    display: flex;
    gap: 0.6rem;
    margin-bottom: 1.2rem;
    flex-wrap: wrap;
    align-items: center;
  }
  .filter-btn {
    padding: 0.4rem 1rem;
    border-radius: 100px;
    border: 1px solid var(--border);
    background: transparent;
    color: var(--muted);
    font-family: var(--font-body);
    font-size: 0.8rem;
    cursor: pointer;
    transition: all 0.2s;
  }
  .filter-btn.active {
    background: var(--accent);
    color: #0f0e17;
    border-color: var(--accent);
    font-weight: 600;
  }
  .filter-btn:hover:not(.active) { border-color: var(--accent); color: var(--accent); }

  /* Custom range */
  .custom-range {
    display: none;
    gap: 0.6rem;
    align-items: center;
    flex-wrap: wrap;
    margin-bottom: 1rem;
  }
  .custom-range.show { display: flex; }
  .custom-range input { max-width: 150px; }
  .custom-range label { color: var(--muted); font-size: 0.8rem; white-space: nowrap; }

  /* Category filter */
  .cat-filter-row {
    display: flex;
    gap: 0.5rem;
    flex-wrap: wrap;
    margin-bottom: 1rem;
  }
  .cat-chip {
    padding: 0.28rem 0.75rem;
    border-radius: 100px;
    border: 1px solid var(--border);
    background: transparent;
    font-size: 0.75rem;
    cursor: pointer;
    transition: all 0.2s;
    font-family: var(--font-body);
    color: var(--muted);
  }
  .cat-chip.active { font-weight: 600; }

  /* Expense list */
  .expense-list { display: flex; flex-direction: column; gap: 0.6rem; max-height: 460px; overflow-y: auto; padding-right: 4px; }
  .expense-list::-webkit-scrollbar { width: 4px; }
  .expense-list::-webkit-scrollbar-track { background: transparent; }
  .expense-list::-webkit-scrollbar-thumb { background: var(--border); border-radius: 4px; }

  .expense-item {
    display: flex;
    align-items: center;
    gap: 0.9rem;
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    padding: 0.8rem 1rem;
    animation: slideIn 0.25s ease;
    transition: border-color 0.2s;
  }
  .expense-item:hover { border-color: var(--accent); }
  @keyframes slideIn { from { opacity: 0; transform: translateY(-8px); } to { opacity: 1; transform: translateY(0); } }

  .cat-icon {
    width: 38px; height: 38px;
    border-radius: 10px;
    display: flex; align-items: center; justify-content: center;
    font-size: 1.1rem;
    flex-shrink: 0;
  }
  .expense-info { flex: 1; min-width: 0; }
  .expense-name { font-weight: 500; font-size: 0.9rem; white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }
  .expense-meta { font-size: 0.74rem; color: var(--muted); margin-top: 2px; }
  .expense-amount { font-family: var(--font-display); font-size: 1.1rem; color: var(--accent); flex-shrink: 0; }

  .empty-state { text-align: center; padding: 2.5rem 1rem; color: var(--muted); }
  .empty-state .icon { font-size: 2.5rem; margin-bottom: 0.8rem; }
  .empty-state p { font-size: 0.9rem; }

  /* Category breakdown */
  .breakdown-section { margin-top: 2rem; }
  .breakdown-title { font-size: 0.78rem; color: var(--muted); text-transform: uppercase; letter-spacing: 0.08em; margin-bottom: 0.8rem; }
  .cat-bar-item { margin-bottom: 0.9rem; }
  .cat-bar-header { display: flex; justify-content: space-between; align-items: center; margin-bottom: 0.35rem; }
  .cat-bar-name { font-size: 0.85rem; display: flex; align-items: center; gap: 0.5rem; }
  .cat-bar-amount { font-size: 0.85rem; font-weight: 600; }
  .bar-track { height: 6px; background: var(--surface2); border-radius: 100px; overflow: hidden; }
  .bar-fill { height: 100%; border-radius: 100px; transition: width 0.5s ease; }

  /* Period totals */
  .period-totals {
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    gap: 0.7rem;
    margin-top: 1.5rem;
  }
  .period-total-card {
    background: var(--surface2);
    border: 1px solid var(--border);
    border-radius: var(--radius-sm);
    padding: 0.9rem;
    text-align: center;
  }
  .period-total-card .pt-label { font-size: 0.7rem; color: var(--muted); text-transform: uppercase; letter-spacing: 0.06em; margin-bottom: 0.3rem; }
  .period-total-card .pt-value { font-family: var(--font-display); font-size: 1.2rem; color: var(--accent4); }

  /* Toast */
  .toast {
    position: fixed;
    bottom: 2rem;
    right: 2rem;
    background: var(--accent3);
    color: #0f0e17;
    padding: 0.7rem 1.2rem;
    border-radius: var(--radius-sm);
    font-weight: 600;
    font-size: 0.85rem;
    z-index: 1000;
    transform: translateY(100px);
    opacity: 0;
    transition: all 0.3s ease;
  }
  .toast.show { transform: translateY(0); opacity: 1; }

  /* Scrollbar for panel */
  .panel.right { overflow: hidden; }

  .section-divider { border: none; border-top: 1px solid var(--border); margin: 1.2rem 0; }
</style>
</head>
<body>

<div class="app">
  <!-- Header -->
  <header>
    <div>
      <div class="logo">Expen<span>zo</span></div>
      <div class="tagline">Track. Filter. Understand your money.</div>
    </div>
    <div style="display:flex;gap:0.6rem;align-items:center;">
      <span style="font-size:0.8rem;color:var(--muted);" id="today-date"></span>
    </div>
  </header>

  <!-- Summary Cards -->
  <div class="summary-grid">
    <div class="summary-card total">
      <div class="card-label">Filtered Total</div>
      <div class="card-value total" id="sum-total">₹0.00</div>
      <div class="card-sub" id="sum-period">All time</div>
    </div>
    <div class="summary-card period">
      <div class="card-label">Avg per Day</div>
      <div class="card-value period" id="sum-avg">₹0.00</div>
      <div class="card-sub">In selected range</div>
    </div>
    <div class="summary-card top-cat">
      <div class="card-label">Top Category</div>
      <div class="card-value top-cat" id="sum-topcat">—</div>
      <div class="card-sub" id="sum-topcat-amt"></div>
    </div>
    <div class="summary-card count">
      <div class="card-label">Transactions</div>
      <div class="card-value count" id="sum-count">0</div>
      <div class="card-sub">In selected range</div>
    </div>
  </div>

  <!-- Main Grid -->
  <div class="main-grid">
    <!-- Add Expense Panel -->
    <div class="panel">
      <div class="panel-title"><div class="dot"></div> Add Expense</div>

      <div class="form-group">
        <label>Description</label>
        <input type="text" id="inp-desc" placeholder="e.g. Grocery shopping" />
      </div>
      <div class="form-row">
        <div class="form-group">
          <label>Amount (₹)</label>
          <input type="number" id="inp-amount" placeholder="0.00" min="0" step="0.01"/>
        </div>
        <div class="form-group">
          <label>Date</label>
          <input type="date" id="inp-date"/>
        </div>
      </div>
      <div class="form-row">
        <div class="form-group">
          <label>Category</label>
          <select id="inp-cat">
            <option value="Household">🏠 Household</option>
            <option value="Education">📚 Education</option>
            <option value="Food & Dining">🍽️ Food & Dining</option>
            <option value="Transport">🚗 Transport</option>
            <option value="Healthcare">💊 Healthcare</option>
            <option value="Entertainment">🎬 Entertainment</option>
            <option value="Shopping">🛍️ Shopping</option>
            <option value="Utilities">💡 Utilities</option>
            <option value="Travel">✈️ Travel</option>
            <option value="Other">📦 Other</option>
          </select>
        </div>
        <div class="form-group">
          <label>Payment Mode</label>
          <select id="inp-mode">
            <option value="Cash">💵 Cash</option>
            <option value="Card">💳 Card</option>
            <option value="UPI">📱 UPI</option>
            <option value="Net Banking">🏦 Net Banking</option>
          </select>
        </div>
      </div>
      <div class="form-group">
        <label>Note (optional)</label>
        <textarea id="inp-note" rows="2" placeholder="Any extra detail..."></textarea>
      </div>
      <button class="btn btn-primary" onclick="addExpense()">+ Add Expense</button>

      <hr class="section-divider"/>

      <!-- Period Totals Auto-computed -->
      <div class="breakdown-title">Quick Period Totals</div>
      <div class="period-totals">
        <div class="period-total-card">
          <div class="pt-label">Today</div>
          <div class="pt-value" id="pt-today">₹0</div>
        </div>
        <div class="period-total-card">
          <div class="pt-label">This Week</div>
          <div class="pt-value" id="pt-week">₹0</div>
        </div>
        <div class="period-total-card">
          <div class="pt-label">This Year</div>
          <div class="pt-value" id="pt-year">₹0</div>
        </div>
      </div>
    </div>

    <!-- Expenses List Panel -->
    <div class="panel right">
      <div class="panel-title"><div class="dot" style="background:var(--accent4)"></div> Expenses</div>

      <!-- Period Filter -->
      <div class="filter-bar">
        <button class="filter-btn active" data-period="all" onclick="setPeriod('all',this)">All</button>
        <button class="filter-btn" data-period="today" onclick="setPeriod('today',this)">Today</button>
        <button class="filter-btn" data-period="week" onclick="setPeriod('week',this)">This Week</button>
        <button class="filter-btn" data-period="month" onclick="setPeriod('month',this)">This Month</button>
        <button class="filter-btn" data-period="year" onclick="setPeriod('year',this)">This Year</button>
        <button class="filter-btn" data-period="custom" onclick="setPeriod('custom',this)">Custom</button>
      </div>

      <!-- Custom Range -->
      <div class="custom-range" id="custom-range-row">
        <label>From</label>
        <input type="date" id="custom-from" onchange="renderAll()"/>
        <label>To</label>
        <input type="date" id="custom-to" onchange="renderAll()"/>
      </div>

      <!-- Category Chips -->
      <div class="cat-filter-row" id="cat-chips"></div>

      <!-- List -->
      <div class="expense-list" id="expense-list"></div>

      <!-- Breakdown -->
      <div class="breakdown-section">
        <hr class="section-divider"/>
        <div class="breakdown-title">Category Breakdown</div>
        <div id="cat-breakdown"></div>
      </div>
    </div>
  </div>
</div>

<div class="toast" id="toast"></div>

<script>
// ── State ──────────────────────────────────────────────────────
const CAT_META = {
  "Household":     { icon:"🏠", color:"#e8c547" },
  "Education":     { icon:"📚", color:"#6bffc8" },
  "Food & Dining": { icon:"🍽️", color:"#ff9f43" },
  "Transport":     { icon:"🚗", color:"#a78bfa" },
  "Healthcare":    { icon:"💊", color:"#ff6b6b" },
  "Entertainment": { icon:"🎬", color:"#fd79a8" },
  "Shopping":      { icon:"🛍️", color:"#74b9ff" },
  "Utilities":     { icon:"💡", color:"#fdcb6e" },
  "Travel":        { icon:"✈️", color:"#55efc4" },
  "Other":         { icon:"📦", color:"#b2bec3" },
};

let expenses = JSON.parse(localStorage.getItem('expenzo_data') || '[]');
let activePeriod = 'all';
let activeCat = 'All';

function save() { localStorage.setItem('expenzo_data', JSON.stringify(expenses)); }

// ── Helpers ────────────────────────────────────────────────────
function today() { return new Date().toISOString().split('T')[0]; }

function startOfWeek() {
  const d = new Date();
  const day = d.getDay(); // 0=Sun
  d.setDate(d.getDate() - day);
  return d.toISOString().split('T')[0];
}

function startOfMonth() {
  const d = new Date();
  return `${d.getFullYear()}-${String(d.getMonth()+1).padStart(2,'0')}-01`;
}

function startOfYear() {
  return `${new Date().getFullYear()}-01-01`;
}

function inRange(dateStr) {
  const d = dateStr;
  if (activePeriod === 'all') return true;
  if (activePeriod === 'today') return d === today();
  if (activePeriod === 'week') return d >= startOfWeek() && d <= today();
  if (activePeriod === 'month') return d >= startOfMonth() && d <= today();
  if (activePeriod === 'year') return d >= startOfYear() && d <= today();
  if (activePeriod === 'custom') {
    const from = document.getElementById('custom-from').value;
    const to = document.getElementById('custom-to').value;
    if (!from || !to) return true;
    return d >= from && d <= to;
  }
  return true;
}

function fmt(n) {
  return '₹' + Number(n).toLocaleString('en-IN', {minimumFractionDigits:2, maximumFractionDigits:2});
}

function fmtShort(n) {
  if (n >= 100000) return '₹'+(n/100000).toFixed(1)+'L';
  if (n >= 1000) return '₹'+(n/1000).toFixed(1)+'K';
  return fmt(n);
}

// ── Add Expense ────────────────────────────────────────────────
function addExpense() {
  const desc = document.getElementById('inp-desc').value.trim();
  const amount = parseFloat(document.getElementById('inp-amount').value);
  const date = document.getElementById('inp-date').value;
  const cat = document.getElementById('inp-cat').value;
  const mode = document.getElementById('inp-mode').value;
  const note = document.getElementById('inp-note').value.trim();

  if (!desc) return showToast('⚠️ Enter a description');
  if (!amount || amount <= 0) return showToast('⚠️ Enter a valid amount');
  if (!date) return showToast('⚠️ Pick a date');

  expenses.unshift({ id: Date.now(), desc, amount, date, cat, mode, note });
  save();
  renderAll();
  showToast('✓ Expense added!');

  document.getElementById('inp-desc').value = '';
  document.getElementById('inp-amount').value = '';
  document.getElementById('inp-note').value = '';
}

// ── Delete ─────────────────────────────────────────────────────
function deleteExpense(id) {
  expenses = expenses.filter(e => e.id !== id);
  save();
  renderAll();
  showToast('🗑 Deleted');
}

// ── Period filter ──────────────────────────────────────────────
function setPeriod(p, btn) {
  activePeriod = p;
  document.querySelectorAll('.filter-btn').forEach(b => b.classList.remove('active'));
  btn.classList.add('active');
  const cr = document.getElementById('custom-range-row');
  if (p === 'custom') cr.classList.add('show'); else cr.classList.remove('show');
  renderAll();
}

// ── Render ─────────────────────────────────────────────────────
function renderAll() {
  renderCatChips();
  const filtered = getFiltered();
  renderList(filtered);
  renderSummary(filtered);
  renderBreakdown(filtered);
  renderPeriodTotals();
}

function getFiltered() {
  return expenses.filter(e => {
    const periodOk = inRange(e.date);
    const catOk = activeCat === 'All' || e.cat === activeCat;
    return periodOk && catOk;
  });
}

function renderCatChips() {
  const cats = ['All', ...Object.keys(CAT_META)];
  const used = new Set(expenses.map(e=>e.cat));
  const container = document.getElementById('cat-chips');
  container.innerHTML = cats.map(c => {
    if (c !== 'All' && !used.has(c)) return '';
    const meta = CAT_META[c];
    const isActive = activeCat === c;
    const col = meta ? meta.color : 'var(--accent)';
    return `<button class="cat-chip${isActive?' active':''}"
      style="${isActive?`background:${col}22;border-color:${col};color:${col}`:''}"
      onclick="setCat('${c}')">
      ${meta?meta.icon+' ':''}${c}
    </button>`;
  }).join('');
}

function setCat(c) {
  activeCat = c;
  renderAll();
}

function renderList(filtered) {
  const el = document.getElementById('expense-list');
  if (!filtered.length) {
    el.innerHTML = `<div class="empty-state"><div class="icon">🪹</div><p>No expenses found.<br/>Add one to get started!</p></div>`;
    return;
  }
  // Sort newest first
  const sorted = [...filtered].sort((a,b) => b.date.localeCompare(a.date) || b.id - a.id);
  el.innerHTML = sorted.map(e => {
    const meta = CAT_META[e.cat] || {icon:'📦', color:'#b2bec3'};
    return `<div class="expense-item">
      <div class="cat-icon" style="background:${meta.color}22;">${meta.icon}</div>
      <div class="expense-info">
        <div class="expense-name">${e.desc}</div>
        <div class="expense-meta">${e.cat} &middot; ${formatDate(e.date)} &middot; ${e.mode}${e.note?' &middot; '+e.note:''}</div>
      </div>
      <div class="expense-amount">${fmt(e.amount)}</div>
      <button class="btn btn-sm btn-danger" onclick="deleteExpense(${e.id})">✕</button>
    </div>`;
  }).join('');
}

function formatDate(d) {
  const [y,m,day] = d.split('-');
  return `${day}/${m}/${y}`;
}

function renderSummary(filtered) {
  const total = filtered.reduce((s,e)=>s+e.amount, 0);
  // Days in range
  let days = 1;
  if (filtered.length > 1) {
    const dates = filtered.map(e=>e.date).sort();
    const ms = new Date(dates[dates.length-1]) - new Date(dates[0]);
    days = Math.max(1, Math.round(ms/86400000)+1);
  }
  const avg = total / days;

  // Top cat
  const catTotals = {};
  filtered.forEach(e => catTotals[e.cat] = (catTotals[e.cat]||0)+e.amount);
  const topCat = Object.entries(catTotals).sort((a,b)=>b[1]-a[1])[0];

  const periodLabels = {all:'All time',today:'Today',week:'This week',month:'This month',year:'This year',custom:'Custom range'};

  document.getElementById('sum-total').textContent = fmtShort(total);
  document.getElementById('sum-period').textContent = (periodLabels[activePeriod]||'') + (activeCat!=='All'?' · '+activeCat:'');
  document.getElementById('sum-avg').textContent = fmtShort(avg);
  document.getElementById('sum-topcat').textContent = topCat ? (CAT_META[topCat[0]]?.icon||'') + ' ' + topCat[0] : '—';
  document.getElementById('sum-topcat-amt').textContent = topCat ? fmtShort(topCat[1]) : '';
  document.getElementById('sum-count').textContent = filtered.length;
}

function renderBreakdown(filtered) {
  const catTotals = {};
  filtered.forEach(e => catTotals[e.cat] = (catTotals[e.cat]||0)+e.amount);
  const total = filtered.reduce((s,e)=>s+e.amount,0);
  const sorted = Object.entries(catTotals).sort((a,b)=>b[1]-a[1]);

  const container = document.getElementById('cat-breakdown');
  if (!sorted.length) { container.innerHTML = '<div style="color:var(--muted);font-size:0.85rem;">No data.</div>'; return; }

  container.innerHTML = sorted.map(([cat, amt]) => {
    const pct = total ? (amt/total*100).toFixed(1) : 0;
    const meta = CAT_META[cat] || {icon:'📦', color:'#b2bec3'};
    return `<div class="cat-bar-item">
      <div class="cat-bar-header">
        <span class="cat-bar-name">${meta.icon} ${cat}</span>
        <span class="cat-bar-amount" style="color:${meta.color}">${fmt(amt)} <span style="color:var(--muted);font-weight:400;">(${pct}%)</span></span>
      </div>
      <div class="bar-track"><div class="bar-fill" style="width:${pct}%;background:${meta.color}"></div></div>
    </div>`;
  }).join('');
}

function renderPeriodTotals() {
  const sum = (fn) => expenses.filter(e=>fn(e.date)).reduce((s,e)=>s+e.amount,0);
  document.getElementById('pt-today').textContent = fmtShort(sum(d=>d===today()));
  document.getElementById('pt-week').textContent = fmtShort(sum(d=>d>=startOfWeek()&&d<=today()));
  document.getElementById('pt-year').textContent = fmtShort(sum(d=>d>=startOfYear()&&d<=today()));
}

// ── Toast ──────────────────────────────────────────────────────
function showToast(msg) {
  const t = document.getElementById('toast');
  t.textContent = msg;
  t.classList.add('show');
  setTimeout(()=>t.classList.remove('show'), 2200);
}

// ── Init ───────────────────────────────────────────────────────
document.getElementById('inp-date').value = today();
document.getElementById('today-date').textContent = new Date().toLocaleDateString('en-IN',{weekday:'long',day:'numeric',month:'long',year:'numeric'});
renderAll();

// Allow Enter key in desc field
document.getElementById('inp-desc').addEventListener('keydown', e => { if(e.key==='Enter') document.getElementById('inp-amount').focus(); });
</script>
</body>
</html>
