# VocaSched-DT-Dataset
Dataset and evaluation files for VocaSched-DT: A digital-twin-driven cloud-edge scheduling framework for practical teaching resources in higher education.
VocaSched-DT Dataset Release

**VocaSched-DT: A Digital-Twin-Driven Cloud–Edge Collaborative Scheduling Framework for Practical Teaching Resources in Digital Education**

## Overview

VocaSched-DT is a teaching-aware cloud–edge scheduling framework designed for practical teaching environments in higher education. The dataset represents practical teaching tasks as structured records combining:

- Teaching context
- Resource demand
- Scheduling constraints
- Digital-twin environment state
- Scheduler decisions and evaluation outcomes

## Repository Files

| File | Description |
|---|---|
| `task_records.csv` | Main task-state records used as scheduler input |
| `scheduler_decisions.csv` | VocaSched-DT priority scores, fairness correction, congestion risk, and placement decisions |
| `scheduler_results.csv` | Evaluation results for FCFS, EDF, Round Robin, Multi-Objective Optimizer, DRL-Based Adaptive Scheduler, and VocaSched-DT |
| `scheduler_performance_summary.csv` | Overall scheduler comparison across system-level and teaching-service metrics |
| `scenario_summary.csv` | Scenario-wise performance under normal day, overlap, exam load, network degradation, and edge stress |
| `department_summary.csv` | Department-wise distribution and VocaSched-DT outcomes |
| `practical_validation_nem_lab.csv` | Practical validation results for the NEM laboratory case |
| `resource_nodes.csv` | Local edge, peer edge, and cloud resource pool details |
| `course_catalog.csv` | Department-wise practical course catalog |
| `task_templates.csv` | Workload template ranges for each task class |
| `data_dictionary.csv` | Column definitions |
| `dataset_construction_protocol.csv` | Dataset construction steps aligned with the paper methodology |
| `quality_control_report.csv` | Consistency and validation checks |
| `file_index.txt` | List of repository files |

## Dataset Structure

The main task records follow the VocaSched-DT task model:

```text
Task = {Teaching Context, Resource Demand, Scheduling Constraints, Environment State}
```

How to Use

Open the CSV files in Microsoft Excel, Python, R, MATLAB, or any spreadsheet/data-analysis tool.

```For Python:

import pandas as pd

tasks = pd.read_csv("task_records.csv")
results = pd.read_csv("scheduler_results.csv")
summary = pd.read_csv("scheduler_performance_summary.csv")

print(tasks.head())
```
print(summary)
Citation

If you use this dataset, please cite the related paper:

VocaSched-DT: A Digital-Twin-Driven Cloud–Edge Collaborative Scheduling Framework for Practical Teaching Resources in Digital Education.
