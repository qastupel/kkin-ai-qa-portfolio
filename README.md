# QA Portfolio: Web Application Testing for KernelKin (kkin.ai)
## 1. Project Description
* **Test Object:** Web application kkin.ai
* **Application Type:** SaaS / AI-driven web platform.
* **Business Logic (based on exploratory analysis):** The platform is designed for creating, storing, and organizing personal and family memories (digital heritage), as well as interacting with personal AI agents based on the uploaded context.
* **Testing Context and Features:**
Testing is conducted using the Black-Box Testing method in the complete absence of project documentation and technical specifications. System requirements were reverse-engineered based on user scenarios (Reverse Engineering) and general quality standards for web applications (UI/UX, security, performance).
## 2. Testing Goals and Objectives
* **Main Goal:** Evaluate the current quality of the product, verify the functionality of critical user scenarios (Critical Path), and identify defects affecting user experience and system stability.
* **Key Objectives:**
1. **System Decomposition:** Study the application structure and create a functionality map (Mind Map).
2. **Test Design:** Develop test documentation (checklists and test cases) covering positive and negative scenarios.
3. **Functional Verification:** Test registration/authorization modules, onboarding, media content uploading, and AI interaction.
4. **UI/UX and Cross-Browser Testing:** Evaluate layout correctness and interface responsiveness across various screen resolutions (Desktop / Mobile).
5. **Basic Non-Functional Analysis:** Conduct a preliminary performance audit (loading speed) and basic security checks (field validation, session management).
6. **Defect Documentation:** Record all identified discrepancies as structured bug reports and generate a final testing report.
## 3. Repository Structure and Artifacts List
This repository contains all artifacts created during the manual testing of the project:
| Folder / File | Description of Artifact |	Status |
| --- | --- | --- |
|[README.md](README.md)|	General project description, testing goals, and repository navigation.|	✅ Ready|
| [MindMap](/MindMap/MindMap.png)	| Application mind map (MindMap.png / .xmind) reflecting module decomposition and user paths.	| ✅ Ready |
| [TestDesign](/TestDesign/)	| Checklists for smoke and regression testing, as well as detailed test cases in .md and .xlsx formats. |	🔄 In Progress |
| [BugReports](/BugReports/) |	Registry of found defects and detailed bug reports (Summary, STR, ER/AR, Severity/Priority, console logs, and screenshots). |	⏳ Pending |
| [NonFunctional](/NonFunctional/) |	Performance measurement results (Google Lighthouse reports) and a basic security check checklist.	| ⏳ Pending |
| [TestReport](/TestReport/) |	Final Test Summary Report with metrics, bug statistics, and general product quality conclusions.	| ⏳ Pending |
## 4. Test Environment
* **OS:** macOS 27.0.1 (26A434)
* **Browsers:** Google Chrome 157.0.8103.38 (primary), Safari 27.0.1
* **Tools:** Chrome DevTools (Network, Console, Device Toolbar, Lighthouse), XMind / Draw.io, screenshot tools (Lightshot / Monosnap).

<img width="1719" height="1018" alt="kernell" src="https://github.com/user-attachments/assets/da793226-054f-4ff1-b5cb-5eb033a7563f" />

