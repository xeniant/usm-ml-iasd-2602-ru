# Machine Learning: exercise solutions

Solutions of the exercises for the Machine Learning course (semester 1), USM, group IASD 2602 R, 2026-2027.

## Structure

- `notebooks/<NN>/original/`: original notebooks of lesson NN from the teacher
- `notebooks/<NN>/solution/`: my solutions for lesson NN

## Running locally

The notebooks read the course CSV files from a `datasets/` folder in the project root. The data is not included in this repository.

```
python3.12 -m venv .venv
.venv/bin/pip install -r requirements.txt
.venv/bin/jupyter lab
```
