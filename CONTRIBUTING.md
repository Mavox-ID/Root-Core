# Contributing to Root Core

Thank you for your interest in contributing to **Root Core**.
We welcome developers, testers, designers, technical writers, and anyone who wants to help improve the system.

Root Core is focused on stability, performance, clean architecture, and long-term maintainability. Please read this guide before contributing.

---

# Table of Contents

1. Ways to Contribute
2. Development Standards
3. Reporting Bugs
4. Suggesting Features
5. Code Contributions
6. Commit Guidelines
7. Pull Request Process
8. Security Issues
9. Code Style
10. Community Expectations

---

# 1. Ways to Contribute

You can help Root Core in many ways:

* Fix bugs
* Improve performance
* Add features
* Improve documentation
* Refactor old code
* Test on different hardware
* Review pull requests
* Suggest ideas

Every meaningful contribution matters.

---

# 2. Development Standards

Root Core values:

* Clean and readable code
* Modular design
* Minimal unnecessary dependencies
* Security-first decisions
* Predictable behavior
* Good documentation
* Backward compatibility when possible

Please avoid rushed or experimental code without justification.

---

# 3. Reporting Bugs

When opening an issue, include:

* Root Core version
* Environment / hardware
* Steps to reproduce
* Expected result
* Actual result
* Logs / screenshots if relevant

Example:

```text
Version: 1.4.2
Platform: x86_64 / QEMU
Issue: Filesystem panic after mount
Steps:
1. Boot system
2. Mount second disk
3. Run fscheck
```

Clear bug reports save time.

---

# 4. Suggesting Features

Before requesting a feature:

* Check if it already exists
* Search open issues
* Explain the use case
* Explain why it benefits Root Core

Good request:

```text
Add read-only mount mode for safer recovery operations.
```

Weak request:

```text
Add cool stuff.
```

---

# 5. Code Contributions

## Getting Started

1. Fork the repository
2. Create a branch

```bash
git checkout -b feature/short-description
```

3. Make focused changes
4. Test thoroughly
5. Submit a pull request

---

# 6. Commit Guidelines

Use clear commit messages.

Preferred format:

```text
module: short description
```

Examples:

```text
kernel: fix scheduler deadlock
fs: improve inode validation
boot: reduce startup delay
docs: update install guide
```

Avoid:

```text
fix stuff
update
changes
```

---

# 7. Pull Request Process

Each pull request should:

* Solve one specific problem
* Compile successfully
* Pass tests
* Include documentation if behavior changed
* Avoid unrelated edits

Please include:

* What changed
* Why it changed
* How it was tested
* Any compatibility impact

Large PRs may be asked to split into smaller parts.

---

# 8. Security Issues

Do **not** open public issues for serious vulnerabilities.

Instead, privately report:

* privilege escalation
* memory corruption
* authentication bypass
* unsafe defaults
* remote attack vectors

Use the project security contact channel.

---

# 9. Code Style

General rules:

* Prefer clarity over cleverness
* Keep functions focused
* Avoid deeply nested logic
* Use descriptive names
* Comment non-obvious logic
* Keep formatting consistent

For low-level/system code:

* Validate inputs
* Check boundaries
* Handle failures explicitly
* Avoid hidden side effects

---

# 10. Community Expectations

Be respectful and constructive.

We do not accept:

* harassment
* spam
* hostility
* low-effort disruption
* plagiarism

Technical disagreement is welcome. Personal attacks are not.

---

# Final Notes

Root Core is built for reliability and serious engineering discipline.

If you want to improve the system, we appreciate your effort.

Thank you for contributing.
