# Research Reading Map

## Overview
This repository is a public reading map for mobile manipulation, active perception, coverage planning, and state estimation papers. It is intended to organize research themes, paper notes, implementation links, and future experiment ideas in one reproducible place.

The current repository contains the initial public structure. Paper notes, diagrams, bibliographies, and reading paths will be added over time.

## Research/Engineering Motivation
Robotics research spans many connected areas: planning, control, perception, estimation, optimization, and system integration. A reading map helps turn scattered papers into an organized path from fundamentals to implementation.

This repository is meant to support research planning by connecting papers to questions, methods, assumptions, metrics, and possible reproduction tasks.

## Features
- Planned reading map for mobile manipulation and active perception.
- Planned paper notes grouped by topic.
- Planned bibliography and citation tracking.
- Planned diagrams showing relationships between methods.
- Planned reproduction checklist for selected papers.

## Method
The reading map will organize papers using a lightweight structure:

1. Topic area and research question.
2. Core idea of each paper.
3. Assumptions and system model.
4. Metrics, datasets, or experimental setup.
5. Relationship to other papers.
6. Possible implementation or reproduction notes.

The goal is to summarize enough to guide research and engineering decisions without copying copyrighted paper content.

## Installation
Clone the repository:

```bash
git clone https://github.com/WikiGenius/research-reading-map.git
cd research-reading-map
```

Optional Python environment for future bibliography/map scripts:

```bash
python -m venv .venv
. .venv/bin/activate
pip install -r requirements.txt
```

On Windows PowerShell:

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
pip install -r requirements.txt
```

## Run
This repository is currently a documentation scaffold. Planned script pattern:

```bash
python scripts/build_reading_map.py
```

Paper notes and topic pages will live under `docs/`.

## Results
Generated maps, figures, topic graphs, and bibliography summaries will be stored under `results/` and `media/`.

Planned artifacts:

- Topic graph of papers and methods.
- Paper summary tables.
- Reading-order roadmap.
- Reproduction checklist for selected papers.

## Limitations
- This repository currently contains structure, not a complete literature review.
- Paper notes will be summaries and personal research notes, not substitutes for reading the original papers.
- Some implementation details may be deferred until related experiments are public.

## Roadmap
- [ ] Add core paper list for active perception.
- [ ] Add mobile manipulation reading path.
- [ ] Add coverage planning and state estimation sections.
- [ ] Add bibliography file and generated summary table.
- [ ] Add links to reports or reproduction experiments.

## Citation / Acknowledgment
All papers, books, libraries, courses, and datasets summarized here should be cited clearly in the relevant notes. Copyrighted paper text should not be copied into this repository beyond short, properly attributed excerpts.
