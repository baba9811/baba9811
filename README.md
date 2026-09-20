# Kyubum Hwang

AI Research Engineer at Infobank. I build AI services and contribute to open-source projects.

M.S. in Applied Artificial Intelligence, Sungkyunkwan University.

[Research Notes](https://baba9811.github.io/) · [English paper reviews](https://baba9811.github.io/en/blog/) · [Publications](https://scholar.google.com/citations?user=fzAb1AIAAAAJ) · [LinkedIn](https://www.linkedin.com/in/kyubum-hwang-5a04b2212/)

<!-- BEGIN OPEN SOURCE CONTRIBUTIONS -->
## Open Source Contributions

- **[agno-agi/agno](https://github.com/agno-agi/agno)**: Fixed silent CSV row loss during asynchronous pagination by applying header skipping only to the first page. ([PR #9995](https://github.com/agno-agi/agno/pull/9995)) Identified silent text loss in grouped PowerPoint shapes, traced the cause to missing traversal of nested shapes, and provided a minimal reproduction used to verify the upstream fix. ([Issue #9999](https://github.com/agno-agi/agno/issues/9999))
- **[edwardkim/rhwp](https://github.com/edwardkim/rhwp)**: Fixed keyboard activation failures in text and highlight color controls by separating selection-preserving mousedown handling from standard click activation. ([PR #6786](https://github.com/edwardkim/rhwp/pull/6786))
- **[google/adk-docs](https://github.com/google/adk-docs)**: Clarified that Python session-history filters limit the loaded event view while preserving stored history when new events are appended. ([PR #2244](https://github.com/google/adk-docs/pull/2244))
- **[google/adk-python](https://github.com/google/adk-python)**: Fixed empty-text artifacts being treated as missing by removing an incorrect rejection in the shared in-memory load path. ([PR #7072](https://github.com/google/adk-python/pull/7072)) Fixed file artifact creation timestamps changing on every metadata read by preserving persisted timestamps in the shared conversion helper. ([PR #7113](https://github.com/google/adk-python/pull/7113))
- **[i-am-bee/beeai-framework](https://github.com/i-am-bee/beeai-framework)**: Fixed incorrect GrepTool search results for leading-hyphen patterns by separating ripgrep options from search arguments. ([PR #1660](https://github.com/i-am-bee/beeai-framework/pull/1660)) Prevented GrepTool from consuming or waiting on host input by isolating ripgrep's stdin with DEVNULL. ([PR #1661](https://github.com/i-am-bee/beeai-framework/pull/1661)) Fixed default file, shell and console I/O failures in new execution contexts by providing local fallbacks when reading ContextVars. ([PR #1662](https://github.com/i-am-bee/beeai-framework/pull/1662))
- **[pandas-dev/pandas](https://github.com/pandas-dev/pandas)**: Fixed empty cells left by hidden indexes and columns in Typst table output by filtering hidden cells while preserving sparse MultiIndex labels. ([PR #68991](https://github.com/pandas-dev/pandas/pull/68991))
- **[ratatui/ratatui](https://github.com/ratatui/ratatui)**: Fixed a BufferDiff rendering bug that left stale background and underline styles on wide Unicode glyphs by clearing trailing cells before repainting. ([PR #2743](https://github.com/ratatui/ratatui/pull/2743))
<!-- END OPEN SOURCE CONTRIBUTIONS -->

## Publications

### Journal Articles

- [What do we want to know from a chatbot? Identifying inquiries among adult survivors of childhood and adolescent cancer in South Korea](https://doi.org/10.1016/j.ejon.2026.103202). *European Journal of Oncology Nursing*, 2026. Co-author.
- [Power engineering domain pretrained language model with natural language processing benchmarks](https://doi.org/10.1016/j.compeleceng.2026.111034). *Computers and Electrical Engineering*, 2026. First author.
- [GPT-empowered question-answer dataset for informative and empathetic support for Korean childhood cancer survivors](https://doi.org/10.1016/j.eswa.2025.129548). *Expert Systems with Applications*, 2026. First author.
- [Korean Generation-based Empathetic Chatbot using Reinforcement Learning](https://doi.org/10.6109/jkiice.2023.27.7.830). *Journal of the Korea Institute of Information and Communication Engineering*, 2023. First author.

### Conference Papers

- [MILD Bot: Multidisciplinary Childhood Cancer Survivor Question-Answering Bot](https://aclanthology.org/2024.emnlp-industry.49/). *EMNLP Industry Track*, 2024. Co-author.
- [Can a Chatbot be Useful in Childhood Cancer Survivorship? Development of a Chatbot for Survivors of Childhood Cancer](https://doi.org/10.1145/3583780.3615234). *CIKM*, 2023. Co-author.

### Conference Abstracts

- [Identifying Inquiries for an Artificial Intelligence-Based Informatic Chatbot Among Young Adult Survivors of Childhood Cancer Using a Topic Modeling Approach](https://sswr.confex.com/sswr/2025/webprogram/Paper55573.html). *SSWR*, 2025. ePoster. Co-author.
- [Motivation and Benefits of Using Artificial Intelligence-Based Chatbots Among Young Adult Survivors of Childhood Cancer](https://onlinelibrary.wiley.com/doi/full/10.1002/pbc.31444#pbc31444-sec-22600). *SIOP*, 2024. Abstract EP677/#736. Co-author.
