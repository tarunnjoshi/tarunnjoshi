<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=7c3aed&height=200&section=header&text=Tarun%20Joshi&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Frontend%20Developer&descAlignY=58&descSize=20&animation=fadeIn" width="100%"/>

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3000&pause=1000&color=7C3AED&center=true&vCenter=true&width=600&lines=Frontend+Developer+%F0%9F%9A%80;React+%26+Next.js+Expert+%E2%9A%A1;CiviCRM+Specialist+%F0%9F%94%A7;Open+Source+Contributor+%F0%9F%8C%9F)](https://github.com/DenverCoder1/readme-typing-svg)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tarun-joshi-a57323234)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/tarunnjoshi)
[![Portfolio](https://img.shields.io/badge/Portfolio-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://tarunnjoshi.github.io/portfolio)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tarun12joshi@gmail.com)

</div>

---

## 👨‍💻 About Me

```javascript
const tarun = {
  role      : "Frontend Developer",
  company   : "ColoredCow, Haryana 🇮🇳",
  location  : "Almora, Uttarakhand",
  experience: "3.5+ years",
  education : "B.Tech — THDC-IHET Tehri (UTU, 2022)",
  focus     : ["React", "Next.js", "CiviCRM", "Blockchain"],
  currentWork: "Sparklegacy — Digital Legacy Platform",
  funFact   : "I automated 90% of Goonj NGO's manual operations 🏆"
};
```

- 🚀 Building **production-grade web applications** for 3.5+ years
- 🔭 Currently leading **Sparklegacy** — a blockchain-based digital legacy platform
- 🌱 **Open source** — 3 PRs merged into **CiviCRM core** (shipped in 6.15 / 6.16 / 6.17) + CiviCRM extensions for Razorpay & WhatsApp (Glific)
- 🏆 **Top Innovator Award** by UpLink (World Economic Forum) for SankalpTaru
- 💡 Reduced NGO operational effort by **90%** through CiviCRM automation at Goonj
- 📫 Reach me at **tarun12joshi@gmail.com**

---

## 🚀 Featured Projects

| Project | Description | Tech Stack | Links |
|--------|-------------|-----------|-------|
| ⛓️ **Sparklegacy** | Digital legacy platform with blockchain-based digital wills — frontend architecture, product strategy & system design | `Next.js` `Django` `Blockchain` `Web3` `TypeScript` | 🔒 Private |
| 💛 **Goonj** | Transitioned India's iconic NGO from manual to fully automated ops. Open-source CiviCRM extensions for Razorpay & WhatsApp (Glific) | `CiviCRM` `WordPress` `PHP` `Razorpay` `WhatsApp API` | [🔗 Goonj.org](https://goonj.org) · [💻 GitHub](https://github.com/ColoredCow/goonj) |
| 🌱 **SankalpTaru** | Award-winning step-counting & gamification platform. **Top Innovator — WEF UpLink** & **8th e-North East Award 2023** | `React` `React Native` `Laravel` `WordPress` | [🔗 SankalpTaru.org](https://sankalptaru.org) |
| 🥗 **MegaFitMeals** | E-commerce platform for US-based meal delivery company. Custom checkout, Klaviyo + ShipStation integrations | `WordPress` `WooCommerce` `PHP` `Klaviyo` `ShipStation` | [🔗 MegaFitMeals.com](https://megafitmeals.com) |
| 👑 **Prince's Trust International** | Educational chatbot for UK's leading youth charity — guided students to certifications & career placements | `RapidPro` `Tableau` `EdTech` | 🔒 Private |
| 🏢 **Employee Portal** | Centralized platform for organizational operations and employee management at ColoredCow | `React` `Laravel` `MySQL` | [🔗 GitHub](https://github.com/ColoredCow/portal) |

---

## 🧩 Open Source — CiviCRM Contributions

### ✅ Merged into CiviCRM Core

| PR | What it fixes | Shipped in |
|----|---------------|-----------|
| [#35463](https://github.com/civicrm/civicrm-core/pull/35463) **Per-request caching on hot paths** | `CRM_Extension_Mapper::getModules()` was querying `civicrm_extension` ~8,700× per page load (~41% of all queries on a contact summary page). Added `Civi::$statics` caching there and in `CoreUtil::getOptionValueFields()`. | ![6.15](https://img.shields.io/badge/CiviCRM-6.15-81C459?style=flat-square) |
| [#35425](https://github.com/civicrm/civicrm-core/pull/35425) **MailingJob `writeToDB()` performance** | Removed redundant `Activity.create` API calls, repeated lookups and per-contact duplicate-check queries during bulk sends — cuts ~250K+ queries on a 250K-recipient mailing. | ![6.16](https://img.shields.io/badge/CiviCRM-6.16-81C459?style=flat-square) |
| [#36350](https://github.com/civicrm/civicrm-core/pull/36350) **Fix "View / Edit Multiple Choice Options" link** | Regression fix: the custom-field edit form's options button opened *Custom Field Groups* after the options screen moved to SearchKit/Afform. Re-pointed it to the new route with `option_group_id`. | ![6.17](https://img.shields.io/badge/CiviCRM-6.17-81C459?style=flat-square) |

### 🔌 CiviCRM Extensions

| Extension | Description | Links |
|-----------|-------------|-------|
| 💬 **civiglific** | WhatsApp for CiviCRM via [Glific](https://glific.org) — sync CiviCRM groups to Glific collections, send contribution receipts & messages on WhatsApp. Author & maintainer. | [💻 GitHub](https://github.com/tarunnjoshi/civiglific) |
| 💳 **civirazorpay** | Razorpay payment processor for CiviCRM (UPI, cards, netbanking). Extended for Goonj with recurring subscriptions, webhook deadlock-retry, and settlement/reconciliation crons. | [💻 GitHub](https://github.com/ColoredCow/civirazorpay) · [📦 Extensions Directory](https://civicrm.org/extensions/razorpay-payment-processor) · [🍴 Goonj fork](https://github.com/ColoredCow/goonj/tree/main/wp-content/civi-extensions/civirazorpay) |
| 🏗️ **goonjcustom** | Goonj's core CiviCRM extension — collection camps, urban planned visits, volunteer & event workflows, PAN verification, recurring-donation reminders, duplicate-contact merging, AWS SES mailing. Lead developer & top contributor on the Goonj repo (2,200+ commits). | [💻 GitHub](https://github.com/ColoredCow/goonj/tree/main/wp-content/civi-extensions/goonjcustom) |

---

## 🛠️ Tech Stack

### ⚡ Frontend
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-007ACC?style=for-the-badge&logo=typescript&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-764ABC?style=for-the-badge&logo=redux&logoColor=white)
![React Native](https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)
![Material UI](https://img.shields.io/badge/Material_UI-007FFF?style=for-the-badge&logo=mui&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)

### 🔧 Backend & CMS
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![Django](https://img.shields.io/badge/Django-092E20?style=for-the-badge&logo=django&logoColor=white)
![WordPress](https://img.shields.io/badge/WordPress-21759B?style=for-the-badge&logo=wordpress&logoColor=white)
![WooCommerce](https://img.shields.io/badge/WooCommerce-96588A?style=for-the-badge&logo=woocommerce&logoColor=white)
![CiviCRM](https://img.shields.io/badge/CiviCRM-81C459?style=for-the-badge&logoColor=white)

### 🗄️ Databases & Cloud
![MySQL](https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=for-the-badge&logo=mongodb&logoColor=white)
![AWS](https://img.shields.io/badge/AWS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white)

### 🛠️ Tools & Workflow
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)
![VS Code](https://img.shields.io/badge/VS_Code-007ACC?style=for-the-badge&logo=visual-studio-code&logoColor=white)
![Postman](https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-8DD6F9?style=for-the-badge&logo=webpack&logoColor=black)
![Figma](https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white)

---

## 📊 GitHub Stats

<div align="center">
  <img width="49%" src="https://github-readme-stats.hackclub.dev/api?username=tarunnjoshi&show_icons=true&theme=tokyonight&hide_border=true&count_private=true" />
  <img width="49%" src="https://streak-stats.demolab.com/?user=tarunnjoshi&theme=tokyonight&hide_border=true" />
</div>

<div align="center">
  <img width="50%" src="https://github-readme-stats.hackclub.dev/api/top-langs/?username=tarunnjoshi&layout=compact&theme=tokyonight&hide_border=true&langs_count=8" />
</div>

---

## 🏆 Achievements

<div align="center">

![WEF UpLink](https://img.shields.io/badge/%F0%9F%8F%86_Top_Innovator-WEF_UpLink_%28SankalpTaru%29-7C3AED?style=for-the-badge)
![e-North East Award](https://img.shields.io/badge/%F0%9F%A5%87_8th_e--North_East_Award-2023-7C3AED?style=for-the-badge)
![CiviCRM Core](https://img.shields.io/badge/%F0%9F%A7%A9_CiviCRM_Core_Contributor-3_PRs_merged_%286.15%E2%80%936.17%29-81C459?style=for-the-badge)
![Goonj](https://img.shields.io/badge/%F0%9F%92%9B_Goonj-90%25_ops_automated-F59E0B?style=for-the-badge)

</div>

---

## 📈 Contribution Graph

<div align="center">
  <img src="https://ghchart.rshah.org/7c3aed/tarunnjoshi" alt="Tarun Joshi's GitHub contribution chart" width="100%" />
</div>

---

## 🤝 Let's Connect

<div align="center">

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/tarun-joshi-a57323234)
[![Portfolio](https://img.shields.io/badge/Portfolio-Visit-7C3AED?style=for-the-badge&logo=vercel&logoColor=white)](https://tarunnjoshi.github.io/portfolio)
[![Email](https://img.shields.io/badge/Email-Say_Hi-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:tarun12joshi@gmail.com)

</div>

---

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=7c3aed&height=100&section=footer" width="100%"/>

  **⭐ If you like my work, consider starring my repos!**

  ![Profile Views](https://komarev.com/ghpvc/?username=tarunnjoshi&color=7c3aed&style=for-the-badge&label=Profile+Views)
</div>
