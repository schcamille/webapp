# Contributing to webapp

Thank you for your interest in contributing to this project! We welcome contributions from the community.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [Development Setup](#development-setup)
- [How to Contribute](#how-to-contribute)
- [Coding Guidelines](#coding-guidelines)
- [Commit Guidelines](#commit-guidelines)
- [Pull Request Process](#pull-request-process)
- [Reporting Issues](#reporting-issues)
- [Questions](#questions)

## Code of Conduct

By participating in this project, you agree to maintain a respectful and inclusive environment for everyone.

## Getting Started

Before you begin:
- Make sure you have a GitHub account
- Familiarize yourself with the project by reading the README.md
- Check existing issues and pull requests to avoid duplication

## Development Setup

### Prerequisites

- Node.js (v14 or higher recommended)
- npm, yarn, or pnpm package manager
- Git

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

### Running the Development Server

Start the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

The application will be available at [http://localhost:3000](http://localhost:3000).

### Building the Project

To create a production build:

```bash
npm run build
# or
yarn build
# or
pnpm build
```

### Starting the Production Server

After building, you can start the production server:

```bash
npm start
# or
yarn start
# or
pnpm start
```

## How to Contribute

### Reporting Bugs

If you find a bug, please create an issue with:
- A clear, descriptive title
- A detailed description of the issue
- Steps to reproduce the problem
- Expected behavior vs. actual behavior
- Screenshots (if applicable)
- Environment details (OS, Node version, browser, etc.)

### Suggesting Enhancements

We welcome suggestions for new features or improvements:
- Create an issue with a clear title and detailed description
- Explain why this enhancement would be useful
- Provide examples if possible

### Submitting Code Changes

1. **Create a branch** for your changes:
   ```bash
   git checkout -b feature/your-feature-name
   # or
   git checkout -b fix/your-bug-fix
   ```

2. **Make your changes** following our coding guidelines

3. **Test your changes** thoroughly:
   - Ensure the development server runs without errors
   - Test the production build
   - Verify all existing functionality still works

4. **Commit your changes** with clear, descriptive commit messages

5. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Open a Pull Request** against the main repository

## Coding Guidelines

### JavaScript/React Best Practices

- Use functional components and React Hooks
- Follow React best practices for component structure
- Write clean, readable, and maintainable code
- Add comments for complex logic

### Styling

- Follow the existing code style in the project
- Use consistent formatting (consider using Prettier)
- Keep components modular and reusable

### Content Security Policy (CSP)

This project implements strict CSP with nonces. When adding new features:
- Be aware of CSP restrictions
- Avoid inline scripts and styles without proper nonce handling
- Test that your changes work with the CSP configuration

## Commit Guidelines

Write clear, concise commit messages:

- Use the present tense ("Add feature" not "Added feature")
- Use the imperative mood ("Move cursor to..." not "Moves cursor to...")
- Limit the first line to 72 characters or less
- Reference issues and pull requests liberally after the first line

Example:
```
Add user authentication feature

- Implement login form component
- Add authentication middleware
- Update user context provider

Fixes #123
```

## Pull Request Process

1. **Update documentation** if you're adding or changing functionality
2. **Ensure your code follows** the project's coding guidelines
3. **Test your changes** thoroughly
4. **Update the README.md** if necessary
5. **Fill out the pull request template** completely
6. **Wait for review** - maintainers will review your PR and may request changes

### Pull Request Review

- Address all review comments
- Keep the conversation focused and professional
- Be patient - reviews may take time
- Make requested changes in new commits (don't force push during review)

## Reporting Issues

### Security Vulnerabilities

If you discover a security vulnerability, please DO NOT open a public issue. Instead:
- Email the maintainers directly (if contact information is available)
- Provide a detailed description of the vulnerability
- Wait for acknowledgment before disclosing publicly

### Bug Reports

Use the GitHub issue tracker to report bugs. Include:
- Steps to reproduce
- Expected vs. actual behavior
- Environment details
- Screenshots or error logs if applicable

### Feature Requests

Feature requests are welcome! Please:
- Check if the feature has already been requested
- Provide a clear use case
- Explain how it benefits the project

## Questions

If you have questions:
- Check existing documentation first
- Search closed issues - your question may have been answered
- Open a new issue with the "question" label
- Be specific and provide context

## License

By contributing, you agree that your contributions will be licensed under the same license as the project.

---

Thank you for contributing to webapp! 🎉
