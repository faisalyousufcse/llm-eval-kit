# llm-eval-kit

Reproducible evaluation harness for language-model tasks.

> Status: planned. This repository holds the project outline, and the code is on its way.

## Overview

A lightweight harness for defining evaluation tasks, running models against them and scoring the results with deterministic, versioned graders.

## Planned features

- Task definitions as plain YAML plus Python graders
- Exact-match, numeric-tolerance and rubric scorers
- Run manifests that pin model, prompt and data versions
- Per-item result tables for error analysis

## Tech stack

Python, pandas, pytest

## Roadmap

- [ ] Project skeleton and CI
- [ ] Core implementation
- [ ] Tests and examples
- [ ] Documentation

## License

MIT. See [LICENSE](LICENSE).
