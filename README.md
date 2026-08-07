<h2 align="left">Hi, I'm Antonin Do Souto</h2>

<h3 align="left">C/C++ Linux Engineer · Systems Debugging · Embedded Reliability · Technical Trainer</h3>

<p align="left">
I work on Linux, C and C++ systems where failures are hard to reproduce or explain: crashes, freezes, watchdog resets, stale data, communication failures and unclear runtime behavior.
</p>

<p align="left">
My focus is making those failures observable, reducing uncertainty and turning incomplete evidence into a structured technical investigation.
</p>

<p align="left">
  <b>6+ years in independent software development</b> ·
  <b>3+ years in technical training</b> ·
  Based in <b>Porto, Portugal</b>
</p>

---

<h3 align="left">What I work on</h3>

<ul>
  <li>
    <b>Linux & native debugging:</b>
    C/C++, crashes, memory issues, core dumps, traces, runtime failures and performance investigation
  </li>
  <li>
    <b>Failure handling & reliability:</b>
    deterministic state machines, fault handling, degraded modes, fail-safe behavior, watchdogs and recovery logic
  </li>
  <li>
    <b>Embedded & telemetry systems:</b>
    stale or lost data, communication failures, runtime instability, observability and system supervision
  </li>
  <li>
    <b>Technical rescue & training:</b>
    structured investigation, debugging methodology, C/C++, Linux, Git and Docker
  </li>
</ul>

---

<h3 align="left">Technical toolbox</h3>

<div align="center">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/c/c-original.svg" height="42" alt="C" />
  <img width="18" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/cplusplus/cplusplus-original.svg" height="42" alt="C++" />
  <img width="18" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/rust/rust-original.svg" height="42" alt="Rust" />
  <img width="18" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linux/linux-original.svg" height="42" alt="Linux" />
  <img width="18" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/docker/docker-original.svg" height="42" alt="Docker" />
  <img width="18" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/git/git-original.svg" height="42" alt="Git" />
</div>

<br>

<p align="center">
  <code>GDB</code> ·
  <code>Valgrind</code> ·
  <code>ASan / UBSan</code> ·
  <code>strace</code> ·
  <code>ltrace</code> ·
  <code>perf</code> ·
  <code>systemd</code> ·
  <code>journald</code> ·
  <code>CMake</code>
</p>

---

<h3 align="left">Selected systems work</h3>

<h4>
  <a href="https://github.com/pop-os/launcher/pull/291">
    Pop!_OS COSMIC Launcher
  </a>
</h4>

<p>
  <code>Rust</code>
  <code>Wayland</code>
  <code>screencopy</code>
  <code>async</code>
  <code>open upstream PR</code>
</p>

<p>
Open upstream pull request adding Alt-Tab window thumbnails through asynchronous Wayland screencopy,
SHM buffer processing, RGBA thumbnail generation, caching and refresh handling inside an existing Rust codebase.
</p>

<h4>
  <a href="https://github.com/avainfo/AegisEdge">
    Aegis Edge
  </a>
</h4>

<p>
  <code>C++</code>
  <code>UDP telemetry</code>
  <code>fault injection</code>
  <code>degraded modes</code>
  <code>working prototype</code>
</p>

<p>
Resilient telemetry prototype with a C++ core that reacts explicitly to delayed, stale and lost data through
<code>NORMAL</code>, <code>DEGRADED</code> and <code>LOST</code> states.
A controllable chaos proxy injects latency, packet loss and complete communication cuts to demonstrate degradation and recovery.
The project also includes an optional OpenCV-based horizon detection pipeline.
</p>

<h4>
  <a href="https://github.com/PGADS-Dev/Sentinel-Dual-Control-System">
    Sentinel Dual-Control System
  </a>
</h4>

<p>
  <code>C</code>
  <code>deterministic FSM</code>
  <code>fault handling</code>
  <code>active development</code>
</p>

<p>
Embedded reliability demonstrator currently focused on a portable behavioral core with explicit
<code>INIT</code>, <code>NOMINAL</code>, <code>DEGRADED</code> and <code>FAIL_SAFE</code> states,
defined fault events, unit tests and reproducible transition validation.
</p>

<p>
STM32 integration, CAN communication, Raspberry Pi supervision and hardware fault injection are the next implementation stages and are not presented here as completed work.
</p>

<h4>
  <a href="https://github.com/PGADS-Dev/BlackBoxWhisperer">
    BlackBoxWhisperer
  </a>
</h4>

<p>
  <code>TypeScript</code>
  <code>static analysis</code>
  <code>deterministic pipeline</code>
  <code>V1 engine</code>
</p>

<p>
Deterministic static-analysis engine for unfamiliar legacy codebases.
The current V1 includes a functional COBOL adapter and produces reproducible indexes, call graphs, metrics,
risk artifacts and technical reports with hashed inputs and outputs.
</p>

<h4 align="left">Supporting engineering work</h4>

<ul>
  <li>
    <b>
      <a href="https://github.com/avainfo/cpp-linux-debugging-labs">
        C++ Linux Debugging Labs
      </a>
    </b>
    · practical failure-investigation exercises using GDB, Valgrind, sanitizers and Linux diagnostics
  </li>
  <li>
    <b>
      <a href="https://github.com/avainfo/linux_config">
        linux_config
      </a>
    </b>
    · reproducible Linux workstation setup for native development, debugging and diagnostic workflows
  </li>
</ul>

---

<h3 align="left">Failure Triage Sprint</h3>

<p align="left">
I provide short, fixed-scope technical interventions for Linux and embedded teams dealing with crashes,
freezes, watchdog resets, unstable startup, communication failures or difficult-to-explain runtime behavior.
</p>

<p align="left">
The objective is not to promise an instant root cause. It is to reduce uncertainty quickly,
separate facts from assumptions, prioritize credible failure hypotheses, identify missing evidence
and leave the team with a concrete technical next-step plan.
</p>

<ul>
  <li><b>Light sprint:</b> 2 to 3 days</li>
  <li><b>Standard sprint:</b> 4 to 5 days</li>
  <li><b>Typical outputs:</b> technical triage, prioritized hypotheses, evidence gaps, instrumentation recommendations and written next steps</li>
</ul>

---

<h3 align="left">Consulting & availability</h3>

<p align="left">
I am primarily available for remote B2B, contractor and consulting work involving C/C++ Linux engineering,
systems debugging, Embedded Linux, reliability work and technical rescue.
</p>

<p align="left">
I also provide technical training and developer coaching around C, C++, Linux, Git, Docker and practical debugging methodology.
</p>

<p align="left">
Based in <b>Porto, Portugal</b>, working with European and international teams.
Short on-site interventions are possible when hardware access, commissioning or failure reproduction makes them useful.
</p>

<p align="left">
I am also selectively open to systems software roles with strong technical depth.
</p>

---

<h3 align="left">Contact</h3>

<div align="center">
  <a href="https://www.linkedin.com/in/antonin-do-souto/">
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" height="32" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:antonindosouto@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" height="32" alt="Email" />
  </a>
  &nbsp;
  <a href="https://www.malt.fr/profile/antonindosouto">
    <img src="https://img.shields.io/badge/Malt-FC5656?style=for-the-badge" height="32" alt="Malt" />
  </a>
  &nbsp;
  <a href="https://www.codementor.io/@antonindosouto?refer=badge">
    <img src="https://img.shields.io/static/v1?label=Book%20a%20session&message=Codementor&logo=codementor&color=003648&style=for-the-badge" height="32" alt="Book a session on Codementor" />
  </a>
</div>

---

<h3 align="left">GitHub activity</h3>

<div align="center">
  <img src="./profile/stats.svg" width="420" alt="GitHub stats" />
  <img src="./profile/top-langs.svg" width="320" alt="Repository language distribution" />
</div>

<br>

<div align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="./profile/activity-dark.svg" />
    <source media="(prefers-color-scheme: light)" srcset="./profile/activity-light.svg" />
    <img src="./profile/activity-light.svg" width="100%" alt="GitHub activity graph" />
  </picture>
</div>

<br clear="both">

<picture>
  <source
    media="(prefers-color-scheme: dark)"
    srcset="https://raw.githubusercontent.com/avainfo/avainfo/output/snake-dark.svg"
  />
  <source
    media="(prefers-color-scheme: light)"
    srcset="https://raw.githubusercontent.com/avainfo/avainfo/output/snake-light.svg"
  />
  <img
    src="https://raw.githubusercontent.com/avainfo/avainfo/output/snake-light.svg"
    width="100%"
    alt="GitHub contribution snake"
  />
</picture>
