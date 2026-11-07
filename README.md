# Research Reading Map

A reading structure for **perception-aware motion planning**: choosing robot motion based on task-relevant sensing quality and uncertainty as well as motion feasibility.

This repository currently provides organization and note templates. It is not a completed systematic literature review.

## Reading questions

| Theme | Questions to ask |
| --- | --- |
| Task and sensing objective | What does the robot need to observe or estimate? How is sensing quality measured? |
| Observation models | What measurements does the sensor produce? Which assumptions depend on the sensing modality? |
| State estimation and uncertainty | What is uncertain, how is it represented, and is the uncertainty estimate calibrated? |
| Scene representation | What geometry or map does the planner require? How are unknown and occluded regions represented? |
| Motion planning | How are observation quality, motion cost, and robot constraints combined? |
| Control and execution | How do tracking error, timing, and actuator constraints affect sensing? |
| Evaluation | Which baselines, metrics, datasets, and ablations support the claims? |

The research scope is open to different sensors and robot platforms. RGB-D and hyperspectral sensing are initial application interests. Line-scan acquisition and mobile manipulation are useful case studies, not the organizing boundary of the literature.

## Connect reading to implementation

| Area | Related projects |
| --- | --- |
| Planning and tracking | [WMM planning and tracking](https://github.com/WikiGenius/wmm-planning-and-tracking) |
| Estimation and representation | [GTSAM SLAM Vision](https://github.com/WikiGenius/GTSAM_SLAM_VISION), [NeRF Lab](https://github.com/WikiGenius/nerf-lab) |
| Kinematics and execution | [Screw Theory Toolkit](https://github.com/WikiGenius/RoboticScrewTheoryToolkit), [MoveIt grasping](https://github.com/WikiGenius/ros2-moveit-grasping-demo) |
| An initial sensing application | [Line-scan scaffold](https://github.com/WikiGenius/line-scan-mobile-manipulator-demo) |

These links identify possible implementation connections. They do not imply that a paper has been reproduced or a method validated.

## Reading resources

- [Topic taxonomy](docs/topic-taxonomy.md)
- [Paper register](docs/core_papers_table.md) — no completed entries yet
- [Paper-note template](docs/paper-note-template.md)
- [Research layers and project relationships](docs/research-architecture.md)

## Paper-note template

For each selected paper, record:

- **Citation:** authors, title, venue/year, DOI or source URL.
- **Problem:** task, robot, sensor, and operating assumptions.
- **Method:** observation model, objective, planner, and uncertainty treatment.
- **Evidence:** experiments, baselines, metrics, and reported outcomes.
- **Limitations:** what the evidence does not establish.
- **Research connection:** reusable idea, relevant baseline, or application-specific assumption.
- **Reproduction status:** read, analyzed, implemented, or reproduced—with evidence for the status.

Add real citations as papers are selected; placeholder entries are not literature evidence. Keep paper claims separate from personal hypotheses and independently reproduced results.

## Public scope

Public notes may contain bibliographic details, reading categories, and original summaries of shareable material. Confidential collaboration notes, unpublished contribution strategy, and manuscript drafts stay private.

[Return to the research portfolio](https://github.com/WikiGenius).
