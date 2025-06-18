# Contributing to the Speaker Toolkit

First off, thank you for your interest in contributing! 🎉 Whether you're submitting a bug fix, improving documentation, proposing a new feature, or just asking a thoughtful question, we're excited you're here.

This document outlines the process for contributing to the Speaker Toolkit project.

## 👥 Code of Conduct

We follow a [Code of Conduct](CODE_OF_CONDUCT.md) based on mutual respect, inclusion, and collaboration. Please review it before contributing.

## 🛠 How to Contribute

### 1. Fork the Repository

Start by forking the repo and cloning your fork:

```bash
git clone https://github.com/TaleLearnCode/SpeakerToolkit.git
cd SpeakerToolkit
```

### 2. Choose What to Work On

Check our Issues tab for:

- `good first issue` for beginner-friendly tasks
- `help wanted` for contributions that are ready for development
- Open ideas or enhancements you’d like to champion

Open a new issue to suggest something that doesn’t exist yet. We welcome fresh perspectives!

### 3. Create a Branch

Follow our branching convention:

```bash
git checkout -b feature/short-description
```

### 4. Make Your Changes

Please:

- Write clear, modular code with descriptive commit messages.
- Update or add automated tests where applicable.
- Run tests locally (`dotnet test`, `terraform validate`, etc.)
- Follow project naming and code conventions (see [`/docs/developer-conventions-and-practices.md`](/docs/developer-conventions-and-practices.md)

### 5. Add Documentation

If your change affects the public API, CLI behavior, or system architecture, be sure to update relevant docs:

- Architecture: `/docs/architecture/`
- CLI usage: `/cli/README.md`
- ADRs (as needed): `/docs/decisions/`

### 6. Submit a Pull Request

Push your branch and open a Pull Request against `main`. In your PR:

- Provide a clear summary of what you changed and why
- Reference any related issues (e.g., “Fixes #42”)
- Use GitHub’s checklists and labels to help reviewers

## 🔍 Review Process

We aim to review PRs within a few business days. You may receive comments or suggested changes. Please don’t take them personally. We want to make your contributions shine!

A PR is ready when:

- All automated checks pass.
- There’s a straightforward problem/solution narrative.
- Code and documentation are aligned.
- Another maintainer signs off

## 🤝 Contributor Tips

- Keep changes small and focused; multiple smaller PRs are better than one massive one.
- Favor clarity and readability over cleverness.
- Ask questions in issues or PRs if something is unclear, and we’ll help.
- If you’re contributing architecture or cross-cutting changes, check in early via a draft PR or discussion

## 📜 License

By contributing to this project, you agree that your contributions will be licensed under the [MIT License](LICENSE).