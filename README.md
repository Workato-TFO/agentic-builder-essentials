# Agentic Builder Essentials — Lab Guide

A lab guide for building a help desk genie with Workato Agent studio. Served via GitHub
Pages from the `docs/` folder (branch `main`, folder `/docs`).

## Lab

| Lab | Phases | Time |
|---|---|---|
| [Build your first Genie with Agent studio](docs/index.html) | 5 phases, 15 tasks | 2 to 3 hours |

## Structure

- `docs/` — the published surface: the lab as one self-contained page (Pages source)
- Every commit is checked by the publish guard workflow
  (`.github/workflows/publish-guard.yml`); the same checks run locally as a
  pre-push hook. Enable it once per clone with:

```
git config core.hooksPath .githooks
```

## Contributing

Content is authored and reviewed elsewhere; this repo holds only pressed,
vetted output. Do not edit lab HTML in place — changes land as a fresh press.
