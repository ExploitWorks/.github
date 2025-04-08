# Contributing to ExploitWorks Projects

Thank you for your interest in contributing to ExploitWorks! We're excited to have you join our community of security professionals and developers working on open-source security tools.

## Table of Contents

- [Code of Conduct](#code-of-conduct)
- [Security Considerations](#security-considerations)
- [How to Contribute](#how-to-contribute)
  - [Reporting Issues](#reporting-issues)
  - [Feature Requests](#feature-requests)
  - [Pull Requests](#pull-requests)
- [Development Process](#development-process)
  - [Setting Up Your Environment](#setting-up-your-environment)
  - [Coding Standards](#coding-standards)
  - [Testing](#testing)
- [Ethical Guidelines](#ethical-guidelines)
- [Communication](#communication)

## Code of Conduct

We are committed to providing a welcoming and inclusive experience for everyone. Please read our [Code of Conduct](https://github.com/ExploitWorks/.github/blob/main/CODE_OF_CONDUCT.md) before participating.

## Security Considerations

Given the nature of our projects, security is of utmost importance:

- **Responsible Disclosure**: If you discover a security vulnerability, please do NOT open a public issue. Instead, email us at [contact-exploitworks@pm.me](mailto:contact-exploitworks@pm.me).
- **Tool Usage**: All tools are designed for ethical use only. Contributors must ensure their code does not introduce unintended vulnerabilities.
- **Sensitive Features**: Any feature that could be potentially misused must include adequate safeguards and documentation.

## How to Contribute

### Reporting Issues

- Check existing issues first to avoid duplicates
- Use our issue templates where available
- Include detailed information:
  - Steps to reproduce
  - Expected vs. actual behavior
  - Screenshots or logs (with sensitive information redacted)
  - Environment details (OS, software versions)
  - Any potential solutions you've considered

### Feature Requests

- Use the feature request template
- Provide a clear use case
- Explain how this feature aligns with the project's goals
- Consider potential ethical implications

### Pull Requests

1. **Fork the repository** and create your branch from `main`
2. **Install development dependencies** according to project-specific instructions
3. **Make your changes**, adhering to the coding standards
4. **Add tests** for your changes
5. **Run the test suite** to ensure nothing breaks
6. **Update documentation** to reflect any changes
7. **Submit your pull request** using our PR template

## Development Process

### Setting Up Your Environment

Each project has specific setup instructions in its README, but generally:

```bash
# Clone your fork of the repository
git clone https://github.com/your-username/project-name.git

# Add the main repository as 'upstream'
git remote add upstream https://github.com/ExploitWorks/project-name.git

# Create a branch for your work
git checkout -b feature/your-feature-name
```

### Coding Standards

- Follow existing code style and conventions
- Use meaningful variable and function names
- Comment your code when necessary, especially for complex security-related logic
- Keep functions focused and modular
- Language-specific guidelines:
  - Python: Follow PEP 8 style guide
  - Shell: Use POSIX-compliant syntax where possible
  - JavaScript/TypeScript: Follow ESLint configuration

### Testing

- Write tests for all new features and bug fixes
- Ensure existing tests pass locally before submitting
- For security tools, include negative tests to verify proper error handling

## Ethical Guidelines

- All contributions must be intended for ethical use
- Code must not contain backdoors, malicious functionality, or privacy violations
- Features should be designed with the principle of "do no harm"
- Documentation should emphasize proper, legal use of tools

## Communication

- **Issues**: Use GitHub issues for bug reports and feature discussions
- **Pull Requests**: For code contributions and reviews
- **Discussions**: Join GitHub Discussions for broader topics and questions
- **Chat**: For real-time communication (if applicable to your project)

Thank you for contributing to making security tools more accessible, effective, and ethical! 
