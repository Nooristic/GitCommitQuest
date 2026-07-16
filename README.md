# ⚔️ GitCommitQuest 

An interactive, local development tool that parses your project's Git commit history and transforms your real-world coding habits into a retro, downloadable RPG Character Card. Built completely using Python, native log-parsing logic, and a dynamic frontend.

##  The Real-World "Twist"
Instead of building a generic script, GitCommitQuest analyzes local text-based Git logs (`.git/logs/HEAD`) to calculate gaming statistics. It identifies text patterns, calculates timestamps, and determines software engineering profiles based on real repository data.

##  Algorithmic Class Logic
The app dynamically reads your commit strings and assigns attributes:
*  **Attack**: Triggered by structural keywords (`add`, `feat`, `create`).
*  **Defense**: Triggered by stability and troubleshooting keywords (`fix`, `bug`, `patch`).
*  **Speed**: Triggered by optimisation efforts (`clean`, `refactor`, `optimize`).
*  **Dark Magic**: Triggered by temporal logic (any commit recorded between 11:00 PM and 5:00 AM).

###  Character Archetypes Generated:
*  **Night-Owl Necromancer**: Massive dark magic stats from late-night sprints.
*  **Code Berserker**: Dominated by rapid feature expansions and feature additions.
*  **Bug Paladin**: High defense marks earned from resolving systemic bugs and issues.
*  **Agile Rogue**: Heavy speed ratings gained from extensive refactoring and cleaning.

### Tech Stack
* **Backend Engine**: Python 3 (Native File Processing, String-parsing Matrix, Datetime calculation)
* **Web UI Framework**: Flask (Request Routing & Context Rendering)
* **Frontend Layer**: HTML5 Canvas, Tailwind CSS Core, Google Fonts (Retro Monospace)
* **Asset Generation**: `html2canvas` CDN integration for instant client-side image rendering

---

