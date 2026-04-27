# VocaSched-DT-Dataset
Dataset and evaluation files for VocaSched-DT: A digital-twin-driven cloud-edge scheduling framework for practical teaching resources in higher education.
VocaSched-DT Dataset Release

Purpose:
This repository contains the dataset files used to represent cloud-edge scheduling for practical teaching in higher education. The data structure follows the paper's task model, where each task record combines teaching context, resource demand, scheduling constraints, and digital-twin environment state.

Main files:
1. task_records.csv
   Core task-state records used as scheduler input.
2. scheduler_decisions.csv
   VocaSched-DT priority score, congestion risk, fairness correction, and placement decision.
3. scheduler_results.csv
   Evaluation results for FCFS, EDF, Round Robin, Multi-Objective Optimizer, DRL-Based Adaptive Scheduler, and VocaSched-DT.
4. scheduler_performance_summary.csv
   Overall comparison across system-level and teaching-service metrics.
5. scenario_summary.csv
   Scenario-level results for normal day, overlapping practical classes, exam-week priority load, network degradation, and edge-node stress.
6. department_summary.csv
   Department-level distribution and VocaSched-DT outcomes.
7. practical_validation_nem_lab.csv
   Practical classroom-side validation table for the NEM laboratory case.
8. resource_nodes.csv
   Local edge, peer edge, and cloud resource pool.
9. course_catalog.csv
   Department-wise practical course catalog.
10. task_templates.csv
   Workload template ranges for each task class.
11. data_dictionary.csv
   Column definitions.
12. dataset_construction_protocol.csv
   Stepwise construction protocol aligned with the methodology.
13. quality_control_report.csv
   Basic validation and consistency checks.

Recommended use:
- Open CSV files in Microsoft Excel.
- Open TXT files in Notepad or any text editor.
