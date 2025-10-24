# Contributing to webapp

Thank you for your interest in contributing to this project! We appreciate your help in making this webapp better.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
- [Development Process](#development-process)
- [Submitting Changes](#submitting-changes)
- [Coding Guidelines](#coding-guidelines)
- [Reporting Bugs](#reporting-bugs)
- [Suggesting Enhancements](#suggesting-enhancements)

## Code of Conduct

By participating in this project, you are expected to uphold a standard of respectful and professional conduct. Please be considerate and respectful of others.

## Getting Started

1. **Fork the repository** on GitHub
2. **Clone your fork** locally:
   ```bash
   git clone https://github.com/YOUR_USERNAME/webapp.git
   cd webapp
   ```
   (Replace `YOUR_USERNAME` with your GitHub username)
3. **Navigate to the project directory**:
   ```bash
   cd with-strict-csp-app
   ```
4. **Install dependencies**:
   ```bash
   npm install
   ```
5. **Run the development server**:
   ```bash
   npm run dev
   ```

The application will be available at `http://localhost:3000`.

## How to Contribute

There are many ways to contribute to this project:

- Report bugs
- Suggest new features or enhancements
- Improve documentation
- Submit pull requests with bug fixes or new features
- Review pull requests

## Development Process

1. **Create a new branch** for your work:
   ```bash
   git checkout -b feature/your-feature-name
   ```
   or
   ```bash
   git checkout -b fix/your-bug-fix
   ```

2. **Make your changes** following the coding guidelines

3. **Test your changes**:
   ```bash
   npm run build
   npm run start
   ```

4. **Commit your changes** with clear, descriptive commit messages:
   ```bash
   git add .
   git commit -m "Description of your changes"
   ```

## Submitting Changes

1. **Push your changes** to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

2. **Create a Pull Request** from your fork to the main repository

3. **Describe your changes** clearly in the pull request description:
   - What problem does it solve?
   - How does it work?
   - Any breaking changes?
   - Screenshots (if applicable)

4. **Wait for review** - maintainers will review your pull request and may request changes

## Coding Guidelines

- Follow the existing code style and conventions
- Write clear, self-documenting code
- Add comments for complex logic
- Ensure your code works in both development and production environments
- Keep changes focused and minimal - one feature or fix per pull request
- Test your changes thoroughly before submitting

### JavaScript/React Best Practices

- Use functional components and React Hooks
- Follow Next.js conventions and best practices
- Maintain the Content Security Policy (CSP) standards
- Avoid inline styles; use appropriate styling methods

## Reporting Bugs

When reporting bugs, please include:

1. **Clear title and description** of the issue
2. **Steps to reproduce** the bug
3. **Expected behavior** vs **actual behavior**
4. **Environment details**:
   - Node.js version
   - npm version
   - Browser (if applicable)
   - Operating system
5. **Screenshots or error messages** (if applicable)

## Suggesting Enhancements

When suggesting enhancements:

1. **Check existing issues** to avoid duplicates
2. **Clearly describe the enhancement** and its benefits
3. **Explain use cases** where this would be helpful
4. **Consider backwards compatibility** and breaking changes

## Questions?

If you have questions about contributing, feel free to open an issue with the "question" label.

Thank you for contributing!
