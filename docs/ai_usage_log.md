# AI-usage log



Tool | What it was used for | How it was verified |
|---|---|---|---|---|
(Claude Opus 5.5) | Took help and advice for implementation: packaging the code, software engineering, choosing the best dataset for the study area, FastAPI service, web UI, user-study tooling, tests. | Test suite (`python -m pytest`): every search compared against exact optima (network reference and backward Dijkstra), Focal bound checked with an adversarial guide, `h_adm` admissibility/consistency checked on every edge; full pipeline run on the real graph.
