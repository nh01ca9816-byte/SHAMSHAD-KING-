# SHAMSHAD-KING-
<!DOCTYPE html>
<html lang="hi">
<head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no" />
    <title>👑 SHAMSHAD KING – WinGo 1M Prediction</title>
    <meta property="og:title" content="👑 SHAMSHAD KING Prediction" />
    <meta property="og:description" content="WinGo 1M BIG/SMALL Predictor – AI Powered" />
    <meta property="og:image" content="https://i.imgur.com/YOUR_IMAGE_ID.jpg" />
    <meta property="og:url" content="https://YOUR-DOMAIN.com" />
    <meta name="theme-color" content="#0b0e1a" />
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body {
            font-family: 'Segoe UI', system-ui, -apple-system, sans-serif;
            background: linear-gradient(145deg, #0b0e1a 0%, #1a1f2f 100%);
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: flex-start;
            padding: 16px;
            color: #e0e4f0;
        }
        .container {
            max-width: 520px;
            width: 100%;
            background: rgba(22, 28, 46, 0.94);
            backdrop-filter: blur(12px);
            border-radius: 28px;
            padding: 22px 18px 26px;
            box-shadow: 0 20px 60px rgba(0,0,0,0.7), 0 0 0 1px rgba(255,215,0,0.08);
            border: 1px solid rgba(255,215,0,0.1);
            margin-top: 10px;
        }
        .header {
            text-align: center;
            margin-bottom: 18px;
        }
        .header h1 {
            font-size: 1.5rem;
            font-weight: 800;
            background: linear-gradient(135deg, #ffd700, #ffaa00);
            -webkit-background-clip: text;
            -webkit-text-fill-color: transparent;
            letter-spacing: 1px;
        }
        .header .sub {
            color: #8892b0;
            font-size: 0.78rem;
            letter-spacing: 2px;
            margin-top: 2px;
        }
        .status-dot {
            display: inline-block;
            width: 8px; height: 8px;
            border-radius: 50%;
            background: #4ade80;
            margin-right: 5px;
            animation: pulse-dot 1.8s infinite;
        }
        @keyframes pulse-dot {
            0%, 100% { opacity: 1; box-shadow: 0 0 6px #4ade80; }
            50% { opacity: 0.4; box-shadow: 0 0 12px #4ade80; }
        }
        .pred-card {
            background: linear-gradient(135deg, #1e2740, #141a2b);
            border-radius: 22px;
            padding: 20px 16px 18px;
            margin-bottom: 16px;
            border: 1px solid rgba(255,215,0,0.06);
            text-align: center;
        }
        .pred-card .period {
            font-size: 0.82rem;
            color: #8892b0;
            background: rgba(0,0,0,0.3);
            display: inline-block;
            padding: 3px 12px;
            border-radius: 18px;
            font-family: 'Courier New', monospace;
            letter-spacing: 1px;
            margin-bottom: 8px;
        }
        .pred-card .prediction {
            font-size: 2.8rem;
            font-weight: 900;
            letter-spacing: 4px;
            margin: 4px 0 8px;
            transition: all 0.4s ease;
        }
        .pred-card .prediction.big { color: #ef4444; text-shadow: 0 0 40px rgba(239,68,68,0.3); }
        .pred-card .prediction.small { color: #3b82f6; text-shadow: 0 0 40px rgba(59,130,246,0.3); }
        .conf-bar-wrap {
            background: rgba(255,255,255,0.06);
            border-radius: 20px;
            height: 5px;
            overflow: hidden;
            margin: 10px auto 6px;
            max-width: 260px;
        }
        .conf-bar {
            height: 100%;
            border-radius: 20px;
            width: 0%;
            transition: width 0.6s ease;
            background: linear-gradient(90deg, #f59e0b, #ef4444);
        }
        .conf-label {
            font-size: 0.78rem;
            color: #a0a8c0;
        }
        .conf-label strong { color: #ffd700; }
        .score-row {
            display: flex;
            gap: 10px;
            margin: 12px 0 4px;
        }
        .score-box {
            flex: 1;
            background: rgba(0,0,0,0.22);
            border-radius: 14px;
            padding: 10px 6px;
            text-align: center;
            border: 1px solid rgba(255,255,255,0.03);
        }
        .score-box .label {
            font-size: 0.68rem;
            text-transform: uppercase;
            letter-spacing: 1px;
            color: #8892b0;
        }
        .score-box .value {
            font-size: 1.1rem;
            font-weight: 700;
            margin-top: 1px;
        }
        .score-box .value.big-score { color: #ef4444; }
        .score-box .value.small-score { color: #3b82f6; }
        .results-strip {
            display: flex;
            gap: 5px;
            justify-content: center;
            flex-wrap: wrap;
            margin: 10px 0 14px;
        }
        .result-chip {
            width: 30px;
            height: 30px;
            border-radius: 8px;
            display: flex;
            align-items: center;
            justify-content: center;
            font-weight: 700;
            font-size: 0.75rem;
            color: #fff;
        }
        .result-chip.big { background: rgba(239,68,68,0.65); }
        .result-chip.small { background: rgba(59,130,246,0.65); }
        .result-chip.latest {
            transform: scale(1.1);
            border: 2px solid #ffd700;
        }
        .btn-group {
            display: flex;
            gap: 8px;
            margin-top: 10px;
            flex-wrap: wrap;
        }
        .btn {
            flex: 1;
            min-width: 85px;
            padding: 10px 6px;
            border: none;
            border-radius: 14px;
            font-weight: 700;
            font-size: 0.8rem;
            cursor: pointer;
            transition: all 0.2s;
            background: rgba(255,255,255,0.06);
            color: #e0e4f0;
            border: 1px solid rgba(255,255,255,0.05);
            -webkit-tap-highlight-color: transparent;
        }
        .btn:active { transform: scale(0.96); }
        .btn-primary {
            background: linear-gradient(135deg, #ffd700, #f59e0b);
            color: #0b0e1a;
            border: none;
            font-weight: 800;
        }
        .btn-auto-on.active {
            background: rgba(74,222,128,0.25);
            color: #4ade80;
            border-color: rgba(74,222,128,0.2);
        }
        .stats-panel {
            background: rgba(0,0,0,0.2);
            border-radius: 18px;
            padding: 14px 16px;
            margin-top: 12px;
            display: none;
            border: 1px solid rgba(255,215,0,0.05);
        }
        .stats-panel.show { display: block; }
        .stats-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 6px 12px;
            margin-top: 6px;
        }
        .stats-grid .item {
            display: flex;
            justify-content: space-between;
            padding: 3px 0;
            border-bottom: 1px solid rgba(255,255,255,0.03);
            font-size: 0.82rem;
        }
        .stats-grid .item .val { font-weight: 700; color: #ffd700; }
        .stats-grid .item .val.green { color: #4ade80; }
        .stats-grid .item .val.red { color: #ef4444; }
        .footer {
            text-align: center;
            margin-top: 14px;
            font-size: 0.68rem;
            color: #5a6380;
            letter-spacing: 1px;
        }
        .badge {
            display: inline-block;
            background: rgba(255,215,0,0.1);
            padding: 2px 10px;
            border-radius: 30px;
            font-size: 0.62rem;
            color: #ffd700;
            letter-spacing: 1px;
            margin-bottom: 4px;
        }
        .timer-text {
            font-family: 'Courier New', monospace;
            color: #6b7a9a;
            font-size: 0.72rem;
            margin-top: 4px;
            text-align: center;
        }
        .toast {
            background: rgba(0,0,0,0.88);
            color: #fff;
            padding: 8px 18px;
            border-radius: 30px;
            font-size: 0.8rem;
            position: fixed;
            bottom: 24px;
            left: 50%;
            transform: translateX(-50%);
            z-index: 999;
            opacity: 0;
            transition: opacity 0.4s;
            pointer-events: none;
            backdrop-filter: blur(8px);
            border: 1px solid rgba(255,255,255,0.05);
            white-space: nowrap;
        }
        .toast.show { opacity: 1; }
        .share-bar {
            display: flex;
            gap: 6px;
            margin-top: 10px;
            justify-content: center;
        }
        .share-bar .btn {
            flex: 0 1 auto;
            padding: 6px 12px;
            font-size: 0.7rem;
            min-width: auto;
        }
        @media (max-width: 420px) {
            .container { padding: 16px 12px; }
            .pred-card .prediction { font-size: 2.2rem; }
            .btn { font-size: 0.72rem; padding: 8px 4px; min-width: 60px; }
        }
    </style>
</head>
<body>

<div class="container" id="app">
    <div class="header">
        <div class="badge">🔴 LIVE</div>
        <h1>👑 SHAMSHAD KING</h1>
        <div class="sub"><span class="status-dot"></span>WinGo 1M • AI Predictor</div>
    </div>

    <div class="pred-card" id="predCard">
        <div class="period" id="periodDisplay">———</div>
        <div class="prediction" id="predictionDisplay">🎯 —</div>
        <div class="conf-bar-wrap">
            <div class="conf-bar" id="confBar" style="width:0%"></div>
        </div>
        <div class="conf-label" id="confLabel">Confidence: <strong>—</strong></div>
        <div class="score-row">
            <div class="score-box">
                <div class="label">🔴 BIG</div>
                <div class="value big-score" id="bigScore">0.0</div>
            </div>
            <div class="score-box">
                <div class="label">🔵 SMALL</div>
                <div class="value small-score" id="smallScore">0.0</div>
            </div>
        </div>
    </div>

    <div style="text-align:center;font-size:0.72rem;color:#6b7a9a;margin-bottom:2px;">पिछले नतीजे</div>
    <div class="results-strip" id="resultsStrip">
        <span style="color:#5a6380;font-size:0.8rem;">डेटा लोड हो रहा है...</span>
    </div>

    <div class="btn-group">
        <button class="btn btn-primary" id="btnPredict">🎯 प्रेडिक्शन</button>
        <button class="btn btn-auto-on" id="btnAuto">🔄 ऑटो</button>
        <button class="btn" id="btnStats">📊 स्टैट्स</button>
    </div>

    <div class="share-bar">
        <button class="btn" id="btnShare">📤 शेयर करें</button>
    </div>

    <div class="stats-panel" id="statsPanel">
        <div style="display:flex;justify-content:space-between;align-items:center;">
            <span style="font-weight:700;font-size:0.85rem;">📊 आपकी स्टैटिस्टिक्स</span>
            <button class="btn" id="btnStatsClose" style="min-width:auto;padding:3px 10px;font-size:0.7rem;">✕</button>
        </div>
        <div class="stats-grid" id="statsGrid">
            <div class="item"><span>कुल</span><span class="val" id="sTotal">0</span></div>
            <div class="item"><span>जीत</span><span class="val green" id="sWins">0</span></div>
            <div class="item"><span>हार</span><span class="val red" id="sLosses">0</span></div>
            <div class="item"><span>सटीकता</span><span class="val" id="sAccuracy">0%</span></div>
            <div class="item"><span>स्ट्रीक</span><span class="val" id="sStreak">0</span></div>
            <div class="item"><span>बेस्ट</span><span class="val" id="sBest">0</span></div>
            <div class="item" style="grid-column:1/-1;"><span>पिछले 10 में</span><span class="val" id="sLast10">0%</span></div>
        </div>
    </div>

    <div class="timer-text" id="timerDisplay">⏱ अगला अपडेट: —</div>

    <div class="footer">
        👑 <strong>SHAMSHAD KING</strong> &middot; समझदारी से खेलें
    </div>
</div>

<div class="toast" id="toast"></div>

<script>
(function() {
    'use strict';

    // ─── CORS PROXY ────────────────────────────────────────
    // Agar browser CORS block kare, toh yeh proxy use hoga
    const CORS_PROXY = 'https://api.allorigins.win/raw?url=';
    const DIRECT_API = 'https://draw.ar-lottery01.com/WinGo/WinGo_1M/GetHistoryIssuePage.json?ts=';

    const $ = id => document.getElementById(id);
    const periodDisplay = $('periodDisplay');
    const predictionDisplay = $('predictionDisplay');
    const confBar = $('confBar');
    const confLabel = $('confLabel');
    const bigScore = $('bigScore');
    const smallScore = $('smallScore');
    const resultsStrip = $('resultsStrip');
    const timerDisplay = $('timerDisplay');
    const toast = $('toast');
    const statsPanel = $('statsPanel');
    const sTotal = $('sTotal'), sWins = $('sWins'), sLosses = $('sLosses');
    const sAccuracy = $('sAccuracy'), sStreak = $('sStreak'), sBest = $('sBest'), sLast10 = $('sLast10');

    const state = {
        lastResults: [],
        prevPred: null,
        autoOn: false,
        autoInterval: null,
        useProxy: false,
        stats: {
            total: 0, wins: 0, losses: 0,
            streak: 0, bestStreak: 0,
            last10: []
        },
        nextPeriod: '———',
        currentScores: { BIG: 0, SMALL: 0 },
        currentConfidence: 0,
        currentConfLabel: '—'
    };

    function sigmoid(x) { return 1 / (1 + Math.exp(-x)); }
    function getConfLabel(conf) {
        if (conf > 0.85) return '🔥 VERY HIGH';
        if (conf > 0.70) return '✅ HIGH';
        if (conf > 0.60) return '⚠️ MODERATE';
        return '📉 LOW';
    }
    function showToast(msg, dur=2500) {
        toast.textContent = msg;
        toast.classList.add('show');
        clearTimeout(toast._timer);
        toast._timer = setTimeout(() => toast.classList.remove('show'), dur);
    }

    function extractFeatures(period, lastResults) {
        const window = Math.min(50, lastResults.length);
        if (window === 0) return [0,0,0,0,0,0,0];
        const labeled = lastResults.slice(-window).map(r => r >= 5 ? 1 : 0);
        let weightedSum = 0;
        for (let i = 0; i < labeled.length; i++) weightedSum += labeled[i] * (1 / (window - i));
        let streak = 1;
        for (let i = labeled.length - 2; i >= 0; i--) {
            if (labeled[i] === labeled[labeled.length-1]) streak++;
            else break;
        }
        const last3 = parseInt(String(period).slice(-3), 10) || 0;
        const digitSum = String(last3).split('').reduce((a,d) => a + parseInt(d,10), 0);
        const parity = digitSum % 2 === 0 ? 1 : 0;
        const mod7 = last3 % 7 === 0 ? 1 : 0;
        const mod5 = last3 % 5 === 0 ? 1 : 0;
        let flips = 0;
        for (let i = 1; i < labeled.length; i++) if (labeled[i] !== labeled[i-1]) flips++;
        const volatility = flips / Math.max(labeled.length-1, 1);
        const bigRatio = labeled.reduce((a,b) => a + b, 0) / Math.max(labeled.length, 1);
        const deviation = bigRatio - 0.5;
        return [weightedSum, streak, parity, mod7, mod5, volatility, deviation];
    }

    const COEF = [2.0, -1.5, 0.8, 2.0, -1.5, -0.6, 3.0];
    const INT = -0.5;

    function aiPredict(period, lr) {
        const feats = extractFeatures(period, lr);
        const logit = INT + feats.reduce((s, f, i) => s + COEF[i] * f, 0);
        const pb = sigmoid(logit);
        return { pred: pb > 0.5 ? 'BIG' : 'SMALL', probBig: pb };
    }

    function stablePredict(period, lr) {
        if (!lr || lr.length === 0) return { pred: Math.random() > 0.5 ? 'BIG' : 'SMALL', conf: 0.5 };
        const recent = lr.slice(-20);
        const bigCount = recent.filter(r => r >= 5).length;
        const short = lr.slice(-5);
        const shortBig = short.filter(r => r >= 5).length;
        const histTotal = lr.length;
        const histBig = lr.filter(r => r >= 5).length;
        const expectedBig = histTotal * 0.5;
        const dev = (histBig - expectedBig) / Math.max(histTotal, 1) * 100;
        const last3 = parseInt(String(period).slice(-3), 10) || 0;
        const dsum = String(last3).split('').reduce((a,d) => a + parseInt(d,10), 0);
        const periodPred = dsum % 2 === 0 ? 'BIG' : 'SMALL';
        let base, conf;
        if (Math.abs(dev) > 3) {
            if (histBig < histSmall()) { base = 'BIG'; conf = 0.65 + Math.min(Math.abs(dev)/20, 0.25); }
            else { base = 'SMALL'; conf = 0.65 + Math.min(Math.abs(dev)/20, 0.25); }
        } else if (shortBig >= 4) { base = 'SMALL'; conf = 0.6; }
        else if (short.length - shortBig >= 4) { base = 'BIG'; conf = 0.6; }
        else if (bigCount > recent.length/2) { base = 'BIG'; conf = 0.55; }
        else if (bigCount < recent.length/2) { base = 'SMALL'; conf = 0.55; }
        else { base = periodPred; conf = 0.52; }
        return { pred: base, conf };
        function histSmall() { return histTotal - histBig; }
    }

    function patternPredict(lr) {
        if (lr.length < 10) return { pred: null, conf: 0 };
        const labeled = lr.map(r => r >= 5 ? 1 : 0);
        for (let p = 3; p <= 5; p++) {
            if (labeled.length >= p * 2) {
                const rp = labeled.slice(-p);
                const hist = labeled.slice(0, labeled.length - p);
                for (let i = 0; i <= hist.length - p; i++) {
                    let match = true;
                    for (let j = 0; j < p; j++) if (hist[i+j] !== rp[j]) { match = false; break; }
                    if (match) {
                        const ai = i + p;
                        if (ai < hist.length) return { pred: hist[ai] === 1 ? 'BIG' : 'SMALL', conf: 0.72 };
                    }
                }
            }
        }
        return { pred: null, conf: 0 };
    }

    function hybridPredict(period, lr, prevPred) {
        const ai = aiPredict(period, lr);
        const st = stablePredict(period, lr);
        const pat = patternPredict(lr);
        const scores = { BIG: 0, SMALL: 0 };
        if (ai.probBig > 0.5) scores.BIG += ai.probBig * 40;
        else scores.SMALL += (1 - ai.probBig) * 40;
        scores[st.pred] += st.conf * 35;
        if (pat.pred) scores[pat.pred] += pat.conf * 25;
        else scores[st.pred] += 25;
        let base = scores.BIG > scores.SMALL ? 'BIG' : (scores.SMALL > scores.BIG ? 'SMALL' : (Math.random() > 0.5 ? 'BIG' : 'SMALL'));
        if (prevPred && base === prevPred) base = base === 'BIG' ? 'SMALL' : 'BIG';
        const confidence = base === 'BIG' ? ai.probBig : (1 - ai.probBig);
        return { pred: base, scores, confidence };
    }

    async function fetchLatest() {
        const ts = Date.now();
        const urls = [
            DIRECT_API + ts,
            CORS_PROXY + encodeURIComponent(DIRECT_API + ts)
        ];
        for (let i = 0; i < urls.length; i++) {
            try {
                const resp = await fetch(urls[i], {
                    headers: {
                        'User-Agent': 'Mozilla/5.0 (Linux; Android 10)',
                        'Referer': 'https://hgnice.biz'
                    }
                });
                if (!resp.ok) throw new Error('HTTP ' + resp.status);
                const data = await resp.json();
                const list = data?.data?.list || [];
                if (list.length > 0) {
                    if (i === 1) state.useProxy = true;
                    return list;
                }
            } catch(e) { console.warn('Attempt', i+1, 'failed:', e); }
        }
        return null;
    }

    async function doPredict() {
        const list = await fetchLatest();
        if (!list || list.length === 0) {
            renderPrediction(null);
            return;
        }

        const latest = list[0];
        const currPeriod = latest.issueNumber || '';
        
