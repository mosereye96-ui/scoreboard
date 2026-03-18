<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Scoreboard</title>
<style>
*{box-sizing:border-box;margin:0;padding:0;}
body{font-family:-apple-system,BlinkMacSystemFont,'Segoe UI',sans-serif;background:#f5f5f3;color:#1a1a18;min-height:100vh;padding:16px;}
body.dark{background:#1a1a18;color:#f0efe8;}
.app{max-width:480px;margin:0 auto;padding-top:12px;}
.top-bar{display:flex;justify-content:space-between;align-items:flex-start;margin-bottom:12px;gap:12px;}
.brand-block{flex:1;}
.brand{font-size:20px;font-weight:500;margin-bottom:4px;}
.quote{font-size:11px;color:#888780;line-height:1.4;font-style:italic;max-width:280px;}
.top-actions{display:flex;gap:8px;align-items:center;flex-shrink:0;padding-top:2px;}
.icon-btn{width:34px;height:34px;border-radius:50%;border:0.5px solid rgba(0,0,0,0.2);background:none;cursor:pointer;display:flex;align-items:center;justify-content:center;}
.icon-btn svg{width:15px;height:15px;stroke:#888780;fill:none;stroke-width:1.5;}
.nav{display:flex;gap:4px;margin-bottom:16px;background:#e8e8e4;border-radius:10px;padding:4px;}
.nt{flex:1;padding:8px;text-align:center;font-size:13px;font-weight:500;color:#5f5e5a;border-radius:8px;cursor:pointer;border:none;background:none;}
.nt.active{background:#fff;color:#1a1a18;border:0.5px solid rgba(0,0,0,0.1);}
body.dark .nav{background:#2c2c2a;}
body.dark .nt{color:#888780;background:none;}
body.dark .nt.active{background:#3a3a38;color:#f0efe8;border-color:rgba(255,255,255,0.12);}
.view{display:none;}.view.active{display:block;}
.sr{display:grid;grid-template-columns:repeat(4,1fr);gap:8px;margin-bottom:14px;}
.st{background:#e8e8e4;border-radius:8px;padding:10px;}
body.dark .st{background:#2c2c2a;}
.sl{font-size:11px;color:#888780;margin-bottom:3px;}
.sv{font-size:18px;font-weight:500;}
body.dark .sv{color:#f0efe8;}
.card{background:#fff;border:0.5px solid rgba(0,0,0,0.1);border-radius:12px;padding:16px;margin-bottom:12px;}
body.dark .card{background:#242422;border-color:rgba(255,255,255,0.08);}
.ch{display:flex;justify-content:space-between;align-items:center;margin-bottom:12px;}
.ct{font-size:14px;font-weight:500;}
body.dark .ct{color:#f0efe8;}
.badge{font-size:12px;padding:3px 10px;border-radius:8px;font-weight:500;}
.bg{background:#EAF3DE;color:#3B6D11;}.ba{background:#FAEEDA;color:#854F0B;}.br{background:#FCEBEB;color:#A32D2D;}.bb{background:#E6F1FB;color:#185FA5;}
.tr{display:flex;align-items:center;gap:10px;padding:8px 0;border-bottom:0.5px solid rgba(0,0,0,0.08);cursor:pointer;user-select:none;}
.tr:last-child{border-bottom:none;}
body.dark .tr{border-bottom-color:rgba(255,255,255,0.07);}
.ck{width:22px;height:22px;border-radius:50%;border:1.5px solid rgba(0,0,0,0.2);flex-shrink:0;display:flex;align-items:center;justify-content:center;transition:all 0.15s;}
body.dark .ck{border-color:rgba(255,255,255,0.25);}
.ck.done{background:#639922;border-color:#639922;}
.ck.done::after{content:'';display:block;width:5px;height:9px;border:2px solid #fff;border-top:none;border-left:none;transform:rotate(45deg) translateY(-1px);}
.tn{flex:1;font-size:14px;color:#1a1a18;}
body.dark .tn{color:#f0efe8;}
.tn.done{color:#888780;text-decoration:line-through;}
body.dark .tn.done{color:#5f5e5a;}
.tt{font-size:12px;color:#b4b2a9;}
body.dark .tt{color:#5f5e5a;}
.rm-btn{width:22px;height:22px;border-radius:50%;border:0.5px solid rgba(0,0,0,0.15);background:none;cursor:pointer;font-size:16px;color:#b4b2a9;display:flex;align-items:center;justify-content:center;flex-shrink:0;line-height:1;}
body.dark .rm-btn{border-color:rgba(255,255,255,0.15);color:#5f5e5a;}
.add-task-row{display:flex;align-items:center;gap:8px;padding-top:10px;margin-top:4px;border-top:0.5px solid rgba(0,0,0,0.08);}
body.dark .add-task-row{border-top-color:rgba(255,255,255,0.07);}
.add-task-input{flex:1;border:0.5px solid rgba(0,0,0,0.15);border-radius:8px;padding:7px 10px;font-size:13px;background:#f5f5f3;color:#1a1a18;}
body.dark .add-task-input{background:#2c2c2a;border-color:rgba(255,255,255,0.12);color:#f0efe8;}
.add-task-time{width:72px;border:0.5px solid rgba(0,0,0,0.15);border-radius:8px;padding:7px 8px;font-size:13px;background:#f5f5f3;color:#1a1a18;}
body.dark .add-task-time{background:#2c2c2a;border-color:rgba(255,255,255,0.12);color:#f0efe8;}
.plus-btn{width:30px;height:30px;border-radius:50%;background:#3B6D11;border:none;color:#fff;font-size:20px;cursor:pointer;display:flex;align-items:center;justify-content:center;flex-shrink:0;}
.hml{display:grid;grid-template-columns:repeat(7,1fr);gap:4px;margin-bottom:6px;}
.hmll{font-size:10px;color:#b4b2a9;text-align:center;}
body.dark .hmll{color:#5f5e5a;}
.hm{display:grid;grid-template-columns:repeat(7,1fr);gap:4px;margin-bottom:10px;}
.hmd{aspect-ratio:1;border-radius:3px;}
.legend{display:flex;gap:10px;flex-wrap:wrap;font-size:11px;color:#888780;align-items:center;}
body.dark .legend{color:#5f5e5a;}
.ldot{width:10px;height:10px;border-radius:2px;display:inline-block;}
.yg{display:grid;grid-template-columns:repeat(6,minmax(0,1fr));gap:8px;margin-top:8px;}
.ym{text-align:center;}.yml{font-size:10px;color:#888780;margin-bottom:3px;}
body.dark .yml{color:#5f5e5a;}
.ymg{display:grid;grid-template-columns:repeat(7,1fr);gap:1px;}
.yc{aspect-ratio:1;border-radius:1px;}
.overlay{display:none;position:fixed;top:0;left:0;right:0;bottom:0;background:rgba(0,0,0,0.5);z-index:50;align-items:flex-end;justify-content:center;}
.overlay.open{display:flex;}
.sheet{background:#fff;border-radius:16px 16px 0 0;padding:20px;width:100%;max-width:480px;max-height:82vh;overflow-y:auto;}
body.dark .sheet{background:#242422;}
.sheet-title{font-size:16px;font-weight:500;margin-bottom:4px;}
body.dark .sheet-title{color:#f0efe8;}
.sheet-sub{font-size:12px;color:#888780;margin-bottom:16px;}
.ter{display:flex;align-items:center;gap:8px;padding:6px 0;border-bottom:0.5px solid rgba(0,0,0,0.08);}
.ter:last-of-type{border-bottom:none;}
body.dark .ter{border-bottom-color:rgba(255,255,255,0.07);}
.ti{flex:1;border:0.5px solid rgba(0,0,0,0.15);border-radius:6px;padding:7px 10px;font-size:13px;background:#f5f5f3;color:#1a1a18;}
body.dark .ti{background:#2c2c2a;border-color:rgba(255,255,255,0.12);color:#f0efe8;}
.tit{width:74px;border:0.5px solid rgba(0,0,0,0.15);border-radius:6px;padding:7px 8px;font-size:12px;background:#f5f5f3;color:#1a1a18;}
body.dark .tit{background:#2c2c2a;border-color:rgba(255,255,255,0.12);color:#f0efe8;}
.delbtn{width:26px;height:26px;border-radius:50%;border:0.5px solid rgba(0,0,0,0.15);background:none;cursor:pointer;font-size:18px;color:#888;flex-shrink:0;display:flex;align-items:center;justify-content:center;}
body.dark .delbtn{border-color:rgba(255,255,255,0.15);color:#888780;}
.addbtn{width:100%;padding:9px;background:none;border:0.5px dashed rgba(0,0,0,0.2);border-radius:8px;font-size:13px;color:#888;cursor:pointer;margin-top:10px;}
body.dark .addbtn{border-color:rgba(255,255,255,0.15);color:#888780;}
.savebtn{width:100%;padding:12px;background:#3B6D11;color:#fff;border:none;border-radius:8px;font-size:14px;font-weight:500;cursor:pointer;margin-top:12px;}
.close-btn{width:100%;padding:12px;background:#f5f5f3;border:none;border-radius:8px;font-size:14px;cursor:pointer;margin-top:8px;color:#1a1a18;}
body.dark .close-btn{background:#2c2c2a;color:#f0efe8;}
.setting-row{display:flex;align-items:center;justify-content:space-between;padding:14px 0;border-bottom:0.5px solid rgba(0,0,0,0.08);}
body.dark .setting-row{border-bottom-color:rgba(255,255,255,0.07);}
.setting-label{font-size:14px;font-weight:500;color:#1a1a18;}
body.dark .setting-label{color:#f0efe8;}
.setting-desc{font-size:12px;color:#888780;margin-top:2px;}
.toggle{width:44px;height:24px;border-radius:12px;border:none;cursor:pointer;position:relative;transition:background 0.2s;flex-shrink:0;}
.toggle.on{background:#3B6D11;}.toggle.off{background:#b4b2a9;}
.toggle::after{content:'';position:absolute;top:3px;width:18px;height:18px;border-radius:50%;background:#fff;transition:left 0.2s;}
.toggle.on::after{left:23px;}.toggle.off::after{left:3px;}
.time-pick{border:0.5px solid rgba(0,0,0,0.15);border-radius:8px;padding:6px 10px;font-size:13px;background:#f5f5f3;color:#1a1a18;}
body.dark .time-pick{background:#2c2c2a;border-color:rgba(255,255,255,0.12);color:#f0efe8;}
.notif-status{font-size:12px;padding:8px 12px;border-radius:8px;margin-top:8px;background:#f5f5f3;color:#888780;}
body.dark .notif-status{background:#2c2c2a;}
.tasks-section-label{font-size:13px;font-weight:500;color:#1a1a18;margin-bottom:10px;}
body.dark .tasks-section-label{color:#f0efe8;}
.tut-step{display:flex;gap:12px;align-items:flex-start;padding:12px 0;border-bottom:0.5px solid rgba(0,0,0,0.08);}
body.dark .tut-step{border-bottom-color:rgba(255,255,255,0.07);}
.tut-step:last-child{border-bottom:none;}
.tut-num{width:26px;height:26px;border-radius:50%;background:#EAF3DE;display:flex;align-items:center;justify-content:center;font-size:12px;font-weight:500;color:#3B6D11;flex-shrink:0;}
.tut-title{font-size:14px;font-weight:500;color:#1a1a18;margin-bottom:2px;}
body.dark .tut-title{color:#f0efe8;}
.tut-desc{font-size:12px;color:#888780;line-height:1.5;}
</style>
</head>
<body>
<div class="app">
  <div class="top-bar">
    <div class="brand-block">
      <div class="brand">Scoreboard</div>
      <div class="quote" id="daily-quote"></div>
    </div>
    <div class="top-actions">
      <button class="icon-btn" onclick="toggleDark()" title="Dark mode">
        <svg id="dark-icon" viewBox="0 0 24 24"><path d="M21 12.79A9 9 0 1 1 11.21 3a7 7 0 0 0 9.79 9.79z" stroke-linecap="round" stroke-linejoin="round"/></svg>
      </button>
      <button class="icon-btn" onclick="openTutorial()">
        <svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="10"/><path d="M12 16v-4M12 8h.01" stroke-linecap="round"/></svg>
      </button>
      <button class="icon-btn" onclick="openSettings()">
        <svg viewBox="0 0 24 24"><circle cx="12" cy="12" r="3"/><path d="M19.4 15a1.65 1.65 0 0 0 .33 1.82l.06.06a2 2 0 0 1-2.83 2.83l-.06-.06a1.65 1.65 0 0 0-1.82-.33 1.65 1.65 0 0 0-1 1.51V21a2 2 0 0 1-4 0v-.09A1.65 1.65 0 0 0 9 19.4a1.65 1.65 0 0 0-1.82.33l-.06.06a2 2 0 0 1-2.83-2.83l.06-.06A1.65 1.65 0 0 0 4.68 15a1.65 1.65 0 0 0-1.51-1H3a2 2 0 0 1 0-4h.09A1.65 1.65 0 0 0 4.6 9a1.65 1.65 0 0 0-.33-1.82l-.06-.06a2 2 0 0 1 2.83-2.83l.06.06A1.65 1.65 0 0 0 9 4.68a1.65 1.65 0 0 0 1-1.51V3a2 2 0 0 1 4 0v.09a1.65 1.65 0 0 0 1 1.51 1.65 1.65 0 0 0 1.82-.33l.06-.06a2 2 0 0 1 2.83 2.83l-.06.06A1.65 1.65 0 0 0 19.4 9a1.65 1.65 0 0 0 1.51 1H21a2 2 0 0 1 0 4h-.09a1.65 1.65 0 0 0-1.51 1z"/></svg>
      </button>
    </div>
  </div>
  <div class="nav">
    <button class="nt active" onclick="showView('daily',this)">Daily</button>
    <button class="nt" onclick="showView('weekly',this)">Weekly</button>
    <button class="nt" onclick="showView('monthly',this)">Monthly</button>
  </div>
  <div id="v-daily" class="view active">
    <div class="sr">
      <div class="st"><div class="sl">Score</div><div class="sv" id="d-score">0%</div></div>
      <div class="st"><div class="sl">Done</div><div class="sv" id="d-done">0/8</div></div>
      <div class="st"><div class="sl">Streak</div><div class="sv" id="d-streak">0d</div></div>
      <div class="st"><div class="sl">Best</div><div class="sv" id="d-best">--</div></div>
    </div>
    <div class="card">
      <div class="ch"><span class="ct" id="d-date"></span><span class="badge bb" id="d-badge">0%</span></div>
      <div id="task-list"></div>
      <div class="add-task-row">
        <input class="add-task-input" id="new-task-name" placeholder="Add a task..." onkeydown="if(event.key==='Enter')quickAdd()"/>
        <input class="add-task-time" id="new-task-time" placeholder="Time"/>
        <button class="plus-btn" onclick="quickAdd()">+</button>
      </div>
    </div>
    <div class="card"><div class="ch"><span class="ct">This week</span></div><div style="position:relative;width:100%;height:110px;"><canvas id="miniChart"></canvas></div></div>
  </div>
  <div id="v-weekly" class="view">
    <div class="sr">
      <div class="st"><div class="sl">Avg</div><div class="sv" id="w-avg">--</div></div>
      <div class="st"><div class="sl">Best day</div><div class="sv" id="w-best">--</div></div>
      <div class="st"><div class="sl">80%+ days</div><div class="sv" id="w-hits">--</div></div>
      <div class="st"><div class="sl">Streak</div><div class="sv" id="w-streak">0d</div></div>
    </div>
    <div class="card"><div class="ch"><span class="ct">Daily scores</span></div><div style="position:relative;width:100%;height:180px;"><canvas id="weekChart"></canvas></div></div>
    <div class="card"><div class="ch"><span class="ct">Breakdown</span></div><div id="week-bd"></div></div>
  </div>
  <div id="v-monthly" class="view">
    <div class="sr">
      <div class="st"><div class="sl">Avg</div><div class="sv" id="m-avg">--</div></div>
      <div class="st"><div class="sl">Best</div><div class="sv" id="m-best">--</div></div>
      <div class="st"><div class="sl">Perfect</div><div class="sv" id="m-perfect">--</div></div>
      <div class="st"><div class="sl">Active</div><div class="sv" id="m-active">--</div></div>
    </div>
    <div class="card">
      <div class="ch"><span class="ct" id="m-label"></span>
        <div style="display:flex;gap:6px;">
          <button onclick="chMo(-1)" class="icon-btn" style="width:28px;height:28px;font-size:16px;">&#8249;</button>
          <button onclick="chMo(1)" class="icon-btn" style="width:28px;height:28px;font-size:16px;">&#8250;</button>
        </div>
      </div>
      <div class="hml"><span class="hmll">S</span><span class="hmll">M</span><span class="hmll">T</span><span class="hmll">W</span><span class="hmll">T</span><span class="hmll">F</span><span class="hmll">S</span></div>
      <div class="hm" id="heatmap"></div>
      <div class="legend">
        <span style="display:flex;align-items:center;gap:4px;"><span class="ldot" style="background:#EAF3DE;border:0.5px solid #C0DD97;"></span>Low</span>
        <span style="display:flex;align-items:center;gap:4px;"><span class="ldot" style="background:#97C459;"></span>Good</span>
        <span style="display:flex;align-items:center;gap:4px;"><span class="ldot" style="background:#3B6D11;"></span>Crushed it</span>
        <span style="display:flex;align-items:center;gap:4px;"><span class="ldot" style="background:#FCEBEB;border:0.5px solid #F09595;"></span>Missed</span>
      </div>
    </div>
    <div class="card"><div class="ch"><span class="ct">Year overview</span></div><div class="yg" id="year-grid"></div></div>
  </div>
</div>
<div class="overlay" id="settings-overlay" onclick="if(event.target===this)closeSettings()">
  <div class="sheet">
    <div class="sheet-title">Settings</div>
    <div class="sheet-sub">Customize your experience</div>
    <div class="setting-row">
      <div><div class="setting-label">Dark mode</div><div class="setting-desc">Easy on the eyes at night</div></div>
      <button class="toggle off" id="dark-toggle" onclick="toggleDark()"></button>
    </div>
    <div class="setting-row">
      <div><div class="setting-label">Daily reminder</div><div class="setting-desc">Browser notification to check in</div></div>
      <button class="toggle off" id="notif-toggle" onclick="toggleNotif()"></button>
    </div>
    <div id="time-picker-row" style="display:none;padding:10px 0 4px;">
      <div style="font-size:13px;color:#888780;margin-bottom:8px;">Remind me at</div>
      <input type="time" class="time-pick" id="reminder-time" value="08:00" onchange="saveReminderTime()"/>
      <div class="notif-status" id="notif-status">Enable notifications when prompted.</div>
    </div>
    <div style="margin-top:16px;border-top:0.5px solid rgba(0,0,0,0.08);padding-top:16px;">
      <div class="tasks-section-label">Your tasks</div>
      <div id="settings-tasks"></div>
      <button class="addbtn" onclick="sAdd()">+ Add task</button>
    </div>
    <button class="savebtn" onclick="saveSettings()">Save changes</button>
  </div>
</div>
<div class="overlay" id="tutorial-overlay" onclick="if(event.target===this)closeTutorial()">
  <div class="sheet">
    <div class="sheet-title">How Scoreboard works</div>
    <div class="sheet-sub">Quick overview — 30 seconds</div>
    <div class="tut-step"><div class="tut-num">1</div><div><div class="tut-title">Check off tasks daily</div><div class="tut-desc">Tap any task to mark it done. Your score updates live.</div></div></div>
    <div class="tut-step"><div class="tut-num">2</div><div><div class="tut-title">Add or remove on the fly</div><div class="tut-desc">Type in the box at the bottom and hit + to add. Hit x to remove.</div></div></div>
    <div class="tut-step"><div class="tut-num">3</div><div><div class="tut-title">Track your week and month</div><div class="tut-desc">Weekly = bar chart. Monthly = heatmap. Green = win, red = miss.</div></div></div>
    <div class="tut-step"><div class="tut-num">4</div><div><div class="tut-title">Build your streak</div><div class="tut-desc">Every day you complete at least one task keeps it alive.</div></div></div>
    <div class="tut-step"><div class="tut-num">5</div><div><div class="tut-title">Dark mode + reminders</div><div class="tut-desc">Moon icon toggles dark mode. Set a daily reminder in settings.</div></div></div>
    <button class="close-btn" onclick="closeTutorial()">Got it</button>
  </div>
</div>
<script src="https://cdnjs.cloudflare.com/ajax/libs/Chart.js/4.4.1/chart.umd.js"></script>
<script>
const QUOTES=["You don't rise to the level of your goals—you fall to the level of your systems. — James Clear","Discipline is choosing what you want most over what you want now.","Small actions, repeated daily, build unstoppable momentum.","Success isn't built in a day—it's built daily.","Consistency beats intensity every time.","Show up, even when you don't feel like it.","Progress is progress, no matter how small.","Win the day, and the streak will follow.","Every checkmark is a vote for the person you're becoming.","Your habits are your real scoreboard.","Stack enough good days, and you can't lose.","Tiny gains today become massive results tomorrow.","One bad day doesn't break the system—quitting does.","Fall off once, get back twice as fast.","Miss once, never miss twice.","Bad days are part of strong systems.","You don't need motivation—you need standards.","Keep going. That's the whole secret.","Keep the streak alive.","Just one more.","Don't zero today.","You're on track.","Daily > occasionally.","Finish strong.","No one is coming. Build it yourself.","Hard choices, easy life. Easy choices, hard life. — Jerzy Gregorek","Do it tired. Do it unmotivated. Just do it.","Comfort is expensive. Discipline is cheap.","The work you avoid is the life you want."];
const now=new Date(),todayKey=now.toISOString().slice(0,10);
document.getElementById('daily-quote').textContent='"'+QUOTES[Math.floor(now/86400000)%QUOTES.length]+'"';
const MN=['January','February','March','April','May','June','July','August','September','October','November','December'];
const MNS=['Jan','Feb','Mar','Apr','May','Jun','Jul','Aug','Sep','Oct','Nov','Dec'];
const DN=['Sun','Mon','Tue','Wed','Thu','Fri','Sat'];
const DEFAULT=[{n:'Morning workout',t:'6:00 AM'},{n:'Review leads & pipeline',t:'8:30 AM'},{n:'Follow up on open deals',t:'9:00 AM'},{n:'Prospecting calls',t:'10:00 AM'},{n:'Send follow-up texts',t:'12:00 PM'},{n:'Log new leads in CRM',t:'2:00 PM'},{n:'Trade-in evaluations',t:'3:30 PM'},{n:'End-of-day review',t:'6:00 PM'}];
function load(){try{return JSON.parse(localStorage.getItem('sb_v11')||'null');}catch(e){return null;}}
function save(){try{localStorage.setItem('sb_v11',JSON.stringify(state));}catch(e){}}
let state=load()||{history:{},tasks:[],defs:DEFAULT,dark:false,notif:false,reminderTime:'08:00'};
if(!state.defs)state.defs=DEFAULT;
if(!state.tasks||state.tasks.length!==state.defs.length)state.tasks=new Array(state.defs.length).fill(false);
if(!Object.keys(state.history).length){for(let i=1;i<=90;i++){const d=new Date(now);d.setDate(now.getDate()-i);state.history[d.toISOString().slice(0,10)]=Math.round(Math.random()*60+30);}}
function applyDark(){
  document.body.classList.toggle('dark',state.dark);
  const dt=document.getElementById('dark-toggle');if(dt)dt.className='toggle '+(state.dark?'on':'off');
  const di=document.getElementById('dark-icon');if(di)di.style.stroke=state.dark?'#f0efe8':'#888780';
}
function toggleDark(){state.dark=!state.dark;save();applyDark();renderWeekly();renderMonthly();}
function sc(){return state.defs.length?Math.round(state.tasks.filter(Boolean).length/state.defs.length*100):0;}
function bc(s){return s>=80?'bg':s>=50?'ba':s>0?'br':'bb';}
function hc(s){if(s===null||s===undefined)return state.dark?'#2c2c2a':'#e8e8e4';if(s===0)return'#FCEBEB';if(s<50)return'#EAF3DE';if(s<80)return'#97C459';return'#3B6D11';}
function streak(){let n=0;const d=new Date(now);while(true){const k=d.toISOString().slice(0,10);const s=k===todayKey?sc():state.history[k];if(s!==undefined&&s!==null&&s>0){n++;d.setDate(d.getDate()-1);}else break;}return n;}
function wkData(){const r=[];for(let i=6;i>=0;i--){const d=new Date(now);d.setDate(now.getDate()-i);const k=d.toISOString().slice(0,10);const isT=k===todayKey;r.push({label:isT?'Today':DN[d.getDay()],s:isT?sc():(state.history[k]??null),isT});}return r;}
let mc,wc;
function renderDaily(){
  const s=sc(),done=state.tasks.filter(Boolean).length,str=streak();
  const all=Object.values(state.history).filter(x=>x>0);
  const best=all.length?Math.max(...all,s):s;
  document.getElementById('d-score').textContent=s+'%';
  document.getElementById('d-done').textContent=done+'/'+state.defs.length;
  document.getElementById('d-streak').textContent=str+'d';
  document.getElementById('d-best').textContent=best+'%';
  document.getElementById('d-date').textContent=now.toLocaleDateString('en-US',{weekday:'long',month:'short',day:'numeric'});
  const b=document.getElementById('d-badge');b.textContent=s+'%';b.className='badge '+bc(s);
  const list=document.getElementById('task-list');list.innerHTML='';
  state.defs.forEach((t,i)=>{
    const row=document.createElement('div');row.className='tr';
    const area=document.createElement('div');area.style.cssText='display:flex;align-items:center;gap:10px;flex:1;';
    area.innerHTML='<div class="ck '+(state.tasks[i]?'done':'')+'"></div><span class="tn '+(state.tasks[i]?'done':'')+'">'+(t.n||'Untitled')+'</span><span class="tt">'+(t.t||'')+'</span>';
    area.onclick=()=>{state.tasks[i]=!state.tasks[i];state.history[todayKey]=sc();save();renderDaily();};
    const rm=document.createElement('button');rm.className='rm-btn';rm.textContent='x';
    rm.onclick=(e)=>{e.stopPropagation();if(state.defs.length<=1)return;state.defs.splice(i,1);state.tasks.splice(i,1);state.history[todayKey]=sc();save();renderDaily();};
    row.appendChild(area);row.appendChild(rm);list.appendChild(row);
  });
  renderMini();
}
function quickAdd(){
  const name=document.getElementById('new-task-name').value.trim();if(!name)return;
  const time=document.getElementById('new-task-time').value.trim();
  state.defs.push({n:name,t:time});state.tasks.push(false);
  document.getElementById('new-task-name').value='';document.getElementById('new-task-time').value='';
  state.history[todayKey]=sc();save();renderDaily();
}
function renderMini(){
  const wd=wkData();if(mc)mc.destroy();
  const tc=state.dark?'#888780':'#b4b2a9';
  mc=new Chart(document.getElementById('miniChart'),{type:'bar',data:{labels:wd.map(d=>d.label),datasets:[{data:wd.map(d=>d.s??0),backgroundColor:wd.map(d=>d.isT?'#378ADD':d.s>=80?'#639922':d.s>=50?'#BA7517':d.s>0?'#E24B4A':'#555553'),borderRadius:3,borderSkipped:false}]},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false},tooltip:{callbacks:{label:c=>c.raw+'%'}}},scales:{y:{min:0,max:100,display:false},x:{ticks:{font:{size:11},color:tc},grid:{display:false}}}}});
}
function renderWeekly(){
  const wd=wkData();const scores=wd.map(d=>d.s).filter(s=>s!==null);
  const avg=scores.length?Math.round(scores.reduce((a,b)=>a+b,0)/scores.length):0;
  document.getElementById('w-avg').textContent=avg+'%';
  document.getElementById('w-best').textContent=(scores.length?Math.max(...scores):0)+'%';
  document.getElementById('w-hits').textContent=scores.filter(s=>s>=80).length;
  document.getElementById('w-streak').textContent=streak()+'d';
  if(wc)wc.destroy();
  const tc=state.dark?'#888780':'#888780';
  const gc=state.dark?'rgba(255,255,255,0.05)':'rgba(0,0,0,0.05)';
  wc=new Chart(document.getElementById('weekChart'),{type:'bar',data:{labels:wd.map(d=>d.label),datasets:[{data:wd.map(d=>d.s??0),backgroundColor:wd.map(d=>d.isT?'#378ADD':d.s>=80?'#639922':d.s>=50?'#BA7517':d.s>0?'#E24B4A':'#555553'),borderRadius:4,borderSkipped:false}]},options:{responsive:true,maintainAspectRatio:false,plugins:{legend:{display:false},tooltip:{callbacks:{label:c=>c.raw+'%'}}},scales:{y:{min:0,max:100,ticks:{callback:v=>v+'%',font:{size:11},color:tc},grid:{color:gc}},x:{ticks:{font:{size:12},color:tc},grid:{display:false}}}}});
  const bd=document.getElementById('week-bd');bd.innerHTML='';
  const bdc=state.dark?'rgba(255,255,255,0.07)':'rgba(0,0,0,0.08)';
  const txc=state.dark?'#f0efe8':'#1a1a18';
  wd.forEach(d=>{const row=document.createElement('div');row.style.cssText='display:flex;align-items:center;justify-content:space-between;padding:8px 0;border-bottom:0.5px solid '+bdc+';';row.innerHTML='<span style="font-size:14px;color:'+txc+';">'+d.label+'</span><span class="badge '+(d.s===null?'bb':bc(d.s))+'">'+(d.s===null?'--':d.s+'%')+'</span>';bd.appendChild(row);});
}
let vMo=new Date(now.getFullYear(),now.getMonth(),1);
function chMo(dir){vMo=new Date(vMo.getFullYear(),vMo.getMonth()+dir,1);renderMonthly();}
function renderMonthly(){
  const yr=vMo.getFullYear(),mo=vMo.getMonth();
  document.getElementById('m-label').textContent=MN[mo]+' '+yr;
  const dim=new Date(yr,mo+1,0).getDate(),fd=new Date(yr,mo,1).getDay();
  const scores=[];
  for(let d=1;d<=dim;d++){const k=yr+'-'+String(mo+1).padStart(2,'0')+'-'+String(d).padStart(2,'0');scores.push(k===todayKey?sc():(state.history[k]??null));}
  const vs=scores.filter(s=>s!==null);
  document.getElementById('m-avg').textContent=vs.length?Math.round(vs.reduce((a,b)=>a+b,0)/vs.length)+'%':'--';
  document.getElementById('m-best').textContent=vs.length?Math.max(...vs)+'%':'--';
  document.getElementById('m-perfect').textContent=vs.filter(s=>s===100).length;
  document.getElementById('m-active').textContent=vs.filter(s=>s>0).length;
  const hm=document.getElementById('heatmap');hm.innerHTML='';
  for(let i=0;i<fd;i++){const e=document.createElement('div');e.className='hmd';e.style.background='transparent';hm.appendChild(e);}
  scores.forEach((s,idx)=>{const c=document.createElement('div');c.className='hmd';c.style.background=hc(s);c.title=MN[mo]+' '+(idx+1)+': '+(s!==null?s+'%':'no data');hm.appendChild(c);});
  const yg=document.getElementById('year-grid');yg.innerHTML='';
  for(let m=0;m<12;m++){
    const d2=new Date(yr,m+1,0).getDate(),f2=new Date(yr,m,1).getDay();
    const col=document.createElement('div');col.className='ym';
    col.innerHTML='<div class="yml">'+MNS[m]+'</div><div class="ymg" id="ym'+m+'"></div>';
    yg.appendChild(col);
    setTimeout(()=>{const g=document.getElementById('ym'+m);if(!g)return;for(let i=0;i<f2;i++){const e=document.createElement('div');e.className='yc';e.style.background='transparent';g.appendChild(e);}for(let d=1;d<=d2;d++){const k=yr+'-'+String(m+1).padStart(2,'0')+'-'+String(d).padStart(2,'0');const s=k===todayKey?sc():(state.history[k]??null);const c=document.createElement('div');c.className='yc';c.style.background=hc(s);g.appendChild(c);}},0);
  }
}
function showView(v,btn){document.querySelectorAll('.view').forEach(e=>e.classList.remove('active'));document.querySelectorAll('.nt').forEach(e=>e.classList.remove('active'));document.getElementById('v-'+v).classList.add('active');btn.classList.add('active');if(v==='weekly')renderWeekly();else if(v==='monthly')renderMonthly();else renderDaily();}
let sDefs=[];
function openSettings(){sDefs=JSON.parse(JSON.stringify(state.defs));renderSettingsModal();updateNotifUI();document.getElementById('settings-overlay').classList.add('open');}
function closeSettings(){document.getElementById('settings-overlay').classList.remove('open');}
function esc(s){return(s||'').replace(/"/g,'&quot;');}
function renderSettingsModal(){
  const c=document.getElementById('settings-tasks');c.innerHTML='';
  sDefs.forEach((t,i)=>{const row=document.createElement('div');row.className='ter';row.innerHTML='<input class="ti" value="'+esc(t.n)+'" placeholder="Task name" oninput="sDefs['+i+'].n=this.value"/><input class="tit" value="'+esc(t.t)+'" placeholder="Time" oninput="sDefs['+i+'].t=this.value"/><button class="delbtn" onclick="sDel('+i+')">x</button>';c.appendChild(row);});
}
function sAdd(){sDefs.push({n:'',t:''});renderSettingsModal();const ins=document.querySelectorAll('#settings-tasks .ti');ins[ins.length-1].focus();}
function sDel(i){if(sDefs.length<=1)return;sDefs.splice(i,1);renderSettingsModal();}
function saveSettings(){state.defs=JSON.parse(JSON.stringify(sDefs));state.tasks=new Array(state.defs.length).fill(false);state.history[todayKey]=sc();save();closeSettings();renderDaily();}
function toggleNotif(){
  if(!state.notif){if('Notification' in window){Notification.requestPermission().then(p=>{if(p==='granted'){state.notif=true;save();updateNotifUI();document.getElementById('notif-status').textContent='Reminder set for '+state.reminderTime+'.';}else{document.getElementById('notif-status').textContent='Permission denied. Enable in browser settings.';}});}else{document.getElementById('notif-status').textContent='Notifications not supported.';}}
  else{state.notif=false;save();updateNotifUI();}
}
function updateNotifUI(){const t=document.getElementById('notif-toggle');if(t)t.className='toggle '+(state.notif?'on':'off');const row=document.getElementById('time-picker-row');if(row)row.style.display=state.notif?'block':'none';const rt=document.getElementById('reminder-time');if(rt)rt.value=state.reminderTime||'08:00';}
function saveReminderTime(){state.reminderTime=document.getElementById('reminder-time').value;save();document.getElementById('notif-status').textContent='Reminder updated to '+state.reminderTime+'.';}
function openTutorial(){document.getElementById('tutorial-overlay').classList.add('open');}
function closeTutorial(){document.getElementById('tutorial-overlay').classList.remove('open');}
applyDark();state.history[todayKey]=sc();save();renderDaily();renderWeekly();renderMonthly();
</script>
</body>
</html>
