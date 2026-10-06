<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Ahmed Raza | Odoo Technical Developer</title>
<meta name="description" content="Odoo developer in Karachi. Integrations, custom modules, e-commerce, CRM automation, deployment, support and mobile apps.">
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Bricolage+Grotesque:wght@500;700;800&family=IBM+Plex+Sans:wght@400;500&display=swap" rel="stylesheet">
<style>
:root{--bg:#0a0e1f;--card:#121936;--line:rgba(255,255,255,.1);--txt:#e9edf9;--mut:#9aa6c6;--a:#b47be0;--b:#2dd4bf;--g:linear-gradient(110deg,var(--a),var(--b))}
*{box-sizing:border-box;margin:0}
html{scroll-behavior:smooth}
body{background:var(--bg);color:var(--txt);font:400 17px/1.65 "IBM Plex Sans",system-ui,sans-serif;overflow-x:hidden}
a{color:inherit;text-decoration:none}
a:focus-visible,button:focus-visible{outline:3px solid var(--b);outline-offset:3px}
h1,h2,h3{font-family:"Bricolage Grotesque",sans-serif;line-height:1.1}
.wrap{max-width:1080px;margin:0 auto;padding:0 24px}
.grad{background:var(--g);-webkit-background-clip:text;background-clip:text;color:transparent}
#bar{position:fixed;top:0;left:0;height:3px;width:0;background:var(--g);z-index:30}
nav{position:fixed;top:0;width:100%;z-index:20;backdrop-filter:blur(14px);background:rgba(10,14,31,.7);border-bottom:1px solid var(--line)}
nav .wrap{display:flex;justify-content:space-between;align-items:center;height:64px}
.logo{font:800 1.2rem "Bricolage Grotesque"}
nav ul{display:flex;gap:26px;list-style:none;font-size:.95rem;color:var(--mut)}
nav ul a:hover{color:var(--txt)}
.btn{display:inline-block;padding:12px 24px;border-radius:999px;font-weight:500;border:1px solid var(--line);transition:.3s}
.btn.p{background:var(--g);color:#0a0e1f;border:0}
.btn:hover{transform:translateY(-3px);box-shadow:0 10px 30px rgba(180,123,224,.35)}
/* hero */
.hero{min-height:100vh;display:flex;align-items:center;position:relative;overflow:hidden;padding-top:64px}
.blob{position:absolute;border-radius:50%;filter:blur(90px);opacity:.45;animation:float 14s ease-in-out infinite}
.b1{width:420px;height:420px;background:#714b67;top:8%;left:-6%}
.b2{width:380px;height:380px;background:#14b8a6;bottom:0;right:-4%;animation-delay:-5s}
.b3{width:260px;height:260px;background:#6d5bd0;top:40%;left:50%;animation-delay:-9s}
@keyframes float{50%{transform:translate(50px,-40px) scale(1.15)}}
.grid{position:absolute;inset:0;background-image:linear-gradient(var(--line) 1px,transparent 1px),linear-gradient(90deg,var(--line) 1px,transparent 1px);background-size:56px 56px;mask-image:radial-gradient(circle at 50% 40%,#000,transparent 70%);opacity:.5}
.hero .wrap{position:relative}
.pill{display:inline-flex;gap:10px;align-items:center;padding:6px 16px;border:1px solid var(--line);border-radius:999px;font-size:.9rem;color:var(--mut);background:rgba(255,255,255,.04)}
.pill i{width:9px;height:9px;border-radius:50%;background:var(--b);animation:pulse 2s infinite}
@keyframes pulse{0%{box-shadow:0 0 0 0 rgba(45,212,191,.6)}100%{box-shadow:0 0 0 12px transparent}}
h1{font-size:clamp(2.8rem,8vw,5.6rem);font-weight:800;letter-spacing:-.03em;margin:22px 0 12px}
.role{font:700 clamp(1.3rem,3vw,2rem) "Bricolage Grotesque";min-height:2.4rem}
.role::after{content:"|";color:var(--b);animation:blink 1s steps(1) infinite}
@keyframes blink{50%{opacity:0}}
.lead{max-width:60ch;color:var(--mut);margin:18px 0 32px}
.cta{display:flex;gap:14px;flex-wrap:wrap}
.stats{display:grid;grid-template-columns:repeat(auto-fit,minmax(170px,1fr));gap:16px;margin-top:64px}
.stat{padding:22px;border:1px solid var(--line);border-radius:16px;background:rgba(255,255,255,.04)}
.stat b{display:block;font:800 2.4rem "Bricolage Grotesque"}
.stat span{color:var(--mut);font-size:.9rem}
/* sections */
section{padding:110px 0 10px}
.eyebrow{color:var(--b);font-size:.85rem;letter-spacing:.16em;text-transform:uppercase;font-weight:500}
h2{font-size:clamp(2rem,5vw,3.2rem);margin:10px 0 40px;font-weight:800}
.reveal{opacity:0;transform:translateY(34px);transition:opacity .8s,transform .8s}
.reveal.in{opacity:1;transform:none}
.about{display:grid;grid-template-columns:1.4fr 1fr;gap:40px}
.about p{color:var(--mut);margin-bottom:16px}
.facts{display:grid;gap:12px;align-content:start}
.fact{padding:16px 20px;border:1px solid var(--line);border-radius:14px;background:var(--card)}
.fact small{display:block;color:var(--mut)}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(240px,1fr));gap:18px}
.card{position:relative;padding:26px;border-radius:18px;background:var(--card);border:1px solid var(--line);transition:.35s;overflow:hidden}
.card::before{content:"";position:absolute;inset:0;background:var(--g);opacity:0;transition:.35s;z-index:0}
.card>*{position:relative;z-index:1}
.card:hover{transform:translateY(-8px);border-color:var(--a);box-shadow:0 20px 40px rgba(0,0,0,.4)}
.card:hover::before{opacity:.08}
.ico{font-size:1.8rem;display:block;margin-bottom:10px}
.card h3{font-size:1.2rem;margin-bottom:8px}
.card p{color:var(--mut);font-size:.95rem}
.card .res{display:inline-block;margin-top:12px;color:var(--b);font-weight:500;font-size:.9rem}
.tags{display:flex;flex-wrap:wrap;gap:6px;margin-top:14px}
.tags span{font-size:.75rem;padding:3px 10px;border-radius:999px;background:rgba(180,123,224,.14);color:#d9b8f2}
/* timeline */
.tl{position:relative;padding-left:34px}
.tl::before{content:"";position:absolute;left:8px;top:6px;bottom:0;width:2px;background:linear-gradient(var(--a),var(--b),transparent)}
.job{position:relative;margin-bottom:34px}
.job::before{content:"";position:absolute;left:-34px;top:8px;width:18px;height:18px;border-radius:50%;background:var(--bg);border:3px solid var(--b);animation:pulse 2.4s infinite}
.job .when{color:var(--b);font-size:.88rem;font-weight:500}
.job h3{font-size:1.4rem;margin:4px 0}
.job .org{color:var(--mut);margin-bottom:12px}
.job ul{color:var(--mut);padding-left:18px}
.job li{margin-bottom:6px}
.sub{margin-top:16px;padding:18px 20px;border-radius:14px;background:var(--card);border:1px solid var(--line)}
.sub h4{font:700 1.05rem "Bricolage Grotesque";margin-bottom:6px}
/* skills */
.sk{display:grid;grid-template-columns:repeat(auto-fit,minmax(300px,1fr));gap:18px}
.chips{display:flex;flex-wrap:wrap;gap:8px;margin-top:12px}
.chips span{padding:6px 14px;border-radius:999px;border:1px solid var(--line);background:rgba(255,255,255,.04);font-size:.9rem;transition:.25s}
.chips span:hover{background:var(--g);color:#0a0e1f;transform:scale(1.07)}
.marq{overflow:hidden;margin-top:48px;mask-image:linear-gradient(90deg,transparent,#000 10%,#000 90%,transparent)}
.track{display:flex;gap:44px;width:max-content;animation:scroll 32s linear infinite;font:700 1.6rem "Bricolage Grotesque";color:rgba(255,255,255,.22)}
@keyframes scroll{to{transform:translateX(-50%)}}
.edu{display:grid;grid-template-columns:repeat(auto-fit,minmax(280px,1fr));gap:18px}
.contact{text-align:center;padding-bottom:90px}
.contact h2{margin-bottom:16px}
.contact p{color:var(--mut);max-width:52ch;margin:0 auto 30px}
.contact .cta{justify-content:center}
.mail{display:block;margin-top:28px;font:700 clamp(1.2rem,3vw,1.9rem) "Bricolage Grotesque"}
footer{border-top:1px solid var(--line);padding:24px 0;text-align:center;color:var(--mut);font-size:.88rem}
@media(max-width:760px){nav ul{display:none}.about{grid-template-columns:1fr}section{padding-top:80px}}
@media(prefers-reduced-motion:reduce){*{animation:none!important;transition:none!important}.reveal{opacity:1;transform:none}}
</style>
</head>
<body>
<div id="bar"></div>
<nav><div class="wrap"><a class="logo grad" href="#top">AR.</a>
<ul><li><a href="#about">About</a></li><li><a href="#services">Services</a></li><li><a href="#experience">Experience</a></li><li><a href="#projects">Projects</a></li><li><a href="#skills">Skills</a></li><li><a href="#education">Education</a></li></ul>
<a class="btn p" href="#contact">Hire me</a></div></nav>

<header class="hero" id="top">
<div class="blob b1"></div><div class="blob b2"></div><div class="blob b3"></div><div class="grid"></div>
<div class="wrap">
<span class="pill"><i></i>Open to full-time roles and freelance projects</span>
<h1>Hi, I'm <span class="grad">Ahmed Raza</span></h1>
<div class="role" id="role"></div>
<p class="lead">I own Odoo projects from the first requirement to the live system: custom modules, integrations, websites, automation, deployment and support. Based in Karachi, working with clients worldwide.</p>
<div class="cta"><a class="btn p" href="#projects">View my work</a><a class="btn" href="#contact">Get in touch</a></div>
<div class="stats">
<div class="stat"><b data-to="1100" data-s="+">0</b><span>orders on a store I built</span></div>
<div class="stat"><b data-to="12" data-s="+">0</b><span>client projects delivered</span></div>
<div class="stat"><b data-to="600" data-s="+">0</b><span>contacts in automated campaigns</span></div>
<div class="stat"><b data-to="80" data-s="+">0</b><span>email templates customized</span></div>
</div></div></header>

<section id="about"><div class="wrap">
<div class="eyebrow reveal">About</div><h2 class="reveal">Developer, integrator, problem solver</h2>
<div class="about reveal">
<div><p>I'm an Odoo technical developer who enjoys turning messy business processes into clean, automated systems. I work on websites, CRM, accounting, planning, helpdesk, marketing and payments, and I'm comfortable going from a Figma design to a working shop or from a vague request to a webhook-driven integration.</p>
<p>I have worked across <b>multiple Odoo versions</b> and <b>every kind of instance</b>: Odoo Online, Odoo.sh, on-premise and local environments. Beyond Odoo I build with Python, JavaScript, PHP and React Native, and I administer PostgreSQL databases directly.</p>
<p>I like solutions that fit the problem: native configuration when it's enough, a custom module when it's worth it, and a clear explanation either way.</p></div>
<div class="facts"><div class="fact"><small>Location</small>Karachi, Pakistan</div><div class="fact"><small>Currently</small>Odoo Technical Developer, Bundo Tech</div><div class="fact"><small>Languages</small>Urdu (native), English (professional)</div><div class="fact"><small>Availability</small>Full-time roles and freelance</div></div>
</div></div></section>

<section id="services"><div class="wrap">
<div class="eyebrow reveal">What I offer</div><h2 class="reveal">Odoo ERP services</h2>
<div class="cards">
<div class="card reveal"><span class="ico">🔗</span><h3>Integration</h3><p>Connect Odoo with payment gateways, QuickBooks, WordPress, marketing tools and any REST API.</p></div>
<div class="card reveal"><span class="ico">🚀</span><h3>Implementation</h3><p>Set up Odoo around your real workflows across Sales, CRM, Website, Accounting, Helpdesk and Planning.</p></div>
<div class="card reveal"><span class="ico">💻</span><h3>Development</h3><p>Custom modules, portals, reports, automations and website features built to your requirements.</p></div>
<div class="card reveal"><span class="ico">📦</span><h3>Deployment</h3><p>Take your system live on Odoo.sh, on-premise servers or Odoo Online, with testing along the way.</p></div>
<div class="card reveal"><span class="ico">☁️</span><h3>Hosting</h3><p>Hosting setup and management across Odoo.sh and on-premise environments, including database administration.</p></div>
<div class="card reveal"><span class="ico">🧰</span><h3>Support</h3><p>Debugging, fixes and improvements on live production instances so your team keeps working.</p></div>
<div class="card reveal"><span class="ico">🎓</span><h3>Training</h3><p>Hands-on training so your team can use Odoo confidently every day.</p></div>
<div class="card reveal"><span class="ico">🧭</span><h3>Consulting</h3><p>Honest advice on the right approach: configuration, custom module or integration.</p></div>
</div></div></section>

<section id="experience"><div class="wrap">
<div class="eyebrow reveal">Experience</div><h2 class="reveal">Where I've worked</h2>
<div class="tl">
<div class="job reveal"><div class="when">Feb 2026 – Present</div><h3>Odoo Technical Developer</h3><div class="org">Bundo Tech · Full-time · Karachi, Pakistan (on-site)</div>
<ul><li>Started with a month of structured Odoo training, then moved into live client implementation work.</li><li>Own client projects end to end: module development, customization, PostgreSQL administration, third-party integrations and debugging on live production instances.</li><li>Work in Git within the Bundo Tech development team across all client projects.</li></ul>
<div class="sub"><h4>E-commerce platform · 3+ months</h4><ul><li>Built a fully customized Odoo store from scratch that now processes 1,100+ orders.</li><li>Integrated a secure Bitcoin payment gateway with automated order confirmation.</li><li>Built an affiliate and referral program: 10+ affiliates onboarded with automated commission payouts.</li><li>Deployed 6 marketing automation campaigns across a 600+ contact database.</li></ul></div>
<div class="sub"><h4>Robotics e-commerce · current client</h4><ul><li>Building product pages for a grass-cutting robotics company.</li><li>Configuring Helpdesk with a Website to Helpdesk to Repair flow and notification workflows.</li></ul></div>
<div class="sub"><h4>Other client work</h4><ul><li>Planning customization and employee attendance portal.</li><li>Accounting: payment reconciliation and landed costs; QuickBooks sync.</li><li>CRM pipeline automation, lead-to-project workflow, website builds, WordPress plugin, React Native apps.</li></ul></div>
</div></div></div></section>

<section id="projects"><div class="wrap">
<div class="eyebrow reveal">Projects</div><h2 class="reveal">Selected work</h2>
<div class="cards">
<div class="card reveal"><span class="ico">🛒</span><h3>E-commerce platform</h3><p>Complete sites for two companies: hero products, flash sales, brand filters, quantity pricing, fast checkout, Dutch and French translations, technical SEO, Google Tag Manager and a Channable product feed.</p><span class="res">1,100+ orders in production</span><div class="tags"><span>Website</span><span>SEO</span><span>GTM</span><span>Python</span></div></div>
<div class="card reveal"><span class="ico">💳</span><h3>Payment integrations</h3><p>BTCPay Server for Bitcoin and multiple coins, Klarna, and custom Rampex and PayLio providers with API and webhook sync.</p><span class="res">3 providers, orders synced</span><div class="tags"><span>Payments</span><span>Webhooks</span><span>REST</span></div></div>
<div class="card reveal"><span class="ico">🤝</span><h3>Affiliate and referral</h3><p>Apply, approve, auto-create the portal login and email. Dashboards with stats, product feeds and tracked links.</p><span class="res">10+ affiliates, automated payouts</span><div class="tags"><span>Portal</span><span>Affiliate</span><span>Automation</span></div></div>
<div class="card reveal"><span class="ico">📣</span><h3>Marketing automation</h3><p>Email and Marketing Automation campaigns with a custom module for detailed campaign statistics and exact checkout-time capture.</p><span class="res">6 campaigns, 600+ contacts</span><div class="tags"><span>Marketing</span><span>Email</span><span>Reports</span></div></div>
<div class="card reveal"><span class="ico">📈</span><h3>Automated CRM pipeline</h3><p>Lead to won deal with no manual steps: timed call tasks, follow-up emails, lost reasons, calendar blocks and a 50% deposit invoice on win.</p><span class="res">Fully hands-off</span><div class="tags"><span>CRM</span><span>Automated actions</span><span>Calendar</span></div></div>
<div class="card reveal"><span class="ico">📁</span><h3>Lead-to-project workflow</h3><p>NDA and proposal stages, automatic Documents folders, files sent via chatter, projects created from leads, POs from projects.</p><span class="res">CRM to Purchase, linked</span><div class="tags"><span>Documents</span><span>Project</span><span>Purchase</span></div></div>
<div class="card reveal"><span class="ico">🔧</span><h3>Repair and support flow</h3><p>A tunnel from website to helpdesk ticket to repair order, a 20+ page product catalog and sales notifications on confirmed orders.</p><span class="res">Website, Helpdesk, Repair</span><div class="tags"><span>Helpdesk</span><span>Repair</span><span>Website</span></div></div>
<div class="card reveal"><span class="ico">📱</span><h3>Mobile apps</h3><p>React Native apps: customer-support ticketing for complaints and service requests, and a beach-hut booking app with slot holding and payments.</p><span class="res">End to end, Odoo backend</span><div class="tags"><span>React Native</span><span>API</span><span>Payments</span></div></div>
<div class="card reveal"><span class="ico">🧩</span><h3>More builds</h3><p>Planning auto-slots and attendance portal, reconciliation and landed costs, QuickBooks sync, an Odoo to WordPress PHP plugin, CV import script, websites from drag-and-drop and Figma.</p><span class="res">Many industries</span><div class="tags"><span>Planning</span><span>Accounting</span><span>PHP</span><span>WordPress</span></div></div>
</div></div></section>

<section id="skills"><div class="wrap">
<div class="eyebrow reveal">Skills</div><h2 class="reveal">Tools I work with</h2>
<div class="sk">
<div class="card reveal"><h3>Odoo</h3><div class="chips"><span>Website</span><span>eCommerce</span><span>Sales</span><span>CRM</span><span>Planning</span><span>Helpdesk</span><span>Repair</span><span>Accounting</span><span>Contacts</span><span>Documents</span><span>Project</span><span>Purchase</span><span>Marketing Automation</span><span>Email Marketing</span><span>Affiliate</span><span>Payments</span><span>Custom modules</span><span>ORM</span><span>QWeb reports</span></div></div>
<div class="card reveal"><h3>Programming</h3><div class="chips"><span>Python</span><span>JavaScript</span><span>PHP</span><span>React Native</span><span>C/C++</span><span>Java</span><span>SQL</span></div></div>
<div class="card reveal"><h3>Integrations</h3><div class="chips"><span>REST APIs</span><span>Webhooks</span><span>BTCPay Server</span><span>Klarna</span><span>QuickBooks</span><span>WordPress</span><span>Google Tag Manager</span><span>Channable</span></div></div>
<div class="card reveal"><h3>Data and environments</h3><div class="chips"><span>PostgreSQL</span><span>MySQL</span><span>Odoo Online</span><span>Odoo.sh</span><span>On-premise</span><span>Local setup</span><span>Ngrok</span></div></div>
<div class="card reveal"><h3>Tools</h3><div class="chips"><span>Git</span><span>GitHub</span><span>VS Code</span><span>Figma to web</span></div></div>
<div class="card reveal"><h3>Working style</h3><div class="chips"><span>End-to-end ownership</span><span>Debugging</span><span>Team collaboration</span><span>Clear communication</span></div></div>
</div>
<div class="marq"><div class="track"><span>ODOO</span><span>PYTHON</span><span>POSTGRESQL</span><span>JAVASCRIPT</span><span>REACT NATIVE</span><span>PHP</span><span>REST API</span><span>ODOO.SH</span><span>ODOO</span><span>PYTHON</span><span>POSTGRESQL</span><span>JAVASCRIPT</span><span>REACT NATIVE</span><span>PHP</span><span>REST API</span><span>ODOO.SH</span></div></div>
</div></section>

<section id="education"><div class="wrap">
<div class="eyebrow reveal">Education</div><h2 class="reveal">Background</h2>
<div class="edu">
<div class="card reveal"><span class="ico">🎓</span><h3>BS Computer Science</h3><p>University of Karachi, Pakistan</p><span class="res">Dec 2021 – Dec 2025</span></div>
<div class="card reveal"><span class="ico">📘</span><h3>HSC, Pre-Engineering</h3><p>Govt. Degree College SRE Majeed, Karachi</p><span class="res">Sept 2019 – July 2021</span></div>
<div class="card reveal"><span class="ico">🗣️</span><h3>Languages</h3><p>Urdu (native)<br>English (professional working proficiency)</p></div>
</div></div></section>

<section class="contact" id="contact"><div class="wrap reveal">
<div class="eyebrow">Contact</div><h2>Let's build something <span class="grad">together</span></h2>
<p>I'm open to full-time Odoo developer roles and freelance projects: integrations, custom modules, websites, automation, deployment and support.</p>
<div class="cta"><a class="btn p" href="mailto:ar.razaahmed22@gmail.com">Send me an email</a><a class="btn" href="https://linkedin.com/in/ahmed-raza-193686146">LinkedIn</a><a class="btn" href="https://github.com/araza2003">GitHub</a></div>
<a class="mail grad" href="mailto:ar.razaahmed22@gmail.com">ar.razaahmed22@gmail.com</a>
</div></section>
<footer>© 2026 Ahmed Raza · Karachi, Pakistan · Client names are withheld to respect confidentiality.</footer>

<script>
const roles=["Odoo Developer","Integration Specialist","Full-Stack Engineer","React Native Builder"];
let r=0,c=0,del=false;const el=document.getElementById("role");
(function type(){const w=roles[r];el.textContent=w.slice(0,c);
if(!del&&c<w.length){c++;setTimeout(type,90)}else if(!del){del=true;setTimeout(type,1400)}
else if(c>0){c--;setTimeout(type,45)}else{del=false;r=(r+1)%roles.length;setTimeout(type,300)}})();
const io=new IntersectionObserver(es=>es.forEach(e=>{if(e.isIntersecting){e.target.classList.add("in");io.unobserve(e.target)}}),{threshold:.12});
document.querySelectorAll(".reveal").forEach((n,i)=>{n.style.transitionDelay=(i%4)*70+"ms";io.observe(n)});
const co=new IntersectionObserver(es=>es.forEach(e=>{if(!e.isIntersecting)return;const n=e.target,t=+n.dataset.to,s=n.dataset.s||"";let v=0;
const st=()=>{v+=Math.ceil(t/60);if(v>=t){n.textContent=t.toLocaleString()+s}else{n.textContent=v.toLocaleString();requestAnimationFrame(st)}};st();co.unobserve(n)}),{threshold:.6});
document.querySelectorAll("[data-to]").forEach(n=>co.observe(n));
addEventListener("scroll",()=>{const h=document.documentElement;document.getElementById("bar").style.width=(h.scrollTop/(h.scrollHeight-h.clientHeight)*100)+"%"},{passive:true});
</script>
</body>
</html>
