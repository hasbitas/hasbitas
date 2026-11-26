# Hi, I'm Bircan Taş

I'm a second-year Artificial Intelligence and Data Engineering student at Atatürk University, Türkiye.

## What I work on

- AI/ML agents, memory and context, and ways to evaluate their results.
- Computer vision, including object detection in UAV imagery.
- Quantum computing as a side interest.

## Featured projects

| Project | What it does | Tech | Link |
| --- | --- | --- | --- |
| aerial-detection-pipeline | Detects vehicles, people and landing areas in UAV imagery, estimates motion with camera movement compensation, and checks landing-area suitability, with a demo and CSV output. | Ultralytics YOLO (YOLO26s), optical flow, Gradio | [GitHub](https://github.com/hasbitas/aerial-detection-pipeline) |
| AlloyForge | An AI-assisted alloy design MVP combining a learning agent, thermodynamic screening, and surrogate prediction. | PyTorch PPO, FastAPI, React | [GitHub](https://github.com/hasbitas/alloyforge) |

## Agent tooling

Small, dependency-free Python tools I built for my own AI-agent workflow and then split out of my private setup. Each one runs on its own; docs are in Turkish with an English summary.

| Project | What it does | Link |
| --- | --- | --- |
| nobet | Hard gate for sub-agent work: file ownership, untouchable tests, fresh "done" evidence, secret-free subprocesses; scans the work tree and git history for personal data. | [GitHub](https://github.com/hasbitas/nobet) |
| hatir | Semantic search (embedding + lexical RRF) and retrieval evaluation for a markdown note vault: hit@k, MRR, negative sets, note quality report. | [GitHub](https://github.com/hasbitas/hatir) |
| anlik | Claude Code `PreToolUse` hook that shows a rule right when the agent is about to run the related command, not at session start. | [GitHub](https://github.com/hasbitas/anlik) |
| serit | Git discipline for parallel agent sessions on one repo: protected main, lane branches, commit only your own files, merge and push gates. | [GitHub](https://github.com/hasbitas/serit) |
| vaka | Turns real agent mistakes into behavioral eval cases: case format, reference/negative/empty validation, capability and regression suites. | [GitHub](https://github.com/hasbitas/vaka) |
| teslim | Pre-publish check before a repo goes public (noreply identity, full-history personal data and secret scan, CI), plus a hook that blocks publishing without a valid receipt. | [GitHub](https://github.com/hasbitas/teslim) |
| beceri | Toolkit for writing AI-agent skills (SKILL.md): validator with flexible and strict profiles, scaffolding from templates, two ready skills, and a 75-task coding benchmark with integrity checks. | [GitHub](https://github.com/hasbitas/beceri) |

## Models on Hugging Face

Scores below are validation mAP50 on the project's own split.

| Model | Task | mAP50 |
| --- | --- | --- |
| [yolo26s-aerial-uav](https://huggingface.co/1at33/yolo26s-aerial-uav) | Vehicle, person, UAP and UAI detection | 0.899 |
| [yolo12s-aerial-vehicle-person](https://huggingface.co/1at33/yolo12s-aerial-vehicle-person) | Vehicle and person detection | 0.885 |
| [yolo26m-landing-zones](https://huggingface.co/1at33/yolo26m-landing-zones) | Landing-zone detection and suitability | 0.858 |

## Open-source contributions

- **[AvenoxBeyin](https://github.com/avenoxai/avenoxbeyin)** (open-source Obsidian + Claude Code second-brain system with persistent cross-session memory): I stress-tested v3.12.0 and found 8 issues: 3 high (private-note summaries leaking into recap and daily views, case-insensitive paths bypassing the privacy gate on Windows, broken-YAML private notes treated as public), 3 medium (triage exposing private paths, supersedes cycles retiring notes silently, a `:` in a note name blocking the journal) and 2 low (secret filter missing zero-width and split forms, partial batch ingest not reported). I fixed all eight ([fix branch](https://github.com/hasbitas/avenoxbeyin/tree/fixes/v3.12.0-stress-test)); the fail-closed privacy fix was merged upstream in [PR #525](https://github.com/avenoxai/avenoxbeyin/pull/525).



## Tech

Python · PyTorch · Ultralytics YOLO · OpenCV · FastAPI · React/TypeScript · pandas · Git

## Contact

[LinkedIn](https://www.linkedin.com/in/bircan-tas) · [GitHub](https://github.com/hasbitas) · [Hugging Face](https://huggingface.co/1at33)
