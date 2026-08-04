# Awesome-Online-Exam-Platform

# Similar Projects to Online Exam Platforms

**Online Exam Platforms** enable organizations to create, deliver, proctor, and grade secure online assessments, quizzes, and high-stakes exams. Features typically include question banks, timed tests, remote proctoring, lockdown browsers, analytics, and candidate management. Leading commercial platforms include Mercer Mettl, TestGorilla, Exam.net, Digiexam, ExamSoft, Honorlock, ProctorU, Inspera, Questionmark, and TestReach.

Below is a **curated list** of notable platforms and their open-source equivalents. Open-source options are strong for assessment delivery and basic exam management; advanced AI proctoring and enterprise-scale candidate authentication are less common as pure open-source solutions and are often added via plugins or hybrid approaches.

## 🏢 SaaS / Hosted Platforms

- **[Mercer Mettl](https://mettl.com/)** — Comprehensive online assessment and proctoring platform widely used for hiring, certification, and education.
- **[TestGorilla](https://www.testgorilla.com/)**, **[Exam.net](https://exam.net/)**, **[Digiexam](https://www.digiexam.com/)**, **[ExamSoft](https://examsoft.com/)**, **[Inspera](https://www.inspera.com/)**, **[Questionmark](https://www.questionmark.com/)**, **[TestReach](https://www.testreach.com/)** — Online exam delivery, digital assessment, and secure testing platforms.
- **[Honorlock](https://honorlock.com/)**, **[ProctorU](https://www.proctoru.com/)** (Meazure Learning) — Specialized remote proctoring and exam integrity solutions.

## 🔓 Open-Source Software

### Full Open-Source Assessment & Exam Platforms
- **[Moodle](https://moodle.org/)** — The most widely used open-source LMS, featuring a mature Quiz engine, extensive question types, question banks, and strong community support. Can be hardened for secure exams with **Safe Exam Browser** and proctoring plugins.
- **[TCExam](https://github.com/tecnickcom/tcexam)** — Dedicated open-source Computer-Based Assessment (CBA) system for creating, scheduling, delivering, and reporting on quizzes, tests, and exams. Lightweight, self-hosted, and focused purely on assessment.
- **[TAO Testing](https://www.taotesting.com/)** — Open-source assessment platform with strong support for open standards (especially QTI). Used by educational institutions and testing organizations that need portable, standards-based item banks.
- **[QST](https://github.com/bobb34/QST)** (Quiz/Survey/Test) — Feature-rich open-source multi-tenant assessment platform supporting many question types, scheduling, results, and self-hosting.

### Proctoring & Secure Delivery Components
- Open-source proctoring projects and plugins (including components from Open edX and community tools) that provide webcam monitoring, lockdown browser integration, or basic integrity checks.
- **Safe Exam Browser** (SEB) — Open-source lockdown browser frequently paired with Moodle and other platforms to restrict the testing environment.
- Community and research-oriented open-source proctoring systems that use computer vision for behavior monitoring (often requiring self-hosting and customization).

### Related Open-Source Tools
- Open edX (and its proctoring subsystem) for organizations already in the Open edX ecosystem.
- Smaller open-source exam creators, simulators, and coding-assessment platforms useful for practice tests or technical hiring.

### Typical Open-Source Approach
1. **Core assessment engine** — Moodle Quiz, TCExam, or TAO
2. **Secure delivery** — Safe Exam Browser + network/access controls
3. **Proctoring** — Plugin-based or separate open-source/AI monitoring tools (or hybrid with a commercial proctoring service)
4. **Question management** — Built-in banks + import/export (QTI where supported)
5. **Results & analytics** — Platform reporting + export to external tools

This combination allows institutions and companies to run secure online exams with full data ownership and without per-candidate SaaS fees, while still achieving strong assessment capabilities.

---

**How to contribute**  
Fork this repository, add a new project (with link + short description + category), and open a pull request.  
Prefer actively maintained open-source projects related to online exams, computer-based assessment, proctoring, or secure testing platforms.

**License**  
This list is public domain / CC0. Feel free to copy into your own awesome list or README.

Star the projects you find useful — open exam tools help educators and organizations assess fairly and transparently! 📝
