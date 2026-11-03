# Data, Democracy and Development: course work

Quarto website: Home, DDD 2, DDD 3, DDD 4.

## Folders
- `ddd2/`, `ddd3/`, `ddd4/`: pages of each course
- `ddd4/images/`: put the images used by the Computational Statistics notes here
- `data/`: datasets (see below)
- `docs/`: the built website (created by `quarto render`)

## Build
1. `quarto render`
2. Commit and push.
3. GitHub: Settings → Pages → Branch `main`, folder `/docs`.

## Data
IHDS data may not be shared publicly (ICPSR terms), so `*.dta` and `*.csv` are git-ignored. Pages that use data keep their saved results in `_freeze/`; commit that folder.
