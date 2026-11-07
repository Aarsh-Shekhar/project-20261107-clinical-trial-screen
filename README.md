# Clinical Trial Screen

Screens synthetic candidates against eligibility criteria.

## What it includes

- deterministic sample data
- scoring and ranking logic
- command line report
- unit tests
- continuous validation workflow

## Run

```bash
python3 -m clinical_trial_screen.cli --input data/sample_candidates.json
```

## Test

```bash
python3 -m unittest discover tests
```
