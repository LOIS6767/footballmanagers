[futbol_manager_2026.html](https://github.com/user-attachments/files/34692673/futbol_manager_2026.html)
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Fútbol Manager 2026</title>
<style>
:root{--bg:#0b1220;--panel:#141f32;--panel2:#1b2a42;--line:#2a3b56;--text:#edf4ff;--muted:#9aacc5;--green:#35d07f;--gold:#f5c451;--red:#ff6b72}
*{box-sizing:border-box}body{margin:0;background:radial-gradient(circle at 20% 0%,#19314a 0,#0b1220 42%);color:var(--text);font:15px/1.45 system-ui,-apple-system,Segoe UI,Roboto,Arial}
header{padding:22px max(18px,calc((100% - 1180px)/2));border-bottom:1px solid var(--line);background:#0b1423dd;display:flex;align-items:center;justify-content:space-between;gap:15px;flex-wrap:wrap}
.brand{display:flex;gap:12px;align-items:center}.crest{width:48px;height:54px;clip-path:polygon(8% 0,92% 0,85% 72%,50% 100%,15% 72%);background:linear-gradient(145deg,#35d07f,#167b54);display:grid;place-items:center;font-size:25px;color:#062516;font-weight:900}
h1{font-size:22px;margin:0;letter-spacing:.4px}header small,.muted{color:var(--muted)}.wrap{max-width:1180px;margin:auto;padding:22px 18px 50px}
.stats{display:grid;grid-template-columns:repeat(4,1fr);gap:12px;margin-bottom:18px}.stat,.panel{background:linear-gradient(160deg,#17253a,#111c2e);border:1px solid var(--line);border-radius:16px;padding:16px;box-shadow:0 10px 28px #0002}
.stat span{display:block;color:var(--muted);font-size:12px;text-transform:uppercase;letter-spacing:1px}.stat strong{font-size:24px}
.tabs{display:flex;gap:8px;overflow:auto;margin:18px 0}.tab,button,select,input{font:inherit}.tab,button{border:1px solid var(--line);background:#1a2940;color:var(--text);padding:10px 14px;border-radius:10px;cursor:pointer;white-space:nowrap}.tab.active,button.primary{background:var(--green);border-color:var(--green);color:#062516;font-weight:800}.tab:hover,button:hover{filter:brightness(1.12)}button:disabled{opacity:.4;cursor:not-allowed}
.grid{display:grid;grid-template-columns:1.15fr .85fr;gap:16px}.panel h2{margin:0 0 14px;font-size:18px}.hero{background:linear-gradient(120deg,#174c3c,#122c39 65%,#1d2c45);border:1px solid #2b6c55;border-radius:16px;padding:20px;margin-bottom:16px;position:relative;overflow:hidden}.hero:after{content:"⚽";position:absolute;right:25px;top:5px;font-size:90px;opacity:.12}.hero h2{font-size:26px;margin:0 0 4px}.row{display:flex;align-items:center;justify-content:space-between;gap:12px}.badge{font-size:11px;padding:4px 8px;border-radius:20px;background:#243953;color:#b9cbe3}.good{color:var(--green)}.gold{color:var(--gold)}
label{display:block;color:var(--muted);font-size:12px;margin:10px 0 5px}input,select{width:100%;padding:10px 11px;border-radius:9px;background:#0d1828;color:var(--text);border:1px solid var(--line)}
.actions{display:flex;gap:8px;flex-wrap:wrap;margin-top:12px}.match{background:#0d1929;border:1px solid var(--line);border-radius:14px;padding:16px;text-align:center}.teams{display:grid;grid-template-columns:1fr auto 1fr;align-items:center;gap:12px;margin:14px 0}.team{font-weight:800}.vs{color:var(--muted);font-size:12px}.score{font-size:32px;font-weight:900;letter-spacing:2px}.event{padding:8px 10px;border-left:3px solid var(--green);background:#13243a;border-radius:5px;margin:7px 0;text-align:left;font-size:13px}
table{width:100%;border-collapse:collapse;font-size:13px}th,td{text-align:left;padding:9px 7px;border-bottom:1px solid var(--line)}th{color:var(--muted);font-weight:600}.player{display:grid;grid-template-columns:1fr auto auto;align-items:center;gap:10px;padding:10px 0;border-bottom:1px solid var(--line)}.player:last-child{border:0}.ovr{font-weight:900;color:var(--gold)}.price{color:var(--muted);font-size:12px}
.pitch-wrap{margin-top:16px;text-align:left}.pitch-label,.pitch-legend{display:flex;justify-content:space-between;gap:8px;flex-wrap:wrap;color:#b9d5c4;font-size:10px;letter-spacing:.6px;margin:7px 2px}.pitch{height:390px;position:relative;overflow:hidden;border:2px solid #d8f4df;border-radius:9px;background:repeating-linear-gradient(0deg,#19764a 0,#19764a 48px,#208653 48px,#208653 96px);box-shadow:inset 0 0 25px #063b25}.pitch:before{content:"";position:absolute;inset:0;border:1px solid #d8f4df55;pointer-events:none}.halfway{position:absolute;left:0;right:0;top:50%;border-top:1px solid #eaffefaa}.center-circle{position:absolute;width:95px;height:95px;border:1px solid #eaffefaa;border-radius:50%;left:50%;top:50%;transform:translate(-50%,-50%)}.penalty{position:absolute;left:25%;width:50%;height:14%;border:1px solid #eaffefaa}.penalty.top{top:0;border-top:0}.penalty.bottom{bottom:0;border-bottom:0}.goal{position:absolute;left:39%;width:22%;height:4%;border:2px solid #eaffefaa}.goal.top{top:0;border-top:0}.goal.bottom{bottom:0;border-bottom:0}.pitch-player{position:absolute;transform:translate(-50%,-50%);width:44px;text-align:center;z-index:2}.pitch-player .shirt{width:31px;height:31px;margin:auto;border:2px solid #dfffea;border-radius:50%;background:linear-gradient(145deg,#58b9ff,#1761b0);display:grid;place-items:center;color:white;font-size:10px;font-weight:900;box-shadow:0 3px 7px #062b1c99}.pitch-player.keeper .shirt{background:linear-gradient(145deg,#ffd76a,#b87813);color:#30200a}.pitch-player .pname{display:block;color:white;font-size:9px;font-weight:800;text-shadow:0 1px 3px #062b1c,1px 1px 2px #062b1c;white-space:nowrap;margin-top:2px}.ball{position:absolute;z-index:4;left:50%;top:50%;font-size:22px;filter:drop-shadow(0 2px 2px #063b25);animation:ballMove 5.5s ease-in-out infinite alternate}.pitch.live .ball{animation-duration:2.8s}.pitch.live .pitch-player{animation:playerPulse 1.2s ease-in-out infinite alternate}.pitch-legend{font-size:10px;color:#d4e8d9}.pitch-legend span:first-child{color:#91cbff}@keyframes ballMove{0%{left:48%;top:48%;transform:rotate(0)}18%{left:24%;top:31%;transform:rotate(130deg)}37%{left:69%;top:22%;transform:rotate(260deg)}58%{left:78%;top:66%;transform:rotate(390deg)}78%{left:35%;top:78%;transform:rotate(520deg)}100%{left:53%;top:42%;transform:rotate(650deg)}}@keyframes playerPulse{from{filter:brightness(1)}to{filter:brightness(1.25)}}.hidden{display:none!important}.notice{padding:10px 12px;border-radius:9px;background:#1d3b32;color:#aaf0ca;margin-top:12px;font-size:13px}.footer{text-align:center;color:var(--muted);font-size:12px;margin-top:24px}
@media(max-width:760px){.stats{grid-template-columns:repeat(2,1fr)}.grid{grid-template-columns:1fr}.wrap{padding-top:14px}.hero h2{font-size:22px}}
</style>
</head>
<body>
<header><div class="brand"><div class="crest">FM</div><div><h1>FÚTBOL MANAGER 2026</h1><small>Tu club. Tus decisiones. Tu leyenda.</small></div></div><div class="muted" id="seasonLabel">TEMPORADA 2026/27</div></header>
<main class="wrap">
<section class="stats">
 <div class="stat"><span>Presupuesto</span><strong id="money">50 M€</strong></div>
 <div class="stat"><span>Jornada</span><strong id="round">1 / 10</strong></div>
 <div class="stat"><span>Balance</span><strong id="record">0V · 0E · 0D</strong></div>
 <div class="stat"><span>Reputación</span><strong id="reputation">⭐ 1</strong></div>
</section>
<div class="hero"><div class="row"><div><div class="badge">MODO CARRERA</div><h2 id="clubTitle">Atlético Vigo</h2><div id="managerLine">Entrenador: Míster</div></div><div style="font-size:42px">🏆</div></div></div>
<nav class="tabs">
 <button class="tab active" data-tab="inicio">🏠 Inicio</button><button class="tab" data-tab="partido">⚽ Partido</button><button class="tab" data-tab="plantilla">👥 Plantilla</button><button class="tab" data-tab="mercado">💰 Fichajes</button><button class="tab" data-tab="liga">🏆 Clasificación</button><button class="tab" data-tab="club">⚙️ Mi club</button>
</nav>
<section id="inicio" class="page">
 <div class="grid">
  <div class="panel"><h2>📅 Próximo encuentro</h2><div class="match"><div class="badge">LIGA · JORNADA <span id="nextRound">1</span></div><div class="teams"><div class="team" id="homeName">Atlético Vigo</div><div class="vs">VS</div><div class="team" id="awayName">Real Madrid</div></div><div class="muted">Estadio Municipal · 20:00</div><div class="actions" style="justify-content:center"><button class="primary" onclick="openTab('partido')">Preparar partido</button></div></div></div>
  <div class="panel"><h2>📋 Resumen del club</h2><p class="muted" id="clubSummary">Tu aventura empieza ahora. Construye un equipo campeón.</p><div class="row"><span>Valor de plantilla</span><b id="squadValue">82 M€</b></div><div class="row"><span>Jugadores</span><b id="playerCount">11</b></div><div class="row"><span>Último resultado</span><b id="lastResult">—</b></div><div id="notice" class="notice">¡Bienvenido, míster! La directiva confía en ti.</div></div>
 </div>
</section>
<section id="partido" class="page hidden">
 <div class="grid"><div class="panel"><h2>⚽ Centro de partidos</h2><label>Formación</label><select id="formation"><option>4-3-3</option><option>4-4-2</option><option>3-5-2</option><option>4-2-3-1</option><option>5-3-2</option></select><label>Estilo de juego</label><select id="style"><option>Equilibrado</option><option>Ofensivo</option><option>Defensivo</option><option>Presión alta</option></select><div class="match" style="margin-top:14px"><div class="badge">PARTIDO OFICIAL</div><div class="teams"><div class="team" id="matchHome">Atlético Vigo</div><div class="vs">VS</div><div class="team" id="matchAway">Real Madrid</div></div><div id="matchScore" class="score">— : —</div><div class="muted" id="matchStatus">Elige cómo quieres jugar el encuentro.</div>
<div class="pitch-wrap"><div class="pitch-label"><span>🔵 TU EQUIPO</span><span>FICHA TÁCTICA · <b id="pitchFormation">4-3-3</b></span></div><div class="pitch" id="pitch">
 <div class="halfway"></div><div class="center-circle"></div><div class="penalty top"></div><div class="penalty bottom"></div><div class="goal top"></div><div class="goal bottom"></div><div id="pitchPlayers"></div><div class="ball" id="matchBall">⚽</div>
</div><div class="pitch-legend"><span>● Jugadores de campo</span><span>⚽ Balón en movimiento</span></div></div>
</div><div class="actions"><button class="primary" id="watchBtn" onclick="playMatch(true)">▶ Ver partido</button><button onclick="playMatch(false)">⏩ Simular partido</button></div></div>
 <div class="panel"><h2>📺 Retransmisión</h2><div id="commentary" class="muted">Todavía no ha comenzado el partido. Pulsa «Ver partido» para seguir los acontecimientos minuto a minuto o simúlalo directamente.</div></div></div>
</section>
<section id="plantilla" class="page hidden"><div class="panel"><h2>👥 Primera plantilla</h2><div id="squadList"></div></div></section>
<section id="mercado" class="page hidden"><div class="grid"><div class="panel"><h2>🔎 Jugadores en el mercado</h2><label>Posición</label><select id="positionFilter" onchange="renderMarket()"><option value="Todos">Todas</option><option>Delantero</option><option>Centrocampista</option><option>Defensa</option><option>Portero</option></select><div id="marketList"></div></div><div class="panel"><h2>📝 Tu estrategia</h2><p class="muted">Ficha jugadores para mejorar el equipo. El precio se descuenta de tu presupuesto al instante.</p><div class="row"><span>Dinero disponible</span><b class="good" id="marketMoney">50 M€</b></div><div class="row"><span>Fichajes realizados</span><b id="transferCount">0</b></div><div class="notice">Consejo: equilibra tu plantilla. Un gran delantero no lo es todo.</div></div></div></section>
<section id="liga" class="page hidden"><div class="panel"><h2>🏆 Clasificación</h2><div style="overflow:auto"><table><thead><tr><th>#</th><th>Club</th><th>J</th><th>G</th><th>E</th><th>P</th><th>Pts</th></tr></thead><tbody id="leagueTable"></tbody></table></div></div></section>
<section id="club" class="page hidden"><div class="grid"><div class="panel"><h2>⚙️ Datos del club</h2><label>Nombre del club</label><input id="clubInput" maxlength="24" value="Atlético Vigo"><label>Nombre del entrenador</label><input id="managerInput" maxlength="24" value="Míster"><label>Presupuesto inicial (M€)</label><select id="budgetInput"><option value="20">20 M€</option><option value="50" selected>50 M€</option><option value="100">100 M€</option><option value="250">250 M€</option></select><div class="actions"><button class="primary" onclick="saveClub()">Guardar cambios</button><button onclick="resetGame()">Nueva partida</button></div></div><div class="panel"><h2>💾 Partida</h2><p class="muted">Tu progreso se guarda automáticamente en este navegador.</p><div class="notice">Puedes cerrar el juego y volver más tarde desde el mismo dispositivo y navegador.</div></div></div></section>
<div class="footer">Fútbol Manager 2026 · Juego de navegador · Partidas guardadas localmente</div>
</main>
<script>
const initialSquad=[
 {name:"Iván Pereira",pos:"Portero",ovr:77,value:8},{name:"Hugo Castro",pos:"Defensa",ovr:76,value:7},{name:"Mateo López",pos:"Defensa",ovr:78,value:9},{name:"Bruno Silva",pos:"Defensa",ovr:75,value:6},{name:"Nico Fernández",pos:"Defensa",ovr:77,value:8},{name:"Adrián Gómez",pos:"Centrocampista",ovr:80,value:12},{name:"Lucas Rey",pos:"Centrocampista",ovr:78,value:10},{name:"Pablo Varela",pos:"Centrocampista",ovr:75,value:7},{name:"Diego Martín",pos:"Delantero",ovr:82,value:16},{name:"Samuel Torres",pos:"Delantero",ovr:79,value:12},{name:"Álex Romero",pos:"Delantero",ovr:74,value:6}
];
const marketPlayers=[
 {name:"Leo Ramírez",pos:"Delantero",ovr:84,price:18},{name:"Álex Silva",pos:"Centrocampista",ovr:81,price:14},{name:"Dani Costa",pos:"Defensa",ovr:78,price:9},{name:"Marco Santos",pos:"Portero",ovr:82,price:12},{name:"Iker Torres",pos:"Delantero",ovr:76,price:8},{name:"Pablo Martín",pos:"Centrocampista",ovr:75,price:7},{name:"Gabriel Ruiz",pos:"Defensa",ovr:83,price:17},{name:"Enzo Vidal",pos:"Delantero",ovr:88,price:32},{name:"Tomás Gil",pos:"Portero",ovr:75,price:5},{name:"Joel Méndez",pos:"Centrocampista",ovr:86,price:25},{name:"Sergio León",pos:"Defensa",ovr:80,price:13},{name:"Mario Núñez",pos:"Delantero",ovr:80,price:15}
];
const opponents=["Real Madrid","FC Barcelona","Atlético de Madrid","Sevilla FC","Valencia CF","Real Betis","Athletic Club","Villarreal CF","Girona FC","Real Sociedad"];
let state;
function fresh(){return {club:"Atlético Vigo",manager:"Míster",money:50,round:1,w:0,d:0,l:0,reputation:1,squad:initialSquad.map(x=>({...x})),bought:[],table:opponents.map(n=>({name:n,p:0,w:0,d:0,l:0,pts:0})),last:"—",finished:false};}
function load(){try{state=JSON.parse(localStorage.getItem("fm26save"))||fresh()}catch(e){state=fresh()} }
function save(){localStorage.setItem("fm26save",JSON.stringify(state));render()}
function openTab(id){document.querySelectorAll(".page").forEach(p=>p.classList.add("hidden"));document.getElementById(id).classList.remove("hidden");document.querySelectorAll(".tab").forEach(b=>b.classList.toggle("active",b.dataset.tab===id));}
document.querySelectorAll(".tab").forEach(b=>b.addEventListener("click",()=>openTab(b.dataset.tab)));
function nextOpponent(){return opponents[(state.round-1)%opponents.length]}
function render(){let $=id=>document.getElementById(id);$("money").textContent=state.money+" M€";$("marketMoney").textContent=state.money+" M€";$("round").textContent=state.finished?"FIN":state.round+" / 10";$("record").textContent=`${state.w}V · ${state.d}E · ${state.l}D`;$("reputation").textContent="⭐ "+state.reputation;$("clubTitle").textContent=state.club;$("managerLine").textContent="Entrenador: "+state.manager;$("homeName").textContent=state.club;$("matchHome").textContent=state.club;$("awayName").textContent=nextOpponent();$("matchAway").textContent=nextOpponent();$("nextRound").textContent=state.round;$("squadValue").textContent=state.squad.reduce((a,p)=>a+p.value,0)+" M€";$("playerCount").textContent=state.squad.length;$("lastResult").textContent=state.last;$("transferCount").textContent=state.bought.length;$("clubSummary").textContent=`${state.club} compite en la liga. Tu objetivo: terminar entre los primeros.`;$("clubInput").value=state.club;$("managerInput").value=state.manager;renderSquad();renderMarket();renderTable();}
function renderSquad(){document.getElementById("squadList").innerHTML=state.squad.map(p=>`<div class="player"><div><b>${p.name}</b><div class="price">${p.pos} · Valor ${p.value} M€</div></div><span class="ovr">${p.ovr} MED</span><span class="badge">Titular</span></div>`).join("");renderPitch()}
function renderPitch(){
 const formation=document.getElementById("formation")?.value||"4-3-3";
 const shapes={"4-3-3":[[50,89],[18,72],[39,76],[61,76],[82,72],[34,53],[50,58],[66,53],[24,28],[50,20],[76,28]],"4-4-2":[[50,89],[18,72],[39,76],[61,76],[82,72],[20,48],[40,54],[60,54],[80,48],[37,25],[63,25]],"3-5-2":[[50,89],[25,72],[50,76],[75,72],[14,51],[33,53],[50,58],[67,53],[86,51],[38,26],[62,26]],"4-2-3-1":[[50,89],[18,72],[39,76],[61,76],[82,72],[39,57],[61,57],[22,35],[50,40],[78,35],[50,20]],"5-3-2":[[50,89],[12,72],[31,76],[50,78],[69,76],[88,72],[32,52],[50,57],[68,52],[38,27],[62,27]]};
 const starters=state.squad.slice(0,11);const coords=shapes[formation]||shapes["4-3-3"];
 document.getElementById("pitchFormation").textContent=formation;
 document.getElementById("pitchPlayers").innerHTML=starters.map((p,i)=>{const [x,y]=coords[i];const initials=p.name.split(" ").map(w=>w[0]).slice(0,2).join("").toUpperCase();return `<div class="pitch-player ${p.pos==="Portero"?"keeper":""}" style="left:${x}%;top:${y}%"><div class="shirt">${initials}</div><span class="pname">${p.name.split(" ")[0]}</span></div>`}).join("");
}
document.getElementById("formation").addEventListener("change",renderPitch);
function renderMarket(){let f=document.getElementById("positionFilter")?.value||"Todos";let available=marketPlayers.filter(p=>(f==="Todos"||p.pos===f)&&!state.bought.includes(p.name));document.getElementById("marketList").innerHTML=available.map((p,i)=>`<div class="player"><div><b>${p.name}</b><div class="price">${p.pos} · ${p.price} M€</div></div><span class="ovr">${p.ovr}</span><button ${state.money<p.price?"disabled":""} onclick="buy('${p.name}')">Fichar</button></div>`).join("")||'<p class="muted">No hay jugadores disponibles en esta posición.</p>'}
function renderTable(){let mine={name:state.club,p:state.w+state.d+state.l,w:state.w,d:state.d,l:state.l,pts:state.w*3+state.d};let rows=[...state.table,mine].sort((a,b)=>b.pts-a.pts||b.w-a.w);document.getElementById("leagueTable").innerHTML=rows.map((t,i)=>`<tr style="${t.name===state.club?'background:#1c3c32;font-weight:800':''}"><td>${i+1}</td><td>${t.name}</td><td>${t.p}</td><td>${t.w}</td><td>${t.d}</td><td>${t.l}</td><td><b>${t.pts}</b></td></tr>`).join("")}
function buy(name){let p=marketPlayers.find(x=>x.name===name);if(!p||state.money<p.price)return;state.money-=p.price;state.bought.push(name);state.squad.push({...p,value:p.price});document.getElementById("notice").textContent=`¡Fichaje cerrado! ${name} ya es jugador de ${state.club}.`;save()}
function saveClub(){state.club=document.getElementById("clubInput").value.trim()||"Mi FC";state.manager=document.getElementById("managerInput").value.trim()||"Míster";save();document.getElementById("notice").textContent="Datos del club actualizados."}
let matchBusy=false;
function playMatch(watch){
 if(state.finished||matchBusy)return;
 matchBusy=true;
 const buttons=[...document.querySelectorAll("#partido .actions button")];buttons.forEach(b=>b.disabled=true);
 const avg=state.squad.reduce((a,p)=>a+p.ovr,0)/state.squad.length;
 const style=document.getElementById("style").value;
 const boost=style==="Ofensivo"?1:style==="Defensivo"?-.2:style==="Presión alta"?.6:0;
 const strength=(avg-75)/5+boost;
 let home=Math.max(0,Math.min(5,Math.floor(Math.random()*3+Math.random()*2+strength*.35)));
 let away=Math.max(0,Math.min(5,Math.floor(Math.random()*3+Math.random()*1.5+(80-avg)*.12)));
 if(Math.random()<.18)away++;if(Math.random()<.18)home++;
 const events=[`2' · ¡Comienza el partido! ${state.club} sale con ${document.getElementById("formation").value}.`,`18' · Primera ocasión clara para ${state.club}.`,`34' · El rival responde con un contraataque peligroso.`,`45' · Descanso. El marcador está ${home}-${away}.`,`61' · ¡La afición empuja! El equipo busca el gol.`,`78' · Últimos minutos: máxima tensión.`,`90' · ¡Final del partido! ${home}-${away} frente a ${nextOpponent()}.`];
 const pitch=document.getElementById("pitch");
 pitch.classList.add("live");
 document.getElementById("matchScore").textContent="0 : 0";
 document.getElementById("matchStatus").textContent=watch?"EN DIRECTO · 0'":"SIMULANDO...";
 document.getElementById("commentary").innerHTML="";
 if(!watch){
   finishMatch(home,away);
   pitch.classList.remove("live");matchBusy=false;buttons.forEach(b=>b.disabled=false);return;
 }
 let tick=0;let shownHome=0,shownAway=0;
 const timer=setInterval(()=>{
   const minute=[2,18,34,45,61,78,90][tick];
   if(tick===2&&home>0)shownHome=Math.max(1,Math.round(home/2));
   if(tick===4)shownAway=away>0?Math.max(1,Math.round(away/2)):0;
   if(tick===5){shownHome=home;shownAway=away;}
   if(tick===6){shownHome=home;shownAway=away;}
   document.getElementById("matchScore").textContent=shownHome+" : "+shownAway;
   document.getElementById("matchStatus").textContent=`EN DIRECTO · ${minute}'`;
   document.getElementById("commentary").innerHTML+=`<div class="event">${events[tick]}</div>`;
   tick++;
   if(tick>=events.length){
     clearInterval(timer);finishMatch(home,away);pitch.classList.remove("live");matchBusy=false;buttons.forEach(b=>b.disabled=false);
   }
 },950);
}
function finishMatch(home,away){
 const opponent=nextOpponent();
 state.last=`${home} - ${away} vs ${opponent}`;
 if(home>away)state.w++;else if(home===away)state.d++;else state.l++;
 const opp=state.table.find(t=>t.name===opponent);
 if(opp){opp.p++;if(away>home){opp.w++;opp.pts+=3}else if(away===home){opp.d++;opp.pts++}else opp.l++}
 let my=state.table.find(t=>t.name===state.club);
 if(!my){my={name:state.club,p:0,w:0,d:0,l:0,pts:0};state.table.push(my)}
 my.p++;if(home>away){my.w++;my.pts+=3}else if(home===away){my.d++;my.pts++}else my.l++;
 if(home>away){state.reputation=Math.min(5,state.reputation+1);state.money+=2}
 else if(home===away)state.money+=1;
 document.getElementById("matchScore").textContent=home+" : "+away;
 document.getElementById("matchStatus").textContent="FINAL DEL PARTIDO";
 if(!document.getElementById("commentary").innerHTML)document.getElementById("commentary").innerHTML=`<div class="event">Partido simulado. Resultado final: ${state.last}.</div>`;
 state.round++;
 if(state.round>10){state.finished=true;document.getElementById("notice").textContent="¡Temporada terminada! Revisa la clasificación final."}
 else document.getElementById("notice").textContent=home>away?"¡Victoria! La directiva está encantada.":home===away?"Empate. Hay que seguir trabajando.":"Derrota. Toca levantar cabeza.";
 save();
 document.getElementById("round").textContent=state.finished?"FIN":state.round+" / 10";
 document.getElementById("nextRound").textContent=state.round;
 document.getElementById("awayName").textContent=nextOpponent();
 document.getElementById("matchAway").textContent=nextOpponent();
 if(state.finished)document.getElementById("matchStatus").textContent="TEMPORADA FINALIZADA";
}
function resetGame(){if(confirm("¿Seguro que quieres empezar una nueva partida? Se borrará el progreso actual.")){state=fresh();save();document.getElementById("commentary").textContent="Nueva temporada. ¡Mucha suerte, míster!";document.getElementById("matchScore").textContent="— : —";document.getElementById("matchStatus").textContent="Elige cómo quieres jugar el encuentro."}}
load();render();renderPitch();
</script>
</body></html>
