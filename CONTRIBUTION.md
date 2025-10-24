# Contributing to webapp

Thank you for your interest in contributing to this project! We welcome contributions from the community.

## Table of Contents

- [Getting Started](#getting-started)
- [Development Setup](#development-setup)
- [How to Contribute](#how-to-contribute)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Reporting Issues](#reporting-issues)
- [Code of Conduct](#code-of-conduct)

## Getting Started

Before you begin:
- Make sure you have a GitHub account
- Read through the project documentation in the README.md
- Check existing issues and pull requests to avoid duplicates

## Development Setup

This project contains a Next.js application with strict Content Security Policy (CSP) implementation.

### Prerequisites

- Node.js (LTS version recommended)
- npm, yarn, or pnpm package manager

### Installation

1. Fork the repository on GitHub
2. Clone your fork locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/webapp.git
   cd webapp
   ```

3. Navigate to the application directory:
   ```bash
   cd with-strict-csp-app
   ```

4. Install dependencies:
   ```bash
   npm install
   # or
   yarn install
   # or
   pnpm install
   ```

5. Run the development server:
   ```bash
   npm run dev
   # or
   yarn dev
   # or
   pnpm dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser to see the result.

## How to Contribute

### Types of Contributions

We welcome various types of contributions:

- **Bug fixes**: Found a bug? Please report it or fix it
- **Feature enhancements**: Have an idea? Open an issue to discuss it first
- **Documentation**: Improve or add to our documentation
- **Tests**: Add test coverage or improve existing tests
- **Code quality**: Refactoring, optimization, or improving code readability

### Contribution Workflow

1. **Find or create an issue**: Check if an issue exists for what you want to work on. If not, create one.
2. **Discuss your approach**: Comment on the issue to discuss your proposed solution.
3. **Fork and branch**: Fork the repo and create a feature branch from `main`.
4. **Make your changes**: Implement your changes with clear, concise commits.
5. **Test your changes**: Ensure all tests pass and add new tests if needed.
6. **Submit a pull request**: Open a PR with a clear description of your changes.

## Pull Request Process

1. **Branch naming**: Use descriptive branch names (e.g., `fix/csp-header-bug`, `feature/add-dark-mode`)

2. **Commit messages**: Write clear, concise commit messages:
   ```
   Short (50 chars or less) summary

   More detailed explanatory text, if necessary. Wrap it to about 72
   characters. The blank line separating the summary from the body is
   critical.
   ```

3. **Update documentation**: Update the README.md or other docs if needed.

4. **Add tests**: Include tests for new features or bug fixes.

5. **Run tests**: Ensure all tests pass before submitting:
   ```bash
   npm run build
   npm run start
   ```

6. **Pull request description**: Provide a clear description of:
   - What problem does this solve?
   - How does this change address the problem?
   - Any breaking changes?
   - Screenshots (if applicable)

7. **Review process**: 
   - Your PR will be reviewed by maintainers
   - Address any requested changes
   - Once approved, a maintainer will merge your PR

## Coding Standards

- Follow the existing code style in the project
- Use meaningful variable and function names
- Comment complex logic
- Keep functions small and focused
- Avoid unnecessary dependencies
- Ensure your code works with the strict CSP implementation

### JavaScript/React Best Practices

- Use functional components and hooks
- Follow React best practices
- Ensure Next.js optimizations are maintained
- Test CSP compliance for any new features

## Reporting Issues

When reporting issues, please include:

1. **Description**: A clear and concise description of the issue
2. **Steps to reproduce**: Detailed steps to reproduce the behavior
3. **Expected behavior**: What you expected to happen
4. **Actual behavior**: What actually happened
5. **Environment**: 
   - Node.js version
   - npm/yarn/pnpm version
   - Browser (if applicable)
   - Operating system
6. **Screenshots**: If applicable, add screenshots to help explain the problem
7. **Additional context**: Any other relevant information

### Issue Template

```markdown
**Description**
A clear description of the issue

**Steps to Reproduce**
1. Go to '...'
2. Click on '...'
3. See error

**Expected Behavior**
What should happen

**Actual Behavior**
What actually happens

**Environment**
- Node.js version: 
- Package manager: 
- Browser: 
- OS: 

**Screenshots**
If applicable

**Additional Context**
Any other relevant information
```

## Code of Conduct

### Our Pledge

We are committed to providing a welcoming and inclusive environment for all contributors.

### Expected Behavior

- Be respectful and considerate
- Welcome newcomers and help them get started
- Focus on constructive feedback
- Accept constructive criticism gracefully
- Show empathy towards other community members

### Unacceptable Behavior

- Harassment or discrimination of any kind
- Trolling, insulting, or derogatory comments
- Publishing others' private information
- Any other conduct that could be considered inappropriate

### Enforcement

Instances of abusive, harassing, or otherwise unacceptable behavior may be reported to the project maintainers. All complaints will be reviewed and investigated promptly and fairly.

## Questions?

If you have questions or need help, feel free to:
- Open an issue with the "question" label
- Reach out to the maintainers

## License

By contributing to this project, you agree that your contributions will be licensed under the same license as the project.

---

Thank you for contributing to webapp! 🎉
