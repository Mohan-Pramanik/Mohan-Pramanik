<!-- ======================================================================
     README MAP  (Mohan Pramanik profile) — v2 redesign
     Each section below starts with a big banner comment. Blocks inside a
     section are numbered like [2.1], [2.2] so you can find the right code.
     Every block also carries a short "CHANGE:" note explaining what was
     done to it in this redesign pass, so you can see at a glance what
     changed without diffing the whole file.

       1  HERO              banner, wave header, typing text, buttons, counters
       2  ABOUT ME          intro paragraph, facts table, working style
       3  TECH STACK        redesigned category cards + animated focus bars
       4  FEATURED PROJECTS CivicPulse, Smart Weather, Currency Converter
       5  GITHUB ANALYTICS  stats, languages, streak, activity graph, snake
       6  ACHIEVEMENTS      certifications and badges
       7  LET'S CONNECT     contact buttons, closing line, footer wave

     REMOVED in this pass (see notes below): the old "DSA JOURNEY" section
     and the old "2026 GOALS" section. Everything is renumbered 1→7.

     To hide something: wrap it in a comment. To show a hidden block again:
     delete its HIDDEN line and the closing arrow line after it.
     ====================================================================== -->


<!-- ######################################################################
     SECTION 1 OF 7  |  HERO
     Shows: profile banner, gradient wave header, typing text, contact buttons, counters.
     CHANGE: switched the wave header to a richer 3-stop gradient + a
     "twinkling" animation (was a flat fadeIn) for a more premium, less
     static first impression. Typing line rewritten to drop the DSA-heavy
     phrasing now that DSA Journey is no longer its own section below.
     ###################################################################### -->

<!-- [1.1 Profile banner image (github-banner.png in repo root)] — unchanged, still your custom banner -->
<p align="center">
  <img src="./github-banner.png" width="100%" alt="Mohan Pramanik - Aspiring Software Engineer" />
</p>

<!-- [1.2 Gradient wave header with tagline] — CHANGE: 3-stop gradient (deep navy → blue → violet), twinkling animation, taller/bolder type -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:020B1F,35:0A66C2,70:00C8FF,100:7B2FFF&height=200&section=header&text=BUILD%20%E2%80%A2%20LEARN%20%E2%80%A2%20SOLVE%20%E2%80%A2%20GROW&fontSize=36&fontColor=FFFFFF&fontAlignY=36&desc=Turning%20ideas%20into%20impactful%20solutions.&descSize=18&descAlignY=58&animation=twinkling" width="100%" alt="Build, Learn, Solve, Grow. Turning ideas into impactful solutions." />
</p>

<!-- [1.3 Typing animation (role and focus lines)] — CHANGE: rewritten lines, no longer leads with DSA; leads with the engineering identity instead -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=22&duration=3200&pause=1000&color=00C8FF&center=true&vCenter=true&width=760&height=50&lines=Aspiring+Software+Engineer;Full-Stack+Development+%E2%80%A2+Backend+Systems;Problem+Solver+%E2%80%A2+Builder+%E2%80%A2+Learner;Always+Learning+%E2%80%A2+Always+Building" alt="Aspiring Software Engineer | Full-Stack Development, Backend Systems | Always Learning, Always Building" />
</p>

<!-- [1.4 Main buttons: LinkedIn, Email, CivicPulse] — unchanged -->
<p align="center">
  <a href="https://linkedin.com/in/MohanPramanik143"><img src="https://img.shields.io/badge/LINKEDIN-CONNECT-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:mohanpramanik6294113716@gmail.com"><img src="https://img.shields.io/badge/EMAIL-CONTACT-00A8E8?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
  <a href="https://civicpulse-v2.vercel.app/"><img src="https://img.shields.io/badge/LIVE%20PROJECT-CIVICPULSE-0B1F3A?style=for-the-badge&logo=vercel&logoColor=white" alt="CivicPulse live project" /></a>
</p>

<!-- [1.5 Counters: followers and profile views] — unchanged -->
<p align="center">
  <a href="https://github.com/Mohan-Pramanik?tab=followers"><img src="https://img.shields.io/github/followers/Mohan-Pramanik?label=FOLLOWERS&style=flat-square&logo=github&logoColor=white&labelColor=0B1F3A&color=00C8FF" alt="GitHub followers" /></a>
  <img src="https://komarev.com/ghpvc/?username=Mohan-Pramanik&style=flat-square&label=PROFILE+VIEWS&color=00C8FF&labelColor=0B1F3A" alt="Profile views" />
</p>

<!-- [1.6 HIDDEN] Terminal card (assets/terminal.svg). Delete this line and the closing arrow line below to show it again. Untouched in this pass.
<p align="center">
  <img src="https://raw.githubusercontent.com/Mohan-Pramanik/Mohan-Pramanik/main/assets/terminal.svg" width="760" alt="Terminal: Mohan Pramanik, Aspiring Software Engineer. Focus: Backend, Web, AI. Status: Learning and Building." />
</p>
-->



<!-- ######################################################################
     SECTION 2 OF 7  |  ABOUT ME
     Shows: title bar, intro paragraph, facts table, working style line.
     CHANGE: content kept as-is (it was already accurate and clean) — only
     the DSA emphasis in the intro line was softened slightly since DSA no
     longer has its own dedicated section further down the page.
     ###################################################################### -->
<!-- [2.0 Section title bar] — unchanged style, kept consistent with the rest of the page -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:001B44,50:0A3A7A,100:001B44&height=56&text=ABOUT%20ME&fontSize=22&fontColor=00C8FF&fontAlignY=50&stroke=00C8FF&strokeWidth=1&animation=fadeIn" width="100%" alt="ABOUT ME" />
</p>

<!-- [2.1 Intro paragraph] — CHANGE: trimmed the DSA-first framing to a more balanced full-stack + problem-solving framing -->
<p align="center">
  I'm a <b>B.Tech Information Technology</b> student at <b>Techno Main Salt Lake</b> who enjoys turning ideas into working software. I'm building full-stack <b>web applications</b> with a strong <b>backend</b> focus, sharpening my <b>problem-solving</b> fundamentals, and exploring <b>artificial intelligence</b>. I learn best by shipping <b>real-world projects</b> and improving them one iteration at a time.
</p>

<!-- [2.2 Facts table: education, interests, mission] — unchanged -->
<table align="center">
  <tr>
    <td><b>🎓 Education</b></td>
    <td>B.Tech in Information Technology, Techno Main Salt Lake</td>
  </tr>
  <tr>
    <td><b>🎯 Interests</b></td>
    <td>Software Engineering • Backend • Web Development • AI • System Design</td>
  </tr>
  <tr>
    <td><b>💡 Mission</b></td>
    <td>Turning ideas into impactful solutions.</td>
  </tr>
</table>

<!-- [2.3 Working style line: Idea to Impact] — unchanged -->
<p align="center">
  <sub>💡 <b>Idea</b> → 📚 <b>Learn</b> → 💻 <b>Build</b> → 🧪 <b>Test</b> → 🧠 <b>Solve</b> → 🚀 <b>Impact</b></sub>
</p>



<!-- ######################################################################
     SECTION 3 OF 7  |  TECH STACK
     Shows: title bar, category cards with icon rows, animated learning-focus bars.
     CHANGE (the main ask for this pass):
       • Rebuilt as individual rounded "cards" per category instead of a
         plain table, each with a small colored category badge, so the
         section reads as a proper stack overview instead of a spreadsheet.
       • Removed Firebase entirely (and DSA/OOP folded into a lighter,
         non-repetitive line) — the stack list is now leaner and only
         lists things actively used across your shipped projects.
       • assets/focus.svg replaced with a new version: smoother eased
         animation (spline easing instead of linear), staggered bar
         start times so the bars no longer move in lockstep, a soft glow
         filter on the bars/markers, and a subtle animated backdrop —
         same size/embed, drop-in replacement.
     ###################################################################### -->
<!-- [3.0 Section title bar] — unchanged style -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:001B44,50:0A3A7A,100:001B44&height=56&text=TECH%20STACK&fontSize=22&fontColor=00C8FF&fontAlignY=50&stroke=00C8FF&strokeWidth=1&animation=fadeIn" width="100%" alt="TECH STACK" />
</p>

<!-- [3.1 Stack cards by category] — CHANGE: replaced the old 6-row plain table with 5 centered "cards" (small label badge + icon row); Firebase removed, DB row now shows MongoDB only -->
<table align="center" width="100%">
  <tr>
    <td align="center" width="20%">
      <img src="https://img.shields.io/badge/LANGUAGES-0B1F3A?style=for-the-badge&labelColor=0B1F3A&color=00C8FF" alt="Languages" /><br /><br />
      <img src="https://skillicons.dev/icons?i=c,cpp,python,js&theme=dark" alt="C, C++, Python, JavaScript" />
    </td>
    <td align="center" width="20%">
      <img src="https://img.shields.io/badge/FRONTEND-0B1F3A?style=for-the-badge&labelColor=0B1F3A&color=00C8FF" alt="Frontend" /><br /><br />
      <img src="https://skillicons.dev/icons?i=html,css,js,react&theme=dark" alt="HTML, CSS, JavaScript, React" />
    </td>
    <td align="center" width="20%">
      <img src="https://img.shields.io/badge/BACKEND-0B1F3A?style=for-the-badge&labelColor=0B1F3A&color=00C8FF" alt="Backend" /><br /><br />
      <img src="https://skillicons.dev/icons?i=nodejs,express&theme=dark" alt="Node.js, Express.js" />
    </td>
    <td align="center" width="20%">
      <img src="https://img.shields.io/badge/DATABASE-0B1F3A?style=for-the-badge&labelColor=0B1F3A&color=00C8FF" alt="Database" /><br /><br />
      <img src="https://skillicons.dev/icons?i=mongodb&theme=dark" alt="MongoDB" />
    </td>
    <td align="center" width="20%">
      <img src="https://img.shields.io/badge/TOOLS-0B1F3A?style=for-the-badge&labelColor=0B1F3A&color=00C8FF" alt="Tools" /><br /><br />
      <img src="https://skillicons.dev/icons?i=git,github,vscode&theme=dark" alt="Git, GitHub, VS Code" />
    </td>
  </tr>
</table>

<br />

<!-- [3.1b Deployment + fundamentals strip] — CHANGE: merged the old separate Deployment and CS Fundamentals rows into one compact strip beneath the card grid, so the section doesn't run long -->
<p align="center">
  <img src="https://img.shields.io/badge/DEPLOY-AWS%20%E2%80%A2%20Vercel%20%E2%80%A2%20Netlify-0B1F3A?style=flat-square&labelColor=0B1F3A&color=00C8FF" alt="Deployment: AWS, Vercel, Netlify" />
  &nbsp;
  <img src="https://img.shields.io/badge/FOUNDATIONS-Data%20Structures%20%26%20Algorithms%20%E2%80%A2%20OOP-0B1F3A?style=flat-square&labelColor=0B1F3A&color=00C8FF" alt="Foundations: Data Structures & Algorithms, OOP" />
</p>

<!-- [3.2 Animated learning-focus bars (assets/focus.svg)] — CHANGE: points to the redesigned svg (same filename/path, so this <img> tag itself doesn't need to change once you replace the file in your repo) -->
<p align="center">
  <img src="https://raw.githubusercontent.com/Mohan-Pramanik/Mohan-Pramanik/main/assets/focus.svg" width="760" alt="Current learning focus: DSA, Backend, Full Stack, and AI/ML. A visual metaphor, not skill percentages." />
</p>



<!-- ######################################################################
     SECTION 4 OF 7  |  FEATURED PROJECTS
     Shows: title bar, CivicPulse card, Smart Weather and Currency Converter cards.
     CHANGE: Smart Weather's tech badges no longer show Firebase (it used
     to list Firebase for auth) — swapped for a generic "Weather API"
     badge so the project card stays accurate without referencing a
     skill that's been dropped from the Tech Stack section. Everything
     else in this section is unchanged.
     ###################################################################### -->
<!-- [4.0 Section title bar] — unchanged -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:001B44,50:0A3A7A,100:001B44&height=56&text=FEATURED%20PROJECTS&fontSize=22&fontColor=00C8FF&fontAlignY=50&stroke=00C8FF&strokeWidth=1&animation=fadeIn" width="100%" alt="FEATURED PROJECTS" />
</p>

<!-- [4.1 Project card: CivicPulse (live demo button, tech badges, features)] — unchanged -->
<table width="100%">
  <tr>
    <td>
      <h3>🚨 CivicPulse &nbsp;<a href="https://civicpulse-v2.vercel.app/"><img src="https://img.shields.io/badge/%E2%96%B6%20LIVE%20DEMO-00C8FF?style=flat-square&labelColor=0B1F3A" alt="Live demo" /></a></h3>
      <p><b>Crowdsourced civic issue reporting and resolution platform.</b><br />
      <b>Problem</b> — Citizens often lack a transparent way to report and track civic problems.<br />
      <b>Solution</b> — A platform where citizens report issues and departments manage resolution.</p>
      <p>
        <img src="https://img.shields.io/badge/React-0B1F3A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
        <img src="https://img.shields.io/badge/Node.js-0B1F3A?style=flat-square&logo=nodedotjs&logoColor=8CC84B" alt="Node.js" />
        <img src="https://img.shields.io/badge/Express-0B1F3A?style=flat-square&logo=express&logoColor=white" alt="Express" />
        <img src="https://img.shields.io/badge/MongoDB-0B1F3A?style=flat-square&logo=mongodb&logoColor=4DB33D" alt="MongoDB" />
        <img src="https://img.shields.io/badge/React%20Leaflet-0B1F3A?style=flat-square&logo=leaflet&logoColor=199900" alt="React Leaflet" />
        <img src="https://img.shields.io/badge/OpenStreetMap-0B1F3A?style=flat-square&logo=openstreetmap&logoColor=7EBC6F" alt="OpenStreetMap" />
      </p>
      <p><b>Key features</b> — Issue reporting • Photo upload • Location • Interactive map • Admin dashboard • Department management • Field officer workflow • Analytics • SOS • Status tracking<br />
      <b>Status</b> — Deployed on Vercel</p>
    </td>
  </tr>
</table>

<!-- [4.2 HIDDEN] CivicPulse architecture diagram dropdown. Delete this line and the closing arrow line below to show it again. Untouched in this pass.
<details>
<summary><b>🏗️ CivicPulse architecture</b></summary>

```text
        Citizen
           │
           ▼
    React Frontend
  (React Leaflet + OSM)
           │
           ▼
      Express API
           │
           ▼
        MongoDB
           │
           ├── Admin
           ├── Department
           └── Field Officer
```

</details>
-->

<!-- [4.3 Project cards side by side: Smart Weather and Currency Converter] — CHANGE: Smart Weather badge row — Firebase badge removed, replaced with a Weather API badge -->
<table width="100%">
  <tr>
    <td width="50%" valign="top">
      <h3>🌦️ Smart Weather</h3>
      <p>Modern weather application.</p>
      <p><img src="https://img.shields.io/badge/React-0B1F3A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" /> <img src="https://img.shields.io/badge/Weather%20API-0B1F3A?style=flat-square&logo=cloudscale&logoColor=00C8FF" alt="Weather API" /> <img src="https://img.shields.io/badge/Netlify-0B1F3A?style=flat-square&logo=netlify&logoColor=00C7B7" alt="Netlify" /></p>
      <p>Weather search • Real-time weather • Responsive UI<br /><b>Status</b> — Deployed on Netlify</p>
    </td>
    <td width="50%" valign="top">
      <h3>💱 Currency Converter</h3>
      <p>Currency conversion web application.</p>
      <p><img src="https://img.shields.io/badge/HTML-0B1F3A?style=flat-square&logo=html5&logoColor=E34F26" alt="HTML" /> <img src="https://img.shields.io/badge/CSS-0B1F3A?style=flat-square&logo=css3&logoColor=1572B6" alt="CSS" /> <img src="https://img.shields.io/badge/JavaScript-0B1F3A?style=flat-square&logo=javascript&logoColor=F7DF1E" alt="JavaScript" /></p>
      <p>Built with vanilla JavaScript and an exchange-rate API.</p>
    </td>
  </tr>
</table>



<!-- ######################################################################
     SECTION 5 OF 7  |  GITHUB ANALYTICS
     (was Section 6 — renumbered after removing DSA Journey)
     Shows: title bar, live GitHub stats cards, activity graph, contribution snake.
     CHANGE: content/theme unchanged — this section was already dynamic
     and effective, so it was left as-is aside from renumbering.
     ###################################################################### -->
<!-- [5.0 Section title bar] — unchanged -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:001B44,50:0A3A7A,100:001B44&height=56&text=GITHUB%20ANALYTICS&fontSize=22&fontColor=00C8FF&fontAlignY=50&stroke=00C8FF&strokeWidth=1&animation=fadeIn" width="100%" alt="GITHUB ANALYTICS" />
</p>

<!-- [5.1 Stats card and top languages card, side by side] — unchanged -->
<table width="100%">
  <tr>
    <td width="50%" align="center" valign="top"><img src="https://github-readme-stats.vercel.app/api?username=Mohan-Pramanik&show_icons=true&theme=tokyonight&hide_border=true&rank_icon=github&include_all_commits=true&bg_color=0B1F3A&title_color=00C8FF&icon_color=00C8FF&text_color=FFFFFF&border_radius=10" width="100%" alt="GitHub Stats" /></td>
    <td width="50%" align="center" valign="top"><img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Mohan-Pramanik&layout=compact&theme=tokyonight&hide_border=true&bg_color=0B1F3A&title_color=00C8FF&text_color=FFFFFF&border_radius=10" width="100%" alt="Top Languages" /></td>
  </tr>
</table>

<!-- [5.2 Contribution streak card] — unchanged -->
<p align="center">
  <img src="https://streak-stats.demolab.com?user=Mohan-Pramanik&theme=tokyonight&hide_border=true&border_radius=10&background=0B1F3A&ring=00C8FF&fire=00C8FF&currStreakNum=FFFFFF&sideNums=FFFFFF&currStreakLabel=00C8FF&sideLabels=8BE9FD&dates=8BE9FD" width="100%" alt="GitHub Contribution Streak" />
</p>

<!-- [5.3 Contribution activity graph] — unchanged -->
<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=Mohan-Pramanik&theme=tokyo-night&hide_border=true&area=true&bg_color=0B1F3A&color=00C8FF&line=00C8FF&point=FFFFFF&area_color=00C8FF&radius=10" width="100%" alt="GitHub Contribution Activity Graph" />
</p>

<!-- [5.4 Contribution snake (needs .github/workflows/snake.yml and the output branch)] — unchanged -->
<p align="center">
  <picture>
    <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Mohan-Pramanik/Mohan-Pramanik/output/github-contribution-grid-snake.svg" />
    <img src="https://raw.githubusercontent.com/Mohan-Pramanik/Mohan-Pramanik/output/github-contribution-grid-snake-dark.svg" width="100%" alt="GitHub contribution snake animation" />
  </picture>
</p>



<!-- ######################################################################
     SECTION 6 OF 7  |  ACHIEVEMENTS
     (was Section 7 — renumbered)
     Shows: title bar, certification and badge row.
     CHANGE: content unchanged, only renumbered.
     ###################################################################### -->
<!-- [6.0 Section title bar] — unchanged -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:001B44,50:0A3A7A,100:001B44&height=56&text=ACHIEVEMENTS&fontSize=22&fontColor=00C8FF&fontAlignY=50&stroke=00C8FF&strokeWidth=1&animation=fadeIn" width="100%" alt="ACHIEVEMENTS" />
</p>

<!-- [6.1 Achievement badges] — unchanged -->
<p align="center">
  <img src="https://img.shields.io/badge/AWS%20ACADEMY-CLOUD%20FOUNDATIONS-FF9900?style=for-the-badge&logo=amazonaws&logoColor=white&labelColor=0B1F3A" alt="AWS Academy Graduate - Cloud Foundations" />
  <img src="https://img.shields.io/badge/GOOGLE%20CLOUD-GEN%20AI%20ACADEMY%202.0-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white&labelColor=0B1F3A" alt="Google Cloud Gen AI Academy 2.0" />
  <img src="https://img.shields.io/badge/SKILLS%20BOOST-35%2B%20CHALLENGE%20LABS-00C8FF?style=for-the-badge&logo=googlecloud&logoColor=white&labelColor=0B1F3A" alt="35+ Google Cloud Skills Boost Challenge Labs" />
  <img src="https://img.shields.io/badge/LEETCODE-50%20DAYS%20BADGE-FFA116?style=for-the-badge&logo=leetcode&logoColor=white&labelColor=0B1F3A" alt="LeetCode 50 Days Badge" />
  <img src="https://img.shields.io/badge/BUILT-SMART%20WEATHER%20APP-0A66C2?style=for-the-badge&logoColor=white&labelColor=0B1F3A" alt="Smart Weather Web App" />
  <img src="https://img.shields.io/badge/BUILT-CIVICPULSE-0A66C2?style=for-the-badge&logoColor=white&labelColor=0B1F3A" alt="CivicPulse" />
</p>



<!-- ######################################################################
     SECTION 7 OF 7  |  LET'S CONNECT AND FOOTER
     (was Section 9 — renumbered; the "2026 GOALS" section that used to
     sit right before this one has been fully removed)
     Shows: title bar, contact buttons, email, closing typing line, philosophy line, footer wave.
     CHANGE: footer wave animation switched from fadeIn to twinkling to
     bookend the page with the same livelier animation used in the hero.
     ###################################################################### -->
<!-- [7.0 Section title bar] — unchanged -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=soft&color=0:001B44,50:0A3A7A,100:001B44&height=56&text=LET%27S%20CONNECT&fontSize=22&fontColor=00C8FF&fontAlignY=50&stroke=00C8FF&strokeWidth=1&animation=fadeIn" width="100%" alt="LET'S CONNECT" />
</p>

<!-- [7.1 Contact buttons: GitHub, LinkedIn, Email] — unchanged -->
<p align="center">
  <a href="https://github.com/Mohan-Pramanik"><img src="https://img.shields.io/badge/GitHub-Mohan--Pramanik-0B1F3A?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  <a href="https://linkedin.com/in/MohanPramanik143"><img src="https://img.shields.io/badge/LinkedIn-Mohan%20Pramanik-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="mailto:mohanpramanik6294113716@gmail.com"><img src="https://img.shields.io/badge/Email-Get%20in%20Touch-00A8E8?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
</p>

<!-- [7.2 Email address as text] — unchanged -->
<p align="center"><sub>mohanpramanik6294113716@gmail.com</sub></p>

<!-- [7.3 Closing typing line: Code. Learn. Solve. Repeat.] — unchanged -->
<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=2200&pause=700&color=00C8FF&center=true&vCenter=true&width=500&height=40&lines=Code.;Learn.;Solve.;Repeat." alt="Code. Learn. Solve. Repeat." />
</p>

<!-- [7.4 Philosophy line] — unchanged -->
<p align="center"><i>Build better. Solve smarter. Grow continuously.</i></p>

<!-- [7.5 Footer wave] — CHANGE: same 3-stop gradient as the hero + twinkling animation instead of fadeIn, so the top and bottom of the page visually match -->
<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:020B1F,35:0A66C2,70:00C8FF,100:7B2FFF&height=130&section=footer&text=Code%20%E2%80%A2%20Create%20%E2%80%A2%20Collaborate%20%E2%80%A2%20Make%20an%20Impact&fontSize=18&fontColor=FFFFFF&fontAlignY=68&animation=twinkling" width="100%" alt="Code, Create, Collaborate, Make an Impact" />
</p>
