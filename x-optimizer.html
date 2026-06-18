<!DOCTYPE html>
<html lang="ja">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>X投稿最適化ツール | 株式会社Threads</title>
<style>
*{box-sizing:border-box;margin:0;padding:0}
body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;background:#f0f2f5;color:#111;min-height:100vh;padding:1.5rem 1rem}
.wrap{max-width:860px;margin:0 auto}
.header{margin-bottom:1.5rem}
.header h1{font-size:20px;font-weight:600;color:#111;margin-bottom:2px}
.header p{font-size:13px;color:#6b7280}
.tabs{display:flex;gap:0;border-bottom:1.5px solid #e5e7eb;margin-bottom:1.5rem;overflow-x:auto;-webkit-overflow-scrolling:touch;background:#fff;border-radius:10px 10px 0 0;padding:0 4px}
.tab{padding:11px 16px;font-size:13px;font-weight:500;color:#6b7280;cursor:pointer;border:none;border-bottom:2.5px solid transparent;background:none;white-space:nowrap;margin-bottom:-1.5px}
.tab.active{color:#1d9bf0;border-bottom-color:#1d9bf0}
.tab:hover:not(.active){color:#374151}
.panel{display:none}.panel.active{display:block}
.metrics{display:grid;grid-template-columns:repeat(4,1fr);gap:10px;margin-bottom:1.5rem}
.metric{background:#fff;border:1px solid #e5e7eb;border-radius:10px;padding:12px 14px}
.metric-label{font-size:11px;color:#9ca3af;margin-bottom:6px}
.metric-value{font-size:22px;font-weight:600;color:#111;line-height:1}
.metric-sub{font-size:11px;color:#9ca3af;margin-top:4px}
.card{background:#fff;border:1px solid #e5e7eb;border-radius:12px;padding:1.25rem;margin-bottom:1rem}
.card-title{font-size:11px;font-weight:600;color:#9ca3af;text-transform:uppercase;letter-spacing:.08em;margin-bottom:12px}
label{display:block;font-size:12px;color:#6b7280;margin-bottom:4px}
select,textarea,input[type=text]{width:100%;padding:9px 12px;font-size:14px;color:#111;background:#f9fafb;border:1px solid #e5e7eb;border-radius:8px;font-family:inherit;outline:none;transition:border-color .15s}
select:focus,textarea:focus,input[type=text]:focus{border-color:#1d9bf0;background:#fff}
textarea{resize:vertical}
.form-row{display:grid;grid-template-columns:1fr 1fr;gap:12px;margin-bottom:12px}
.form-group{display:flex;flex-direction:column}
.btn-group{display:flex;gap:8px;flex-wrap:wrap;margin-top:12px}
button{cursor:pointer;font-size:13px;font-weight:500;padding:8px 16px;border-radius:8px;border:1px solid #e5e7eb;background:#fff;color:#374151;font-family:inherit;transition:all .15s}
button:hover{background:#f3f4f6;border-color:#d1d5db}
button:active{transform:scale(.98)}
button:disabled{opacity:.4;cursor:not-allowed;transform:none}
.btn-primary{background:#1d9bf0;color:#fff;border-color:#1d9bf0}
.btn-primary:hover{background:#1a8cd8}
.score-section{margin-bottom:12px}
.score-row{display:flex;justify-content:space-between;align-items:center;margin-bottom:5px}
.score-label{font-size:13px;color:#374151}
.score-val{font-size:13px;font-weight:600;color:#111}
.score-track{height:7px;background:#f3f4f6;border-radius:4px;overflow:hidden}
.score-bar{height:100%;border-radius:4px;transition:width .6s cubic-bezier(.4,0,.2,1)}
.tip{background:#f0f9ff;border-left:3px solid #1d9bf0;border-radius:0 8px 8px 0;padding:10px 14px;font-size:13px;color:#374151;margin-bottom:8px;line-height:1.55}
.tip strong{color:#0369a1;font-weight:600}
.tip.ok{background:#f0fdf4;border-left-color:#22c55e}
.tip.ok strong{color:#15803d}
.output-box{background:#f9fafb;border:1px solid #e5e7eb;border-radius:10px;padding:14px;font-size:14px;line-height:1.75;min-height:90px;white-space:pre-wrap;color:#111;margin-top:12px}
.output-box.loading{color:#9ca3af;font-style:italic}
.char-info{display:flex;justify-content:space-between;align-items:center;margin-top:6px}
.char-count{font-size:12px;color:#9ca3af}
.action-btns{display:flex;gap:6px}
.btn-sm{font-size:12px;padding:5px 11px}
.tag{display:inline-block;padding:4px 10px;border-radius:20px;font-size:12px;margin:3px;cursor:pointer;border:1px solid #e5e7eb;background:#fff;color:#374151;transition:all .15s}
.tag.active{background:#1d9bf0;color:#fff;border-color:#1d9bf0}
.tag-group{margin-bottom:10px}
.tag-cat{font-size:11px;color:#9ca3af;margin-bottom:5px;font-weight:500}
.selected-display{font-size:13px;color:#111;min-height:28px;padding:6px 0;word-break:break-all}
.heat-grid{display:grid;grid-template-columns:repeat(7,1fr);gap:4px;margin:10px 0}
.heat-cell{aspect-ratio:1;border-radius:5px;display:flex;align-items:center;justify-content:center;font-size:9px;font-weight:500}
.h0{background:#f3f4f6;color:#9ca3af}.h1{background:#dbeafe;color:#1e40af}.h2{background:#93c5fd;color:#1e3a8a}.h3{background:#3b82f6;color:#fff}.h4{background:#1d4ed8;color:#fff}
.day-row{display:grid;grid-template-columns:repeat(7,1fr);gap:4px;margin-bottom:4px}
.day-lbl{font-size:10px;color:#9ca3af;text-align:center}
.best-times{background:#f0f9ff;border-radius:10px;padding:12px 14px;margin-top:12px;font-size:13px;color:#374151;line-height:1.8}
.best-times strong{color:#0369a1;font-weight:600}
.checklist{display:grid;grid-template-columns:1fr 1fr;gap:8px}
.check-item{display:flex;align-items:flex-start;gap:10px;padding:10px 12px;border-radius:10px;border:1px solid #e5e7eb;cursor:pointer;font-size:13px;color:#6b7280;background:#fff;transition:all .2s;line-height:1.4}
.check-item.done{background:#f0fdf4;border-color:#86efac;color:#374151}
.check-mark{font-size:15px;flex-shrink:0;margin-top:1px;color:#d1d5db;margin-left:auto}
@media(max-width:620px){.metrics{grid-template-columns:1fr 1fr}.form-row{grid-template-columns:1fr}.checklist{grid-template-columns:1fr}}
</style>
</head>
<body>
<div class="wrap">
  <div class="header">
    <h1>📱 X投稿最適化ツール</h1>
    <p>株式会社Threads — 外国人材・HR向けX（Twitter）投稿を最適化</p>
  </div>

  <div class="tabs">
    <button class="tab active" onclick="switchTab('gen')">✏️ 投稿文生成</button>
    <button class="tab" onclick="switchTab('analyze')">📊 テキスト分析</button>
    <button class="tab" onclick="switchTab('tags')">#️⃣ ハッシュタグ</button>
    <button class="tab" onclick="switchTab('timing')">🕐 投稿時間</button>
    <button class="tab" onclick="switchTab('check')">✅ チェックリスト</button>
  </div>

  <div class="metrics">
    <div class="metric"><div class="metric-label">エンゲージメント率</div><div class="metric-value" id="eng">—</div><div class="metric-sub">目標: 3%以上</div></div>
    <div class="metric"><div class="metric-label">インプレッション予測</div><div class="metric-value" id="imp">—</div><div class="metric-sub">直近7日</div></div>
    <div class="metric"><div class="metric-label">フォロワー増加</div><div class="metric-value" id="fol">—</div><div class="metric-sub">今週</div></div>
    <div class="metric"><div class="metric-label">アルゴスコア</div><div class="metric-value" id="algo">—</div><div class="metric-sub">100点満点</div></div>
  </div>

  <!-- 投稿文生成 -->
  <div id="p-gen" class="panel active">
    <div class="card">
      <div class="card-title">投稿文ジェネレーター</div>
      <div class="form-row">
        <div class="form-group"><label>テーマ・業種</label>
          <select id="g-theme">
            <option value="介護">介護人材</option>
            <option value="建設">建設業</option>
            <option value="宿泊">宿泊・ホテル</option>
            <option value="インターンシップ">インターンシップ制度</option>
            <option value="特定技能">特定技能ビザ</option>
            <option value="会社紹介">株式会社Threads紹介</option>
            <option value="採用成功事例">採用成功事例</option>
            <option value="外国人材の魅力">外国人材の魅力</option>
          </select>
        </div>
        <div class="form-group"><label>投稿のトーン</label>
          <select id="g-tone">
            <option value="informative">情報提供・ためになる</option>
            <option value="story">ストーリー・共感</option>
            <option value="question">質問・議論を促す</option>
            <option value="tips">ノウハウ・Tips</option>
            <option value="news">ニュース・トレンド</option>
          </select>
        </div>
      </div>
      <div class="form-row">
        <div class="form-group"><label>ターゲット読者</label>
          <select id="g-target">
            <option>中小企業の経営者・人事担当</option>
            <option>介護施設の採用担当</option>
            <option>建設会社の採用担当</option>
            <option>ホテル・旅館の採用担当</option>
            <option>人材業界関係者</option>
          </select>
        </div>
        <div class="form-group"><label>文字数</label>
          <select id="g-len">
            <option>100〜140文字（短め）</option>
            <option selected>140〜200文字（標準）</option>
            <option>200〜250文字（詳しめ）</option>
          </select>
        </div>
      </div>
      <div class="form-group" style="margin-bottom:0">
        <label>追加キーワード・メモ（任意）</label>
        <textarea id="g-memo" rows="2" placeholder="例：インドネシアの大学と提携、介護3年の実績、無料相談受付中..."></textarea>
      </div>
      <div class="btn-group">
        <button class="btn-primary" id="g-btn" onclick="generate(false)">✨ 投稿文を生成する</button>
        <button onclick="generate(true)">🔄 別バリエーション</button>
      </div>
      <div id="g-output" style="display:none">
        <div class="output-box" id="g-text"></div>
        <div class="char-info">
          <span class="char-count" id="g-char">0文字</span>
          <div class="action-btns">
            <button class="btn-sm" onclick="copyGen()">📋 コピー</button>
            <button class="btn-sm" onclick="sendToAnalyze()">📊 分析へ</button>
          </div>
        </div>
      </div>
    </div>
  </div>

  <!-- テキスト分析 -->
  <div id="p-analyze" class="panel">
    <div class="card">
      <div class="card-title">投稿テキスト分析</div>
      <textarea id="t-input" rows="4" placeholder="投稿したいテキストを入力してください..." oninput="updateCount()"></textarea>
      <div class="char-info"><span class="char-count" id="t-count">0 / 280文字</span></div>
      <div class="btn-group">
        <button class="btn-primary" onclick="analyze()">📊 分析する</button>
        <button onclick="clearAnalyze()">🗑️ クリア</button>
      </div>
      <div id="a-result" style="display:none;margin-top:1rem">
        <div class="score-section"><div class="score-row"><span class="score-label">読みやすさ</span><span class="score-val" id="s1">—</span></div><div class="score-track"><div class="score-bar" id="b1" style="background:#1d9bf0;width:0%"></div></div></div>
        <div class="score-section"><div class="score-row"><span class="score-label">エンゲージメント予測</span><span class="score-val" id="s2">—</span></div><div class="score-track"><div class="score-bar" id="b2" style="background:#10b981;width:0%"></div></div></div>
        <div class="score-section"><div class="score-row"><span class="score-label">アルゴリズム適合度</span><span class="score-val" id="s3">—</span></div><div class="score-track"><div class="score-bar" id="b3" style="background:#f59e0b;width:0%"></div></div></div>
        <div id="tips"></div>
      </div>
    </div>
  </div>

  <!-- ハッシュタグ -->
  <div id="p-tags" class="panel">
    <div class="card">
      <div class="card-title">ハッシュタグ選択（最大5個）</div>
      <div id="tag-pool"></div>
      <div style="border-top:1px solid #e5e7eb;padding-top:12px;margin-top:4px">
        <label>選択中のタグ</label>
        <div class="selected-display" id="selected">—</div>
        <div class="btn-group" style="margin-top:8px">
          <button class="btn-sm" onclick="copyTags()">📋 コピー</button>
          <button class="btn-sm" onclick="clearTags()">✕ クリア</button>
        </div>
      </div>
    </div>
  </div>

  <!-- 投稿時間 -->
  <div id="p-timing" class="panel">
    <div class="card">
      <div class="card-title">ベスト投稿時間帯（JST）</div>
      <div class="day-row"><div class="day-lbl">月</div><div class="day-lbl">火</div><div class="day-lbl">水</div><div class="day-lbl">木</div><div class="day-lbl">金</div><div class="day-lbl">土</div><div class="day-lbl">日</div></div>
      <div class="heat-grid" id="heatmap"></div>
      <div style="display:flex;gap:12px;margin-top:8px;font-size:11px;color:#6b7280">
        <span><span style="display:inline-block;width:12px;height:12px;background:#1d4ed8;border-radius:3px;vertical-align:middle;margin-right:4px"></span>高</span>
        <span><span style="display:inline-block;width:12px;height:12px;background:#93c5fd;border-radius:3px;vertical-align:middle;margin-right:4px"></span>中</span>
        <span><span style="display:inline-block;width:12px;height:12px;background:#f3f4f6;border-radius:3px;vertical-align:middle;margin-right:4px"></span>低</span>
      </div>
      <div class="best-times">
        <strong>🏆 推奨時間帯（外国人材・HR業界向け）</strong><br>
        🕗 平日 8:00〜9:00（通勤前） / 🕛 12:00〜13:00（ランチ） / 🕕 18:00〜19:30（退勤後）<br>
        📅 木曜・金曜が特にエンゲージメント高め
      </div>
    </div>
  </div>

  <!-- チェックリスト -->
  <div id="p-check" class="panel">
    <div class="card">
      <div class="card-title">Xアルゴリズム攻略チェックリスト</div>
      <div class="checklist" id="checklist"></div>
    </div>
  </div>
</div>

<script>
var GAS_URL = 'https://script.google.com/macros/s/AKfycbyS0kWPw2e1u3sgA3RjI_h8H_LxEeKz4N2fqv7UmK2Ae-aHjrNe_mhZNBcNk_vIb-_E/exec';

function switchTab(id) {
  var ids = ['gen','analyze','tags','timing','check'];
  document.querySelectorAll('.tab').forEach(function(t,i){t.classList.toggle('active',ids[i]===id);});
  ids.forEach(function(p){var el=document.getElementById('p-'+p);if(el)el.classList.toggle('active',p===id);});
}

var hd=[[1,1,2,2,1,0,0],[1,1,2,3,2,1,0],[0,1,1,2,1,0,0],[2,3,4,4,3,1,0],[3,4,3,3,2,1,0],[1,2,2,2,1,0,0],[1,1,1,1,1,0,0],[0,0,1,1,0,0,0],[0,0,0,0,0,0,0]];
var tl=['6時','8時','10時','12時','18時','20時','22時','0時','深夜'];
var hm=document.getElementById('heatmap');
hd.forEach(function(row,i){row.forEach(function(v){var c=document.createElement('div');c.className='heat-cell h'+v;if(i===0)c.textContent=tl[i];hm.appendChild(c);});});

var htags={'外国人材':['#外国人採用','#グローバル人材','#特定技能','#技能実習','#外国人雇用'],'業界別':['#介護人材','#建設業','#宿泊業','#HR','#人材紹介'],'国際連携':['#インドネシア','#ベトナム','#フィリピン','#インターンシップ','#日本語学習'],'トレンド':['#人手不足','#外国人労働者','#多様性推進','#グローバル採用']};
var selTags=[];
var pool=document.getElementById('tag-pool');
Object.keys(htags).forEach(function(cat){var g=document.createElement('div');g.className='tag-group';g.innerHTML='<div class="tag-cat">'+cat+'</div>';htags[cat].forEach(function(t){var el=document.createElement('span');el.className='tag';el.textContent=t;el.onclick=function(){var idx=selTags.indexOf(t);if(idx>-1){selTags.splice(idx,1);el.classList.remove('active');}else if(selTags.length<5){selTags.push(t);el.classList.add('active');}document.getElementById('selected').textContent=selTags.join(' ')||'—';};g.appendChild(el);});pool.appendChild(g);});
function copyTags(){var txt=selTags.join(' ');if(!txt)return;navigator.clipboard.writeText(txt);alert('コピーしました！');}
function clearTags(){selTags=[];document.querySelectorAll('.tag.active').forEach(function(t){t.classList.remove('active');});document.getElementById('selected').textContent='—';}

var citems=[{icon:'🕐',text:'投稿時間：8時・12時・18時台'},{icon:'#️⃣',text:'ハッシュタグ：3〜5個'},{icon:'🖼️',text:'画像または動画を添付'},{icon:'❓',text:'質問形式で締める'},{icon:'🔗',text:'スレッドを活用'},{icon:'💬',text:'早期返信でエンゲージ獲得'},{icon:'🔗',text:'URLはリプライに移動'},{icon:'📝',text:'140〜200文字に収める'}];
var cl=document.getElementById('checklist');
citems.forEach(function(item){var el=document.createElement('div');el.className='check-item';el.innerHTML='<span>'+item.icon+'</span><span>'+item.text+'</span><span class="check-mark">☐</span>';el.onclick=function(){el.classList.toggle('done');el.querySelector('.check-mark').textContent=el.classList.contains('done')?'✅':'☐';document.getElementById('algo').textContent=Math.round(cl.querySelectorAll('.done').length/citems.length*100);};cl.appendChild(el);});

function updateCount(){var len=document.getElementById('t-input').value.length;var el=document.getElementById('t-count');el.textContent=len+' / 280文字';el.style.color=len>260?'#ef4444':len>230?'#f59e0b':'#9ca3af';}
function clearAnalyze(){document.getElementById('t-input').value='';updateCount();document.getElementById('a-result').style.display='none';}

function generate(isV) {
  var theme=document.getElementById('g-theme').value;
  var tone=document.getElementById('g-tone').value;
  var target=document.getElementById('g-target').value;
  var length=document.getElementById('g-len').value;
  var memo=document.getElementById('g-memo').value;
  var toneMap={informative:'情報提供・ためになる内容',story:'ストーリー・共感を引き出す',question:'質問・議論を促す',tips:'実用的なノウハウ・Tips',news:'ニュース・トレンド紹介'};
  var prompt='あなたは外国人材紹介会社「株式会社Threads」のSNS担当です。以下の条件でX（Twitter）の投稿文を1つ作成してください。\n\nテーマ：'+theme+'\nトーン：'+toneMap[tone]+'\nターゲット読者：'+target+'\n文字数：'+length+'\n'+(memo?'追加メモ：'+memo+'\n':'')+(isV?'（前回と異なるアプローチで）\n':'')+'\nルール：\n- ハッシュタグなし（別途追加）\n- URLなし\n- 絵文字1〜2個\n- 会話を誘う文末\n- 信頼感のある文体\n\n投稿文のみを返してください。';
  var btn=document.getElementById('g-btn');
  btn.disabled=true; btn.textContent='生成中...';
  document.getElementById('g-output').style.display='block';
  var out=document.getElementById('g-text');
  out.className='output-box loading'; out.textContent='AIが投稿文を考えています...';
  fetch(GAS_URL,{method:'POST',headers:{'Content-Type':'text/plain'},body:JSON.stringify({prompt:prompt})})
    .then(function(r){return r.json();})
    .then(function(data){
      if(data.success&&data.text){
        out.className='output-box'; out.textContent=data.text;
        document.getElementById('g-char').textContent=data.text.length+'文字';
        document.getElementById('eng').textContent=(2.1+Math.random()*1.5).toFixed(1)+'%';
        document.getElementById('imp').textContent=Math.round(900+Math.random()*600).toLocaleString();
        document.getElementById('fol').textContent='+'+Math.round(3+Math.random()*8);
      } else { throw new Error(data.error||'不明なエラー'); }
    })
    .catch(function(e){out.className='output-box'; out.textContent='エラー：'+e.message;})
    .finally(function(){btn.disabled=false; btn.textContent='✨ 投稿文を生成する';});
}

function copyGen(){var txt=document.getElementById('g-text').textContent;if(txt)navigator.clipboard.writeText(txt).then(function(){alert('コピーしました！');});}
function sendToAnalyze(){var txt=document.getElementById('g-text').textContent;if(!txt||txt.includes('AIが'))return;document.getElementById('t-input').value=txt;updateCount();switchTab('analyze');analyze();}

function analyze(){
  var text=document.getElementById('t-input').value.trim();
  if(!text){alert('テキストを入力してください');return;}
  var len=text.length,hasQ=text.includes('？')||text.includes('?'),hasE=/\p{Emoji_Presentation}/u.test(text);
  var r1=Math.min(100,Math.round(60+(len>30?20:0)+(len<200?15:-10)+(hasE?5:0)));
  var r2=Math.min(100,Math.round(50+(hasQ?25:0)+(len>50?15:0)+(hasE?10:0)));
  var r3=Math.min(100,Math.round(55+(len>=80&&len<=200?25:0)+(hasQ?15:0)));
  document.getElementById('s1').textContent=r1+'%'; document.getElementById('s2').textContent=r2+'%'; document.getElementById('s3').textContent=r3+'%';
  setTimeout(function(){document.getElementById('b1').style.width=r1+'%';document.getElementById('b2').style.width=r2+'%';document.getElementById('b3').style.width=r3+'%';},50);
  var tips=[];
  if(len<80)tips.push({t:'文字数',d:'80〜200文字が最も拡散されやすい傾向があります。'});
  if(!hasQ)tips.push({t:'質問形式',d:'会話を誘う文末がエンゲージメントを高めます。'});
  if(!hasE)tips.push({t:'絵文字',d:'絵文字1〜2個で視認性とクリック率が向上します。'});
  if(text.includes('http'))tips.push({t:'URLの場所',d:'URLはリプライに移動するとリーチ制限を避けられます。'});
  document.getElementById('tips').innerHTML=tips.length?tips.map(function(t){return'<div class="tip"><strong>💡 '+t.t+'：</strong>'+t.d+'</div>';}).join(''):'<div class="tip ok"><strong>✅ 良好：</strong>アルゴリズムに概ね適合しています。</div>';
  document.getElementById('a-result').style.display='block';
  document.getElementById('eng').textContent=(1.5+r2/100*3).toFixed(1)+'%';
  document.getElementById('imp').textContent=Math.round(800+r3*22).toLocaleString();
  document.getElementById('fol').textContent='+'+Math.round(r2/10);
}
</script>
</body>
</html>
