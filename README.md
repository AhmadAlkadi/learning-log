# learning Log - CV/ML Engineering Roadmap
Started: May 5, 2026
Goal: Recovering information and learning new things

## week 1 - Environment Setup + GitHub Hygiene

### Day 1
- Installed Python 3.13.13
- Installed VSCode + Python/Jupyter/GitLens extentions
- Installed Git, configured gloabal user
- Set up SSH key for GitHub
- Created Development folder structure
- Initialized this learning-log repo
### Day 2
- Created first virtual environment using venv
- Installed core ML stack: Numpy, Pandas, scikit-learn, Matplotlib, Jupyter, PyTorch
- Set up .gitignore tamplate for Python projects
- Verified environment with sanity-check notebook
Learned: venv basics, why we never commit venv/, requirements.txt workflow
### Day 3
- Read Pro Git  Chapters 1-3 (Git Basics, Branching)
- Practiced branching workflow: feature branches, mering, deleting
- Practiced undoing changes: restore, restore --staged, commit --amend
- Created personal git-cheatsheet.md
- Set up Git aliases (st, co, br, lg)
- Fixed Git author emial to use personal account

### Day 4 ( Friday, May 8, 2026)
- NumPy fundamentals: array creation, indexing, slicing
- Vectorization: ~100x speedup over Python loops
- Broadcasting rules and practical examples
- Axis operations (axis=0 collapses rows, axis=1 collapses cols)
- Reshaping and transposing
- Solved 5 mini-exercises (pairwise distance was the trickiest)
- First featrue- branch + PR + merge workflow on personal repo

### Day 5
- Pandas Series and DataFrame funamentals
- Reading CSVs, .info(), .describe(), .head()
- Selection: column access, iloc, loc, boolean filtering
- Handling missing data: dropna, fillna with median/mode
- GroupBy + agg for SQL-like aggregations
- Adding derived columns with np.where, np.select, .apply, .str.extract
- worked Titanic dataset for first time
