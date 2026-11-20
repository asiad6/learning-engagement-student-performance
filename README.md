# Learning Engagement and Student Performance

**SE 42 · Data Science Basics**

This project explores associations between online learning activity and academic outcomes in selected Open University courses using the Open University Learning Analytics Dataset (OULAD). The work combines multiple linked dataset tables, including student registrations, assessments, course structure, virtual learning materials, and daily VLE interactions.

## Project contents

- `notebooks/learning_engagement_student_performance.ipynb` — analysis notebook.
- `deliverables/presentation.pptx` — available 10-slide presentation.
- `deliverables/project_description.docx` — project description.
- `deliverables/speaker_notes.md` — presentation notes.
- `outputs/figures/` — six figures used by the project.
- `data/raw/` — empty dataset placeholder; raw data is not bundled.

## Data and findings

The project examines outcome frequency, engagement across outcomes, weekly activity, material types, and differences across modules. The executed analysis reports Pass as the most common outcome (12,361 student-course registrations; 37.9%). Mean total clicks are 2,666.8 for Distinction, 1,921.8 for Pass, 651.9 for Fail, and 314.0 for Withdrawn. The most-clicked material type is `oucontent` (11,206,803 clicks). These are descriptive associations and do not establish that clicking causes better outcomes.

The raw OULAD archive is intentionally excluded because of its size. Download it from the [UCI OULAD dataset page](https://archive.ics.uci.edu/dataset/349/open+university+learning+analytics+dataset) and place it at `data/raw/oulad_uci.zip`. Then follow `RUN_ON_MAC.md`. The notebook reads the 10.6-million-row interaction file in chunks.

## Citation

Kuzilek, J., Hlosta, M., & Zdrahal, Z. (2017). *Open University Learning Analytics dataset*. Scientific Data, 4, 170171. https://doi.org/10.1038/sdata.2017.171. UCI DOI: https://doi.org/10.24432/C5KK69.
