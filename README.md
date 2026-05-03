# MBDS Final Exercise Network

This repository has been organized by purpose:

- `dataset/`: stores all raw data files (CSV, GraphML, etc.)
- `markdown/`: stores Markdown documents (currently empty and ready for future documentation)

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
2. Put future analysis reports, method notes, and meeting notes in `markdown/`.
3. Before future submissions, consider adding data cleaning scripts, a field dictionary, and an analysis workflow document.
