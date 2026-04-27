# Using Generative AI Tools - Boon or Bane

This repository stores the research materials for the study **"Using Generative AI Tools - Boon or Bane"**. The files are organised by research stage and data type so that team members can locate, review, analyse, and update project materials consistently.

## Repository Structure

```text
Generative_AI_Research_s4998245/
|-- README.md
|-- admin/
|   |-- participant_information/
|   `-- proposals/
|-- analysis/
|   |-- qualitative/
|   |   `-- reports/
|   `-- quantitative/
|       |-- reports/
|       `-- scripts/
|-- data/
|   |-- processed/
|   |   `-- survey_outputs/
|   `-- raw_restricted/
|       |-- consent_forms/
|       |-- interview_transcripts/
|       `-- survey_responses/
|-- instruments/
|   `-- surveys/
|-- literature_review/
|-- media/
|   |-- photos/
|   `-- presentations/
|-- reports/
|   |-- final_reports/
|   `-- media_reports/
`-- visualisations/
```

## How to Navigate the Files

- `literature_review/` contains background sources such as articles, books, reviews, and white papers.
- `data/raw_restricted/` contains consent forms, interview transcripts, participant demographics, and original survey response files. These materials may include identifiable or sensitive human research data.
- `data/processed/` contains cleaned or summarised data outputs used for analysis and reporting.
- `instruments/` contains survey question files and research instruments.
- `analysis/` contains Python scripts and qualitative or quantitative analysis reports.
- `visualisations/` contains charts and presentation-ready analysis visuals.
- `reports/` contains final reports and media coverage reports.
- `admin/` contains participant information sheets and proposal drafts.
- `media/` contains project photos and presentation materials.

## Access Control Notes

Files in `data/raw_restricted/` should be treated as restricted research data. Only authorised project members should access consent forms, identifiable survey data, demographics, interview transcripts, and participant-related photos. Public sharing should use de-identified, processed, or summary files wherever possible.

## Naming Convention

Files should use descriptive names that include the research topic, document type, date or version where relevant, and a short description. Avoid vague names such as `final.docx` or `data.csv`. Consistent naming makes files easier to search, sort, cite, and review.

## Collaboration Guidelines

1. Pull the latest changes from `main` before starting work.
2. Create a branch with a clear name, such as `add-survey-analysis` or `update-literature-review`.
3. Keep each commit focused on one meaningful change.
4. Write commit messages that describe what changed, for example `Organise survey response files` or `Update README collaboration notes`.
5. Open a pull request for review before merging into `main`.
6. Do not place new sensitive raw data in public folders. Use `data/raw_restricted/` and confirm access requirements with the research team.

## Version Control Purpose

Git and GitHub are used in this project to track changes, document project development, support collaboration, and provide a backup of the organised research repository.
