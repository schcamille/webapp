# Contributing to webapp

Thank you for your interest in contributing to this project! We welcome contributions from the community.

## Table of Contents

- [Getting Started](#getting-started)
- [Development Setup](#development-setup)
- [Making Contributions](#making-contributions)
- [Code Style Guidelines](#code-style-guidelines)
- [Pull Request Process](#pull-request-process)
- [Reporting Issues](#reporting-issues)
- [Community Guidelines](#community-guidelines)

## Getting Started

This is a Next.js webapp project that demonstrates implementing strict Content Security Policy (CSP) with nonces.

Before contributing, please:
- Read through the project [README.md](with-strict-csp-app/README.md) to understand the implementation details
- Check existing issues and pull requests to avoid duplicates
- Familiarize yourself with Next.js and React best practices

## Development Setup

### Prerequisites

- Node.js (latest LTS version recommended)
- npm, yarn, or pnpm package manager
- Git

### Installation

1. Fork the repository on GitHub
2. Clone your fork locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/REPOSITORY-NAME.git
   cd REPOSITORY-NAME
   ```

3. Navigate to the app directory and install dependencies:
   ```bash
   cd with-strict-csp-app
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

4. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the app running

## Making Contributions

### Types of Contributions

We welcome various types of contributions:
- Bug fixes
- Feature enhancements
- Documentation improvements
- Test coverage improvements
- Performance optimizations
- Security improvements

### Contribution Workflow

1. **Create an Issue**: For major changes, create an issue first to discuss what you'd like to change
2. **Fork & Branch**: Create a new branch from `main` for your changes
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/issue-description
   ```
3. **Make Changes**: Implement your changes following our code style guidelines
4. **Test**: Ensure your changes work as expected
5. **Commit**: Write clear, descriptive commit messages
6. **Push**: Push your changes to your fork
7. **Pull Request**: Open a pull request with a clear description of your changes

## Code Style Guidelines

### General Guidelines

- Write clean, readable, and maintainable code
- Follow existing code patterns and conventions in the project
- Use meaningful variable and function names
- Comment complex logic, but prefer self-documenting code
- Keep functions small and focused on a single responsibility

### JavaScript/React Specific

- Use modern JavaScript (ES6+) syntax
- Follow React best practices and hooks patterns
- Use functional components over class components
- Keep component files organized and modular

### Next.js Specific

- Follow Next.js conventions for file structure (pages, components, etc.)
- Use Next.js built-in features appropriately (Image, Link, etc.)
- Implement proper SEO practices with metadata

### Security

- Never commit sensitive information (API keys, passwords, etc.)
- Follow security best practices, especially regarding CSP
- Validate and sanitize user inputs
- Keep dependencies up to date

## Pull Request Process

1. **Update Documentation**: Update the README.md or other documentation if needed
2. **Describe Your Changes**: Provide a clear description of what changes you made and why
3. **Reference Issues**: Link related issues using keywords like "Fixes #123" or "Closes #456"
4. **Keep PRs Focused**: One pull request should address one feature or fix
5. **Respond to Feedback**: Be responsive to code review comments
6. **Ensure CI Passes**: Make sure all automated checks pass

### PR Title Convention

Use descriptive titles with prefixes:
- `feat:` for new features
- `fix:` for bug fixes
- `docs:` for documentation changes
- `refactor:` for code refactoring
- `test:` for adding or updating tests
- `chore:` for maintenance tasks

Example: `feat: add support for custom CSP directives`

## Reporting Issues

When reporting issues, please include:

- **Clear Title**: A descriptive title that summarizes the issue
- **Description**: Detailed description of the problem
- **Steps to Reproduce**: Step-by-step instructions to reproduce the issue
- **Expected Behavior**: What you expected to happen
- **Actual Behavior**: What actually happened
- **Environment**: Browser, Node.js version, OS, etc.
- **Screenshots**: If applicable, add screenshots to help explain the problem

### Issue Labels

We use labels to categorize issues:
- `bug`: Something isn't working
- `enhancement`: New feature or request
- `documentation`: Improvements or additions to documentation
- `good first issue`: Good for newcomers
- `help wanted`: Extra attention is needed

## Community Guidelines

### Code of Conduct

- Be respectful and inclusive
- Welcome newcomers and help them get started
- Provide constructive feedback
- Focus on what is best for the community
- Show empathy towards other community members

### Communication

- Be clear and concise in your communication
- Ask questions if you're unsure about something
- Provide context when reporting issues or requesting features
- Be patient and respectful in discussions

## Questions?

If you have questions about contributing, feel free to:
- Open an issue with the `question` label
- Reach out to the maintainers

Thank you for contributing to this project! 🎉
