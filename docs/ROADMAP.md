# Roadmap

This project is currently a placeholder. The estimates below begin only after the intended integration model is confirmed.

## M0 — Scope and feasibility (1–2 weeks)
- [ ] Inspect repository contents and identify the current implementation (if any).
- [ ] Choose integration model: supported API, external helper, UI extension or patch.
- [ ] Identify Cemu versions and operating systems to support.
- [ ] Review Cemu licensing and compatibility constraints.
**Exit:** written scope and a minimal technical design.

## M1 — Minimal prototype (2–4 weeks)
- [ ] Demonstrate one save-state capture/load workflow using a legally usable test title or synthetic fixture.
- [ ] Define storage location, naming and metadata.
- [ ] Handle invalid, missing and incompatible states safely.
**Exit:** repeatable prototype with documented limitations.

## M2 — Reliability and compatibility (4–8 weeks)
- [ ] Add version detection and compatibility checks.
- [ ] Add atomic writes, backup behavior and corruption handling.
- [ ] Test failure/recovery paths.
**Exit:** automated tests and a compatibility matrix.

## M3 — User experience and release (2–4 weeks)
- [ ] Add configuration and clear status/errors.
- [ ] Document install, use, uninstall and troubleshooting.
- [ ] Package reproducible releases.
**Exit:** release candidate for explicitly supported Cemu versions.

**Planning total:** approximately 2–4 months after scope confirmation. This is not a commitment; emulator integration constraints may change the plan.
