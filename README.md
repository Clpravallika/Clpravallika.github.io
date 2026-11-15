# Project-Hypothesis
Project Hypothesis: NASA Space Apps 2026 entry

<!DOCTYPE html>
<!-- SI disclosure: the code, SVG drawings and component descriptions in this file were generated with an AI chatbot (Claude, by Anthropic) and reviewed by the team. -->
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1, viewport-fit=cover">
<title>Project Hypothesis: Abandoned but Not Forgotten</title>
<meta name="generator" content="SI-assisted: code and text generated with Claude (Anthropic), reviewed by the team">
<meta name="ai-disclosure" content="Code, SVG illustrations and descriptive text were generated with an AI chatbot (Claude) and reviewed against NASA and ISRO sources.">
<style>
:root{--bg:#04091a;--bg2:#0a1631;--panel:#0d1b3c;--line:#1f3b78;--txt:#eaf2ff;--mut:#93a8d4;--cy:#3df2ff;--mg:#ff4fd8;--am:#ffb347;color-scheme:dark;box-sizing:border-box;padding-top:env(safe-area-inset-top,0px);padding-bottom:env(safe-area-inset-bottom,0px)}
*{box-sizing:border-box}html{scroll-padding-top:env(safe-area-inset-top,0px)}
body{margin:0;min-height:100vh;color:var(--txt);font:16px/1.55 "Segoe UI",Roboto,Arial,sans-serif;background:radial-gradient(1px 1px at 12% 18%,#fff8,transparent),radial-gradient(1px 1px at 68% 8%,#fff6,transparent),radial-gradient(1.5px 1.5px at 85% 40%,#fff7,transparent),radial-gradient(ellipse at 50% -10%,#16307a 0,transparent 55%),var(--bg)}
header{padding:24px 20px 4px;max-width:1100px;margin:auto}
h1{margin:0;font-size:clamp(24px,5vw,40px);font-weight:700}h1 span{color:var(--cy);text-shadow:0 0 18px #3df2ff88}
header p{color:var(--mut);margin:8px 0 0;max-width:62ch;font-size:15px}
nav{display:flex;gap:8px;max-width:1100px;margin:14px auto 0;padding:0 20px 6px;overflow-x:auto;scrollbar-width:thin}
nav button{flex:none;padding:10px 14px;border-radius:10px;border:1px solid var(--line);background:var(--bg2);color:var(--txt);font:inherit;font-size:14px;font-weight:600;cursor:pointer;transition:.25s;white-space:nowrap}
nav button:hover,nav button:focus-visible{border-color:var(--cy);box-shadow:0 0 14px #3df2ff44;outline:none}
nav button[aria-selected=true]{border-color:var(--cy);background:linear-gradient(180deg,#123068,#0a1c44);box-shadow:0 0 14px #3df2ff55 inset}
main{max-width:1100px;margin:12px auto 36px;padding:0 20px;display:grid;grid-template-columns:1.4fr 1fr;gap:18px}
@media(max-width:820px){main{grid-template-columns:1fr}}
.stage{position:relative;border:1px solid var(--line);border-radius:16px;overflow:hidden;background:linear-gradient(#3df2ff0d 1px,transparent 1px) 0 0/32px 32px,linear-gradient(90deg,#3df2ff0d 1px,transparent 1px) 0 0/32px 32px,linear-gradient(180deg,#071230,#050c20)}
.stage svg{display:block;width:100%;height:auto}
.hint{position:absolute;left:12px;bottom:8px;font-size:12px;color:var(--mut)}
.hot{cursor:pointer;outline:none}.hot .sh{transition:filter .25s,stroke .25s}
.hot:hover .sh,.hot:focus-visible .sh{filter:drop-shadow(0 0 7px var(--cy));stroke:var(--cy);stroke-width:2.5}
.pulse{fill:var(--cy);animation:pl 2.4s ease-in-out infinite}
@keyframes pl{0%,100%{opacity:.35}50%{opacity:1}}
.side{display:flex;flex-direction:column;gap:14px}
.card{border:1px solid var(--line);border-radius:14px;background:linear-gradient(180deg,var(--panel),#091431);padding:16px 18px}
.card h2{margin:0 0 4px;font-size:20px}.sub{color:var(--cy);font-size:14px;margin-bottom:6px}
.st{display:inline-block;margin:6px 0;padding:2px 10px;border:1px solid var(--am);border-radius:999px;color:var(--am);font-size:13px}
.card ul{margin:8px 0 0;padding-left:18px;font-size:14px;color:#cfdcf5}
.card dl{margin:10px 0 0;display:grid;grid-template-columns:auto 1fr;gap:4px 12px;font-size:14px}.card dt{color:var(--mut)}.card dd{margin:0}
.chips{display:flex;flex-wrap:wrap;gap:8px}
.chips button{padding:8px 12px;border-radius:999px;border:1px solid var(--line);background:transparent;color:var(--txt);font:inherit;font-size:14px;cursor:pointer;transition:.25s}
.chips button:hover,.chips button:focus-visible{border-color:var(--mg);box-shadow:0 0 12px #ff4fd855;outline:none}
#tip{position:fixed;z-index:20;pointer-events:none;max-width:260px;padding:10px 12px;border-radius:10px;background:#071026ee;border:1px solid var(--cy);box-shadow:0 0 18px #3df2ff44;font-size:13px;opacity:0;transition:opacity .2s}
#tip.on{opacity:1}#tip b{color:var(--cy);display:block}#tip i{color:var(--am);font-style:normal}
#veil{position:fixed;inset:0;background:#02060fb0;opacity:0;pointer-events:none;transition:opacity .3s;z-index:30}#veil.on{opacity:1;pointer-events:auto}
#panel{position:fixed;z-index:31;top:0;right:0;bottom:0;width:min(440px,100%);background:linear-gradient(180deg,#0e2050,#070f28);border-left:1px solid var(--cy);transform:translateX(105%);transition:transform .35s cubic-bezier(.2,.8,.2,1);overflow-y:auto;padding:24px 22px calc(28px + env(safe-area-inset-bottom,0px))}
#panel.on{transform:none}
@media(max-width:820px){#panel{top:auto;left:0;width:100%;max-height:82vh;border-left:0;border-top:1px solid var(--cy);border-radius:18px 18px 0 0;transform:translateY(105%)}}
#panel h3{margin:0 0 4px;font-size:24px;color:var(--cy);padding-right:44px}#panel .tag{color:var(--am);font-size:14px}
#panel h4{margin:16px 0 4px;font-size:15px;color:var(--mg)}#panel p{margin:0;color:#d8e4fb;font-size:15px}
.stats{display:grid;grid-template-columns:1fr 1fr;gap:8px;margin-top:16px}.stats div{border:1px solid var(--line);border-radius:10px;padding:8px 10px;font-size:13px;color:var(--mut)}.stats b{display:block;color:var(--txt);font-size:15px}
#close{position:absolute;top:14px;right:14px;width:38px;height:38px;border-radius:50%;border:1px solid var(--line);background:transparent;color:var(--txt);font-size:20px;cursor:pointer}
#close:hover,#close:focus-visible{border-color:var(--mg);box-shadow:0 0 12px #ff4fd866;outline:none}
footer{text-align:center;color:var(--mut);font-size:13px;padding:0 20px 24px}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}}
</style>
</head>
<body>
<header>
<h1>Project <span>Hypothesis</span></h1>
<p>Our entry for the challenge “Abandoned but Not Forgotten”. Nine machines NASA and ISRO sent to the Moon and Mars, from rovers left parked to a lander that fell silent. Pick one, then select a glowing part.</p>
</header>
<nav id="nav" role="tablist" aria-label="Missions"></nav>
<main>
<section class="stage" id="stage"></section>
<aside class="side"><div class="card" id="brief"></div><div class="card"><div class="sub">Components</div><div class="chips" id="chips"></div></div></aside>
</main>
<footer>Simplified schematics drawn in code. Works fully offline.<br>SI disclosure: the code, SVG illustrations and descriptive text were generated with an AI chatbot (Claude, by Anthropic) and reviewed by our team.</footer>
<div id="tip" role="tooltip"></div><div id="veil"></div>
<aside id="panel" role="dialog" aria-modal="true" aria-labelledby="pt"><button id="close" aria-label="Close panel">×</button><div id="pc"></div></aside>
<script>
const G='<defs><linearGradient id="bd" x1="0" y1="0" x2="0" y2="1"><stop offset="0" stop-color="#e8edf6"/><stop offset="1" stop-color="#7d889f"/></linearGradient><linearGradient id="gd" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#ffd37a"/><stop offset=".6" stop-color="#c98a22"/><stop offset="1" stop-color="#7a4d0b"/></linearGradient><linearGradient id="sp" x1="0" y1="0" x2="1" y2="1"><stop offset="0" stop-color="#1b4fd1"/><stop offset="1" stop-color="#0a1c5c"/></linearGradient></defs>';
const hot=(k,l,inner,px,py)=>`<g class="hot" data-k="${k}" tabindex="0" role="button" aria-label="${l}">${inner}<circle class="pulse" cx="${px}" cy="${py}" r="5"/></g>`;
const wh=(x,y,r)=>`<circle cx="${x}" cy="${y}" r="${r}" fill="#121a30" stroke="#aab6cc" stroke-width="2"/><circle cx="${x}" cy="${y}" r="${r/2.3}" fill="none" stroke="#ffb347" stroke-width="2"/>`;
const S={
lrv:{vb:"0 0 400 250",svg:G+hot('ant','High-gain antenna','<path class="sh" d="M245 120 V70" stroke="#aab6cc" stroke-width="4"/><path class="sh" d="M200 70 Q245 40 290 70 Z" fill="url(#bd)" stroke="#cfd8e8"/>',245,56)+
hot('seat','Seats and controller','<g class="sh" fill="#2a3350" stroke="#ffb347"><rect x="160" y="128" width="26" height="26" rx="3"/><rect x="198" y="128" width="26" height="26" rx="3"/><path d="M130 110 L130 135 L160 135" fill="none"/></g>',200,140)+
hot('batt','Chassis and batteries','<rect class="sh" x="95" y="152" width="210" height="18" rx="4" fill="url(#bd)" stroke="#cfd8e8"/><rect class="sh" x="240" y="130" width="50" height="22" rx="3" fill="url(#gd)" stroke="#e7b657"/>',265,141)+
hot('wheels','Wire-mesh wheels',[100,300].map(x=>`<g class="sh"><circle cx="${x}" cy="200" r="32" fill="#121a30" stroke="#aab6cc" stroke-width="3" stroke-dasharray="5 3"/><circle cx="${x}" cy="200" r="14" fill="none" stroke="#ffb347" stroke-width="2"/></g>`).join('')+'<path d="M100 170 V200 M300 170 V200" stroke="#aab6cc" stroke-width="4"/>',100,200)+'<path d="M40 232 H360" stroke="#c9c3b855" stroke-width="2"/>'},
mer:{vb:"0 0 400 250",svg:G+hot('deck','Solar deck','<path class="sh" d="M95 130 L305 130 L330 150 L70 150 Z" fill="url(#sp)" stroke="#6f9cff"/><path d="M130 130 L125 150 M200 130 V150 M270 130 L275 150" stroke="#6f9cff88"/>',200,140)+
hot('mast','Pancam mast','<path class="sh" d="M150 130 V60" stroke="#aab6cc" stroke-width="5"/><rect class="sh" x="130" y="36" width="40" height="22" rx="4" fill="url(#bd)" stroke="#cfd8e8"/><circle cx="141" cy="47" r="5" fill="#06142f" stroke="#3df2ff"/><circle cx="159" cy="47" r="5" fill="#06142f" stroke="#3df2ff"/>',150,28)+
hot('arm','Instrument arm','<path class="sh" d="M320 150 L350 175 L335 198" stroke="#cfd8e8" stroke-width="6" fill="none" stroke-linecap="round" stroke-linejoin="round"/><circle class="sh" cx="333" cy="200" r="10" fill="#2a3350" stroke="#ffb347" stroke-width="2"/>',333,200)+
hot('wheels','Wheels','<g class="sh">'+[100,200,300].map(x=>wh(x,205,24)).join('')+'</g><path d="M100 165 L100 205 M200 165 V205 M300 165 V205" stroke="#9aa6bf" stroke-width="4"/>',200,205)},
msl:{vb:"0 0 400 270",svg:G+hot('wheels','Wheels','<path class="sh" d="M95 160 L120 205 L205 205 L225 170 L290 205" stroke="#9aa6bf" stroke-width="5" fill="none"/><g class="sh">'+[100,195,295].map(x=>wh(x,208,27)).join('')+'</g>',195,208)+
hot('power','Power source','<g class="sh"><path d="M52 112 L100 118 L100 150 L52 156 Z" fill="#a1357f" stroke="#ff9be9"/><path d="M62 114 V154 M72 115 V153 M82 116 V152 M92 117 V151" stroke="#2a0f26" stroke-width="2"/></g>',76,134)+
'<rect x="100" y="108" width="190" height="56" rx="8" fill="url(#bd)" stroke="#cfd8e8"/><rect x="122" y="118" width="60" height="22" rx="3" fill="#0b1a3f" stroke="#3df2ff"/><path d="M194 120 H270 M194 132 H270 M194 144 H250" stroke="#4a5875" stroke-width="2"/>'+
hot('mast','Camera mast','<path class="sh" d="M135 108 V50" stroke="#aab6cc" stroke-width="6"/><rect class="sh" x="112" y="26" width="52" height="26" rx="5" fill="url(#bd)" stroke="#cfd8e8"/><circle cx="126" cy="39" r="7" fill="#06142f" stroke="#3df2ff"/><circle cx="150" cy="39" r="7" fill="#06142f" stroke="#3df2ff"/>',138,18)+
hot('arm','Robotic arm','<path class="sh" d="M290 128 L330 148 L360 182 L342 196" stroke="#cfd8e8" stroke-width="7" fill="none" stroke-linecap="round" stroke-linejoin="round"/><circle class="sh" cx="340" cy="196" r="13" fill="#2a3350" stroke="#ffb347" stroke-width="2"/>',340,196)},
heli:{vb:"0 0 400 270",svg:G+hot('rotor','Counter-rotating rotors','<g class="sh"><rect x="40" y="52" width="320" height="7" rx="3" fill="#cfd8e8"/><rect x="60" y="84" width="280" height="7" rx="3" fill="#8794ad"/></g><path d="M200 59 V84" stroke="#aab6cc" stroke-width="5"/>',200,48)+
hot('solar','Solar panel','<path class="sh" d="M150 38 H250 V50 H150 Z" fill="url(#sp)" stroke="#6f9cff"/>',200,30)+
hot('body','Fuselage and cameras','<rect class="sh" x="170" y="100" width="60" height="70" rx="10" fill="url(#gd)" stroke="#e7b657"/><circle cx="200" cy="165" r="6" fill="#06142f" stroke="#3df2ff"/>',200,130)+
hot('legs','Landing legs','<path class="sh" d="M175 170 L130 235 M225 170 L270 235 M190 170 L170 240 M210 170 L230 240" stroke="#aab6cc" stroke-width="5" stroke-linecap="round" fill="none"/>',130,235)+'<path d="M80 250 H320" stroke="#c4562f66" stroke-width="2"/>'},
vik:{vb:"0 0 400 270",svg:G+hot('solar','Solar panels','<path class="sh" d="M130 90 L270 90 L280 110 L120 110 Z" fill="url(#sp)" stroke="#6f9cff"/>',200,100)+
hot('bay','Rover bay and ramp','<rect class="sh" x="145" y="125" width="110" height="70" rx="6" fill="url(#bd)" stroke="#cfd8e8"/><path class="sh" d="M255 135 L310 205" stroke="#ffb347" stroke-width="6"/><rect x="170" y="140" width="40" height="40" rx="4" fill="#0b1a3f" stroke="#3df2ff"/>',230,160)+
hot('eng','Throttleable engines','<g class="sh" fill="#2a3350" stroke="#ff9d5c"><path d="M150 195 L140 222 L168 222 Z"/><path d="M232 195 L222 222 L250 222 Z"/><path d="M191 195 L181 226 L209 226 Z"/></g>',195,215)+
hot('legs','Landing legs','<path class="sh" d="M145 190 L90 245 M255 190 L310 245" stroke="#aab6cc" stroke-width="6" stroke-linecap="round"/><ellipse class="sh" cx="84" cy="249" rx="20" ry="5" fill="url(#gd)" stroke="#aab6cc"/><ellipse class="sh" cx="316" cy="249" rx="20" ry="5" fill="url(#gd)" stroke="#aab6cc"/>',88,249)}};

const P=(t,tag,fn,eng,role,s)=>({t,tag,fn,eng,role,s});
const LRV={
wheels:P("Wire-mesh wheels","Four wheels, one motor each","Each wheel is a woven mesh of zinc-coated piano wire with titanium chevron treads, driven by its own electric motor.","The mesh deforms over rock and flexes back, saving mass versus rubber and surviving the lunar temperature swing. Four-wheel steering gave a tight turning circle.","Carried two astronauts and tools far beyond walking distance and left tracks that still sit on the surface.",[["Motors","4 (one per wheel)"],["Steering","Front and rear"],["Top speed","about 13 km/h"],["Tire","Woven wire mesh"]]),
ant:P("High-gain antenna","Umbrella dish on a mast","A steerable mesh dish sent TV and voice directly to Earth, and the rover’s TV camera let Mission Control watch launches of the ascent stage.","The dish folds like an umbrella to fit the stowed rover. Astronauts pointed it at Earth by hand, using a simple sight.","Gave the world live color video from the surface for the first time.",[["Type","Folding mesh dish"],["Link","Direct to Earth"],["Camera","Color TV"],["Aim","Manual"]]),
seat:P("Seats and controller","Folding seats, T-handle","Lightweight tube-and-webbing seats and a single T-shaped hand controller sit in front of a small navigation display.","Pushing the handle forward drove, pulling back braked, and tilting steered. A gyro-based unit showed heading and range to the LM so crews could always find the way back.","Let suited astronauts drive and navigate safely, even with limited visibility.",[["Crew","2 astronauts"],["Controller","T-handle"],["Navigation","Gyro and odometer"],["Payload","about 490 kg"]]),
batt:P("Chassis and batteries","Aluminum frame, silver-zinc cells","An aluminum frame folded into a compact bundle, with two non-rechargeable silver-zinc batteries powering motors, avionics and the TV.","Hinged chassis sections folded to fit a bay of the lander. The batteries ran at 36 volts and were sized for roughly 90 km total.","Powered every drive, and the rover was left parked in lunar dust when each crew departed.",[["Mass (Earth)","about 210 kg"],["Battery","2 × 36 V"],["Frame","Folding aluminum"],["Left","On the Moon"]])};
const MER={
deck:P("Solar deck","Top-mounted solar arrays","Triple-junction solar cells on the rover’s top deck charged lithium-ion batteries to run electronics and motors by day.","Panels produced about 900 watt-hours on a clear Martian day at first, falling as dust accumulated. Winter and dust storms put them at risk.","Opportunity’s end came in a global dust storm that blocked light, and Spirit’s power fell short during a winter in a sand trap.",[["Source","Solar"],["Battery","Lithium-ion"],["Rover mass","about 185 kg"],["Design life","90 sols"]]),
mast:P("Pancam mast","Stereo color camera","A pair of cameras with color filters gave high-resolution stereo pictures and also helped read the minerals of far-off rocks.","Mounted at about 1.5 m, it provided human-height views and panoramas that scientists stitched into landscapes.","Found targets for science and picked safe drive routes across plains and hills.",[["Cameras","Stereo pair"],["Height","about 1.5 m"],["Filters","Multispectral"],["Use","Panoramas"]]),
arm:P("Instrument arm","Rock abrasion tool and sensors","A five-joint arm held a grinder (RAT), a microscopic imager, and Mössbauer and X-ray spectrometers against rocks and soil.","The grinder cut a few millimeters into rock to expose fresh minerals unaffected by surface weathering.","Delivered the evidence that liquid water once shaped these sites.",[["Tools","4"],["Joints","5"],["Grinder","RAT"],["Finding","Past water"]]),
wheels:P("Wheels","Six wheels, rocker-bogie","Six aluminum wheels on a rocker-bogie suspension carried each rover over loose sand and rock.","Spirit became stuck in soft sand in 2009, and one wheel on each rover had stopped turning earlier, so teams drove backwards.","Showed how terrain risk shapes missions, and drove lessons for later wheel design.",[["Wheels","6"],["Diameter","about 26 cm"],["Spirit stuck","2009"],["Opportunity","45 km driven"]])};
const MS={
arm:P("Robotic arm","2.1 m arm with tool turret","Positions a turret holding a drill, scoop, hand-lens camera and X-ray spectrometer.","Five joints place tools flat on uneven rock. A percussion drill collects powder for onboard laboratories.","Core of the search for past habitable conditions.",[["Reach","about 2.1 m"],["Joints","5"],["Drill depth","about 5 cm"],["Tools","5"]]),
mast:P("Mastcam","Two color cameras","Two zoom-capable color cameras take wide and detailed images and video of terrain.","Different focal lengths (34 mm and 100 mm) balance field of view with detail from the ~2 m mast.","Scouts targets and plans drives.",[["Sensor","1600 × 1200"],["Lenses","34 / 100 mm"],["Height","about 2 m"],["Video","Yes"]]),
wheels:P("Wheels and suspension","Six aluminum wheels","Cleated aluminum wheels on a rocker-bogie suspension climb over obstacles.","The corner wheels steer. Wear and punctures over the years led drivers to pick gentler paths.","Gives access to the layers of Mount Sharp.",[["Wheels","6"],["Diameter","about 50 cm"],["Speed","about 4 cm/s"],["Suspension","Rocker-bogie"]]),
power:P("Power source (MMRTG)","Nuclear heat to electricity","Converts heat from decaying plutonium-238 dioxide into electricity for the rover and keeps electronics warm.","No moving parts; thermocouples produce about 110 W at landing.","Works day and night, in any season.",[["Electrical","about 110 W"],["Heat","about 2,000 W"],["Fuel","4.8 kg Pu-238"],["Batteries","2 Li-ion"]])};
const PV={
arm:P("Robotic arm","Sampling turret","The 2.1 m arm carries PIXL (X-ray) and SHERLOC (ultraviolet Raman) to study rock chemistry and organics.","Fine-pointing hardware lets it place instruments within millimeters of a rock face.","Selects the most promising rocks for the sample caching system.",[["Reach","about 2.1 m"],["Instruments","PIXL, SHERLOC"],["Cameras","WATSON"],["Goal","Biosignatures"]]),
mast:P("Mastcam-Z and SuperCam","Zooming eyes and laser","Mastcam-Z zooms in color and stereo, while SuperCam fires a laser to vaporize rock and analyze the glowing plasma.","SuperCam also has a microphone, letting scientists hear the laser impact and Mars winds.","Identifies targets from a distance without driving.",[["Imager","Zoom, stereo"],["Laser range","over 7 m"],["Mic","Yes"],["Height","about 2 m"]]),
wheels:P("Wheels","Thicker aluminum wheels","Six wheels with deeper treads and thicker skins than Curiosity’s, built after wear damage was seen.","Each wheel is about 52 cm in diameter, and a rocker-bogie suspension keeps the body stable.","Roves across Jezero Crater’s delta and rim.",[["Wheels","6"