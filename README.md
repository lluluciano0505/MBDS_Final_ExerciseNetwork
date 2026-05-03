# MBDS Final Exercise Network

This repository has been organized by purpose:

- `dataset/`: stores all raw data files (CSV, GraphML, etc.)
- `markdown/`: stores documentation and report outputs

## Current Directory Structure

```text
MBDS_Final_ExerciseNetwork/
├── dataset/
│   └── Network Canvas Export/
│       ├── Anonymous Participant_..._attributeList*.csv
│       ├── Anonymous Participant_..._edgeList*.csv
│       ├── Anonymous Participant_..._ego.csv
│       └── Anonymous Participant_....graphml
├── markdown/
│   └── blog/
│       ├── index.html
│       ├── gym_network_report.qmd
│       └── gym_network_report.html
└── README.md
```

## Data Description

`dataset/Network Canvas Export/` mainly contains the following exported files:

- `*_attributeList*.csv`: node attributes (person-level attributes)
- `*_edgeList*.csv`: edge relationships (connections between people)
- `*_ego.csv`: ego-level (survey respondent) information
- `*.graphml`: graph structure files for network analysis tools

## Recommended Usage

1. Keep raw data read-only; create separate output folders for processed results.
2. Store reports and rendered pages under `markdown/blog/`.
3. Open `markdown/blog/index.html` in a browser to view the blog-style report entry page.

## Rendering Notes

- The Quarto source file is `markdown/blog/gym_network_report.qmd`.
- The rendered page is `markdown/blog/gym_network_report.html`.
- In the QMD setup block, `data_dir` points to `dataset/Network Canvas Export/` for reproducible rendering.
