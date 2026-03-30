# GTlab

[![DOI](https://zenodo.org/badge/727352741.svg)](https://zenodo.org/doi/10.5281/zenodo.10666586)

GTlab is an open and modular framework for collaborative engineering and design. It is developed by the [DLR Institute of Propulsion Technology](https://dlr.de/at) and is currently used to design and simulate propulsion systems and individual components across various levels of detail throughout the entire lifecycle.

GTlab combines data modeling, workflow automation, scripting, and extensibility through plugins in one framework. Originally developed for aircraft propulsion research, it is designed so that methods, modules, and domain-specific extensions can be reused across teams and application areas.

![GTlab screenshot](https://github.com/dlr-gtlab/.github/assets/3213107/e6668213-1bcd-4960-85af-dd5f4cb825f5)

## Why GTlab

GTlab is designed as a reusable research software platform rather than a one-off application for a single method or project. It helps teams bring together data models, engineering methods, automation, and domain knowledge in one shared environment, making complex workflows more transparent, reproducible, and easier to extend over time.

Its open and modular architecture supports sustainable software development in research: core capabilities can be combined with domain-specific modules, while common foundations for data handling, process management, and user interaction remain reusable across projects and teams.

## Key Strengths

- Modular plugin architecture for domain-specific extensions
- Support for collaborative and interdisciplinary engineering workflows
- Integrated data modeling, workflow automation, and scripting
- Open-source core framework with public documentation and downloads
- Designed for reuse, sustainability, and long-term extensibility in research software

## Impact

GTlab has grown from a research-driven software framework into a shared platform with practical relevance in day-to-day engineering work. It is used across multiple DLR institutes and supports collaboration between research, academia, and industrial application contexts.

## Sustainability

GTlab is developed with long-term sustainability in mind. Its open-source core is complemented by public documentation, versioned releases, transparent licensing, issue tracking, code review, installer-based deployment, and automated quality assurance through unit, GUI, and regression testing.

## Get Started

- Website: https://gtlab.de
- User Documentation: https://gtlab.readthedocs.io/projects/user
- Developer Documentation: https://gtlab.readthedocs.io/en/latest/

## Ecosystem

- [gtlab-core](https://github.com/dlr-gtlab/gtlab-core): core framework for collaborative engineering workflows
- [python-module](https://github.com/dlr-gtlab/python-module): Python integration for scripting and automation
- [intelligraph-module](https://github.com/dlr-gtlab/intelligraph-module): graph-based workflow capabilities
- [genh5](https://github.com/dlr-gtlab/genh5): reusable C++ wrapper for HDF5-based data handling
- [gt-logging](https://github.com/dlr-gtlab/gt-logging): shared logging library used across the GTlab ecosystem

## Installation

For normal use, we recommend installing GTlab via the official GTlab Community Installer.

- Download GTlab for Windows or Linux from the [official download page](https://www.gtlab.de/pages/download.html).
- The Community Installer installs GTlab together with the available modules and can also be used to update GTlab.
- For DLR internal users, an internal installer with additional modules is also available through internal DLR distribution channels.
- Building from source is mainly intended for developers and contributors; see the [gtlab-core README](https://github.com/dlr-gtlab/gtlab-core#building-gtlab).

GTlab is supported on Windows and Linux. macOS should theoretically work, but is currently not officially tested.

## Learn More

- Features: https://www.gtlab.de/pages/features.html
- Screenshots: https://www.gtlab.de/pages/screenshots.html
- News: https://www.gtlab.de/#news

## Research & Citation

- Helmholtz Software Directory: https://helmholtz.software/software/gtlab
- Software DOI: https://zenodo.org/doi/10.5281/zenodo.10666586

## Community

- Questions or support: open an issue in the relevant repository or contact [gtlab-support@dlr.de](mailto:gtlab-support@dlr.de).
- Interested in extending GTlab? Start with the [test modules](https://github.com/dlr-gtlab/gtlab-core/tree/master/tests/modules) and the developer documentation.
