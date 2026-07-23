# Contributing to Ultimate AI Lite

Thank you for your interest in contributing to **Ultimate AI Lite**.

Whether you are reporting bugs, improving documentation, optimizing performance, or implementing new features, every contribution is appreciated.

---

<p align="center">

<img src="https://img.shields.io/github/license/rakibul5879/ultimate-ai-lite?style=for-the-badge" />
<img src="https://img.shields.io/github/issues/rakibul5879/ultimate-ai-lite?style=for-the-badge" />
<img src="https://img.shields.io/github/issues-pr/rakibul5879/ultimate-ai-lite?style=for-the-badge" />
<img src="https://img.shields.io/github/last-commit/rakibul5879/ultimate-ai-lite?style=for-the-badge" />
<img src="https://img.shields.io/github/stars/rakibul5879/ultimate-ai-lite?style=for-the-badge" />
<img src="https://img.shields.io/github/forks/rakibul5879/ultimate-ai-lite?style=for-the-badge" />

</p>

---

# Table of Contents

- Why Contribute?
- Ways to Contribute
- Development Setup
- Project Structure
- Coding Guidelines
- Commit Messages
- Pull Requests
- Reporting Bugs
- Suggesting Features
- Documentation
- Security
- Code of Conduct
- License

---

# Why Contribute?

Ultimate AI Lite is an open-source AI client focused on being:

- Lightweight
- Fast
- Modern
- Secure
- Easy to deploy
- Easy to customize
- Compatible with older hardware and browsers

Community contributions help improve the project for everyone.

---

# Ways to Contribute

You can help by:

- Reporting bugs
- Fixing bugs
- Improving documentation
- Improving accessibility
- Optimizing performance
- Improving browser compatibility
- Improving mobile support
- Enhancing the user interface
- Adding new features
- Reviewing pull requests
- Answering community questions
- Suggesting improvements

---

# Development Setup

## Clone the Repository

```bash
git clone https://github.com/rakibul5879/ultimate-ai-lite.git
```

---

## Enter the Project

```bash
cd ultimate-ai-lite
```

---

## Run Locally

Open `index.html` in your browser or use a simple local web server.

Example:

```bash
python -m http.server
```

or

```bash
npx serve
```

---

## Configure the Backend

Deploy the included Cloudflare Worker.

Set your OpenRouter API key as:

```
OPENROUTER_API_KEY
```

Update the Worker endpoint in the application settings.

---

# Project Structure

```
ultimate-ai-lite/

├── index.html
├── worker.js
├── README.md
├── CONTRIBUTING.md
├── SPONSORS.md
├── LICENSE
└── .github/
```

---

# Coding Guidelines

Please follow these principles.

## HTML

- Use semantic HTML.
- Keep the structure clean.
- Avoid unnecessary nesting.

---

## CSS

- Keep styles organized.
- Prefer reusable classes.
- Avoid duplicated rules.
- Maintain responsive layouts.

---

## JavaScript

- Use modern JavaScript where practical.
- Keep functions small.
- Write readable code.
- Avoid global variables when possible.
- Comment complex logic.
- Prefer reusable helper functions.

---

## Performance

Always prioritize:

- Low memory usage
- Fast startup
- Minimal DOM updates
- Efficient rendering
- Small bundle size

---

## Compatibility

Maintain compatibility with:

- Chrome
- Chromium
- Firefox
- Microsoft Edge
- Brave
- Opera

Support older browsers whenever reasonably possible.

---

# Commit Messages

Write clear, descriptive commit messages.

Examples:

```
Add Markdown table rendering

Improve mobile layout

Fix Cloudflare Worker request validation

Optimize local storage handling

Refactor sidebar rendering
```

Avoid messages like:

```
Update

Fix

Changes

Stuff
```

---

# Pull Requests

Before opening a Pull Request, ensure:

- Code builds successfully.
- Existing functionality is not broken.
- No unnecessary dependencies were added.
- Documentation has been updated if needed.
- Formatting is consistent.
- New features have been tested.

Provide a clear description explaining:

- What changed
- Why it changed
- Any limitations
- Screenshots (if UI changes)

---

# Reporting Bugs

When reporting a bug, include:

- Browser
- Browser version
- Operating system
- Steps to reproduce
- Expected behavior
- Actual behavior
- Console errors (if any)
- Screenshots (if applicable)

---

# Suggesting Features

Feature requests should include:

- The problem being solved
- The proposed solution
- Alternative approaches
- Potential drawbacks
- Example use cases

---

# Documentation

Documentation improvements are always welcome.

Examples include:

- README improvements
- API documentation
- Code comments
- Tutorials
- Examples
- Installation guides

---

# Security

If you discover a security vulnerability, please do **not** open a public issue.

Instead, contact the maintainer privately so the issue can be investigated and resolved before disclosure.

---

# Code of Conduct

Please:

- Be respectful.
- Be constructive.
- Welcome newcomers.
- Keep discussions professional.
- Respect differing opinions.
- Focus on improving the project.

Harassment, discrimination, or abusive behavior will not be tolerated.

---

# License

By contributing to Ultimate AI Lite, you agree that your contributions will be licensed under the project's MIT License.

See the LICENSE file for details.

---

# Thank You

Every contribution—whether it is code, documentation, testing, design feedback, or bug reports—helps improve Ultimate AI Lite.

Thank you for supporting the project and helping make it better for everyone.
