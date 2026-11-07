# Topic taxonomy

Organize papers by the problem they address, then tag the sensor and robot used.

| Topic | Reading questions |
| --- | --- |
| Task and observation objectives | What must be observed or estimated? What makes a measurement useful? |
| Sensor models | How do visibility, sampling, noise, timing, and calibration affect observations? |
| Scene representation | How are geometry, unknown space, and occlusion represented? |
| State estimation | What is uncertain? How is uncertainty propagated and evaluated? |
| Motion planning | How are sensing value, motion cost, collision avoidance, and robot constraints combined? |
| Control and execution | How do tracking error, dynamics, and timing affect sensing quality? |
| Evaluation | Which baselines, metrics, ablations, and data support the conclusions? |

Line-scan acquisition, RGB-D, hyperspectral sensing, mobile manipulation, and inspection are application tags. They do not limit the taxonomy to one sensor or platform.

Suggested method tags: `active-perception`, `motion-planning`, `coverage-planning`, `state-estimation`, `scene-representation`, `feedback-control`, and `uncertainty`.

Use [project relationships](research-architecture.md) to connect reading to implementation, and the [paper-note template](paper-note-template.md) to record evidence.
