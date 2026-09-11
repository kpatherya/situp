# Contributing to SIT-UP

Thanks for contributing to this posture-detection research prototype.

## Setup

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

## Quick Validation

Run a syntax pass before opening a pull request:

```bash
python -m py_compile front/front-detector.py side/side-logging.py stream/data-stream.py analysis/stats.py
```

## Contribution Rules

- Keep pull requests focused to one objective.
- Update `README.md` when run commands, required models, or outputs change.
- Do not commit raw participant data or identifiable responses.
- Follow `DATA_POLICY.md` for consent, anonymization, and retention requirements.

## Pull Request Checklist

- [ ] setup instructions still work
- [ ] changed scripts compile
- [ ] data policy was followed
- [ ] outputs and limitations are documented
