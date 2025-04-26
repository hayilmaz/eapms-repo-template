# Contributing to EAPMS Projects

Thank you for your interest in contributing to the EAPMS project! This document outlines the process for contributing to our repositories.

## Code of Conduct

This project adheres to the [Contributor Covenant Code of Conduct](CODE_OF_CONDUCT.md). By participating, you are expected to uphold this code.

## Development Process

1. **Create an Issue**: All changes should be linked to an Issue. If none exists, create one.

2. **Branch from Develop**: Create a feature branch from `develop` following the naming convention:
   ```
   feature/issue-number-brief-description
   ```
   For bugs, use:
   ```
   fix/issue-number-brief-description
   ```

3. **Follow Coding Standards**: Adhere to the project's coding style and linting rules.

4. **Commit Guidelines**: Use Conventional Commits format:
   ```
   feat: add new user authentication feature
   ```
   ```
   fix: resolve login page redirect issue
   ```

5. **Complexity Management**: 
   - Assess the complexity your change adds
   - Document it in the PR template
   - If your change exceeds 5 complexity points, additional review is required

6. **Testing**: Ensure your code includes appropriate tests.

7. **Documentation**: Update documentation as needed.

8. **Pull Request**: Submit a PR against the `develop` branch with a clear description.

## Pull Request Process

1. Fill out the PR template completely
2. Ensure CI checks pass
3. Request review from at least one team member
4. Address any feedback
5. Once approved, the PR will be merged

## Knowledge Management

All significant decisions should be documented. For architectural decisions:

1. Create an ADR (Architectural Decision Record) in the `/docs/decisions` directory
2. Use the standard template
3. Link the ADR in your PR description

## Questions?

If you have any questions, please reach out to the project maintainers or query the LightRAG knowledge base.