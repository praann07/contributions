# Contributions Log

Tracking open-source contributions for job-hunt visibility.

## Week 1 (2026-08-05)
- **excalidraw/excalidraw** — added `CODE_OF_CONDUCT.md` (Contributor Covenant v2.1). PR: https://github.com/excalidraw/excalidraw/pull/11831
- **excalidraw/excalidraw** — opened issue #11832 requesting a `SECURITY.md`.
- **mochajs/mocha** — code review on PR #6200 (afterEach-before-retry error reporting).
- **mochajs/mocha** — code review on PR #6193 (package entry-point / exports -> main).

## Update (2026-11-04)
Merged:
- **microsoft/PyRIT** #3154: request timeout for remote dataset downloads. https://github.com/microsoft/PyRIT/pull/3154
- **NVIDIA/NeMo-Agent-Toolkit** #2443: stop logging the expanded config under `--override` (could expose secrets). https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2443
- **mozilla-ai/otari** #2648: `guardrails validate` warns when a `when_changed` glob matches no file (closes #2007). https://github.com/mozilla-ai/otari/pull/2648

Open (as of 2026-11-04):
- **EleutherAI/delphi** #196: keep `n_train` examples when `train_type` is `mix`. https://github.com/EleutherAI/delphi/pull/196
- **SylphAI-Inc/AdalFlow** #511: make `append_to_jsonl` safe across threads. https://github.com/SylphAI-Inc/AdalFlow/pull/511
- **arc53/DocsGPT** #3062: read markdown, rst and csv files as UTF-8. https://github.com/arc53/DocsGPT/pull/3062

## Update (2026-11-19)
Merged since the last update:
- **TransformerLensOrg/TransformerLens** #1977: reject negative `temperature` and non-positive `repetition_penalty` in `sample_logits` (merged 2026-11-04). https://github.com/TransformerLensOrg/TransformerLens/pull/1977
- **microsoft/PyRIT** #3799: match `%` and `_` literally in the objective and scenario name filters (merged 2026-11-09). https://github.com/microsoft/PyRIT/pull/3799

Five merged in total (PyRIT #3154 and #3799, NeMo Agent Toolkit #2443, otari #2648, TransformerLens #1977).

Still open: EleutherAI/delphi #196, SylphAI-Inc/AdalFlow #511, arc53/DocsGPT #3062, excalidraw/excalidraw #11831 and #11833.

## Update (2026-11-19, later)
Merged: **arc53/DocsGPT** #3062: read markdown, rst and csv files as UTF-8, honoring the caller's decoding-error policy (merged 2026-11-19). https://github.com/arc53/DocsGPT/pull/3062
Six merged in total. Still open: EleutherAI/delphi #196, SylphAI-Inc/AdalFlow #511, excalidraw/excalidraw #11831 and #11833.
