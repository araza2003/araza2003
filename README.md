<p align="center"><img src="assets/header.svg" alt="Ahmed Raza - Odoo Technical Developer" width="100%"></p>

<p align="center">
  <img src="https://img.shields.io/badge/Open_to-Full--time_roles-2dd4bf?style=for-the-badge&labelColor=0a0e1f" alt="Open to full-time roles">
  <img src="https://img.shields.io/badge/Open_to-Freelance_projects-b47be0?style=for-the-badge&labelColor=0a0e1f" alt="Open to freelance projects">
</p>

<p align="center">
  <a href="mailto:ar.razaahmed22@gmail.com"><img src="https://img.shields.io/badge/Email-ar.razaahmed22@gmail.com-714B67?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://linkedin.com/in/ahmed-raza-193686146"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

<p align="center"><b><a href="#about">About</a> · <a href="#services">Services</a> · <a href="#experience">Experience</a> · <a href="#projects">Projects</a> · <a href="#skills">Skills</a> · <a href="#education">Education</a> · <a href="#contact">Contact</a></b></p>

<p align="center"><img src="assets/stats.svg" alt="1,100+ orders, 12+ projects, 600+ contacts, 80+ email templates" width="100%"></p>

<a id="about"></a>
<p align="center"><img src="assets/h-about.svg" alt="About" width="100%"></p>

I'm an **Odoo technical developer** who turns messy business processes into clean, automated systems. I own projects end to end: understanding the requirement, building custom modules and integrations, deploying, and supporting the live system.

I have worked across **multiple Odoo versions** and **every kind of instance**: **Odoo Online, Odoo.sh, on-premise servers and local environments**. Beyond Odoo, I build with **Python, JavaScript, PHP and React Native**, and I administer **PostgreSQL** databases directly.

I like solutions that fit the problem: native configuration when it's enough, a custom module when it's worth it, and a clear explanation either way.

📍 Karachi, Pakistan &nbsp;·&nbsp; 🗣️ Urdu (native), English (professional) &nbsp;·&nbsp; 💼 Odoo Technical Developer at Bundo Tech

<a id="services"></a>
<p align="center"><img src="assets/h-services.svg" alt="Odoo ERP services" width="100%"></p>

<p align="center"><img src="assets/services.svg" alt="Integration, Implementation, Development, Deployment, Hosting, Support, Training, Consulting" width="100%"></p>

<a id="experience"></a>
<p align="center"><img src="assets/h-experience.svg" alt="Experience" width="100%"></p>

### 🟣 Odoo Technical Developer · Bundo Tech
**Feb 2026 – Present** · Full-time · Karachi, Pakistan (on-site)

- Started with a month of structured Odoo training, then moved into live client implementation work
- Own client projects end to end: module development and customization, PostgreSQL administration, third-party integrations, and debugging on live production instances
- Work in Git within the development team across all client projects

<details open>
<summary><b>🛒 E-commerce platform</b> · 3+ months</summary>
<br>

- Built a fully customized Odoo store from scratch that now processes **1,100+ orders**
- Integrated a secure Bitcoin payment gateway with automated order confirmation
- Built an affiliate and referral program: **10+ affiliates** onboarded, automated commission payouts
- Deployed **6 marketing automation campaigns** across a 600+ contact database
</details>

<details open>
<summary><b>🤖 Robotics e-commerce</b> · current client</summary>
<br>

- Building and customizing website product pages for a grass-cutting robotics company
- Configuring Helpdesk for customer support ticketing and notification workflows, connected to Repair orders
</details>

<details>
<summary><b>🧩 Other client work</b></summary>
<br>

- Planning customization and an employee attendance portal
- Accounting customization: payment reconciliation and landed costs; QuickBooks sync
- CRM pipeline automation, lead-to-project workflow, WordPress plugin, React Native apps, website builds
</details>

<a id="projects"></a>
<p align="center"><img src="assets/h-projects.svg" alt="Selected work" width="100%"></p>

<p align="center"><i>Most work is for private clients, so names and code are withheld. Details are available on request. Click a project to expand it.</i></p>

<details>
<summary><b>🛒 E-commerce platform (Dutch and French)</b> &nbsp;·&nbsp; 1,100+ orders in production</summary>
<br>

Complete Odoo websites built from scratch for two companies.

- Home, category and product pages with hero products, best sellers, flash sales, brand filters, quantity pricing and detailed specifications
- Fast one-page checkout customized to client requirements, with exact checkout-time capture for campaigns
- Full Dutch and French translations
- Technical SEO: custom meta fields, canonical tags and schema markup
- Google Tag Manager tracking of page views and button clicks
- Channable product feed module for marketing
- 80+ email templates customized across base and custom modules
</details>

<details>
<summary><b>💳 Payment gateway integrations</b> &nbsp;·&nbsp; Bitcoin, Rampex, PayLio, Klarna</summary>
<br>

- BTCPay Server setup for Bitcoin and multiple coins
- Custom payment provider modules for **Rampex** and **PayLio** with API and webhook integrations that sync orders and payments
- Klarna payment method setup
</details>

<details>
<summary><b>🤝 Affiliate and referral programs</b> &nbsp;·&nbsp; 10+ affiliates, automated payouts</summary>
<br>

- People apply, get approved, and receive an auto-generated password and email
- Portal pages where referrers track their own statistics
- Affiliate dashboard to generate product feeds and special promotion URLs
</details>

<details>
<summary><b>📣 Marketing automation</b> &nbsp;·&nbsp; 6 campaigns, 600+ contacts</summary>
<br>

- Campaigns built with Marketing Automation and Email Marketing
- Custom module showing detailed per-campaign statistics
</details>

<details>
<summary><b>📈 Fully automated CRM pipeline (event studio)</b></summary>
<br>

```mermaid
flowchart LR
    A[Lead created] --> B[1st contact]
    B -->|reached| C[Qualified]
    B -->|not reached| D[Email + 2nd contact]
    D -->|reached| C
    D -->|not reached| E[Email + 3rd contact]
    E -->|reached| C
    E -->|not reached| X[Lost: Not reached]
    C --> F[Quote sent]
    F --> G[Follow-ups 1 to 3]
    G -->|accepted| H[Won]
    G -->|no response| Y[Lost: No response]
    H --> I[50% deposit invoice]
```

- A new lead creates a call task and a calendar block with the request details
- Unreached customers automatically get the right email and a new task on a business-day schedule
- Accepted quotes cancel pending follow-ups; won deals create a deposit invoice and update the calendar
</details>

<details>
<summary><b>📁 Lead-to-project workflow (consulting firm)</b></summary>
<br>

- Custom NDA and proposal stages with document attachment fields
- Documents folder created automatically for every lead
- Files sent through the chatter, then forwarded to the linked Project
- Purchase orders raised from projects; lead activities appear in the calendar
</details>

<details>
<summary><b>🔧 Repair and support flow (robotics company)</b></summary>
<br>

- Product catalog across 20+ website pages built with the Odoo editor
- Custom flow connecting **Website → Helpdesk → Repair**
- Sales notifications when an order is confirmed
</details>

<details>
<summary><b>📱 Mobile apps (React Native)</b></summary>
<br>

- Customer-support ticketing app for complaints and service requests
- Beach-hut booking app covering booking, slot holding and payments
</details>

<details>
<summary><b>➕ More builds</b></summary>
<br>

- Planning with auto-generated slots and an attendance check-in portal
- Accounting: payment reconciliation and landed costs
- QuickBooks sync of orders and payments
- Custom PHP plugin syncing Odoo products to WordPress
- Script extracting data from CVs and certificates into Odoo Contacts
- Websites built with the drag-and-drop editor and from Figma designs
</details>

<a id="skills"></a>
<p align="center"><img src="assets/h-skills.svg" alt="Tools I work with" width="100%"></p>

<p align="center"><img src="assets/marquee.svg" alt="Odoo, Python, PostgreSQL, JavaScript, React Native, PHP, REST API" width="100%"></p>

| | |
|---|---|
| **Odoo** | Website · eCommerce · Sales · CRM · Planning · Helpdesk · Repair · Accounting · Contacts · Documents · Project · Purchase · Marketing Automation · Email Marketing · Affiliate · Payments · Custom modules · ORM · QWeb reports |
| **Programming** | Python · JavaScript · PHP · React Native · C/C++ · Java · SQL |
| **Integrations** | REST APIs · Webhooks · BTCPay Server · Klarna · QuickBooks · WordPress · Google Tag Manager · Channable |
| **Data** | PostgreSQL · MySQL |
| **Environments** | Odoo Online · Odoo.sh · On-premise · Local · Ngrok tunnels for webhook testing |
| **Tools** | Git · GitHub · VS Code · Figma-to-web |

<p align="center">
  <img src="https://img.shields.io/badge/Odoo-714B67?style=for-the-badge&logo=odoo&logoColor=white" alt="Odoo">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native">
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL">
  <img src="https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
  <img src="https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white" alt="WordPress">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
</p>

<a id="education"></a>
<p align="center"><img src="assets/h-education.svg" alt="Education" width="100%"></p>

- 🎓 **BS Computer Science**, University of Karachi, Pakistan · Dec 2021 – Dec 2025
- 📘 **HSC, Pre-Engineering**, Govt. Degree College SRE Majeed, Karachi · Sept 2019 – July 2021
- 🗣️ **Languages:** Urdu (native), English (professional working proficiency)

<a id="contact"></a>
<p align="center"><img src="assets/h-contact.svg" alt="Let's build something together" width="100%"></p>

<p align="center">I'm open to <b>full-time Odoo developer roles</b> and <b>freelance projects</b>: integrations, custom modules, websites, automation, deployment and support.</p>

<p align="center">
  <a href="mailto:ar.razaahmed22@gmail.com"><img src="https://img.shields.io/badge/Send_me_an_email-714B67?style=for-the-badge&logo=gmail&logoColor=white" alt="Email me"></a>
  <a href="https://linkedin.com/in/ahmed-raza-193686146"><img src="https://img.shields.io/badge/Message_me_on_LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
</p>

<p align="center"><img src="assets/footer.svg" alt="" width="100%"></p>
