# Motor Insurance Claims Modelling

Predicting claim frequency and severity on the freMTPL2 French motor
dataset, combining them into a pure premium, and benchmarking GLMs
against gradient boosting.

**Status:** in progress

## Data
freMTPL2freq and freMTPL2sev, via OpenML (IDs 41214 and 41215).

## Setup
    python -m venv .venv
    source .venv/bin/activate
    pip install -r requirements.txt