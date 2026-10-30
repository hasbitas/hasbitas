# Hi, I'm Hasan Bircan Taş

I'm a second-year Artificial Intelligence and Data Engineering student at Atatürk University, Türkiye.

## What I work on

- AI/ML agents, memory and context, and ways to evaluate their results.
- Computer vision, including object detection in UAV imagery.
- Quantum computing as a side interest.

## Featured projects

| Project | What it does | Tech | Link |
| --- | --- | --- | --- |
| aerial-detection-pipeline | Detects objects in UAV imagery for TEKNOFEST 2026 Aviation AI task 1, estimates motion with camera movement compensation, and checks landing-area suitability, with a demo and CSV output. | Ultralytics YOLO (YOLO26s), optical flow, Gradio | [GitHub](https://github.com/hasbitas/aerial-detection-pipeline) |
| AlloyForge | An AI-assisted alloy design MVP combining a learning agent, thermodynamic screening, and surrogate prediction. | PyTorch PPO, FastAPI, React | [GitHub](https://github.com/hasbitas/alloyforge) |
| YAP-IS | An AI leave planner with ER-load forecasting. | CatBoost, FastAPI | [GitHub](https://github.com/hasbitas/yapay_zeka_destekli_izin_zamanlay-c-_sistemi) |

## Models on Hugging Face

Scores below are validation mAP50 on the project's own split.

| Model | Task | mAP50 |
| --- | --- | --- |
| [yolo26s-aerial-uav](https://huggingface.co/Has1tas/yolo26s-aerial-uav) | Vehicle, person, UAP and UAI detection | 0.899 |
| [yolo12s-aerial-vehicle-person](https://huggingface.co/Has1tas/yolo12s-aerial-vehicle-person) | Vehicle and person detection | 0.885 |
| [yolo26m-landing-zones](https://huggingface.co/Has1tas/yolo26m-landing-zones) | Landing-zone detection and suitability | 0.858 |

## Open-source contributions

- **[AvenoxBeyin](https://github.com/avenoxai/avenoxbeyin)** (open-source Obsidian + Claude Code second-brain system with persistent cross-session memory): I stress-tested v3.12.0 and found 8 issues: 3 high (private-note summaries leaking into recap and daily views, case-insensitive paths bypassing the privacy gate on Windows, broken-YAML private notes treated as public), 3 medium (triage exposing private paths, supersedes cycles retiring notes silently, a `:` in a note name blocking the journal) and 2 low (secret filter missing zero-width and split forms, partial batch ingest not reported). I fixed all eight ([fix branch](https://github.com/hasbitas/avenoxbeyin/tree/fixes/v3.12.0-stress-test)); the fail-closed privacy fix was merged upstream in [PR #525](https://github.com/avenoxai/avenoxbeyin/pull/525).

## Currently

Building a personal agent/evaluation lab — coming soon.

## Tech

Python · PyTorch · Ultralytics YOLO · OpenCV · FastAPI · React/TypeScript · pandas · Git

## Contact

[GitHub](https://github.com/hasbitas) · [Hugging Face](https://huggingface.co/Has1tas)
