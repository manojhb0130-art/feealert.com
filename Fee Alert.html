<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1"/>
  <title>FeeAlert School Portal</title>
  <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
  <style>
    :root{
      --bg:#0b1020; --surface:#0f1730; --card:#0f1a38;
      --text:#e9eefc; --muted:#a9b6df; --brand:#5b8cff; --brand2:#7c4dff;
      --danger:#ff4d6d; --success:#2dd4bf; --warning:#ffd166;
      --border:rgba(255,255,255,.08); --shadow: 0 14px 40px rgba(0,0,0,.35);
      --radius:16px;
    }
    *{box-sizing:border-box}
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Arial;
      background: radial-gradient(1200px 800px at 20% -10%, rgba(91,140,255,.35), transparent 60%),
                  radial-gradient(900px 600px at 110% 10%, rgba(124,77,255,.30), transparent 55%),
                  linear-gradient(180deg, #070a15, #0b1020 40%, #070a15);
      color:var(--text);
      min-height:100vh;
    }
    .app{display:flex; min-height:100vh;}
    .sidebar{
      width:280px; padding:18px; position:sticky; top:0; height:100vh;
      background:linear-gradient(180deg, rgba(15,23,48,.9), rgba(11,16,32,.9));
      border-right:1px solid var(--border);
      backdrop-filter: blur(10px);
    }
    .brand{
      display:flex; gap:10px; align-items:center; padding:14px 12px; border-radius:14px;
      background: linear-gradient(135deg, rgba(91,140,255,.18), rgba(124,77,255,.14));
      border:1px solid var(--border);
      box-shadow: 0 10px 30px rgba(0,0,0,.25);
    }
    .logo{
      width:38px; height:38px; border-radius:12px;
      background: radial-gradient(circle at 30% 30%, rgba(255,255,255,.9), rgba(255,255,255,.2) 35%, transparent 60%),
                  linear-gradient(135deg, var(--brand), var(--brand2));
      box-shadow: 0 10px 30px rgba(91,140,255,.25);
    }
    .brand h2{margin:0; font-size:16px;}
    .brand p{margin:2px 0 0; font-size:12px; color:var(--muted);}

    .nav{margin-top:14px; display:flex; flex-direction:column; gap:8px;}
    .nav button{
      width:100%; text-align:left; padding:12px 12px; border-radius:14px;
      border:1px solid var(--border); background:rgba(255,255,255,.03);
      color:var(--text); cursor:pointer;
      display:flex; gap:10px; align-items:center;
    }
    .nav button.active{background:linear-gradient(135deg, rgba(91,140,255,.20), rgba(124,77,255,.16));}
    .nav small{color:var(--muted); display:block; margin-top:6px; line-height:1.4;}

    .content{flex:1; padding:22px;}
    .topbar{
      display:flex; align-items:center; justify-content:space-between; gap:12px;
      padding:14px 16px; border-radius:var(--radius);
      background:rgba(15,23,48,.65); border:1px solid var(--border);
      backdrop-filter: blur(10px);
      box-shadow: var(--shadow);
    }
    .topbar .title{display:flex; flex-direction:column}
    .topbar .title h1{margin:0; font-size:18px;}
    .topbar .title span{font-size:12px; color:var(--muted);}
    .rightbar{display:flex; align-items:center; gap:10px; flex-wrap:wrap;}
    .pill{
      display:inline-flex; align-items:center; gap:8px;
      padding:10px 12px; border-radius:999px;
      border:1px solid var(--border);
      background:rgba(255,255,255,.03);
      color:var(--muted);
      font-size:12px;
    }
    .btnTop{
      padding:10px 12px; border-radius:999px;
      border:1px solid var(--border);
      background:rgba(255,255,255,.04);
      color:var(--text);
      cursor:pointer;
      font-weight:700;
    }
    .btnTop:hover{background:rgba(255,255,255,.06);}
    .grid{margin-top:16px; display:grid; grid-template-columns: 1.1fr .9fr; gap:14px;}
    @media (max-width: 980px){
      .sidebar{display:none}
      .grid{grid-template-columns:1fr}
      .content{padding:16px}
    }
    .card{
      background: rgba(15,26,56,.65);
      border:1px solid var(--border);
      border-radius: var(--radius);
      padding:16px;
      box-shadow: var(--shadow);
      backdrop-filter: blur(10px);
    }
    .card h3{margin:0 0 10px; font-size:14px;}
    .muted{color:var(--muted); font-size:12px;}
    .stats{display:grid; grid-template-columns: repeat(3, 1fr); gap:10px; margin-top:12px;}
    .stat{padding:12px; border-radius:14px; border:1px solid var(--border); background:rgba(255,255,255,.03);}
    .stat .k{font-size:12px; color:var(--muted);}
    .stat .v{font-size:18px; margin-top:6px; font-weight:700;}
    .stat .v small{font-size:12px; color:var(--muted); font-weight:500;}
    .form{
      display:grid;
      grid-template-columns: repeat(4, 1fr);
      gap:10px;
      margin-top:10px;
    }
    .form input{
      width:100%;
      padding:11px 12px;
      border-radius:14px;
      border:1px solid var(--border);
      background:rgba(8,12,25,.55);
      color:var(--text);
      outline:none;
    }
    .form input::placeholder{color:rgba(169,182,223,.65)}
    .btnrow{display:flex; gap:10px; margin-top:10px; flex-wrap:wrap;}
    .btn{
      padding:11px 14px;
      border-radius:14px;
      border:1px solid var(--border);
      background:linear-gradient(135deg, rgba(91,140,255,.9), rgba(124,77,255,.85));
      color:white;
      cursor:pointer;
      font-weight:700;
    }
    .btn.secondary{background:rgba(255,255,255,.05); color:var(--text);}
    .btn.danger{background:rgba(255,77,109,.15); color:#ffd7df; border-color:rgba(255,77,109,.35);}
    .btn.success{background:rgba(45,212,191,.12); color:#d9fffa; border-color:rgba(45,212,191,.35);}
    .btn:active{transform: translateY(1px);}
    table{width:100%; border-collapse:separate; border-spacing:0 10px; margin-top:10px;}
    thead th{text-align:left; font-size:12px; color:var(--muted); padding:0 10px 6px;}
    tbody tr{background: rgba(255,255,255,.03); border:1px solid var(--border);}
    tbody td{padding:12px 10px; border-top:1px solid var(--border); border-bottom:1px solid var(--border); font-size:13px;}
    tbody tr td:first-child{border-left:1px solid var(--border); border-radius:14px 0 0 14px;}
    tbody tr td:last-child{border-right:1px solid var(--border); border-radius:0 14px 14px 0;}
    .tag{
      display:inline-flex; align-items:center; gap:6px;
      padding:6px 10px; border-radius:999px; font-size:12px;
      border:1px solid var(--border);
      background:rgba(255,255,255,.04);
      color:var(--muted);
      white-space:nowrap;
    }
    .tag.warn{color:#fff1cc; border-color:rgba(255,209,102,.35); background:rgba(255,209,102,.12);}
    .tag.ok{color:#d9fffa; border-color:rgba(45,212,191,.35); background:rgba(45,212,191,.10);}

    .toasts{position:fixed; right:16px; bottom:16px; display:flex; flex-direction:column; gap:10px; z-index:9999; max-width: 360px;}
    .toast{
      background: rgba(8,12,25,.92);
      border:1px solid var(--border);
      border-radius: 16px;
      box-shadow: var(--shadow);
      padding:12px 12px 10px;
      backdrop-filter: blur(10px);
      animation: pop .18s ease-out;
    }
    @keyframes pop{from{transform:translateY(8px); opacity:.7} to{transform:translateY(0); opacity:1}}
    .toast .hdr{display:flex; justify-content:space-between; gap:10px; align-items:center; margin-bottom:6px;}
    .toast .hdr b{font-size:12px;}
    .toast .hdr span{font-size:11px; color:var(--muted);}
    .toast .msg{font-size:13px; line-height:1.35; color:var(--text); white-space:pre-wrap;}
    .toast .actions{margin-top:8px; display:flex; gap:8px; flex-wrap:wrap;}
    .mini{
      padding:7px 10px; border-radius:999px; border:1px solid var(--border);
      background:rgba(255,255,255,.04); color:var(--text); cursor:pointer; font-size:12px;
    }
    .mini.primary{background:rgba(91,140,255,.18); border-color:rgba(91,140,255,.35);}

    .modalback{position:fixed; inset:0; background:rgba(0,0,0,.55); display:none; align-items:center; justify-content:center; z-index:9998;}
    .modal{
      width:min(560px, calc(100% - 24px));
      background: rgba(15,26,56,.92);
      border:1px solid var(--border);
      border-radius: 18px;
      box-shadow: var(--shadow);
      padding:16px;
      backdrop-filter: blur(12px);
    }
    .modal h3{margin:0 0 6px; font-size:15px}
    .modal .row{display:grid; grid-template-columns:1fr 1fr; gap:10px; margin-top:10px;}
    .modal input, .modal textarea{
      width:100%;
      padding:11px 12px;
      border-radius:14px;
      border:1px solid var(--border);
      background:rgba(8,12,25,.55);
      color:var(--text);
      outline:none;
      font-family:inherit;
    }
    .modal textarea{min-height:90px; resize:vertical}
    .modal .btnrow{justify-content:flex-end}
    .hint{font-size:12px; color:var(--muted); margin-top:8px; line-height:1.45}
  </style>
</head>

<body>
<div class="app">
  <aside class="sidebar">
    <div class="brand">
      <div class="logo"></div>
      <div>
        <h2>FeeAlert School Portal</h2>
        <p>Admin + Student access</p>
      </div>
    </div>

    <div class="nav">
      <button class="active" onclick="showView('dashboard')">🏫 Dashboard</button>
      <button onclick="showView('students')">👨‍🎓 Students</button>
      <button onclick="showView('notifications')">💬 Notifications</button>
      <button onclick="showView('settings')">⚙️ Settings</button>
      <small>
        Email sending note: pure HTML apps cannot send email automatically. This portal opens a Gmail compose window with prefilled details — you click <b>Send</b>.
      </small>
    </div>
  </aside>

  <main class="content">
    <div class="topbar">
      <div class="title">
        <h1 id="pageTitle">Dashboard</h1>
        <span id="pageSub">School Management • Fee Tracking & Alerts</span>
      </div>
      <div class="rightbar">
        <div class="pill" id="loginStatus">🔒 Locked</div>
        <button class="btnTop" id="logoutBtn" onclick="logout()" style="display:none;">Logout</button>
      </div>
    </div>

    <!-- AUTH VIEW -->
    <section class="card" id="view-auth" style="margin-top:16px;">
      <h3>Portal Access</h3>
      <div class="muted">Choose Admin login or Student login.</div>

      <div class="btnrow">
        <button class="btn secondary" onclick="switchAuth('admin')">Admin Login</button>
        <button class="btn secondary" onclick="switchAuth('student')">Student Login</button>
      </div>

      <!-- Admin -->
      <div id="adminAuth" style="margin-top:12px;">
        <div class="muted">Admin login</div>
        <div class="form" style="grid-template-columns: 1fr 1fr;">
          <input id="loginPass" type="password" placeholder="Admin password" />
          <button class="btn" onclick="loginAdmin()">Login</button>
        </div>
        <div class="btnrow" id="firstSetupRow" style="display:none;">
          <button class="btn" onclick="openFirstSetupModal()">First time setup: Create Admin Password</button>
        </div>
      </div>

      <!-- Student -->
      <div id="studentAuth" style="margin-top:12px; display:none;">
        <div class="muted">Student login (ask admin for your Student PIN)</div>
        <div class="form" style="grid-template-columns: 1fr 1fr 1fr;">
          <input id="studentRoll" placeholder="Roll / USN" />
          <input id="studentPin" type="password" placeholder="Student PIN" />
          <button class="btn" onclick="loginStudent()">Login</button>
        </div>
      </div>

      <div class="hint">
        Student PIN is set by Admin while adding/editing student. (Example PIN: 1234)
      </div>
    </section>

    <!-- DASHBOARD VIEW -->
    <section class="grid" id="view-dashboard" style="display:none;">
      <div class="card">
        <h3>Quick Stats</h3>
        <div class="muted">Overview of fees and pending amounts.</div>
        <div class="stats">
          <div class="stat"><div class="k">Total Students</div><div class="v" id="statStudents">0</div></div>
          <div class="stat"><div class="k">Total Fees</div><div class="v" id="statTotal">₹0 <small>sum</small></div></div>
          <div class="stat"><div class="k">Collected</div><div class="v" id="statPaid">₹0 <small>paid</small></div></div>
        </div>
        <div class="stats" style="grid-template-columns:repeat(2,1fr); margin-top:10px;">
          <div class="stat"><div class="k">Pending</div><div class="v" id="statDue">₹0 <small>due</small></div></div>
          <div class="stat"><div class="k">Due Soon (≤ 3 days)</div><div class="v" id="statDueSoon">0 <small>students</small></div></div>
        </div>
        <div class="btnrow" style="margin-top:12px;">
          <button class="btn" onclick="showView('students')">Manage Students</button>
          <button class="btn secondary" onclick="showView('notifications')">Notification Center</button>
        </div>
      </div>

      <div class="card">
        <h3>Fee Analytics</h3>
        <div class="muted">Total vs Collected</div>
        <canvas id="feeChart" style="margin-top:12px;"></canvas>
        <div class="hint">Chart updates automatically.</div>
      </div>
    </section>

    <!-- STUDENTS VIEW -->
    <section class="card" id="view-students" style="display:none; margin-top:16px;">
      <h3>Student Management</h3>
      <div class="muted">Add, edit, delete students. Send alerts (single & bulk).</div>

      <div class="form">
        <input id="roll" placeholder="Roll / USN" />
        <input id="name" placeholder="Student name" />
        <input id="email" placeholder="Email (gmail)" />
        <input id="pin" placeholder="Student PIN (e.g., 1234)" />
        <input id="total" type="number" placeholder="Total fee (₹)" />
        <input id="paid" type="number" placeholder="Paid fee (₹)" />
        <input id="duedate" type="date" />
        <div></div>
      </div>
      <div class="btnrow">
        <button class="btn" onclick="addStudent()">Add Student</button>
        <button class="btn secondary" onclick="exportCSV()">Export CSV</button>
        <button class="btn success" onclick="bulkDueSoon()">Auto-send alerts for Due Soon</button>
      </div>

      <table>
        <thead>
          <tr>
            <th style="width:120px;">Roll</th>
            <th>Name</th>
            <th style="width:180px;">Email</th>
            <th style="width:90px;">PIN</th>
            <th style="width:110px;">Total</th>
            <th style="width:110px;">Paid</th>
            <th style="width:110px;">Due</th>
            <th style="width:150px;">Status</th>
            <th style="width:320px;">Actions</th>
          </tr>
        </thead>
        <tbody id="studentRows"></tbody>
      </table>

      <div class="hint">
        About email: This app opens a Gmail compose window. You must click <b>Send</b> inside Gmail.
      </div>
    </section>

    <!-- STUDENT PORTAL VIEW -->
    <section class="card" id="view-student" style="display:none; margin-top:16px;">
      <h3>Student Portal</h3>
      <div class="muted">Only your fee details are visible here.</div>

      <div class="stats" style="grid-template-columns:repeat(4,1fr); margin-top:12px;">
        <div class="stat"><div class="k">Name</div><div class="v" id="spName">-</div></div>
        <div class="stat"><div class="k">Roll</div><div class="v" id="spRoll">-</div></div>
        <div class="stat"><div class="k">Due Date</div><div class="v" id="spDueDate">-</div></div>
        <div class="stat"><div class="k">Status</div><div class="v" id="spStatus">-</div></div>
      </div>

      <div class="stats" style="grid-template-columns:repeat(3,1fr); margin-top:10px;">
        <div class="stat"><div class="k">Total Fee</div><div class="v" id="spTotal">₹0</div></div>
        <div class="stat"><div class="k">Paid</div><div class="v" id="spPaid">₹0</div></div>
        <div class="stat"><div class="k">Pending</div><div class="v" id="spPending">₹0</div></div>
      </div>

      <div class="btnrow" style="margin-top:12px;">
        <button class="btn secondary" onclick="studentLogout()">Student Logout</button>
      </div>
    </section>

    <!-- NOTIFICATIONS VIEW -->
    <section class="card" id="view-notifications" style="display:none; margin-top:16px;">
      <h3>Notification Center</h3>
      <div class="muted">All alerts (email / SMS-style) are logged here.</div>
      <div class="btnrow">
        <button class="btn secondary" onclick="clearNotifications()">Clear Notifications</button>
      </div>
      <div id="notifList" style="margin-top:10px;"></div>
    </section>

    <!-- SETTINGS VIEW -->
    <section class="card" id="view-settings" style="display:none; margin-top:16px;">
      <h3>Settings</h3>
      <div class="muted">Change admin password and manage saved data.</div>
      <div class="btnrow">
        <button class="btn" onclick="openChangePasswordModal()">Change Admin Password</button>
        <button class="btn danger" onclick="clearAllData()">Clear All Data (Password + Students)</button>
      </div>
      <div class="hint">Clearing all data removes: students, notifications, admin password.</div>
    </section>
  </main>
</div>

<!-- TOASTS -->
<div class="toasts" id="toasts"></div>

<!-- MODAL BACKDROP -->
<div class="modalback" id="modalBack" onclick="closeModal(event)">
  <div class="modal" id="modal" onclick="event.stopPropagation()"></div>
</div>

<script>
/* Storage keys */
const KEY_STUDENTS = "feealert_students_v3";
const KEY_PASSWORD = "feealert_admin_password_v3";
const KEY_NOTIFS   = "feealert_notifications_v3";
const KEY_ADMIN_LOCKED = "feealert_admin_locked_v3";
const KEY_STUDENT_SESSION = "feealert_student_session_v3";

/* State */
let students = JSON.parse(localStorage.getItem(KEY_STUDENTS) || "[]");
let notifications = JSON.parse(localStorage.getItem(KEY_NOTIFS) || "[]");
let adminPassword = localStorage.getItem(KEY_PASSWORD) || "";
let adminLoggedIn = (localStorage.getItem(KEY_ADMIN_LOCKED) === "false");
let studentSession = JSON.parse(localStorage.getItem(KEY_STUDENT_SESSION) || "null"); // {roll}
let chart = null;

/* Helpers */
function formatINR(n){ try{ return "₹" + (Number(n)||0).toLocaleString("en-IN"); }catch(e){ return "₹" + (Number(n)||0); } }
function daysUntil(dateStr){
  const today = new Date(); today.setHours(0,0,0,0);
  const d = new Date(dateStr); d.setHours(0,0,0,0);
  return Math.round((d - today)/(1000*60*60*24));
}
function escapeHtml(str){
  return String(str||"").replaceAll("&","&amp;").replaceAll("<","&lt;").replaceAll(">","&gt;")
    .replaceAll('"',"&quot;").replaceAll("'","&#039;");
}
function saveAll(){
  localStorage.setItem(KEY_STUDENTS, JSON.stringify(students));
  localStorage.setItem(KEY_NOTIFS, JSON.stringify(notifications));
}

/* Top status */
function setLoginStatus(){
  const pill = document.getElementById("loginStatus");
  const logoutBtn = document.getElementById("logoutBtn");

  if(adminLoggedIn){
    pill.textContent = "✅ Admin Logged In";
    pill.style.borderColor = "rgba(45,212,191,.35)";
    pill.style.color = "var(--success)";
    logoutBtn.style.display = "";
  }else if(studentSession){
    pill.textContent = "🎓 Student Session";
    pill.style.borderColor = "rgba(91,140,255,.35)";
    pill.style.color = "var(--brand)";
    logoutBtn.style.display = "none";
  }else{
    pill.textContent = "🔒 Locked";
    pill.style.borderColor = "rgba(255,255,255,.08)";
    pill.style.color = "var(--muted)";
    logoutBtn.style.display = "none";
  }
}

/* Auth switch */
function switchAuth(mode){
  document.getElementById("adminAuth").style.display = mode==="admin" ? "" : "none";
  document.getElementById("studentAuth").style.display = mode==="student" ? "" : "none";
}

/* Views */
function hideAllViews(){
  ["auth","dashboard","students","student","notifications","settings"].forEach(v=>{
    document.getElementById("view-"+v).style.display="none";
  });
}
function showView(name){
  // Access rules:
  if(studentSession){
    name = "student";
  }else if(!adminLoggedIn){
    name = "auth";
  }
  hideAllViews();
  document.getElementById("view-"+name).style.display = "";

  const titleMap = {auth:"Portal Access", dashboard:"Dashboard", students:"Students", student:"Student Portal", notifications:"Notifications", settings:"Settings"};
  document.getElementById("pageTitle").innerText = titleMap[name] || "Dashboard";
  document.getElementById("pageSub").innerText = (name==="auth")
    ? "Choose Admin or Student login"
    : "School Management • Fee Tracking & Alerts";

  // sidebar active
  const sidebarButtons = document.querySelectorAll(".nav button");
  sidebarButtons.forEach(btn=>btn.classList.remove("active"));
  const idx = {dashboard:0, students:1, notifications:2, settings:3}[name];
  if(idx !== undefined && sidebarButtons[idx]) sidebarButtons[idx].classList.add("active");

  refreshUI();
}

/* Admin login / setup */
function openFirstSetupModal(){
  openModal(`
    <h3>Create Admin Password</h3>
    <div class="muted">First time setup (required before admin login).</div>
    <div class="row">
      <input id="sp1" type="password" placeholder="New password"/>
      <input id="sp2" type="password" placeholder="Confirm password"/>
    </div>
    <div class="btnrow">
      <button class="btn secondary" onclick="closeModal()">Cancel</button>
      <button class="btn" onclick="setPassword()">Save Password</button>
    </div>
    <div class="hint">Password is stored only in this browser (localStorage).</div>
  `);
}
function setPassword(){
  const p1 = (document.getElementById("sp1").value||"").trim();
  const p2 = (document.getElementById("sp2").value||"").trim();
  if(p1.length < 4){ toast("Password too short","Use at least 4 characters.",[]); return; }
  if(p1 !== p2){ toast("Passwords do not match","Re-check and try again.",[]); return; }
  adminPassword = p1;
  localStorage.setItem(KEY_PASSWORD, adminPassword);
  toast("Password Saved","Now login as admin.",[]);
  closeModal();
  refreshUI();
}
function loginAdmin(){
  const pass = (document.getElementById("loginPass").value||"");
  if(!adminPassword){
    toast("Admin password not set","Click First time setup to create one.",[{text:"Create Password", action:openFirstSetupModal, primary:true}]);
    return;
  }
  if(pass === adminPassword){
    adminLoggedIn = true;
    localStorage.setItem(KEY_ADMIN_LOCKED, "false");
    document.getElementById("loginPass").value = "";
    toast("Login Successful","Welcome Admin. Portal unlocked.",[{text:"Open Dashboard", action:()=>showView("dashboard"), primary:true}]);
    showView("dashboard");
  }else{
    toast("Wrong Password","Please try again.",[]);
  }
}
function logout(){
  adminLoggedIn = false;
  localStorage.setItem(KEY_ADMIN_LOCKED, "true");
  toast("Logged Out","Admin session ended.",[]);
  showView("auth");
}

/* Student login */
function loginStudent(){
  const roll = (document.getElementById("studentRoll").value||"").trim();
  const pin = (document.getElementById("studentPin").value||"").trim();
  const s = students.find(x => x.roll === roll);
  if(!s){ toast("Not found","Roll number not found. Ask admin.",[]); return; }
  if((s.pin||"") !== pin){ toast("Wrong PIN","Check your Student PIN.",[]); return; }
  studentSession = {roll};
  localStorage.setItem(KEY_STUDENT_SESSION, JSON.stringify(studentSession));
  toast("Student Login","Welcome!",[{text:"Open Portal", action:()=>showView("student"), primary:true}]);
  showView("student");
}
function studentLogout(){
  studentSession = null;
  localStorage.removeItem(KEY_STUDENT_SESSION);
  toast("Logged Out","Student session ended.",[]);
  showView("auth");
}

/* Change password (after login only) */
function openChangePasswordModal(){
  if(!adminLoggedIn){
    toast("Admin login required","Login first to change password.",[]);
    return;
  }
  openModal(`
    <h3>Change Admin Password</h3>
    <div class="muted">Enter old password, then set the new one.</div>
    <div class="row">
      <input id="oldp" type="password" placeholder="Old password"/>
      <input id="newp" type="password" placeholder="New password"/>
    </div>
    <div class="row">
      <input id="newp2" type="password" placeholder="Confirm new password"/>
      <div></div>
    </div>
    <div class="btnrow">
      <button class="btn secondary" onclick="closeModal()">Cancel</button>
      <button class="btn" onclick="changePassword()">Update</button>
    </div>
  `);
}
function changePassword(){
  const oldp = (document.getElementById("oldp").value||"").trim();
  const newp = (document.getElementById("newp").value||"").trim();
  const newp2 = (document.getElementById("newp2").value||"").trim();
  if(oldp !== adminPassword){ toast("Old password incorrect","Try again.",[]); return; }
  if(newp.length < 4){ toast("New password too short","Use at least 4 characters.",[]); return; }
  if(newp !== newp2){ toast("Mismatch","New passwords do not match.",[]); return; }
  adminPassword = newp;
  localStorage.setItem(KEY_PASSWORD, adminPassword);
  toast("Password Updated","Admin password changed successfully.",[]);
  closeModal();
}

/* Students CRUD */
function addStudent(){
  if(!adminLoggedIn){ toast("Admin login required","Login as admin.",[]); return; }

  const roll = (document.getElementById("roll").value||"").trim();
  const name = (document.getElementById("name").value||"").trim();
  const email = (document.getElementById("email").value||"").trim();
  const pin = (document.getElementById("pin").value||"").trim();
  const total = Number(document.getElementById("total").value||0);
  const paid = Number(document.getElementById("paid").value||0);
  const duedate = document.getElementById("duedate").value;

  if(!roll || !name || !email || !pin || !total || !duedate){
    toast("Missing fields","Fill Roll, Name, Email, PIN, Total Fee and Due Date.",[]);
    return;
  }
  if(paid < 0 || total < 0 || paid > total){
    toast("Invalid amounts","Paid should be between 0 and Total fee.",[]);
    return;
  }
  if(students.some(s=>s.roll===roll)){
    toast("Duplicate roll","This roll number already exists. Use Edit.",[]);
    return;
  }

  students.push({roll, name, email, pin, total, paid, duedate, createdAt: new Date().toISOString()});
  saveAll();
  toast("Student Added",`${name} added.`,[]);
  clearStudentForm();
  refreshUI();
}
function clearStudentForm(){
  ["roll","name","email","pin","total","paid","duedate"].forEach(id=>document.getElementById(id).value="");
}
function deleteStudent(index){
  if(!adminLoggedIn) return;
  const s = students[index];
  if(!confirm(`Delete ${s.name} (${s.roll})?`)) return;
  students.splice(index,1);
  saveAll();
  toast("Deleted","Student record removed.",[]);
  refreshUI();
}
function openEditStudentModal(index){
  if(!adminLoggedIn) return;
  const s = students[index];
  openModal(`
    <h3>Edit Student</h3>
    <div class="muted">Update details and save.</div>
    <div class="row">
      <input id="e_roll" value="${escapeHtml(s.roll)}" disabled />
      <input id="e_name" value="${escapeHtml(s.name)}" />
    </div>
    <div class="row">
      <input id="e_email" value="${escapeHtml(s.email)}" />
      <input id="e_pin" value="${escapeHtml(s.pin||"")}" />
    </div>
    <div class="row">
      <input id="e_total" type="number" value="${Number(s.total)||0}" />
      <input id="e_paid" type="number" value="${Number(s.paid)||0}" />
    </div>
    <div class="row">
      <input id="e_duedate" type="date" value="${escapeHtml(s.duedate)}" />
      <div></div>
    </div>
    <div class="btnrow">
      <button class="btn secondary" onclick="closeModal()">Cancel</button>
      <button class="btn" onclick="saveEdit(${index})">Save Changes</button>
    </div>
  `);
}
function saveEdit(index){
  const s = students[index];
  const name = (document.getElementById("e_name").value||"").trim();
  const email = (document.getElementById("e_email").value||"").trim();
  const pin = (document.getElementById("e_pin").value||"").trim();
  const total = Number(document.getElementById("e_total").value||0);
  const paid  = Number(document.getElementById("e_paid").value||0);
  const duedate = document.getElementById("e_duedate").value;

  if(!name || !email || !pin || !total || !duedate){
    toast("Missing fields","Name, Email, PIN, Total Fee and Due Date are required.",[]);
    return;
  }
  if(paid < 0 || total < 0 || paid > total){
    toast("Invalid amounts","Paid should be between 0 and Total fee.",[]);
    return;
  }
  s.name=name; s.email=email; s.pin=pin; s.total=total; s.paid=paid; s.duedate=duedate;
  saveAll();
  toast("Saved","Student updated.",[]);
  closeModal();
  refreshUI();
}

/* Alerts (Gmail compose) */
function gmailComposeUrl(to, subject, body){
  // Opens Gmail web compose (works even without mail client setup)
  const base = "https://mail.google.com/mail/?view=cm&fs=1";
  return `${base}&to=${encodeURIComponent(to)}&su=${encodeURIComponent(subject)}&body=${encodeURIComponent(body)}`;
}
function addNotification(n){
  notifications.unshift(n);
  notifications = notifications.slice(0, 200);
  localStorage.setItem(KEY_NOTIFS, JSON.stringify(notifications));
  toast(`${n.type} prepared`, `${n.student}\n${n.message}`, []);
}
function openNotifyModal(index){
  if(!adminLoggedIn) return;
  const s = students[index];
  const due = Math.max(0, (Number(s.total)||0) - (Number(s.paid)||0));
  const suggested = `Hi ${s.name}, your pending fee is ${formatINR(due)}. Due date: ${s.duedate}. Please pay before deadline to avoid penalty. -FeeAlert`;
  const smsLike = `FEE ALERT: Pending ${formatINR(due)} | Due: ${s.duedate} | ${s.name} (${s.roll}).`;

  openModal(`
    <h3>Send Alert</h3>
    <div class="muted">This will open Gmail compose. You must click <b>Send</b> inside Gmail.</div>
    <div class="row">
      <input value="${escapeHtml(s.email)}" id="toEmail" />
      <input value="${escapeHtml(s.name)}" id="toName" />
    </div>
    <textarea id="msgBox">${escapeHtml(suggested)}</textarea>
    <div class="btnrow">
      <button class="btn secondary" onclick="closeModal()">Cancel</button>
      <button class="btn success" onclick="sendGmail(${index}, false)">Open Gmail (Email)</button>
      <button class="btn" onclick="sendGmail(${index}, true)">Open Gmail (SMS-style)</button>
    </div>
    <div class="hint">Tip: SMS-style is short format (sent via email for demo).</div>
  `);
}
function sendGmail(index, smsStyle){
  const s = students[index];
  const to = (document.getElementById("toEmail").value||s.email||"").trim();
  const msg = (document.getElementById("msgBox").value||"").trim();
  if(!to || !to.includes("@")){ toast("Invalid email","Enter a valid email.",[]); return; }

  const subject = smsStyle ? "FEE ALERT (SMS-style)" : "Fee Reminder";
  const body = smsStyle ? msg.replace(/\n/g," ") : msg;

  addNotification({
    type: smsStyle ? "SMS-style" : "Email",
    to, student: `${s.name} (${s.roll})`,
    message: body,
    time: new Date().toISOString()
  });

  const url = gmailComposeUrl(to, subject, body);
  window.open(url, "_blank");
  closeModal();
}

/* Bulk due soon */
function bulkDueSoon(){
  if(!adminLoggedIn) return;
  const dueSoon = students
    .map((s,i)=>({s,i,due:Math.max(0,(Number(s.total)||0)-(Number(s.paid)||0)), days:daysUntil(s.duedate)}))
    .filter(x=>x.due>0 && x.days<=3);

  if(dueSoon.length===0){
    toast("No Due Soon", "No students are due within 3 days.", []);
    return;
  }

  const list = dueSoon.map(x => `<div class="tag warn" style="margin:6px 6px 0 0;">${escapeHtml(x.s.name)} • ${escapeHtml(x.s.roll)} • Due in ${x.days}d</div>`).join("");
  openModal(`
    <h3>Bulk Alerts: Due Soon</h3>
    <div class="muted">We will open Gmail compose tabs one-by-one (browser may block too many tabs). Best: click "Open Next" repeatedly.</div>
    <div style="margin-top:10px;">${list}</div>
    <div class="btnrow">
      <button class="btn secondary" onclick="closeModal()">Close</button>
      <button class="btn success" onclick="startBulk(${dueSoon.map(x=>x.i).join(",")})">Open Next</button>
    </div>
    <div class="hint">Each click opens 1 Gmail compose window. You click Send inside Gmail.</div>
  `);
  // store list for step-wise opening
  window.__bulkQueue = dueSoon.map(x=>x.i);
}
function startBulk(){
  if(!window.__bulkQueue || window.__bulkQueue.length===0){
    toast("Done","No more students in bulk queue.",[]);
    return;
  }
  const idx = window.__bulkQueue.shift();
  const s = students[idx];
  const due = Math.max(0,(Number(s.total)||0)-(Number(s.paid)||0));
  const msg = `FEE ALERT: Pending ${formatINR(due)} | Due: ${s.duedate} | ${s.name} (${s.roll}).`;
  addNotification({type:"Bulk SMS-style", to:s.email, student:`${s.name} (${s.roll})`, message:msg, time:new Date().toISOString()});
  window.open(gmailComposeUrl(s.email, "FEE ALERT (Bulk)", msg), "_blank");
  toast("Opened Gmail compose", `Next: ${s.name} (${s.roll})`, []);
}

/* Notifications view */
function renderNotifications(){
  const box = document.getElementById("notifList");
  if(!box) return;
  if(notifications.length === 0){
    box.innerHTML = `<div class="muted">No notifications yet. Send one from Students page.</div>`;
    return;
  }
  box.innerHTML = notifications.map(n=>{
    const t = new Date(n.time);
    const timeStr = t.toLocaleString();
    const cls = (n.type||"").toLowerCase().includes("sms") ? "warn" : "ok";
    return `
      <div class="card" style="margin-bottom:10px; background:rgba(255,255,255,.03); box-shadow:none;">
        <div style="display:flex; justify-content:space-between; gap:10px; align-items:flex-start;">
          <div>
            <div class="tag ${cls}">${escapeHtml(n.type)}</div>
            <div style="margin-top:8px; font-weight:700;">${escapeHtml(n.student)}</div>
            <div class="muted" style="margin-top:4px;">To: ${escapeHtml(n.to)}</div>
          </div>
          <div class="muted">${escapeHtml(timeStr)}</div>
        </div>
        <div style="margin-top:10px; white-space:pre-wrap; line-height:1.35;">${escapeHtml(n.message)}</div>
      </div>
    `;
  }).join("");
}
function clearNotifications(){
  if(!confirm("Clear notification history?")) return;
  notifications = [];
  localStorage.setItem(KEY_NOTIFS, "[]");
  toast("Cleared","Notification history removed.",[]);
  refreshUI();
}

/* CSV export */
function exportCSV(){
  if(students.length === 0){ toast("No data","Add students first.",[]); return; }
  const header = ["Roll","Name","Email","PIN","Total","Paid","DueDate"];
  const rows = students.map(s=>[s.roll,s.name,s.email,s.pin,s.total,s.paid,s.duedate]);
  const csv = [header, ...rows].map(r=>r.map(v=>String(v).replace(/"/g,'""')).map(v=>`"${v}"`).join(",")).join("\n");
  const blob = new Blob([csv], {type:"text/csv;charset=utf-8;"});
  const url = URL.createObjectURL(blob);
  const a = document.createElement("a"); a.href=url; a.download="feealert_students.csv";
  document.body.appendChild(a); a.click(); a.remove(); URL.revokeObjectURL(url);
  toast("Exported","CSV downloaded.",[]);
}

/* Clear all data */
function clearAllData(){
  if(!confirm("This will delete password + students + notifications. Continue?")) return;
  localStorage.removeItem(KEY_STUDENTS);
  localStorage.removeItem(KEY_NOTIFS);
  localStorage.removeItem(KEY_PASSWORD);
  localStorage.setItem(KEY_ADMIN_LOCKED, "true");
  localStorage.removeItem(KEY_STUDENT_SESSION);
  students=[]; notifications=[]; adminPassword=""; adminLoggedIn=false; studentSession=null;
  toast("All data cleared","Portal locked. Setup password again.",[]);
  showView("auth");
}

/* Render UI */
function refreshUI(){
  setLoginStatus();

  // First time setup button
  document.getElementById("firstSetupRow").style.display = adminPassword ? "none" : "";

  // Student rows
  const body = document.getElementById("studentRows");
  if(body){
    body.innerHTML = students.map((s,i)=>{
      const due = Math.max(0,(Number(s.total)||0)-(Number(s.paid)||0));
      const dleft = daysUntil(s.duedate);
      const statusTag = (due===0) ? `<span class="tag ok">Paid</span>` : (dleft<=3 ? `<span class="tag warn">Due Soon</span>` : `<span class="tag">Pending</span>`);
      return `
        <tr>
          <td>${escapeHtml(s.roll)}</td>
          <td>${escapeHtml(s.name)}</td>
          <td>${escapeHtml(s.email)}</td>
          <td>${escapeHtml(s.pin||"")}</td>
          <td>${formatINR(s.total)}</td>
          <td>${formatINR(s.paid)}</td>
          <td>${formatINR(due)}</td>
          <td>${statusTag}</td>
          <td style="display:flex; gap:8px; align-items:center; flex-wrap:wrap;">
            <button class="mini primary" onclick="openNotifyModal(${i})">Send Alert</button>
            <button class="mini" onclick="openEditStudentModal(${i})">Edit</button>
            <button class="mini" onclick="deleteStudent(${i})" style="border-color:rgba(255,77,109,.35); background:rgba(255,77,109,.12);">Delete</button>
          </td>
        </tr>
      `;
    }).join("");
  }

  // Dashboard stats
  const totalStudents = students.length;
  const totalFees = students.reduce((sum,s)=>sum+(Number(s.total)||0),0);
  const totalPaid = students.reduce((sum,s)=>sum+(Number(s.paid)||0),0);
  const totalDue = Math.max(0, totalFees-totalPaid);
  const dueSoon = students.filter(s=>{
    const due = Math.max(0,(Number(s.total)||0)-(Number(s.paid)||0));
    return due>0 && daysUntil(s.duedate)<=3;
  }).length;

  setText("statStudents", totalStudents);
  setText("statTotal", `${formatINR(totalFees)} <small>sum</small>`, true);
  setText("statPaid", `${formatINR(totalPaid)} <small>paid</small>`, true);
  setText("statDue", `${formatINR(totalDue)} <small>due</small>`, true);
  setText("statDueSoon", `${dueSoon} <small>students</small>`, true);

  renderChart(totalFees, totalPaid);
  renderNotifications();

  // Student portal details
  if(studentSession){
    const s = students.find(x=>x.roll===studentSession.roll);
    if(s){
      const due = Math.max(0,(Number(s.total)||0)-(Number(s.paid)||0));
      const status = (due===0) ? "Paid ✅" : (daysUntil(s.duedate)<=3 ? "Due Soon ⚠️" : "Pending");
      setText("spName", s.name);
      setText("spRoll", s.roll);
      setText("spDueDate", s.duedate);
      setText("spStatus", status);
      setText("spTotal", formatINR(s.total));
      setText("spPaid", formatINR(s.paid));
      setText("spPending", formatINR(due));
    }
  }
}

function setText(id, txt, html=false){
  const el=document.getElementById(id);
  if(!el) return;
  if(html) el.innerHTML=txt; else el.innerText=txt;
}

function renderChart(totalFees, totalPaid){
  const ctx = document.getElementById("feeChart");
  if(!ctx) return;
  if(chart){ chart.destroy(); chart=null; }
  chart = new Chart(ctx,{
    type:'bar',
    data:{ labels:['Total Fees','Collected'], datasets:[{label:'Amount', data:[totalFees,totalPaid]}] },
    options:{
      responsive:true,
      plugins:{ legend:{ labels:{ color:"#e9eefc" } } },
      scales:{
        x:{ ticks:{ color:"#a9b6df" }, grid:{ color:"rgba(255,255,255,.06)"} },
        y:{ ticks:{ color:"#a9b6df" }, grid:{ color:"rgba(255,255,255,.06)"} }
      }
    }
  });
}

/* Toast */
function toast(title, message, actions){
  const wrap=document.getElementById("toasts");
  const t=document.createElement("div");
  t.className="toast";
  const now=new Date();
  const time=now.toLocaleTimeString([], {hour:'2-digit', minute:'2-digit'});
  t.innerHTML = `
    <div class="hdr"><b>${escapeHtml(title)}</b><span>${escapeHtml(time)}</span></div>
    <div class="msg">${escapeHtml(message)}</div>
    <div class="actions"></div>
  `;
  const act=t.querySelector(".actions");
  (actions||[]).forEach(a=>{
    const b=document.createElement("button");
    b.className="mini"+(a.primary?" primary":"");
    b.textContent=a.text;
    b.onclick=()=>{ try{a.action();}catch(e){} };
    act.appendChild(b);
  });
  wrap.appendChild(t);
  setTimeout(()=>{ t.style.opacity="0"; t.style.transform="translateY(8px)"; }, 5200);
  setTimeout(()=>{ try{t.remove();}catch(e){} }, 5600);
}

/* Modal */
function openModal(html){ document.getElementById("modal").innerHTML=html; document.getElementById("modalBack").style.display="flex"; }
function closeModal(e){
  if(e && e.target && e.target.id !== "modalBack") return;
  document.getElementById("modalBack").style.display="none";
  document.getElementById("modal").innerHTML="";
}

/* Init */
(function init(){
  if(localStorage.getItem(KEY_ADMIN_LOCKED) === null){
    localStorage.setItem(KEY_ADMIN_LOCKED, "true");
    adminLoggedIn = false;
  }else{
    adminLoggedIn = (localStorage.getItem(KEY_ADMIN_LOCKED) === "false");
  }
  // If admin logged in but student session exists, prefer student session view
  setLoginStatus();
  showView("dashboard");
})();
</script>
</body>
</html>
