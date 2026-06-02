# Research Reading Map

Public research-reading and architecture scaffold for mobile manipulation, active perception, coverage planning, state estimation, and uncertainty-aware control.

## Purpose

This repository exists to organize public-facing literature structure, paper-note templates, topic taxonomies, and links between research themes and public repositories. It is not a private research notebook and does not contain confidential gap analysis, advisor notes, unpublished paper drafts, or copied paper content.

The repository currently includes a research architecture map, a topic taxonomy, and a reusable paper-note template. Full paper notes, bibliographies, diagrams, and reading paths will be added over time.

## Relation to My PhD Direction

My research focuses on structure-aware planning and control for mobile manipulation, where robot motion actively acquires useful visual/spectral information under physical, geometric, sensing, and uncertainty constraints.

This reading map supports that direction by organizing public literature themes around:

- mobile manipulation,
- active sensing and active perception,
- line-scan / RGB-to-hyperspectral proxy scanning,
- coverage planning,
- geometric visibility constraints,
- state estimation and SLAM,
- uncertainty-aware control,
- ROS2/MoveIt and implementation pathways.

Main public links:

| Theme | Related repo | Role |
|---|---|---|
| Structure-aware active scanning | [`line-scan-mobile-manipulator-demo`](https://github.com/WikiGenius/line-scan-mobile-manipulator-demo) | Public anchor scaffold for line-scan / RGB-hyperspectral active scanning. |
| Mobile manipulation execution | [`ros2-moveit-grasping-demo`](https://github.com/WikiGenius/ros2-moveit-grasping-demo) | ROS2/MoveIt2 perception-guided grasping and execution evidence. |
| State estimation / SLAM | [`GTSAM_SLAM_VISION`](https://github.com/WikiGenius/GTSAM_SLAM_VISION) | Factor-graph visual estimation and SLAM-style experiments. |
| Control / dynamics | [`robotics-control-learning-labs`](https://github.com/WikiGenius/robotics-control-learning-labs) | State-space, LQR, observers, and control baselines. |
| ROS2 systems | [`ros2-mobile-robotics-labs`](https://github.com/WikiGenius/ros2-mobile-robotics-labs) | ROS2 mobile robotics learning and simulation workflows. |
| 3D perception / view synthesis | [`nerf-lab`](https://github.com/WikiGenius/nerf-lab) | NeRF/ray-based intuition for viewpoint coverage and scene representation. |

## Maturity Level

**Current status:** Public research scaffold / early-stage organization repo

This repository is currently intended to organize the public-facing literature and research architecture. It does not yet represent a complete literature review, systematic review, or validated research taxonomy.

### Implemented now

- [x] Repository structure
- [x] README and project organization
- [x] Public research architecture map
- [x] Topic taxonomy
- [x] Paper-note template
- [ ] Core paper bibliography
- [ ] Reading path by topic
- [ ] Summary tables
- [ ] Method relationship diagrams
- [ ] Reproduction checklist for selected papers

### Not included publicly

- Private gap analysis
- Advisor/collaborator notes
- Full paper drafts
- Confidential experiment ideas
- Full unpublished method comparisons
- Copied figures/tables/text from papers

## Current Contents

```text
docs/research-architecture.md   public repo architecture and release policy
docs/topic-taxonomy.md          public topic structure
docs/paper-note-template.md     reusable note template
scripts/                        future bibliography/map scripts
results/                        future generated tables/graphs
media/                          future diagrams or public figures
```

## What This Repo Demonstrates Now

This repo currently demonstrates:

- a public architecture map for the GitHub research portfolio,
- a topic taxonomy for active scanning, manipulation, control, estimation, and 3D perception,
- a safe paper-note template that avoids copying copyrighted content,
- a place to link papers to future public reproductions.

It does not yet contain a complete literature review.

## Planned Development Roadmap

- **Stage 0: repository scaffold** - organize README, docs, public/private policy, and templates.
- **Stage 1: toy public structure** - maintain topic taxonomy and note template.
- **Stage 2: bibliography table** - add core paper list with citation links.
- **Stage 3: method map** - connect topics, assumptions, metrics, and public repos.
- **Stage 4: reproduction planning** - identify public-safe toy reproductions.
- **Stage 5: generated outputs** - create summary tables or diagrams.
- **Stage 6: paper-supporting private implementation** - keep private gap analysis and unpublished comparisons elsewhere.
- **Stage 7: post-publication public release** - add paper/report links after approval.

## Public / Private Boundary

Public here:

- paper lists,
- high-level summaries in my own words,
- topic taxonomy,
- public repo links,
- citation metadata,
- public-safe reproduction ideas.

Private elsewhere:

- private gap analysis,
- advisor feedback,
- collaborator notes,
- unpublished paper strategy,
- detailed private method comparisons,
- reviewer-response planning.

## How to Run

This repository is currently documentation-first. Start with:

```text
docs/research-architecture.md
docs/topic-taxonomy.md
docs/paper-note-template.md
```

No complete runnable bibliography generator is included yet. The next planned step is to add a small bibliography table or script.

Planned script pattern:

```bash
python scripts/build_reading_map.py
```

## Expected Future Outputs

Future public artifacts may include:

- bibliography tables,
- topic graphs,
- reading-order roadmaps,
- paper summary tables,
- reproduction checklists,
- diagrams connecting papers to public repos.

## Limitations

This repository is currently an early-stage public scaffold. It does not yet include:

- a complete literature review,
- systematic search protocol,
- full bibliography,
- validated taxonomy,
- benchmark comparisons,
- paper-level results.

Paper notes should be summaries and personal research notes, not substitutes for reading the original papers.

## Citation / Acknowledgment

All papers, books, libraries, courses, and datasets summarized here should be cited clearly in the relevant notes. Copyrighted paper text should not be copied into this repository beyond short, properly attributed excerpts.

## Rights and Reuse

This repository is shared as a public academic portfolio/scaffold. Unless a separate open-source license is explicitly added, all rights are reserved by the author.

## Research Architecture

See [`docs/research-architecture.md`](docs/research-architecture.md) for the public repository architecture and private/public release policy.
