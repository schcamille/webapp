# Contributing to webapp

Thank you for your interest in contributing to this project! This document provides guidelines and instructions for contributing.

## Table of Contents

- [Getting Started](#getting-started)
- [Development Setup](#development-setup)
- [How to Contribute](#how-to-contribute)
- [Pull Request Process](#pull-request-process)
- [Code Standards](#code-standards)
- [Testing](#testing)
- [Questions or Issues](#questions-or-issues)

## Getting Started

Before you begin:
- Make sure you have a GitHub account
- Familiarize yourself with the project by reading the [project README](with-strict-csp-app/README.md)
- Check existing [issues](../../issues) and [pull requests](../../pulls) to see if your contribution is already being worked on

## Development Setup

### Prerequisites

- Node.js (latest LTS version recommended)
- npm or yarn package manager

### Setup Instructions

1. Fork the repository on GitHub
2. Clone your fork locally:
   ```bash
   git clone https://github.com/YOUR-USERNAME/webapp.git
   cd webapp
   ```

3. Navigate to the Next.js application directory:
   ```bash
   cd with-strict-csp-app
   ```

4. Install dependencies:
   ```bash
   npm install
   ```

5. Run the development server:
   ```bash
   npm run dev
   ```

6. Open [http://localhost:3000](http://localhost:3000) in your browser to see the application

## How to Contribute

### Reporting Bugs

If you find a bug, please create an issue with:
- A clear, descriptive title
- Detailed steps to reproduce the bug
- Expected behavior vs actual behavior
- Screenshots if applicable
- Your environment details (OS, Node version, browser, etc.)

### Suggesting Enhancements

We welcome suggestions for enhancements! Please create an issue with:
- A clear, descriptive title
- Detailed description of the proposed enhancement
- Any relevant examples or mockups
- Explanation of why this enhancement would be useful

### Contributing Code

1. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature/your-feature-name
   ```
   or
   ```bash
   git checkout -b fix/your-bug-fix
   ```

2. Make your changes following our [code standards](#code-standards)

3. Test your changes thoroughly

4. Commit your changes with a clear commit message:
   ```bash
   git commit -m "Add feature: description of your changes"
   ```

5. Push to your fork:
   ```bash
   git push origin feature/your-feature-name
   ```

6. Create a Pull Request from your fork to the main repository

## Pull Request Process

1. Ensure your code follows the project's code standards
2. Update documentation if needed
3. Make sure all tests pass
4. Provide a clear description of the changes in your PR
5. Link any related issues in the PR description
6. Be responsive to feedback and be prepared to make changes if requested
7. Once approved, a maintainer will merge your PR

## Code Standards

- Write clean, readable, and maintainable code
- Follow existing code style and conventions in the project
- Use meaningful variable and function names
- Comment your code where necessary, especially for complex logic
- Keep functions small and focused on a single task
- Ensure your code works across different browsers and devices

### JavaScript/React Guidelines

- Follow modern JavaScript (ES6+) best practices
- Use functional components and hooks in React
- Keep components modular and reusable
- Avoid inline styles; use CSS modules or styled components as per project conventions

## Testing

Before submitting a pull request:

1. Build the application:
   ```bash
   npm run build
   ```

2. Run the production server to test:
   ```bash
   npm start
   ```

3. Test your changes in multiple browsers if applicable
4. Ensure no console errors or warnings appear

## Questions or Issues

If you have questions about contributing, feel free to:
- Open an issue with the question label
- Reach out to the maintainers

## Code of Conduct

Please note that this project follows a code of conduct. By participating, you are expected to:
- Be respectful and inclusive
- Welcome newcomers and help them get started
- Accept constructive criticism gracefully
- Focus on what is best for the community and project

Thank you for contributing to make this project better!
