# Contributing to webapp

Thank you for your interest in contributing to this project! We welcome contributions from everyone.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Getting Started](#getting-started)
- [How to Contribute](#how-to-contribute)
- [Development Setup](#development-setup)
- [Pull Request Process](#pull-request-process)
- [Coding Standards](#coding-standards)
- [Testing](#testing)
- [Reporting Bugs](#reporting-bugs)
- [Feature Requests](#feature-requests)

## Code of Conduct

By participating in this project, you are expected to uphold a respectful and collaborative environment. Please be kind and courteous to others.

## Getting Started

1. Fork the repository on GitHub
2. Clone your fork locally
3. Create a new branch for your contribution
4. Make your changes
5. Test your changes
6. Submit a pull request

## How to Contribute

There are many ways to contribute to this project:

- **Report bugs**: If you find a bug, please create an issue with detailed information
- **Suggest features**: Have an idea? Open an issue to discuss it
- **Submit pull requests**: Fix bugs, add features, or improve documentation
- **Improve documentation**: Help make our docs better
- **Review pull requests**: Provide feedback on open PRs

## Development Setup

This project contains a Next.js application with strict Content Security Policy (CSP).

### Prerequisites

- Node.js (latest LTS version recommended)
- npm, yarn, or pnpm

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/schcamille/webapp.git
   cd webapp
   ```

2. Navigate to the application directory:
   ```bash
   cd with-strict-csp-app
   ```

3. Install dependencies:
   ```bash
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

5. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application.

### Building for Production

```bash
npm run build
# or
yarn build
# or
pnpm build
```

### Starting Production Server

```bash
npm start
# or
yarn start
# or
pnpm start
```

## Pull Request Process

1. **Create a new branch**: Use a descriptive name for your branch
   ```bash
   git checkout -b feature/your-feature-name
   ```

2. **Make your changes**: Keep changes focused and atomic

3. **Test your changes**: Ensure your changes work as expected

4. **Commit your changes**: Write clear, concise commit messages
   ```bash
   git commit -m "Add: brief description of your changes"
   ```

5. **Push to your fork**:
   ```bash
   git push origin feature/your-feature-name
   ```

6. **Open a pull request**: 
   - Provide a clear title and description
   - Reference any related issues
   - Describe what changes you made and why

7. **Address review feedback**: Be responsive to comments and questions

8. **Wait for approval**: A maintainer will review and merge your PR

## Coding Standards

- Follow the existing code style in the project
- Use meaningful variable and function names
- Write clear comments for complex logic
- Keep functions small and focused
- Ensure your code is properly formatted

### JavaScript/React Guidelines

- Use modern ES6+ syntax
- Follow React best practices
- Use functional components with hooks when possible
- Keep components small and reusable

## Testing

- Test your changes manually by running the development server
- Ensure the application builds successfully
- Verify that existing functionality still works
- If applicable, add tests for new features

## Reporting Bugs

When reporting bugs, please include:

- **Clear title**: A descriptive summary of the issue
- **Description**: Detailed explanation of the problem
- **Steps to reproduce**: How to trigger the bug
- **Expected behavior**: What should happen
- **Actual behavior**: What actually happens
- **Environment**: Browser, OS, Node.js version, etc.
- **Screenshots**: If applicable

## Feature Requests

We welcome feature suggestions! When requesting a feature:

- Check if the feature already exists or has been requested
- Provide a clear description of the feature
- Explain why this feature would be useful
- Include examples or use cases if possible

## Questions?

If you have questions or need help, feel free to:

- Open an issue for discussion
- Reach out to the maintainers

---

Thank you for contributing to this project! 🎉
