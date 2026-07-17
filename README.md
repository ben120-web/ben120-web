# Ben Russell

ML and systems engineer with a Physics BSc and Electronics Engineering MSc. I
build reliable machine-learning systems from data contracts and algorithm
design through reproducible training, deployment, observability and CI/CD.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Ben_Russell-0A66C2?logo=linkedin)](https://www.linkedin.com/in/ben-russell-384999189/)
[![MSc pipeline](https://github.com/ben120-web/Masters/actions/workflows/ci.yml/badge.svg)](https://github.com/ben120-web/Masters/actions/workflows/ci.yml)
[![Coding agent](https://github.com/ben120-web/Back-End-Development-Course/actions/workflows/ci.yml/badge.svg)](https://github.com/ben120-web/Back-End-Development-Course/actions/workflows/ci.yml)

## Selected engineering work

| Project | Problem and engineering evidence | Stack | Live evidence |
| --- | --- | --- | --- |
| [ECG motion-artefact denoising](https://github.com/ben120-web/Masters) | End-to-end biomedical ML system with subject-grouped data, validation contracts, DVC lineage, tracked experiments, tested inference API, model governance and container delivery. | Python, PyTorch, DVC, MLflow, TensorBoard, FastAPI, Docker, GitHub Actions | [v1.0.0](https://github.com/ben120-web/Masters/releases/tag/v1.0.0) · [CI](https://github.com/ben120-web/Masters/actions/workflows/ci.yml) · [Space](https://huggingface.co/spaces/ben120/Electrode_Motion_Removal_ECG) · [model card](https://github.com/ben120-web/Masters/blob/main/MODEL_CARD.md) |
| [Workspace-bounded coding agent](https://github.com/ben120-web/Back-End-Development-Course) | Tool-using agent with bounded filesystem access, path/symlink traversal defences, time-limited subprocesses and adversarial boundary tests. | Python, Google Gen AI SDK, pytest, Ruff | [v1.0.0](https://github.com/ben120-web/Back-End-Development-Course/releases/tag/v1.0.0) · [CI](https://github.com/ben120-web/Back-End-Development-Course/actions/workflows/ci.yml) · [security model](https://github.com/ben120-web/Back-End-Development-Course#security-model) |
| [FoodVision deployment](https://huggingface.co/spaces/ben120/Food_Classification) | CPU-hosted transfer-learning demo with a documented input domain and explicit out-of-distribution limitations. | PyTorch, EfficientNet, Gradio, Hugging Face Spaces | [live application](https://huggingface.co/spaces/ben120/Food_Classification) |

## Capability map

| Area | Evidence |
| --- | --- |
| ML engineering and MLOps | Reproducible [`prepare → train → evaluate`](https://github.com/ben120-web/Masters/blob/main/dvc.yaml) DAG, MLflow/TensorBoard tracking, transparent [reference metrics and promotion decision](https://github.com/ben120-web/Masters/tree/main/reports/reference), model/data documentation and versioned release automation. |
| Data engineering | Deterministic data preparation, schema and leakage validation, subject-aware splitting, content-addressed DVC outputs and pipeline lineage in the [ECG pipeline](https://github.com/ben120-web/Masters/tree/main/src/ecg_denoising). |
| Systems and API design | Typed inference contracts, health/readiness endpoints, runtime metrics, non-root containers and a [tool-boundary-focused coding agent](https://github.com/ben120-web/Back-End-Development-Course). |
| Algorithms and scientific computing | Residual 1-D denoising, signal-quality metrics and documented complexity; [DSP](https://github.com/ben120-web/Masters/tree/main/coursework/digital_signal_processing), [Kalman filtering](https://github.com/ben120-web/Masters/tree/main/coursework/kalman_filter) and a tested [finite-horizon MPC](https://github.com/ben120-web/Masters/blob/main/coursework/quadcopter_control/model_predictive_controller.py). |
| Applied deep learning | Computer vision, transfer learning, experiment tracking and deployment work retained transparently in the [PyTorch learning archive](https://github.com/ben120-web/Deep-Learning-Projects.). |
| Delivery and quality | Automated linting, typing, tests, package/container builds, dependency updates, security scanning and tag-driven releases across maintained projects. |

## How I engineer

- Start with the data and failure modes: provenance, leakage boundaries, input
  contracts and measurable baselines before model complexity.
- Keep research reproducible: version code, parameters, data lineage, metrics
  and artifacts independently.
- Treat deployment as part of the model: typed APIs, health checks,
  observability, least privilege and rollback paths are designed up front.
- Report limitations honestly. Educational work is labelled as such, and the
  ECG system is explicitly a research prototype rather than a medical device.

## Portfolio baseline

The `v1.0.0` tags mark the first reviewed portfolio baseline. Maintained systems
are packaged and release-gated; educational and idea repositories use the same
tag only to identify a cleaned archival snapshot, not to imply production
support.

## Foundations

My Physics and Electronics background informs how I approach ML: derive the
signal model, establish a conventional baseline, understand identifiability and
error, then choose the simplest system that meets the operational requirement.
The MSc archive includes control, estimation, signal processing, intelligent
systems and wireless sensing work alongside the maintained ML system.

## Contact

[LinkedIn](https://www.linkedin.com/in/ben-russell-384999189/) · GitHub: `ben120-web`
