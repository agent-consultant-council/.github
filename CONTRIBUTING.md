# Contributing to Agent Consultant Council

Thank you for your interest in contributing to Agent Consultant Council. We welcome bug reports, feature proposals, documentation improvements, architectural discussions, and code contributions.

### Before Contributing

1. Check the repository README and existing documentation.
2. Search existing issues before creating a new one.
3. For significant changes, open an issue or discussion first.
4. Keep changes focused on the responsibility of the repository.

### Development Guidelines

* Follow the existing architecture and conventions.
* Prefer modular and maintainable implementations.
* Avoid unnecessary dependencies.
* Include tests for new functionality where applicable.
* Update documentation when behavior or interfaces change.
* Do not commit secrets, credentials, personal information, or private configuration.
* Maintain compatibility with shared council contracts.

### Branch Naming

Use descriptive branch names:

* `feat/feature-name`
* `fix/bug-description`
* `docs/documentation-update`
* `refactor/component-name`
* `test/test-description`
* `chore/maintenance-task`

### Commit Messages

Use **Conventional Commits**:

* `feat`: New functionality
* `fix`: Bug fixes
* `docs`: Documentation
* `refactor`: Code restructuring
* `test`: Tests
* `chore`: Maintenance

**Example:**
`feat(core): add consultation orchestration`

### Pull Requests

Every pull request should:

1. Describe the problem or motivation.
2. Explain the proposed changes.
3. Reference related issues when applicable.
4. Include testing information.
5. Identify documentation or contract changes.
6. Highlight breaking changes.

Keep pull requests focused and reasonably sized.

### Architecture and Cross-Repository Changes

Changes affecting shared contracts, provider interfaces, security boundaries, or multiple repositories should be discussed before implementation.

Avoid introducing repository-specific behavior that breaks shared ecosystem conventions.

### Security

Never disclose vulnerabilities publicly before coordinating responsible disclosure.

For security concerns, follow the repository's `SECURITY.md` instructions.

### License

By contributing, you agree that your contributions are provided under the license applicable to the repository you are contributing to.
