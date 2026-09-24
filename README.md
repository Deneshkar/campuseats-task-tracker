# CampusEats Task Tracker

Simple task tracker for the CampusEats Lab 8 exercise.

## Project structure

- `src/tasks.js` - initial CampusEats task list
- `.github/workflows/ci.yml` - GitHub Actions CI workflow

## Usage

Run the task list:

```bash
node src/tasks.js
```

Expected output:

```text
CampusEats has 3 open tasks
```

## CI

On push / pull request to `main`, the `CI / build-and-check` workflow checks out the repo,
lists files, and verifies `README.md` exists:

```bash
test -f README.md && echo "README found"
```
