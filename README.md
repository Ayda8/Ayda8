<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
    <img src="assets/header-light.svg" width="1200" alt="Aida Kabiri — Java backends, AI agents that care. A user talks to an AI agent, safety rules decide, and the family is notified.">
  </picture>
</div>

<div align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=22&pause=1200&color=2DD4BF&center=true&vCenter=true&width=760&lines=Hi%2C+I%27m+Aida+%E2%80%94+Java+backend+developer.;Building+AI+agents+with+Spring+AI.;Safety+rules+stay+outside+the+model.;Evals+first.+Then+prompts.;Coffee+in.+Clean+architecture+out." alt="Hi, I'm Aida, Java backend developer. Building AI agents with Spring AI. Safety rules stay outside the model." />
</div>

<div align="center">
  <img src="https://visitor-badge.laobi.icu/badge?page_id=Ayda8.Ayda8&amp;left_color=%23141A3A&amp;right_color=%237C8CFF&amp;left_text=PROFILE%20VIEWS" alt="Profile views" />
  <a href="https://github.com/Ayda8?tab=followers"><img src="https://img.shields.io/github/followers/Ayda8?label=FOLLOWERS&style=flat-square&color=2DD4BF&labelColor=141A3A" alt="Followers" /></a>
  <img src="https://img.shields.io/badge/JAVA-21-141A3A?style=flat-square&logo=openjdk&logoColor=FBBF24&labelColor=141A3A&color=7C8CFF" alt="Java 21" />
  <img src="https://img.shields.io/badge/OPEN%20TO-WORK%20IN%20GERMANY-141A3A?style=flat-square&labelColor=141A3A&color=0F9488" alt="Open to work in Germany" />
</div>

<img src="assets/divider.svg" width="100%" alt="" />

## `$ whoami`

```java
var aida = new Developer(
    "Aida Kabiri",                                   // name
    "Java Backend Developer · AI Engineering",       // role
    List.of("Spring Boot", "Spring AI", "JPA"),      // daily drivers
    List.of("Oracle", "PostgreSQL"),                 // where the data lives
    "B.Sc. Computer Science, 2023 – present",        // education
    "AI agents for assistive technology",            // what I'm building
    "Tehran, Iran"                                   // based in
);
```

I build backend systems in Java: enterprise information systems, and before that digital wallet,
payment and transaction products. Now I'm taking that engineering discipline into LLM applications.

My current project is an AI agent that helps people with disabilities and older adults manage their
medication, and keeps their family in the loop. The rule I build by: **an LLM may talk, but it never
decides anything safety-critical.** Those decisions live in plain, tested Java code, and every change
to the agent is measured with evals before it ships.

<img src="assets/divider.svg" width="100%" alt="" />

## `$ ls ~/projects`

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🩺 Caregiver Agent</h3>
      <p>An LLM agent that manages medication schedules and alerts caregivers. Runs fully local with Ollama and keeps working without internet. Safety rules in a deterministic rule engine, guarded by ArchUnit; evals before prompts.</p>
      <p><code>Java 21</code> <code>Spring Boot 3.5</code> <code>Spring AI</code> <code>Ollama</code> <code>Flyway</code></p>
      <img src="https://img.shields.io/badge/status-in%20progress%20%C2%B7%20private-141A3A?style=flat-square&labelColor=141A3A&color=FBBF24" alt="In progress, private repository">
    </td>
    <td width="50%" valign="top">
      <h3>🪙 <a href="https://github.com/stupidprogrammer4/amu-pulse">Amu Pulse</a></h3>
      <p>Precious-metals price tracking with AI-scored market signals, built as a team. I built the identity module (JWT refresh tokens stored as SHA-256 hashes, login audit log) and the news crawler.</p>
      <p><code>Python</code> <code>FastAPI</code> <code>Dishka</code> <code>PostgreSQL</code></p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🎓 University Management System</h3>
      <p>Enrollment with capacity and timetable-conflict checks, batch enrollment, weighted-GPA transcripts as PDFs, role-based access. Built in a structured mentorship program.</p>
      <p><code>Spring Boot</code> <code>JSF / PrimeFaces</code> <code>Oracle</code> <code>JasperReports</code></p>
    </td>
    <td width="50%" valign="top">
      <h3>🖼️ Lumina</h3>
      <p>An art gallery web app, made as a gift for a painter in my family.</p>
      <p><code>Spring Boot</code> <code>PostgreSQL</code> <code>JWT</code> <code>React / Vite</code> <code>Docker</code></p>
    </td>
  </tr>
</table>

<img src="assets/divider.svg" width="100%" alt="" />

## `$ mvn dependency:tree`

<div align="center">

**Backend**<br>
<img src="https://img.shields.io/badge/Java-141A3A?style=for-the-badge&logo=openjdk&logoColor=FBBF24" alt="Java">
<img src="https://img.shields.io/badge/Spring%20Boot-141A3A?style=for-the-badge&logo=springboot&logoColor=6DB33F" alt="Spring Boot">
<img src="https://img.shields.io/badge/Spring%20Security-141A3A?style=for-the-badge&logo=springsecurity&logoColor=6DB33F" alt="Spring Security">
<img src="https://img.shields.io/badge/Hibernate-141A3A?style=for-the-badge&logo=hibernate&logoColor=BCAE79" alt="Hibernate">
<img src="https://img.shields.io/badge/JWT-141A3A?style=for-the-badge&logo=jsonwebtokens&logoColor=7C8CFF" alt="JWT">

**AI engineering**<br>
<img src="https://img.shields.io/badge/Spring%20AI-141A3A?style=for-the-badge&logo=spring&logoColor=2DD4BF" alt="Spring AI">
<img src="https://img.shields.io/badge/Ollama-141A3A?style=for-the-badge&logo=ollama&logoColor=FFFFFF" alt="Ollama">
<img src="https://img.shields.io/badge/Tool%20calling-141A3A?style=for-the-badge&logoColor=2DD4BF" alt="Tool calling">
<img src="https://img.shields.io/badge/Evals-141A3A?style=for-the-badge&logoColor=2DD4BF" alt="Evals">

**Data**<br>
<img src="https://img.shields.io/badge/Oracle-141A3A?style=for-the-badge&logo=oracle&logoColor=F80000" alt="Oracle">
<img src="https://img.shields.io/badge/PostgreSQL-141A3A?style=for-the-badge&logo=postgresql&logoColor=7C8CFF" alt="PostgreSQL">
<img src="https://img.shields.io/badge/Flyway-141A3A?style=for-the-badge&logo=flyway&logoColor=E0303A" alt="Flyway">
<img src="https://img.shields.io/badge/Redis-141A3A?style=for-the-badge&logo=redis&logoColor=FF4438" alt="Redis">

**Frontend · Build · Ops**<br>
<img src="https://img.shields.io/badge/React-141A3A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React">
<img src="https://img.shields.io/badge/PrimeFaces-141A3A?style=for-the-badge&logoColor=FBBF24" alt="PrimeFaces">
<img src="https://img.shields.io/badge/Maven-141A3A?style=for-the-badge&logo=apachemaven&logoColor=E05A3A" alt="Maven">
<img src="https://img.shields.io/badge/Docker-141A3A?style=for-the-badge&logo=docker&logoColor=2496ED" alt="Docker">
<img src="https://img.shields.io/badge/GitHub%20Actions-141A3A?style=for-the-badge&logo=githubactions&logoColor=7C8CFF" alt="GitHub Actions">
<img src="https://img.shields.io/badge/Linux-141A3A?style=for-the-badge&logo=linux&logoColor=FBBF24" alt="Linux">
<img src="https://img.shields.io/badge/Python-141A3A?style=for-the-badge&logo=python&logoColor=FBBF24" alt="Python">

</div>

<img src="assets/divider.svg" width="100%" alt="" />

## `$ ./stats --live`

<div align="center">
  <a href="https://github.com/Ayda8">
    <img width="410" src="https://github-readme-stats-salesp07.vercel.app/api?username=Ayda8&amp;show_icons=true&amp;hide_border=true&amp;bg_color=141A3A&amp;title_color=7C8CFF&amp;text_color=CBD5E1&amp;icon_color=2DD4BF&amp;include_all_commits=true&amp;count_private=true&amp;rank_icon=github&amp;disable_animations=true&amp;custom_title=Aida%27s%20GitHub%20stats" alt="GitHub stats">
  </a>
  <a href="https://github.com/Ayda8?tab=repositories">
    <img width="390" src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=Ayda8&amp;layout=compact&amp;hide_border=true&amp;bg_color=141A3A&amp;title_color=7C8CFF&amp;text_color=CBD5E1&amp;langs_count=6&amp;card_width=390&amp;disable_animations=true&amp;custom_title=Languages" alt="Languages across my public repositories">
  </a>
</div>

<div align="center">
  <img width="600" src="https://streak-stats.demolab.com/?user=Ayda8&amp;hide_border=true&amp;background=141A3A&amp;ring=7C8CFF&amp;fire=FBBF24&amp;currStreakLabel=2DD4BF&amp;sideLabels=CBD5E1&amp;dates=AEB6DA&amp;sideNums=F4F5FF&amp;currStreakNum=F4F5FF&amp;stroke=2C3566&amp;card_width=600&amp;date_format=M%20j&amp;disable_animations=true" alt="Contribution streak">
</div>

<img src="assets/divider.svg" width="100%" alt="" />

## `$ cat principles.md`

> **Safety lives in code, not in prompts.** If a mistake can hurt someone, a tested rule decides, not a model.<br>
> **Measure before you tune.** Evals first, then prompts, then models.<br>
> **Write the decision down.** Every important choice gets an ADR, so future me knows *why*.

<img src="assets/divider.svg" width="100%" alt="" />

## `$ curl aida.contact`

<div align="center">
  <a href="mailto:aydakabiri71@gmail.com"><img src="https://img.shields.io/badge/Email-141A3A?style=for-the-badge&logo=gmail&logoColor=FBBF24" alt="Email" /></a>
  <a href="https://github.com/Ayda8"><img src="https://img.shields.io/badge/GitHub-141A3A?style=for-the-badge&logo=github&logoColor=F4F5FF" alt="GitHub" /></a>
</div>

<br>

<div align="center">
  <sub><code>System.out.println("Thanks for stopping by ☕");</code></sub>
</div>
