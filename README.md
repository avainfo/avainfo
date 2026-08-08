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
  <img src="./assets/icons/c.svg" height="42" alt="C" />
  <img width="18" />
  <img src="./assets/icons/cpp.svg" height="42" alt="C++" />
  <img width="18" />
  <img src="./assets/icons/Rust.svg" height="42" alt="Rust" />
  <img width="18" />
  <img src="./assets/icons/linux.svg" height="42" alt="Linux" />
  <img width="18" />
  <img src="./assets/icons/docker.svg" height="42" alt="Docker" />
  <img width="18" />
  <img src="./assets/icons/git.svg" height="42" alt="Git" />
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

<br>

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

<br>

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

<br>

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
    <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHdpZHRoPSIyMDAiIGhlaWdodD0iMjAwIiB2aWV3Qm94PSIwIDAgMzgyIDM4MiI+CiAgPHBhdGggZmlsbD0iIzAwNzdiNyIgZD0iTTM0Ny40NDUgMEgzNC41NTVDMTUuNDcxIDAgMCAxNS40NzEgMCAzNC41NTV2MzEyLjg4OUMwIDM2Ni41MjkgMTUuNDcxIDM4MiAzNC41NTUgMzgyaDMxMi44ODlDMzY2LjUyOSAzODIgMzgyIDM2Ni41MjkgMzgyIDM0Ny40NDRWMzQuNTU1QzM4MiAxNS40NzEgMzY2LjUyOSAwIDM0Ny40NDUgMCIvPgogIDxwYXRoIGZpbGw9IiNmZmYiIGQ9Ik04Ni43NDggMTIzLjQzMmMtMjIuNDU5IDAtNDAuNjY2LTE4LjIwNy00MC42NjYtNDAuNjY2UzY0LjI4OSA0Mi4xIDg2Ljc0OCA0Mi4xczQwLjY2NiAxOC4yMDcgNDAuNjY2IDQwLjY2Ni0xOC4yMDYgNDAuNjY2LTQwLjY2NiA0MC42NjZNMTE4LjIwNyAzMjkuODQ0YzAgNS41NTQtNC41MDIgMTAuMDU2LTEwLjA1NiAxMC4wNTZINjUuMzQ1Yy01LjU1NCAwLTEwLjA1Ni00LjUwMi0xMC4wNTYtMTAuMDU2VjE1MC40MDNjMC01LjU1NCA0LjUwMi0xMC4wNTYgMTAuMDU2LTEwLjA1Nmg0Mi44MDZjNS41NTQgMCAxMC4wNTYgNC41MDIgMTAuMDU2IDEwLjA1NnpNMzQxLjkxIDMzMC42NTRjMCA1LjEwNi00LjE0IDkuMjQ2LTkuMjQ2IDkuMjQ2SDI4Ni43M2MtNS4xMDYgMC05LjI0Ni00LjE0LTkuMjQ2LTkuMjQ2di04NC4xNjhjMC0xMi41NTYgMy42ODMtNTUuMDIxLTMyLjgxMy01NS4wMjEtMjguMzA5IDAtMzQuMDUxIDI5LjA2Ni0zNS4yMDQgNDIuMTF2OTcuMDc5YzAgNS4xMDYtNC4xMzkgOS4yNDYtOS4yNDYgOS4yNDZoLTQ0LjQyNmMtNS4xMDYgMC05LjI0Ni00LjE0LTkuMjQ2LTkuMjQ2VjE0OS41OTNjMC01LjEwNiA0LjE0LTkuMjQ2IDkuMjQ2LTkuMjQ2aDQ0LjQyNmM1LjEwNiAwIDkuMjQ2IDQuMTQgOS4yNDYgOS4yNDZ2MTUuNjU1YzEwLjQ5Ny0xNS43NTMgMjYuMDk3LTI3LjkxMiA1OS4zMTItMjcuOTEyIDczLjU1MiAwIDczLjEzMSA2OC43MTYgNzMuMTMxIDEwNi40NzJ6Ii8+Cjwvc3ZnPg==" height="32" alt="LinkedIn" />
  </a>
  &nbsp;
  <a href="mailto:antonindosouto@gmail.com">
    <img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" height="32" alt="Email" />
  </a>
  &nbsp;
  <a href="https://www.malt.fr/profile/antonindosouto">
    <img src="https://img.shields.io/badge/Malt-FC5656?style=for-the-badge&logo=data:image/svg%2bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIGFyaWEtbGFiZWw9Ik1hbHQiIHJvbGU9ImltZyIgdmlld0JveD0iMCAwIDUxMiA1MTIiIGZpbGw9IiMwMDAwMDAiPjxnIGlkPSJTVkdSZXBvX2JnQ2FycmllciIgc3Ryb2tlLXdpZHRoPSIwIj48L2c+PGcgaWQ9IlNWR1JlcG9fdHJhY2VyQ2FycmllciIgc3Ryb2tlLWxpbmVjYXA9InJvdW5kIiBzdHJva2UtbGluZWpvaW49InJvdW5kIj48L2c+PGcgaWQ9IlNWR1JlcG9faWNvbkNhcnJpZXIiPjxyZWN0IHdpZHRoPSI1MTIiIGhlaWdodD0iNTEyIiByeD0iMTUlIiBmaWxsPSIjZmM1NjU2Ij48L3JlY3Q+IDxwYXRoIGZpbGw9IiNmZmZmZmYiIGQ9Im00MDguNCAxMDMuOGMtMzIuNS0zMi40LTY3LjEtMTEuNC04OC44IDEwLjJMMTE0LjggMzE4LjhjLTIxLjcgMjEuNy00NC40IDU0LjctMTAuMiA4OC44YzM0LjEgMzQuMSA2NyAxMS40IDg4LjctMTAuM2wyMDQuOC0yMDQuOGMyMS43LTIxLjYgNDIuNy01Ni4zIDEwLjMtODguN3ptLTE5NS43LTguNCA0My40IDQzLjQgNDQuMS00NC4yYzMtMyA2LTUuOCA5LjEtOC40Yy00LjYtMjMuMy0xNy45LTQ0LjQtNTMuMy00NC40Yy0zNS40IDAtNDguNyAyMS4yLTUzLjIgNDQuNWMzLjMgMi45IDYuNiA1LjggOS45IDkuMXptODcuNSAzMjIuMS00NC4xLTQ0LjEtNDMuNCA0My4zYy0zLjMgMy4zLTYuNSA2LjQtOS44IDkuMmM1IDIzLjggMTkgNDUuNSA1My4xIDQ1LjVjMzQuMiAwIDQ4LjMtMjEuOSA1My4yLTQ1LjdjLTMtMi42LTYtNS4yLTktOC4yem0tMTA1LjktMjE3aC04My42Yy0zMC43IDAtNzAgOS43LTcwIDU1LjVjMCAzNC4zIDIxLjkgNDguMyA0NS44IDUzLjJjMi44LTMuMiAxMDcuOC0xMDguNyAxMDcuOC0xMDguN3ptMjMxLjUgMi4zYy0yLjYgMy0xMDcuOSAxMDguOC0xMDcuOSAxMDguOGg4Mi40YzMwLjcgMCA3MC03LjMgNzAtNTUuNmMwLTM1LjMtMjEuMS00OC42LTQ0LjUtNTMuMnptLTIwNC4xLTI5LjcgMTQuOS0xNC45LTQzLjMtNDMuNGMtMjEuNy0yMS43LTU0LjYtNDQuNC04OC44LTEwLjJjLTI1IDI1LTE5LjQgNDkuNC02LjIgNjkuMWM0LjEtLjMgMTIzLjQtLjYgMTIzLjQtLjZ6bTY4LjcgMTY1LjktMTUgMTUgNDQuMiA0NC4xYzIxLjcgMjEuNyA1Ni4zIDQyLjcgODguNyAxMC4zYzI0LjItMjQuMiAxOC43LTQ5LjcgNS4zLTcwYy00LjMuMy0xMjMuMi42LTEyMy4yLjZ6Ij48L3BhdGg+IDwvZz48L3N2Zz4=" height="32" alt="Malt" />
  </a>
  &nbsp;
  <a href="https://www.codementor.io/@antonindosouto?refer=badge">
    <img src="https://img.shields.io/badge/CODEMENTOR-033446?style=for-the-badge&logo=codementor&logoColor=white" height="32" alt="Codementor" &logoSize=auto />
  </a>
</div>

---

<h3 align="left">GitHub activity</h3>

<div align="center">
  <img src="./profile/stats.svg" width="50%" alt="GitHub stats" />
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
