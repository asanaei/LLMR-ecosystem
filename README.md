# The LLMR Ecosystem

Landing page for the LLMR family of R packages -- R tools for model-assisted
research.

Live at **https://asanaei.github.io/LLMR-ecosystem/** (plain static HTML,
served by GitHub Pages from this branch).

| Package | What it does | Status |
|---|---|---|
| [LLMR](https://github.com/asanaei/LLMR) | Common provider interface | CRAN |
| [LLMRagent](https://github.com/asanaei/LLMRagent) | Governed agents, multi-agent designs, and experiments | GitHub; CRAN submission imminent |
| [LLMRcontent](https://github.com/asanaei/LLMRcontent) | Content analysis: codebook coding with sealed validation, robustness audits, and replication archives | GitHub; CRAN submission imminent |
| [LLMRpanel](https://github.com/asanaei/LLMRpanel) | Benchmarked Likert, choice, open-response, and conjoint instruments for persona panels (with a built-in GUI) | GitHub; CRAN submission imminent |
| [FocusGroup](https://github.com/asanaei/FocusGroup) | Focus-group simulation with LLM agents (with a built-in GUI) | GitHub; CRAN submission imminent |
| [LLMR.shiny](https://github.com/asanaei/LLMR.shiny) | Shared Shiny infrastructure that ships with the family's GUI packages and is not used directly | CRAN |

## Point-and-click

Three packages ship a Shiny front end, all built on `LLMR.shiny`:

- `LLMRcontent::run_content_studio()` -- content analysis (codebook, gold set, coding tournament, validation report).
- `LLMRpanel::run_panel_studio()` -- persona-panel surveys (Likert and choice items, benchmark comparison).
- `FocusGroup::run_focus_studio()` -- focus groups (run a session, analyze a transcript, or run a continuation experiment).
