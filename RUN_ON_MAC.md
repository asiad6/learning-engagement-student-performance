# Run this project on your Mac

## 1. Open the project folder

1. Extract the project ZIP.
2. Open the `student-performance-learning-engagement` folder.
3. Open Terminal, type `cd ` (including the space), drag the project folder into Terminal, and press Return.

## 2. Install the packages

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## 3. Download the dataset once

1. Open the official [UCI OULAD dataset page](https://archive.ics.uci.edu/dataset/349/open+university+learning+analytics+dataset) in Safari.
2. Download the 44.6 MB ZIP archive.
3. Move it into `data/raw/` and rename it `oulad_uci.zip`.

The raw archive is not included in this project or GitHub repository. Manual browser download is recommended because some local Python installations can have SSL certificate problems.

## 4. Open and run the notebook

```bash
jupyter lab
```

Open `notebooks/learning_engagement_student_performance.ipynb` and choose **Kernel → Restart Kernel and Run All Cells**. The 10.6-million-row `studentVle.csv` file is processed in chunks. Allow several hundred MB of disk space.

## 5. Check the output

- 10,655,280 interaction rows processed from `studentVle.csv`.
- 32,593 student-course registrations in the joined analysis table.
- Five research-question answers printed.
- Six diagrams saved in `outputs/figures/`.
- No red error outputs in the notebook.

The notebook also saves compact summary CSV files in `outputs/`. The raw archive stays excluded from Git by `.gitignore`; generated figures and summaries can be included in the repository.
