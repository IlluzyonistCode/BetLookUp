# BetLookUp

> *Outsmart the odds with self-evolving intelligence.*

![Python](https://img.shields.io/badge/Python-3776AB.svg?style=flat-square&logo=Python&logoColor=white)

## Overview

BetLookUp is a self-evolving sports betting analysis engine. It uses NEAT (NeuroEvolution of Augmenting Topologies) to train and refine neural networks against historical betting data, dynamically loading providers and coordinating the full data-fetch-to-prediction workflow.

---

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Contributing](#contributing)
- [License](#license)

---

## Features

|      | Component         | Details                                                                                                                                                                                                                                          |
| :--- | :---------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ⚙️  | **Architecture**  | <ul><li>Python-based script architecture — likely single-entry-point driven</li><li>NEAT (NeuroEvolution of Augmenting Topologies) neural network via `neat-python`</li><li>Feed-forward network topology defined in `config-feedforward.txt`</li><li>External data fetched via `requests` (likely betting odds/sports APIs)</li></ul> |
| 🔩 | **Code Quality**  | <ul><li>No linting or formatting tools detected (e.g., no `flake8`, `black`, `pylint`)</li><li>No type annotations or static analysis tooling evident</li><li>Minimal project scaffolding — flat structure inferred</li></ul>                    |
| 📄 | **Documentation** | <ul><li>`license` file present — project has explicit licensing</li><li>No `README`, `CHANGELOG`, or `docs/` directory detected</li><li>NEAT config file (`config-feedforward.txt`) serves as implicit model documentation</li></ul>            |
| 🔌 | **Integrations**  | <ul><li>`requests` library used for HTTP calls — likely integrates with a **betting odds API**</li><li>No webhook, OAuth, or SDK integrations detected</li><li>No CI/CD pipeline (e.g., GitHub Actions, CircleCI) configured</li></ul>          |
| 🧩 | **Modularity**    | <ul><li>Low modularity inferred — no package structure (`__init__.py`) detected</li><li>NEAT config externalized to `config-feedforward.txt` — good separation of model config from code</li><li>No evidence of reusable modules or utility layers</li></ul> |
| ⚡️  | **Performance**   | <ul><li>NEAT evolutionary algorithm — computationally intensive for large populations/generations</li><li>Feed-forward topology is faster than recurrent alternatives</li><li>No async or parallel processing tooling detected (e.g., no `asyncio`, `multiprocessing`)</li></ul> |

---

## Project Structure

```
└── BetLookUp/
    ├── betlookup.py
    ├── config-feedforward.txt
    ├── LICENSE
    ├── README.md
    └── requirements.txt
```

---

## Getting Started

### Prerequisites

- Python 3.10+ / Node.js 18+ *(depending on the stack above)*

### Installation

```sh
git clone "https://github.com/IlluzyonistCode/BetLookUp
cd BetLookUp"
pip install -r requirements.txt
```

### Usage

```sh
python main.py
```

---

## Contributing

- [Report Issues](https://github.com/IlluzyonistCode/BetLookUp/issues)
- [Submit Pull Requests](https://github.com/IlluzyonistCode/BetLookUp/pulls)
- [Discussions](https://github.com/IlluzyonistCode/BetLookUp/discussions)

---

## License

Distributed under the [AGPL-3.0](LICENSE) license.
