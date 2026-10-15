# NBA Home-Court Advantage (2016-17 to 2025-26)

Rares Weintraub 
(i6438440), 
MAT2007 Introduction to Programming,
Maastricht University

## How to run the code

**Dependencies:** Python 3.9 or newer, with the packages `pandas`, `numpy` and `matplotlib`.

**Installation:**

```
pip install pandas numpy matplotlib
```

(use `pip3` on macOS/Linux if `pip` is not found)

**Execution:** put `anal_3.py` and the dataset file `nba-home-court-2017-2026.csv` in the same folder, then run from that folder:

```
python anal_3.py
```

**Conditions:**
- The CSV must keep the name `nba-home-court-2017-2026.csv` and sit next to `anal_3.py`.
- The script runs in a few seconds. It prints the results in the terminal and opens four plot windows one after the other; close a window to see the next one.

## Dataset

The dataset (NBA game results, 11,777 games) can be found at: **https://www.kaggle.com/datasets/mrbridge/nba-home-court-2017-2026**


**No manual cleaning is needed.** Use the raw file as downloaded. The script cleans it automatically by removing neutral-site games and All-Star/exhibition games (fake team codes), which leaves 11,731 games for the analysis.
