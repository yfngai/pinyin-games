<!DOCTYPE html>
<html lang="zh-TW">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
  <title>拼音小高手 - 二年級聽音辨韻母大賽 (4秒長音放大版)</title>
  <style>
    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
      user-select: none;
      -webkit-user-select: none;
    }

    body {
      font-family: -apple-system, BlinkMacSystemFont, "Microsoft JhengHei", "Segoe UI", Roboto, sans-serif;
      background: linear-gradient(135deg, #0f172a 0%, #1e293b 100%);
      min-height: 100vh;
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 10px;
    }

    .game-card {
      background: #ffffff;
      width: 100%;
      max-width: 680px;
      border-radius: 24px;
      box-shadow: 0 20px 30px rgba(0, 0, 0, 0.35);
      overflow: hidden;
      display: flex;
      flex-direction: column;
      position: relative;
    }

    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      padding: 12px 16px;
      background: #f8fafc;
      border-bottom: 2px solid #e2e8f0;
    }

    .stat-box {
      display: flex;
      align-items: center;
      gap: 4px;
      font-size: 0.95rem;
      font-weight: 700;
      color: #334155;
    }

    .stat-value {
      font-size: 1.2rem;
      color: #ea580c;
    }

    .level-badge {
      background: #0284c7;
      color: #fff;
      padding: 2px 8px;
      border-radius: 12px;
      font-size: 0.85rem;
    }

    .mute-btn {
      background: #e2e8f0;
      border: none;
      border-radius: 20px;
      padding: 5px 10px;
      font-size: 0.8rem;
      font-weight: bold;
      cursor: pointer;
      color: #475569;
      transition: background 0.2s;
    }

    .mute-btn:hover {
      background: #cbd5e1;
    }

    .question-banner {
      background: linear-gradient(90deg, #1e293b 0%, #334155 100%);
      color: #ffffff;
      padding: 14px 16px;
      text-align: center;
      box-shadow: inset 0 -4px 8px rgba(0, 0, 0, 0.2);
      min-height: 125px;
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      gap: 6px;
    }

    .question-hint {
      font-size: 0.9rem;
      color: #38bdf8;
      font-weight: 700;
      letter-spacing: 1px;
    }

    .question-text {
      font-size: 1.25rem;
      font-weight: 800;
      line-height: 1.4;
      color: #ffffff;
      letter-spacing: 1px;
    }

    .audio-btn {
      background: #0284c7;
      color: #ffffff;
      border: none;
      padding: 6px 18px;
      border-radius: 20px;
      font-size: 0.95rem;
      font-weight: bold;
      cursor: pointer;
      box-shadow: 0 3px 8px rgba(2, 132, 199, 0.4);
      transition: transform 0.1s, background-color 0.2s;
      display: inline-flex;
      align-items: center;
      gap: 6px;
    }

    .audio-btn:hover {
      background: #0369a1;
      transform: scale(1.05);
    }

    .canvas-container {
      position: relative;
      width: 100%;
      background: #1e293b;
    }

    canvas {
      display: block;
      width: 100%;
      height: auto;
      cursor: pointer;
    }

    .overlay {
      position: absolute;
      top: 0;
      left: 0;
      width: 100%;
      height: 100%;
      background: rgba(255, 255, 255, 0.97);
      backdrop-filter: blur(5px);
      display: flex;
      flex-direction: column;
      justify-content: flex-start;
      align-items: center;
      padding: 24px 20px;
      text-align: center;
      z-index: 10;
      overflow-y: auto;
    }

    .overlay.hidden {
      display: none;
    }

    .user-inputs-top {
      display: flex;
      gap: 8px;
      justify-content: center;
      margin-bottom: 16px;
      width: 100%;
    }

    .user-inputs-top input {
      width: 95px;
      padding: 6px 10px;
      border: 2px solid #cbd5e1;
      border-radius: 10px;
      font-size: 0.9rem;
      font-weight: bold;
      text-align: center;
      outline: none;
      transition: border-color 0.2s, box-shadow 0.2s;
      user-select: auto;
      -webkit-user-select: auto;
    }

    .user-inputs-top input:focus {
      border-color: #ea580c;
      box-shadow: 0 0 6px rgba(234, 88, 12, 0.3);
    }

    .overlay h1 {
      font-size: 1.5rem;
      color: #0f172a;
      margin-bottom: 8px;
    }

    .overlay p {
      font-size: 0.9rem;
      color: #475569;
      line-height: 1.5;
      margin-bottom: 16px;
      max-width: 500px;
    }

    .btn-group {
      display: flex;
      gap: 12px;
      margin-top: 10px;
      justify-content: center;
      width: 100%;
    }

    .btn {
      background: #ea580c;
      color: white;
      border: none;
      padding: 10px 24px;
      font-size: 1.05rem;
      font-weight: bold;
      border-radius: 50px;
      cursor: pointer;
      box-shadow: 0 6px 16px rgba(234, 88, 12, 0.35);
      transition: transform 0.15s ease, background-color 0.2s;
    }

    .btn-secondary {
      background: #0284c7;
      box-shadow: 0 6px 16px rgba(2, 132, 199, 0.35);
    }

    .btn-secondary:hover {
      background: #0369a1;
    }

    .btn:hover {
      transform: translateY(-2px);
      background: #c2410c;
    }

    .btn:active {
      transform: translateY(0);
    }

    .final-score {
      font-size: 2.6rem;
      font-weight: 900;
      color: #ea580c;
      margin: 4px 0;
    }

    .leaderboard-container {
      width: 100%;
      max-width: 420px;
      background: #f8fafc;
      border: 2px solid #e2e8f0;
      border-radius: 16px;
      padding: 10px;
      margin-top: 8px;
    }

    .leaderboard-title {
      font-size: 0.95rem;
      font-weight: 800;
      color: #0f172a;
      margin-bottom: 6px;
    }

    .leaderboard-table {
      width: 100%;
      border-collapse: collapse;
      font-size: 0.85rem;
    }

    .leaderboard-table th, .leaderboard-table td {
      padding: 5px 6px;
      text-align: center;
      border-bottom: 1px solid #e2e8f0;
    }

    .leaderboard-table th {
      background: #e2e8f0;
      color: #334155;
      font-weight: 700;
    }

    .leaderboard-table tr:nth-child(1) td { color: #d97706; font-weight: 800; }
    .leaderboard-table tr:nth-child(2) td { color: #475569; font-weight: 800; }
    .leaderboard-table tr:nth-child(3) td { color: #b45309; font-weight: 800; }
  </style>
</head>
<body>

  <div class="game-card">
    <div class="header">
      <div class="stat-box">⏳ <span id="time-display" class="stat-value">1:30</span></div>
      <div class="stat-box"><span id="level-display" class="level-badge">第 1 關 (基礎單韻母)</span></div>
      <div class="stat-box">📌 <span id="q-progress" class="stat-value">1/150</span></div>
      <div class="stat-box">🏆 <span id="score-display" class="stat-value">0</span></div>
      <button id="mute-btn" class="mute-btn">🔊 音效：開</button>
    </div>

    <div class="question-banner">
      <div id="question-hint" class="question-hint">🎧 聽音節長音（約4秒），找出正確的韻母！</div>
      <div id="question-text" class="question-text">載入中...</div>
      <button id="play-audio-btn" class="audio-btn">🔊 點擊重播讀音 (4秒長音)</button>
    </div>

    <div class="canvas-container">
      <canvas id="gameCanvas" width="600" height="500"></canvas>

      <div id="start-screen" class="overlay">
        <div class="user-inputs-top">
          <input type="text" id="input-class" placeholder="班別 (如2A)" maxlength="10">
          <input type="text" id="input-id" placeholder="學號 (如01)" maxlength="10">
        </div>

        <h1>🏀 單韻母與四聲 - 聽音辨韻大賽 🎧</h1>
        <p><b>二年級漢語拼音專題練習 (150字大題庫)</b><br>
        <b>玩法說明：</b>聽系統播放的長音（約4秒）後，投進帶有正確單韻母的籃球！<br>
        🏀 <b>每投進一球得 10 分！</b><br>
        • <b>第 1 關：基礎單韻母</b>（顯示拼音，辨認 a, o, e, i, u, ü）<br>
        • <b>第 2 關：單韻母與四聲</b>（<b>不顯示拼音</b>，混和不同韻母與聲調）<br>
        <b>滿 60 分即可自動晉級第二關！限時 1分30秒</b>，輸入班號後開始！</p>

        <button id="start-btn" class="btn">開始挑戰 (1分30秒)</button>
      </div>

      <div id="end-screen" class="overlay hidden" style="justify-content: center;">
        <h1>⏰ 挑戰時間到！</h1>
        <p id="player-info-display" style="font-weight: bold; color: #0284c7; margin-bottom: 0;"></p>
        <div id="final-score" class="final-score">0</div>
        <p id="eval-text" style="font-weight: bold; margin-bottom: 6px;"></p>
        
        <div class="leaderboard-container">
          <div class="leaderboard-title">🏆 班級最高分龍虎榜 (Top 5)</div>
          <table class="leaderboard-table">
            <thead>
              <tr>
                <th>名次</th>
                <th>班別</th>
                <th>學號</th>
                <th>最高分</th>
              </tr>
            </thead>
            <tbody id="leaderboard-body">
            </tbody>
          </table>
        </div>

        <div class="btn-group">
          <button id="restart-btn" class="btn">再次挑戰</button>
          <button id="switch-player-btn" class="btn btn-secondary">換人遊玩</button>
        </div>
      </div>
    </div>
  </div>

  <script>
    // 150 個適合小二學生能認讀且屬於單韻母 (a, o, e, i, u, ü) 的漢字庫
    const RAW_VOCAB = [
      // === a (25字) ===
      { c: "八", p: "bā", b: "a", t: "ā" }, { c: "爸", p: "bà", b: "a", t: "à" },
      { c: "爬", p: "pá", b: "a", t: "á" }, { c: "怕", p: "pà", b: "a", t: "à" },
      { c: "媽", p: "mā", b: "a", t: "ā" }, { c: "馬", p: "mǎ", b: "a", t: "ǎ" },
      { c: "打", p: "dǎ", b: "a", t: "ǎ" }, { c: "踏", p: "tà", b: "a", t: "à" },
      { c: "拿", p: "ná", b: "a", t: "á" }, { c: "哪", p: "nǎ", b: "a", t: "ǎ" },
      { c: "拉", p: "lā", b: "a", t: "ā" }, { c: "喇", p: "lǎ", b: "a", t: "ǎ" },
      { c: "蠟", p: "là", b: "a", t: "à" }, { c: "哈", p: "hā", b: "a", t: "ā" },
      { c: "扎", p: "zhā", b: "a", t: "ā" }, { c: "查", p: "chá", b: "a", t: "á" },
      { c: "叉", p: "chā", b: "a", t: "ā" }, { c: "沙", p: "shā", b: "a", t: "ā" },
      { c: "傻", p: "shǎ", b: "a", t: "ǎ" }, { c: "雜", p: "zá", b: "a", t: "á" },
      { c: "擦", p: "cā", b: "a", t: "ā" }, { c: "撒", p: "sā", b: "a", t: "ā" },
      { c: "蛙", p: "wā", b: "a", t: "ā" }, { c: "牙", p: "yá", b: "a", t: "á" },
      { c: "鴨", p: "yā", b: "a", t: "ā" },

      // === o (15字) ===
      { c: "玻", p: "bō", b: "o", t: "ō" }, { c: "播", p: "bō", b: "o", t: "ō" },
      { c: "坡", p: "pō", b: "o", t: "ō" }, { c: "破", p: "pò", b: "o", t: "ò" },
      { c: "婆", p: "pó", b: "o", t: "ó" }, { c: "摸", p: "mō", b: "o", t: "ō" },
      { c: "磨", p: "mó", b: "o", t: "ó" }, { c: "抹", p: "mǒ", b: "o", t: "ǒ" },
      { c: "墨", p: "mò", b: "o", t: "ò" }, { c: "佛", p: "fó", b: "o", t: "ó" },
      { c: "我", p: "wǒ", b: "o", t: "ǒ" }, { c: "窩", p: "wō", b: "o", t: "ō" },
      { c: "握", p: "wò", b: "o", t: "ò" }, { c: "喔", p: "ō", b: "o", t: "ō" },
      { c: "莫", p: "mò", b: "o", t: "ò" },

      // === e (30字) ===
      { c: "哥", p: "gē", b: "e", t: "ē" }, { c: "割", p: "gē", b: "e", t: "ē" },
      { c: "各", p: "gè", b: "e", t: "è" }, { c: "科", p: "kē", b: "e", t: "ē" },
      { c: "棵", p: "kē", b: "e", t: "ē" }, { c: "渴", p: "kě", b: "e", t: "ě" },
      { c: "客", p: "kè", b: "e", t: "è" }, { c: "喝", p: "hē", b: "e", t: "ē" },
      { c: "盒", p: "hé", b: "e", t: "é" }, { c: "河", p: "hé", b: "e", t: "é" },
      { c: "和", p: "hé", b: "e", t: "é" }, { c: "鵝", p: "é", b: "e", t: "é" },
      { c: "蛾", p: "é", b: "e", t: "é" }, { c: "額", p: "é", b: "e", t: "é" },
      { c: "餓", p: "è", b: "e", t: "è" }, { c: "惡", p: "è", b: "e", t: "è" },
      { c: "車", p: "chē", b: "e", t: "ē" }, { c: "扯", p: "chě", b: "e", t: "ě" },
      { c: "蛇", p: "shé", b: "e", t: "é" }, { c: "舍", p: "shè", b: "e", t: "è" },
      { c: "熱", p: "rè", b: "e", t: "è" }, { c: "惹", p: "rě", b: "e", t: "ě" },
      { c: "遮", p: "zhē", b: "e", t: "ē" }, { c: "哲", p: "zhé", b: "e", t: "é" },
      { c: "冊", p: "cè", b: "e", t: "è" }, { c: "策", p: "cè", b: "e", t: "è" },
      { c: "特", p: "tè", b: "e", t: "è" }, { c: "德", p: "dé", b: "e", t: "é" },
      { c: "樂", p: "lè", b: "e", t: "è" }, { c: "設", p: "shè", b: "e", t: "è" },

      // === i (40字) ===
      { c: "衣", p: "yī", b: "i", t: "ī" }, { c: "醫", p: "yī", b: "i", t: "ī" },
      { c: "姨", p: "yí", b: "i", t: "í" }, { c: "椅", p: "yǐ", b: "i", t: "ǐ" },
      { c: "億", p: "yì", b: "i", t: "ì" }, { c: "比", p: "bǐ", b: "i", t: "ǐ" },
      { c: "筆", p: "bǐ", b: "i", t: "ǐ" }, { c: "幣", p: "bì", b: "i", t: "ì" },
      { c: "皮", p: "pí", b: "i", t: "í" }, { c: "匹", p: "pǐ", b: "i", t: "ǐ" },
      { c: "米", p: "mǐ", b: "i", t: "ǐ" }, { c: "迷", p: "mí", b: "i", t: "í" },
      { c: "密", p: "mì", b: "i", t: "ì" }, { c: "低", p: "dī", b: "i", t: "ī" },
      { c: "底", p: "dǐ", b: "i", t: "ǐ" }, { c: "弟", p: "dì", b: "i", t: "ì" },
      { c: "提", p: "tí", b: "i", t: "í" }, { c: "題", p: "tí", b: "i", t: "í" },
      { c: "泥", p: "ní", b: "i", t: "í" }, { c: "你", p: "nǐ", b: "i", t: "ǐ" },
      { c: "離", p: "lí", b: "i", t: "í" }, { c: "禮", p: "lǐ", b: "i", t: "ǐ" },
      { c: "雞", p: "jī", b: "i", t: "ī" }, { c: "七", p: "qī", b: "i", t: "ī" },
      { c: "期", p: "qī", b: "i", t: "ī" }, { c: "起", p: "qǐ", b: "i", t: "ǐ" },
      { c: "器", p: "qì", b: "i", t: "ì" }, { c: "西", p: "xī", b: "i", t: "ī" },
      { c: "喜", p: "xǐ", b: "i", t: "ǐ" }, { c: "細", p: "xì", b: "i", t: "ì" },
      { c: "只", p: "zhī", b: "i", t: "ī" }, { c: "枝", p: "zhī", b: "i", t: "ī" },
      { c: "紙", p: "zhǐ", b: "i", t: "ǐ" }, { c: "吃", p: "chī", b: "i", t: "ī" },
      { c: "獅", p: "shī", b: "i", t: "ī" }, { c: "詩", p: "shī", b: "i", t: "ī" },
      { c: "十", p: "shí", b: "i", t: "í" }, { c: "是", p: "shì", b: "i", t: "ì" },
      { c: "日", p: "rì", b: "i", t: "ì" }, { c: "字", p: "zì", b: "i", t: "ì" },

      // === u (25字) ===
      { c: "烏", p: "wū", b: "u", t: "ū" }, { c: "屋", p: "wū", b: "u", t: "ū" },
      { c: "無", p: "wú", b: "u", t: "ú" }, { c: "五", p: "wǔ", b: "u", t: "ǔ" },
      { c: "武", p: "wǔ", b: "u", t: "ǔ" }, { c: "物", p: "wù", b: "u", t: "ù" },
      { c: "霧", p: "wù", b: "u", t: "ù" }, { c: "不", p: "bù", b: "u", t: "ù" },
      { c: "布", p: "bù", b: "u", t: "ù" }, { c: "撲", p: "pū", b: "u", t: "ū" },
      { c: "葡", p: "pú", b: "u", t: "ú" }, { c: "木", p: "mù", b: "u", t: "ù" },
      { c: "目", p: "mù", b: "u", t: "ù" }, { c: "堵", p: "dǔ", b: "u", t: "ǔ" },
      { c: "讀", p: "dú", b: "u", t: "ú" }, { c: "兔", p: "tù", b: "u", t: "ù" },
      { c: "圖", p: "tú", b: "u", t: "ú" }, { c: "怒", p: "nù", b: "u", t: "ù" },
      { c: "路", p: "lù", b: "u", t: "ù" }, { c: "鹿", p: "lù", b: "u", t: "ù" },
      { c: "姑", p: "gū", b: "u", t: "ū" }, { c: "鼓", p: "gǔ", b: "u", t: "ǔ" },
      { c: "哭", p: "kū", b: "u", t: "ū" }, { c: "苦", p: "kǔ", b: "u", t: "ǔ" },
      { c: "湖", p: "hú", b: "u", t: "ú" },

      // === ü (15字) ===
      { c: "魚", p: "yú", b: "ü", t: "ǘ" }, { c: "雨", p: "yǔ", b: "ü", t: "ǚ" },
      { c: "玉", p: "yù", b: "ü", t: "ǜ" }, { c: "綠", p: "lǜ", b: "ü", t: "ǜ" },
      { c: "女", p: "nǚ", b: "ü", t: "ǚ" }, { c: "居", p: "jū", b: "ü", t: "ǖ" },
      { c: "局", p: "jú", b: "ü", t: "ǘ" }, { c: "舉", p: "jǔ", b: "ü", t: "ǚ" },
      { c: "句", p: "jù", b: "ü", t: "ǜ" }, { c: "去", p: "qù", b: "ü", t: "ǜ" },
      { c: "取", p: "qǔ", b: "ü", t: "ǚ" }, { c: "虛", p: "xū", b: "ü", t: "ǖ" },
      { c: "許", p: "xǔ", b: "ü", t: "ǚ" }, { c: "律", p: "lǜ", b: "ü", t: "ǜ" },
      { c: "曲", p: "qǔ", b: "ü", t: "ǚ" }
    ];

    const ALL_BASE_VOWELS = ["a", "o", "e", "i", "u", "ü"];
    const ALL_TONED_VOWELS = [
      "ā", "á", "ǎ", "à",
      "ō", "ó", "ǒ", "ò",
      "ē", "é", "ě", "è",
      "ī", "í", "ǐ", "ì",
      "ū", "ú", "ǔ", "ù",
      "ǖ", "ǘ", "ǚ", "ǜ"
    ];

    // 動態生成關卡題庫與隨機干擾選項
    function generateQuestionPools() {
      const qL1 = [];
      const qL2 = [];

      RAW_VOCAB.forEach(item => {
        // 第一關干擾選項：正確單韻母 + 隨機3個其他單韻母
        const wrongBases = ALL_BASE_VOWELS.filter(v => v !== item.b).sort(() => Math.random() - 0.5).slice(0, 3);
        const optionsL1 = [item.b, ...wrongBases];

        qL1.push({
          char: item.c,
          pinyin: item.p,
          textToSpeak: item.c,
          correct: item.b,
          options: optionsL1
        });

        // 第二關干擾選項：帶調單韻母 + 隨機3個其他帶調單韻母
        const wrongToned = ALL_TONED_VOWELS.filter(v => v !== item.t).sort(() => Math.random() - 0.5).slice(0, 3);
        const optionsL2 = [item.t, ...wrongToned];

        qL2.push({
          char: item.c,
          pinyin: item.p,
          textToSpeak: item.c,
          correct: item.t,
          options: optionsL2
        });
      });

      return { qL1, qL2 };
    }

    let allGeneratedQuestions = generateQuestionPools();
    let audioCtx = null;
    let isMuted = false;

    function initAudio() {
      if (!audioCtx) audioCtx = new (window.AudioContext || window.webkitAudioContext)();
      if (audioCtx.state === 'suspended') audioCtx.resume();
    }

    function playSound(type) {
      if (isMuted) return;
      initAudio();
      const osc = audioCtx.createOscillator();
      const gain = audioCtx.createGain();
      osc.connect(gain);
      gain.connect(audioCtx.destination);
      const now = audioCtx.currentTime;

      if (type === 'swish') {
        osc.type = 'triangle';
        osc.frequency.setValueAtTime(600, now);
        osc.frequency.exponentialRampToValueAtTime(1200, now + 0.15);
        gain.gain.setValueAtTime(0.3, now);
        gain.gain.exponentialRampToValueAtTime(0.01, now + 0.15);
        osc.start(now);
        osc.stop(now + 0.15);
      } else if (type === 'rim') {
        osc.type = 'sawtooth';
        osc.frequency.setValueAtTime(160, now);
        osc.frequency.linearRampToValueAtTime(80, now + 0.2);
        gain.gain.setValueAtTime(0.25, now);
        gain.gain.exponentialRampToValueAtTime(0.01, now + 0.2);
        osc.start(now);
        osc.stop(now + 0.2);
      } else if (type === 'levelup') {
        osc.type = 'sine';
        osc.frequency.setValueAtTime(440, now);
        osc.frequency.setValueAtTime(880, now + 0.15);
        gain.gain.setValueAtTime(0.3, now);
        gain.gain.exponentialRampToValueAtTime(0.01, now + 0.35);
        osc.start(now);
        osc.stop(now + 0.35);
      } else if (type === 'gameover') {
        osc.type = 'square';
        osc.frequency.setValueAtTime(400, now);
        osc.frequency.linearRampToValueAtTime(150, now + 0.6);
        gain.gain.setValueAtTime(0.2, now);
        gain.gain.linearRampToValueAtTime(0.01, now + 0.6);
        osc.start(now);
        osc.stop(now + 0.6);
      }
    }

    // 播放國語語音 (Web Speech API) - 音量最大化，語速放慢至約 4 秒長音
    function playSpeech(text) {
      if ('speechSynthesis' in window) {
        window.speechSynthesis.cancel();
        const msg = new SpeechSynthesisUtterance(text);
        msg.lang = 'zh-TW';
        msg.volume = 1.0; // 將朗讀音量調至最大
        msg.rate = 0.18;   // 將語速放慢至約 4 秒長音
        window.speechSynthesis.speak(msg);
      }
    }

    // 格式化時間 (秒 -> 分:秒，如 90 -> 1:30)
    function formatTime(seconds) {
      const m = Math.floor(seconds / 60);
      const s = Math.floor(seconds % 60);
      return `${m}:${s < 10 ? '0' : ''}${s}`;
    }

    const canvas = document.getElementById('gameCanvas');
    const ctx = canvas.getContext('2d');
    const timeDisplay = document.getElementById('time-display');
    const scoreDisplay = document.getElementById('score-display');
    const levelDisplay = document.getElementById('level-display');
    const qProgressDisplay = document.getElementById('q-progress');
    const questionText = document.getElementById('question-text');
    const questionHint = document.getElementById('question-hint');
    const playAudioBtn = document.getElementById('play-audio-btn');
    const startScreen = document.getElementById('start-screen');
    const endScreen = document.getElementById('end-screen');
    const startBtn = document.getElementById('start-btn');
    const restartBtn = document.getElementById('restart-btn');
    const switchPlayerBtn = document.getElementById('switch-player-btn');
    const muteBtn = document.getElementById('mute-btn');
    const finalScoreDisplay = document.getElementById('final-score');
    const evalTextDisplay = document.getElementById('eval-text');
    const inputClass = document.getElementById('input-class');
    const inputId = document.getElementById('input-id');
    const playerInfoDisplay = document.getElementById('player-info-display');
    const leaderboardBody = document.getElementById('leaderboard-body');

    let gameState = 'START';
    let score = 0;
    let timeLeft = 90; // 限時 1分30秒 (90秒)
    let lastTime = 0;
    let currentLevel = 1;
    let currentQIndex = 0;
    let questionPool = [];
    let currentStudent = { className: '', studentId: '' };

    const HOOP = { x: 300, y: 105, scale: 1.0 };
    const BALL_POSITIONS = [
      { x: 90,  y: 415 },
      { x: 230, y: 415 },
      { x: 370, y: 415 },
      { x: 510, y: 415 }
    ];

    let optionBalls = [];
    let activeShootBall = null;
    let floatTexts = [];

    function initQuestionPool(level) {
      const source = level === 1 ? allGeneratedQuestions.qL1 : allGeneratedQuestions.qL2;
      questionPool = [...source].sort(() => Math.random() - 0.5);
      currentQIndex = 0;
    }

    function renderQuestionText() {
      const q = questionPool[currentQIndex];
      questionHint.innerHTML = "🎧 聽音節長音（約4秒），找出正確的韻母！";
      
      let charPromptHtml = "";
      if (currentLevel === 1) {
        // 第一關：顯示漢字與拼音
        charPromptHtml = `漢字：<b>「${q.char}」</b> (${q.pinyin})<br><span style="font-size:0.95rem; color:#fde047;">請問這個字的單韻母是什麼？</span>`;
      } else {
        // 第二關：隱藏拼音，考考學生耳朵聽四聲！
        charPromptHtml = `漢字：<b>「${q.char}」</b> <span style="font-size:0.85rem; color:#cbd5e1;">(拼音已隱藏)</span><br><span style="font-size:0.95rem; color:#fde047;">請聽音辨認帶聲調的單韻母！</span>`;
      }

      questionText.innerHTML = charPromptHtml;
      qProgressDisplay.textContent = `${currentQIndex + 1}/${questionPool.length}`;

      // 自動播放當前音節延長讀音
      playSpeech(q.textToSpeak);
    }

    playAudioBtn.addEventListener('click', () => {
      if (questionPool[currentQIndex]) {
        playSpeech(questionPool[currentQIndex].textToSpeak);
      }
    });

    function loadBallsForCurrentQuestion() {
      const q = questionPool[currentQIndex];
      const shuffledOptions = [...q.options].sort(() => Math.random() - 0.5);

      optionBalls = shuffledOptions.map((optText, i) => ({
        symbol: optText,
        startX: BALL_POSITIONS[i].x,
        startY: BALL_POSITIONS[i].y,
        currentX: BALL_POSITIONS[i].x,
        currentY: BALL_POSITIONS[i].y,
        radius: 42,
        isShooting: false
      }));

      activeShootBall = null;
    }

    function loadQuestion() {
      if (currentQIndex >= questionPool.length) {
        initQuestionPool(currentLevel);
      }
      renderQuestionText();
      loadBallsForCurrentQuestion();
    }

    // 第一關滿 60 分進入第二關
    function checkLevelProgression() {
      if (currentLevel === 1 && score >= 60) {
        currentLevel = 2;
        playSound('levelup');
        levelDisplay.textContent = '第 2 關 (四聲調·混和韻母)';
        levelDisplay.style.background = '#ea580c';
        addFloatText('🎉 滿60分晉級第2關！(拼音已隱藏)', 300, 200, '#fde047');
        initQuestionPool(2);
        loadQuestion();
      }
    }

    canvas.addEventListener('click', (e) => {
      if (gameState !== 'PLAYING' || activeShootBall || optionBalls.length === 0) return;

      const rect = canvas.getBoundingClientRect();
      const scaleX = canvas.width / rect.width;
      const scaleY = canvas.height / rect.height;
      const clickX = (e.clientX - rect.left) * scaleX;
      const clickY = (e.clientY - rect.top) * scaleY;

      for (let ball of optionBalls) {
        const dist = Math.hypot(clickX - ball.currentX, clickY - ball.currentY);
        if (dist <= ball.radius + 10) {
          shootBall(ball);
          break;
        }
      }
    });

    function shootBall(ball) {
      ball.isShooting = true;
      activeShootBall = {
        symbol: ball.symbol,
        startX: ball.currentX,
        startY: ball.currentY,
        currentX: ball.currentX,
        currentY: ball.currentY,
        progress: 0,
        radius: ball.radius
      };
    }

    function addFloatText(text, x, y, color) {
      floatTexts.push({ text, x, y, color, alpha: 1.0, life: 50 });
    }

    muteBtn.addEventListener('click', () => {
      isMuted = !isMuted;
      muteBtn.textContent = isMuted ? '🔇 音效：關' : '🔊 音效：開';
    });

    startBtn.addEventListener('click', startGame);
    
    // 再次挑戰：同一位同學直接重新開始
    restartBtn.addEventListener('click', startGame);

    // 換人遊玩：返回首頁並清空班級與學號輸入框
    switchPlayerBtn.addEventListener('click', () => {
      endScreen.classList.add('hidden');
      startScreen.classList.remove('hidden');
      inputClass.value = '';
      inputId.value = '';
      inputClass.focus();
    });

    function startGame() {
      const className = inputClass.value.trim();
      const studentId = inputId.value.trim();

      if (!className || !studentId) {
        alert('請先輸入「班別」與「學號」再開始挑戰喔！');
        return;
      }

      currentStudent = { className, studentId };
      initAudio();
      allGeneratedQuestions = generateQuestionPools(); // 每次開局刷新隨機干擾題庫

      score = 0;
      timeLeft = 90; // 1分30秒 (90秒)
      currentLevel = 1;
      floatTexts = [];
      scoreDisplay.textContent = score;
      timeDisplay.textContent = formatTime(timeLeft);
      levelDisplay.textContent = '第 1 關 (基礎單韻母)';
      levelDisplay.style.background = '#0284c7';

      initQuestionPool(1);
      loadQuestion();

      startScreen.classList.add('hidden');
      endScreen.classList.add('hidden');
      gameState = 'PLAYING';

      lastTime = performance.now();
      requestAnimationFrame(gameLoop);
    }

    function updateLeaderboard(className, studentId, finalScore) {
      let scores = [];
      try {
        scores = JSON.parse(localStorage.getItem('pinyin_game_leaderboard_2g_150v') || '[]');
      } catch (e) {
        scores = [];
      }

      const key = `${className}_${studentId}`;
      const existingIdx = scores.findIndex(item => item.key === key);

      if (existingIdx !== -1) {
        scores[existingIdx].score = Math.max(scores[existingIdx].score, finalScore);
      } else {
        scores.push({ key, className, studentId, score: finalScore });
      }

      scores.sort((a, b) => b.score - a.score);
      localStorage.setItem('pinyin_game_leaderboard_2g_150v', JSON.stringify(scores));

      leaderboardBody.innerHTML = '';
      const top5 = scores.slice(0, 5);
      
      top5.forEach((item, index) => {
        const tr = document.createElement('tr');
        tr.innerHTML = `
          <td>${index + 1}</td>
          <td>${item.className}</td>
          <td>${item.studentId}</td>
          <td>${item.score}</td>
        `;
        leaderboardBody.appendChild(tr);
      });
    }

    function endGame() {
      gameState = 'GAMEOVER';
      playSound('gameover');
      finalScoreDisplay.textContent = score;
      playerInfoDisplay.textContent = `玩家：${currentStudent.className} 班 ${currentStudent.studentId} 號`;

      if (score >= 120) {
        evalTextDisplay.textContent = '🌟 太厲害了！得分突破120分！單韻母與四聲完全掌握！';
      } else if (score >= 80) {
        evalTextDisplay.textContent = '👍 非常棒！聽力與四聲辨識度極佳！';
      } else if (score >= 60) {
        evalTextDisplay.textContent = '👏 成功突破 60 分解鎖第二關！表現優良！';
      } else {
        evalTextDisplay.textContent = '💪 多多聽音練習，下次一定能獲得更棒的成績！';
      }

      updateLeaderboard(currentStudent.className, currentStudent.studentId, score);
      endScreen.classList.remove('hidden');
    }

    function gameLoop(now) {
      if (gameState !== 'PLAYING') return;

      const dt = (now - lastTime) / 1000;
      lastTime = now;

      timeLeft -= dt;
      if (timeLeft <= 0) {
        timeLeft = 0;
        timeDisplay.textContent = "0:00";
        endGame();
        return;
      }
      timeDisplay.textContent = formatTime(Math.ceil(timeLeft));

      if (activeShootBall) {
        activeShootBall.progress += dt * 3.2;

        if (activeShootBall.progress >= 1) {
          const shotBall = activeShootBall;
          activeShootBall = null;

          const currentQ = questionPool[currentQIndex];

          if (shotBall.symbol === currentQ.correct) {
            score += 10; // 每球 10 分
            playSound('swish');
            HOOP.scale = 1.25;
            addFloatText('答對 +10分！', HOOP.x, HOOP.y - 20, '#22c55e');
            scoreDisplay.textContent = score;

            checkLevelProgression();
            currentQIndex++;
            loadQuestion();
          } else {
            score = Math.max(0, score - 5);
            playSound('rim');
            addFloatText('答錯扣5分，再試一次！', HOOP.x, HOOP.y - 20, '#ef4444');
            loadBallsForCurrentQuestion();
          }

          scoreDisplay.textContent = score;
        } else {
          const t = activeShootBall.progress;
          const p0 = { x: activeShootBall.startX, y: activeShootBall.startY };
          const p1 = { x: (activeShootBall.startX + HOOP.x) / 2, y: Math.min(activeShootBall.startY, HOOP.y) - 80 };
          const p2 = { x: HOOP.x, y: HOOP.y + 10 };

          activeShootBall.currentX = (1 - t) * (1 - t) * p0.x + 2 * (1 - t) * t * p1.x + t * t * p2.x;
          activeShootBall.currentY = (1 - t) * (1 - t) * p0.y + 2 * (1 - t) * t * p1.y + t * t * p2.y;
        }
      }

      if (HOOP.scale > 1) {
        HOOP.scale -= dt * 1.5;
      } else {
        HOOP.scale = 1;
      }

      render();
      requestAnimationFrame(gameLoop);
    }

    function render() {
      ctx.clearRect(0, 0, canvas.width, canvas.height);

      ctx.fillStyle = '#1e293b';
      ctx.fillRect(0, 0, canvas.width, canvas.height);

      ctx.strokeStyle = 'rgba(255, 255, 255, 0.08)';
      ctx.lineWidth = 4;
      ctx.beginPath();
      ctx.arc(300, 500, 250, Math.PI, 0);
      ctx.stroke();

      ctx.save();
      ctx.translate(HOOP.x, HOOP.y);
      ctx.scale(HOOP.scale, HOOP.scale);

      ctx.fillStyle = '#ffffff';
      ctx.strokeStyle = '#cbd5e1';
      ctx.lineWidth = 4;
      ctx.beginPath();
      if (ctx.roundRect) ctx.roundRect(-60, -50, 120, 55, 10);
      else ctx.rect(-60, -50, 120, 55);
      ctx.fill();
      ctx.stroke();

      ctx.strokeStyle = '#ea580c';
      ctx.lineWidth = 3;
      ctx.strokeRect(-25, -35, 50, 35);

      ctx.strokeStyle = 'rgba(255, 255, 255, 0.75)';
      ctx.lineWidth = 2;
      ctx.beginPath();
      ctx.moveTo(-28, 5); ctx.lineTo(-14, 45);
      ctx.moveTo(28, 5); ctx.lineTo(14, 45);
      ctx.moveTo(-14, 45); ctx.lineTo(14, 45);
      ctx.moveTo(0, 5); ctx.lineTo(0, 45);
      ctx.moveTo(-20, 22); ctx.lineTo(20, 22);
      ctx.stroke();

      ctx.strokeStyle = '#ea580c';
      ctx.lineWidth = 7;
      ctx.beginPath();
      ctx.ellipse(0, 5, 30, 9, 0, 0, Math.PI * 2);
      ctx.stroke();

      ctx.restore();

      optionBalls.forEach(ball => {
        if (ball.isShooting) return;
        drawBasketball(ball.currentX, ball.currentY, ball.radius, ball.symbol, 1.0);
      });

      if (activeShootBall) {
        const scaleFactor = 1 - (activeShootBall.progress * 0.35);
        drawBasketball(
          activeShootBall.currentX,
          activeShootBall.currentY,
          activeShootBall.radius,
          activeShootBall.symbol,
          scaleFactor
        );
      }

      for (let i = floatTexts.length - 1; i >= 0; i--) {
        const ft = floatTexts[i];
        ctx.save();
        ctx.globalAlpha = ft.alpha;
        ctx.font = '900 22px sans-serif';
        ctx.fillStyle = ft.color;
        ctx.textAlign = 'center';
        ctx.fillText(ft.text, ft.x, ft.y);
        ctx.restore();

        ft.y -= 1.2;
        ft.alpha -= 0.02;
        ft.life--;
        if (ft.life <= 0) floatTexts.splice(i, 1);
      }
    }

    function drawBasketball(x, y, radius, symbolText, scale) {
      ctx.save();
      ctx.translate(x, y);
      ctx.scale(scale, scale);

      ctx.shadowColor = 'rgba(0, 0, 0, 0.4)';
      ctx.shadowBlur = 8;

      ctx.fillStyle = '#f97316';
      ctx.beginPath();
      ctx.arc(0, 0, radius, 0, Math.PI * 2);
      ctx.fill();

      ctx.shadowBlur = 0;
      ctx.strokeStyle = '#c2410c';
      ctx.lineWidth = 3;
      ctx.stroke();

      ctx.strokeStyle = '#0f172a';
      ctx.lineWidth = 2.5;
      ctx.beginPath();
      ctx.moveTo(-radius, 0); ctx.lineTo(radius, 0);
      ctx.moveTo(0, -radius); ctx.lineTo(0, radius);
      ctx.arc(-10, 0, 28, -Math.PI / 2, Math.PI / 2);
      ctx.arc(10, 0, 28, Math.PI / 2, -Math.PI / 2);
      ctx.stroke();

      ctx.fillStyle = '#ffffff';
      ctx.beginPath();
      ctx.arc(0, 0, 24, 0, Math.PI * 2);
      ctx.fill();
      ctx.strokeStyle = '#ea580c';
      ctx.lineWidth = 2;
      ctx.stroke();

      ctx.fillStyle = '#0f172a';
      ctx.font = '900 22px "Comic Sans MS", "Microsoft JhengHei", Arial, sans-serif';
      ctx.textAlign = 'center';
      ctx.textBaseline = 'middle';
      ctx.fillText(symbolText, 0, 1);

      ctx.restore();
    }

    render();
  </script>
</body>
</html>
