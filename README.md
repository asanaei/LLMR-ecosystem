# The LLMR Ecosystem

Landing page for the LLMR family of R packages -- LLM tooling for research,
with the methodology built in.

Live at **https://asanaei.github.io/LLMR-ecosystem/** (plain static HTML,
served by GitHub Pages from this branch).

| Package | What it does |
|---|---|
| [LLMR](https://github.com/asanaei/LLMR) | Unified provider layer (CRAN) |
| [LLMRAgent](https://github.com/asanaei/LLMRAgent) | Agents, multi-agent designs, experiments |
| [LLMRcontent](https://github.com/asanaei/LLMRcontent) | Content analysis: codebook coding with sealed validation, robustness audits, and replication archives |
| [LLMRpanel](https://github.com/asanaei/LLMRpanel) | Calibrated silicon samples (with a built-in GUI) |
| [FocusGroup](https://github.com/asanaei/FocusGroup) | Focus-group simulation with LLM agents (with a built-in GUI) |
| [LLMR.shiny](https://github.com/asanaei/LLMR.shiny) | Shared Shiny substrate for the family's GUIs |

## Point-and-click

Three packages ship a Shiny front end, all built on `LLMR.shiny`:

- `LLMRcontent::run_content_studio()` -- content analysis (codebook, gold set, coding tournament, validation report).
- `LLMRpanel::run_panel_studio()` -- silicon surveys (persona panels, Likert and choice items, calibration).
- `FocusGroup::run_focus_studio()` -- focus groups (run a session, analyze a transcript, or run a continuation experiment).
