<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width,initial-scale=1.0">
<title>IO // COMMAND CENTER V2</title>

<style>
*{box-sizing:border-box;margin:0;padding:0;font-family:Arial,sans-serif}

body{
    background:#020609;
    color:#bdefff;
    min-height:100vh;
    overflow-x:hidden;
}

/* SCANLINES */
body:before{
    content:"";
    position:fixed;
    inset:0;
    pointer-events:none;
    z-index:999;
    background:repeating-linear-gradient(
        0deg,
        rgba(255,255,255,.015) 0px,
        rgba(255,255,255,.015) 1px,
        transparent 1px,
        transparent 4px
    );
}

/* BOOT */

#boot{
    position:fixed;
    inset:0;
    background:#010405;
    z-index:1000;
    display:flex;
    align-items:center;
    justify-content:center;
    padding:25px;
}

.bootbox{
    width:min(700px,100%);
    color:#55eaff;
    font-family:monospace;
    font-size:14px;
}

#bootText{
    white-space:pre-line;
    line-height:1.8;
}

.progress{
    height:4px;
    background:#12323c;
    margin-top:20px;
}

#bar{
    width:0%;
    height:100%;
    background:#55eaff;
    box-shadow:0 0 15px #55eaff;
}

/* LOGIN */

#login{
    min-height:100vh;
    display:none;
    align-items:center;
    justify-content:center;
    background:
      radial-gradient(circle,#123c4b 0%,#061017 35%,#010304 75%);
}

.loginbox{
    width:min(450px,90%);
    padding:42px;
    border:1px solid #39ddff;
    background:rgba(3,13,18,.95);
    box-shadow:0 0 45px rgba(40,220,255,.3);
    text-align:center;
}

.logo{
    font-size:55px;
    font-weight:900;
    letter-spacing:12px;
    color:#62eaff;
    text-shadow:0 0 20px #26dfff;
}

.small{
    color:#54737e;
    letter-spacing:3px;
    font-size:11px;
    margin:8px 0 30px;
}

input{
    width:100%;
    padding:14px;
    background:#061016;
    border:1px solid #20505e;
    color:#dffaff;
    outline:none;
    margin:7px 0;
}

input:focus{
    border-color:#5deaff;
    box-shadow:0 0 12px rgba(60,220,255,.25);
}

button{
    padding:12px 18px;
    border:1px solid #36ddff;
    background:#061b24;
    color:#64eaff;
    cursor:pointer;
    font-weight:bold;
    letter-spacing:1px;
}

button:hover{
    background:#0c3542;
    box-shadow:0 0 15px rgba(60,220,255,.35);
}

.loginbtn{
    width:100%;
    margin-top:12px;
}

#error{
    color:#ff6262;
    min-height:22px;
    margin-top:14px;
    font-size:12px;
}

/* DASHBOARD */

#app{display:none}

header{
    height:70px;
    display:flex;
    align-items:center;
    justify-content:space-between;
    padding:0 22px;
    border-bottom:1px solid #17404d;
    background:#03090d;
}

.headerlogo{
    color:#55eaff;
    font-size:21px;
    font-weight:900;
    letter-spacing:4px;
}

.online{
    color:#61ff9b;
    font-size:11px;
    letter-spacing:2px;
}

.layout{
    display:flex;
}

aside{
    width:220px;
    min-height:calc(100vh - 70px);
    background:#03080c;
    border-right:1px solid #173d49;
    padding:18px 12px;
}

aside button{
    width:100%;
    text-align:left;
    margin-bottom:9px;
}

main{
    flex:1;
    padding:25px;
}

.title{
    font-size:29px;
    letter-spacing:4px;
    color:#d4f9ff;
}

.subtitle{
    color:#557680;
    font-size:12px;
    letter-spacing:2px;
    margin:7px 0 24px;
}

.page{display:none}
.page.active{display:block}

/* CARDS */

.grid{
    display:grid;
    grid-template-columns:repeat(4,1fr);
    gap:14px;
}

.card{
    background:linear-gradient(145deg,#08151c,#03090d);
    border:1px solid #174452;
    padding:18px;
}

.card h3{
    color:#577b85;
    font-size:10px;
    letter-spacing:2px;
    margin-bottom:12px;
}

.number{
    color:#5deaff;
    font-size:31px;
    font-weight:bold;
}

.green{color:#62ff9c}
.yellow{color:#ffe36b}
.red{color:#ff6262}

.wide{grid-column:span 2}

/* MAP */

.map{
    height:300px;
    position:relative;
    overflow:hidden;
    background:
      linear-gradient(#16424d 1px,transparent 1px),
      linear-gradient(90deg,#16424d 1px,transparent 1px),
      #061015;
    background-size:35px 35px;
}

.map:after{
    content:"FICTIONAL SATELLITE GRID";
    position:absolute;
    bottom:10px;
    left:12px;
    color:#45636c;
    font-size:9px;
    letter-spacing:2px;
}

.marker{
    position:absolute;
    width:13px;
    height:13px;
    border-radius:50%;
    background:#5deaff;
    box-shadow:0 0 20px #5deaff;
    animation:pulse 1.6s infinite;
}

.m1{left:22%;top:30%}
.m2{left:68%;top:45%}
.m3{left:43%;top:72%}
.m4{left:82%;top:20%}

@keyframes pulse{
    0%,100%{transform:scale(1);opacity:1}
    50%{transform:scale(1.8);opacity:.45}
}

/* TERMINAL */

.terminal{
    background:#010405;
    border:1px solid #174452;
    min-height:330px;
    padding:18px;
    font-family:monospace;
    color:#5deaff;
    overflow:auto;
}

.termline{
    margin:5px 0;
}

.termInput{
    display:flex;
    margin-top:12px;
}

.termInput span{
    padding:14px 5px 14px 0;
    color:#62ff9c;
}

.termInput input{
    margin:0;
    font-family:monospace;
}

/* ALERT */

.alert{
    border:1px solid #7b2525;
    background:#170607;
    padding:15px;
    margin-bottom:14px;
    color:#ff7777;
}

/* DATABASE */

table{
    width:100%;
    border-collapse:collapse;
    margin-top:15px;
}

th,td{
    border-bottom:1px solid #15333d;
    padding:13px;
    text-align:left;
}

th{
    color:#5deaff;
    font-size:10px;
    letter-spacing:2px;
}

td{
    color:#aac8d0;
    font-size:13px;
}

.badge{
    border:1px solid currentColor;
    padding:4px 7px;
    font-size:9px;
}

/* F-SPAR */

.core{
    width:170px;
    height:170px;
    margin:25px auto;
    border:3px solid #5deaff;
    border-radius:50%;
    display:flex;
    align-items:center;
    justify-content:center;
    font-weight:bold;
    color:#5deaff;
    box-shadow:
      0 0 20px #25dfff,
      inset 0 0 30px rgba(40,220,255,.35);
    animation:core 2s infinite;
}

@keyframes core{
    50%{
        box-shadow:
        0 0 55px #25dfff,
        inset 0 0 45px rgba(40,220,255,.55);
    }
}

/* MOBILE */

@media(max-width:850px){
    aside{
        width:100%;
        min-height:auto;
        display:flex;
        overflow-x:auto;
        gap:7px;
    }

    aside button{
        min-width:140px;
    }

    .layout{display:block}

    .grid{
        grid-template-columns:1fr 1fr;
    }

    .wide{grid-column:span 2}
}

@media(max-width:550px){
    .grid{grid-template-columns:1fr}
    .wide{grid-column:span 1}
    header{padding:0 10px}
    .online{display:none}
}
</style>
</head>

<body>

<!-- BOOT -->

<section id="boot">

<div class="bootbox">

<div id="bootText"></div>

<div class="progress">
<div id="bar"></div>
</div>

</div>

</section>


<!-- LOGIN -->

<section id="login">

<div class="loginbox">

<div class="logo">IO</div>

<div class="small">
IMAGINED ORDER // SECURE TERMINAL V2
</div>

<input
id="code"
type="password"
placeholder="ENTER CLEARANCE CODE"
autocomplete="off"
>

<button class="loginbtn" onclick="login()">
AUTHENTICATE
</button>

<div id="error"></div>

</div>

</section>


<!-- APP -->

<section id="app">

<header>

<div class="headerlogo">
IO // COMMAND CENTER
</div>

<div class="online">
● NETWORK ONLINE
</div>

<button onclick="logout()">
LOCK
</button>

</header>


<div class="layout">

<aside>

<button onclick="page('overview')">▣ OVERVIEW</button>
<button onclick="page('database')">▤ DATABASE</button>
<button onclick="page('fspar')">⚡ F-SPAR</button>
<button onclick="page('terminal')">⌘ TERMINAL</button>
<button onclick="page('alerts')">⚠ ALERTS</button>

</aside>


<main>

<!-- OVERVIEW -->

<section id="overview" class="page active">

<div class="title">COMMAND CENTER</div>

<div class="subtitle">
IO NETWORK // CENTRAL OPERATIONS
</div>

<div class="grid">

<div class="card">
<h3>ACTIVE AGENTS</h3>
<div class="number">47</div>
</div>

<div class="card">
<h3>OPERATIONS</h3>
<div class="number">12</div>
</div>

<div class="card">
<h3>NETWORK</h3>
<div class="number green">99.9%</div>
</div>

<div class="card">
<h3>THREAT LEVEL</h3>
<div class="number yellow">LOW</div>
</div>

<div class="card wide">

<h3>SATELLITE GRID</h3>

<div class="map">

<div class="marker m1"></div>
<div class="marker m2"></div>
<div class="marker m3"></div>
<div class="marker m4"></div>

</div>

</div>

<div class="card wide">

<h3>SYSTEM ACTIVITY</h3>

<p class="termline">[19:40] Network synchronization complete.</p>
<p class="termline">[19:38] Satellite grid refreshed.</p>
<p class="termline">[19:35] F-SPAR monitoring active.</p>
<p class="termline">[19:31] Database integrity: 100%.</p>

</div>

</div>

</section>


<!-- DATABASE -->

<section id="database" class="page">

<div class="title">DATABASE</div>

<div class="subtitle">
FICTIONAL PERSONNEL DATABASE
</div>

<input
id="dbSearch"
placeholder="SEARCH DATABASE..."
onkeyup="searchDB()"
>

<table>

<thead>
<tr>
<th>ID</th>
<th>CODENAME</th>
<th>ROLE</th>
<th>STATUS</th>
</tr>
</thead>

<tbody id="db">

<tr>
<td>IO-001</td>
<td>PHANTOM</td>
<td>FIELD AGENT</td>
<td><span class="badge green">ACTIVE</span></td>
</tr>

<tr>
<td>IO-002</td>
<td>VANGUARD</td>
<td>COMMAND</td>
<td><span class="badge green">ACTIVE</span></td>
</tr>

<tr>
<td>IO-003</td>
<td>NOVA</td>
<td>RESEARCH</td>
<td><span class="badge yellow">STANDBY</span></td>
</tr>

<tr>
<td>IO-004</td>
<td>WRAITH</td>
<td>RECON</td>
<td><span class="badge red">OFFLINE</span></td>
</tr>

</tbody>

</table>

</section>


<!-- F-SPAR -->

<section id="fspar" class="page">

<div class="title">PROJECT F-SPAR</div>

<div class="subtitle">
ENERGY SYSTEM // CLASSIFIED PROJECT
</div>

<div class="grid">

<div class="card wide">

<h3>CORE STATUS</h3>

<div class="core">
F-SPAR
</div>

<p style="text-align:center" class="green">
ENERGY CORE: STABLE
</p>

</div>

<div class="card">

<h3>CORE OUTPUT</h3>
<div class="number">87%</div>

</div>

<div class="card">

<h3>CONTAINMENT</h3>
<div class="number green">ONLINE</div>

</div>

<div class="card wide">

<h3>PROJECT NOTES</h3>

<p>
F-SPAR is a fictional experimental energy-system
project used for this interface.
</p>

<br>

<p class="yellow">
CLEARANCE REQUIRED: LEVEL 7
</p>

</div>

</div>

</section>


<!-- TERMINAL -->

<section id="terminal" class="page">

<div class="title">IO TERMINAL</div>

<div class="subtitle">
LOCAL COMMAND INTERFACE
</div>

<div class="terminal" id="terminalBox">

<div class="termline">
IO TERMINAL V2 INITIALIZED.
</div>

<div class="termline">
Type <b>help</b> for available commands.
</div>

<div id="terminalOutput"></div>

<div class="termInput">

<span>IO&gt;</span>

<input
id="command"
autocomplete="off"
placeholder="ENTER COMMAND..."
onkeydown="runCommand(event)"
>

</div>

</div>

</section>


<!-- ALERTS -->

<section id="alerts" class="page">

<div class="title">ALERT CENTER</div>

<div class="subtitle">
SECURITY MONITORING
</div>

<div class="alert">
⚠ TEST ALERT: Unusual energy reading detected in
fictional sector 07.
</div>

<div class="card">

<h3>SECURITY STATUS</h3>

<p class="green">
ALL FICTIONAL SYSTEMS NOMINAL
</p>

<br>

<p>
No real-world systems are connected to this terminal.
</p>

</div>

</section>


<br>

<div style="font-size:10px;color:#3c5962">
IO LOCAL TERMINAL // V2 // <span id="clock"></span>
</div>

</main>

</div>

</section>


<script>

/* BOOT SEQUENCE */

const bootMessages = [
"IO BIOS v2.0 INITIALIZING...",
"Loading command architecture...",
"Checking encrypted database...",
"Initializing satellite grid...",
"Connecting F-SPAR monitoring...",
"Checking security protocols...",
"Network status: ONLINE",
"BOOT COMPLETE."
];

let messageIndex = 0;

function boot(){

    if(messageIndex < bootMessages.length){

        document.getElementById("bootText")
        .textContent +=
        bootMessages[messageIndex] + "\n";

        document.getElementById("bar")
        .style.width =
        ((messageIndex + 1) /
        bootMessages.length * 100) + "%";

        messageIndex++;

        setTimeout(boot,350);

    }else{

        setTimeout(()=>{

            document.getElementById("boot")
            .style.display="none";

            document.getElementById("login")
            .style.display="flex";

        },700);

    }
}

boot();


/* LOGIN */

const ACCESS_CODE="IO-7429-X";

function login(){

    const value =
    document.getElementById("code").value;

    if(value===ACCESS_CODE){

        document.getElementById("login")
        .style.display="none";

        document.getElementById("app")
        .style.display="block";

    }else{

        document.getElementById("error")
        .textContent="ACCESS DENIED // INVALID CLEARANCE";

    }
}

document.getElementById("code")
.addEventListener("keydown",e=>{

    if(e.key==="Enter") login();

});


/* LOCK */

function logout(){

    document.getElementById("app")
    .style.display="none";

    document.getElementById("login")
    .style.display="flex";

    document.getElementById("code")
    .value="";

}


/* NAVIGATION */

function page(name){

    document.querySelectorAll(".page")
    .forEach(p=>p.classList.remove("active"));

    document.getElementById(name)
    .classList.add("active");

}


/* DATABASE SEARCH */

function searchDB(){

    const search =
    document.getElementById("dbSearch")
    .value.toLowerCase();

    document.querySelectorAll("#db tr")
    .forEach(row=>{

        row.style.display =
        row.textContent
        .toLowerCase()
        .includes(search)
        ? ""
        : "none";

    });

}


/* TERMINAL */

function runCommand(event){

    if(event.key!=="Enter") return;

    const input =
    document.getElementById("command");

    const command =
    input.value.trim().toLowerCase();

    const output =
    document.getElementById("terminalOutput");

    let response="";

    if(command==="help"){

        response=
        "COMMANDS: help | status | agents | fspar | clear";

    }else if(command==="status"){

        response=
        "NETWORK: ONLINE // DATABASE: 100% // THREAT: LOW";

    }else if(command==="agents"){

        response=
        "ACTIVE AGENTS: 47 // STANDBY: 12";

    }else if(command==="fspar"){

        response=
        "F-SPAR: ACTIVE // CORE OUTPUT: 87%";

    }else if(command==="clear"){

        output.innerHTML="";
        input.value="";
        return;

    }else if(command===""){

        return;

    }else{

        response=
        "UNKNOWN COMMAND // TYPE 'help'";

    }

    output.innerHTML +=
    `<div class="termline">
    IO&gt; ${command}
    </div>
    <div class="termline">
    ${response}
    </div>`;

    input.value="";

}


/* CLOCK */

function clock(){

    document.getElementById("clock")
    .textContent =
    new Date().toLocaleTimeString();

}

setInterval(clock,1000);
clock();

</script>

</body>
</html>
