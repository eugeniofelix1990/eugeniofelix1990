# Eugenio Félix Grijalva

### Systems-Minded SDET & QA Automation Engineer

📍 Hermosillo, Sonora, Mexico · 💼 [LinkedIn](https://www.linkedin.com/in/eugeniofelix) · 🗣️ English C1 · Open to remote international teams

---

## 🚀 About me

> **I find what breaks software before users do.**

I'm a systems-minded SDET and QA automation engineer. I started as a civil engineer managing railway construction projects, and it taught me what I still work by: science is defined by its method, not its subject. Form a hypothesis, design the test, document everything, re-analyze, and never accept anything without verification.

I learn by going to the source: documentation, specs, source code and a carefully chosen shelf of references (see [Engineering Library](#-engineering-library)). I go in with a question, like an explorer, and almost always come out with something I'll need later. That lets me test below the UI: device-level code, APIs and behavior under load.

**What I do**

- Break systems deliberately: fuzzing, fault injection, boundary value analysis, negative testing
- Investigate architectures and inter-layer communication to uncover performance and security risks
- Secure and stress APIs and backends: OWASP Top 10, Burp Suite, Postman
- Run load, stress and spike tests: Apache JMeter, k6, wrk
- Automate where it pays off: Python, Bash, Git, with tests built to plug into CI/CD and focused on high-ROI regressions rather than blind coverage

**How I work**

White-, gray- and black-box testing, chosen by risk. Atomic test design, ISTQB-aligned methodology and a disciplined defect lifecycle. I do my best work where there is room to research, design and test deliberately, hunting the bottlenecks, race conditions and logic flaws that only appear under real conditions.

---

## 🛠️ Technical Skills

| Area | Tools & Concepts |
|---|---|
| **Testing & Quality** | SDET, White/Gray/Black-box Testing, ISTQB Methodology, Boundary Value Analysis (BVA), Equivalence Partitioning (EP), Fuzz Testing, Fault Injection, Negative & Misuse-Case Testing, BDD (Behavior-Driven Development), Cucumber, Gherkin, Bug Lifecycle, Accessibility (A11y) Testing |
| **Performance & Security** | Apache JMeter, k6, wrk, Load / Stress / Spike Testing, Burp Suite, OWASP Top 10, API Security & Robustness |
| **Automation & Tools** | Playwright, Pytest, Selenium, Postman, Jira, Xray (Test Management), Git, CI/CD integration |
| **Systems & Low-Level** | C (Raster Filters), CUPS Architecture, ESC/POS Protocols, USB Device Interfacing, Bash, Embedded Concepts, Memory Optimization |
| **Frontend & Architecture** | Advanced CSS, Web Components Overrides, Layout Contraction, `::after` Pseudo-element Injection, SVG Masking, Separation of Concerns (SoC) |
| **Languages** | Python, C, Bash, Java, Kotlin, C++ (Language-agnostic / Project-driven approach) |
| **Environments** | Linux (Mint / Ubuntu / Debian), multi-workstation setups, comfortable moving between environments and stacks that involve other languages |

---

## 📂 Projects

### 🎯 [Urban Routes QA & API Portfolio](https://github.com/eugeniofelix1990/qa-urban-routes-portfolio)
`Python` `Postman` `Selenium` `Jira`
- Atomic test cases designed with ISTQB techniques: Boundary Value Analysis and Equivalence Partitioning.
- Automated API test frameworks in Python with robust validations and automated Jira bug report generation.

### 🔌 [BY P800 Linux Driver & Diagnostic Suite](https://github.com/eugeniofelix1990/by-p800-linux-driver)
`C` `CUPS` `Python` `Bash`
- Open-source native Linux driver for the BY P800 thermal printer, bridging the gap left by Windows-only official drivers.
- C raster filter (`rastertop800.c`) with color space conversion and Floyd-Steinberg error-diffusion dithering.
- Python engineering suite (`p800_probe.py`, `p800_width_test.py`, `p800print.py`) for protocol testing, width calibration, and buffer overflow prevention.
- Automated installation and CUPS integration (`install.sh`): dependency checks, custom PPDs, USB port auto-discovery.

### 🎨 [Advanced CSS Web Component Overrides](https://github.com/eugeniofelix1990/web-component-contraction)
`CSS` `Web Components` `Playwright` `Pytest`
- CSS layout contraction pattern to re-label encapsulated third-party Web Components without layout interference ("phantom width").
- Custom SVG data-URI masks via `::after` pseudo-elements, so icons and labels inherit text colors with no external network requests.
- E2E suite with Playwright and Pytest validating layout constraints, bounding boxes, and A11y name computations in Chromium.

### 🎮 GameMind Core
`Python` `OpenCV`
- Automated video pipeline to classify, trim, and render gameplay recordings, with strict memory management.

### 🛒 We Agree E-commerce Platform
`Python` `Django` `Bootstrap` `Android Studio`
- Backend architecture for a corporate and e-commerce platform, applying SoC and integration testing for endpoint robustness.

---

## 📚 Engineering Library

Documentation, specs and books are how I learn. This is the shelf I have worked through, or am still working through, and keep returning to when I test below the UI.

| Area | References |
|---|---|
| **Testing & Quality Engineering** | *How Google Tests Software* (Whittaker, Arbon, Carollo) · *Python Testing with Pytest* (Brian Okken) |
| **Advanced Automation & Programming** | *Fluent Python* (Luciano Ramalho) · *Expert C Programming: Deep C Secrets* (Peter van der Linden) · *Programming: Principles and Practice Using C++* (Bjarne Stroustrup) · *Automate the Boring Stuff with Python* (Al Sweigart) |
| **Software Architecture & Reliability** | *Designing Data-Intensive Applications* (Martin Kleppmann) · *The Phoenix Project* (Gene Kim, Kevin Behr) |
| **API Security & Web App Testing** | *The Web Application Hacker's Handbook* (Dafydd Stuttard, Marcus Pinto) · OWASP Top 10 Technical Documentation |
| **Performance & Scalability** | *The Art of Application Performance Testing* (Ian Molyneaux) · *Wireshark Network Analysis* (Laura Chappell) |
| **Linux Kernel & System Internals** | *Linux Device Drivers, 3rd Ed.* (Corbet, Rubini, Kroah-Hartman) · *Linux Internals* (Anil Pugalia, SysPlay) · UNSW Linux Internals lecture notes · Linux Documentation Project · Yocto Project, U-Boot and Device Trees (DTS/DTB) |
| **Embedded Systems & Hardware Security** | *Making Embedded Systems* (Elecia White) · *Programming Embedded Systems* (Michael Barr) · *The Hardware Hacker* (Andrew "bunnie" Huang) · *Practical Hardware Pentesting* (Jasper van Woudenberg) · *Classic Game Programming on the NES* · *6502 Assembly Language Programming* |

<details>
<summary>Full reading list</summary>

**Testing & Quality Engineering**
- How Google Tests Software, James A. Whittaker, Jason Arbon & Jeff Carollo
- Python Testing with Pytest, Brian Okken

**Advanced Automation & Programming**
- Fluent Python, Luciano Ramalho
- Expert C Programming: Deep C Secrets, Peter van der Linden
- Head First C, David Griffiths & Dawn Griffiths
- Programming: Principles and Practice Using C++, Bjarne Stroustrup
- C Programming Absolute Beginner's Guide, Greg Perry & Dean Miller
- Automate the Boring Stuff with Python, Al Sweigart

**Software Architecture & Reliability**
- Designing Data-Intensive Applications, Martin Kleppmann
- The Phoenix Project, Gene Kim & Kevin Behr

**API Security & Web App Testing**
- The Web Application Hacker's Handbook, Dafydd Stuttard & Marcus Pinto
- OWASP Top 10 Technical Documentation

**Performance & Scalability**
- The Art of Application Performance Testing, Ian Moline
- Wireshark Network Analysis: The Official Wireshark Certified Network Analyst Study Guide, Laura Chappell

**Linux Kernel & System Internals**
- Linux Device Drivers (3rd Edition), Jonathan Corbet, Alessandro Rubini & Greg Kroah-Hartman
- Linux Internals Course Notes (system operations, boot process, kernel library)
- UNSW Linux Internals Lecture Notes, University of New South Wales
- Linux Kernel Internals, Linux Documentation Project & Addison-Wesley
- Linux Internals, Anil Pugalia (SysPlay)
- Yocto Project Documentation, U-Boot, and Device Trees (DTS/DTB)

**Embedded Systems, Hardware Hacking & Retro Architecture**
- Making Embedded Systems: Design Patterns for Great Software, Elecia White
- Programming Embedded Systems: With C and GNU Development Tools, Michael Barr
- The Hardware Hacker, Andrew "bunnie" Huang
- Practical Hardware Pentesting, Jasper van Woudenberg
- Classic Game Programming on the NES: Make Your Own Retro Video Game
- 6502 Assembly Language Programming

</details>

---

## 🏗️ Previous Career: Civil Engineering & Project Management

- **Lead Construction Supervision Engineer**, CORDINA (Coordinación Técnico Administrativa de Obras), Grupo Sacmag de México. Matías Romero, Oaxaca · 2023 – Present. Led the supervision team (5 field engineers and 1 topographic engineer) for the Main Operations Center of Line Z, Interoceanic Corridor of the Isthmus of Tehuantepec.
- **Lead Railway Construction Supervisor**, ADDIPSA. Mexicali, Baja California · 2022 – 2023. Supervised construction of railway turnouts in a Ferromex operations yard and reported schedule metrics.

---

## 🎓 Education & Certifications

- **B.Sc. in Civil Engineering**, Instituto Tecnológico de Sonora (ITSON)
- **Software QA Engineering Certification Program (SDET Track)**, TripleTen: Automation, API Testing, and Quality Assurance

## 🗣️ Languages

Spanish: Native · English: C1 (Advanced)
