
# 🚀 Project VCS Policies

This document outlines the version control system (VCS) policies for managing code in the repository. It includes naming conventions, commit message guidelines, and templates for branches and tags. By following these conventions, we aim to maintain consistency, readability, and traceability across the project.

## 📑 Table of Contents

1. [Naming Conventions](#naming-conventions)
    - [Branch Name Template](#branch-name-template)
    - [Tag Name Template](#tag-name-template)
    - [Commit Message Format](#commit-message-format)
2. [Detailed Documentation](#detailed-documentation)
3. [Contact Information](#contact-information)
4. [References](#references)

## 📛 Naming Conventions

To keep our repository clean, organized, and easy to navigate, we have established the following naming conventions for branches, tags, and commits.

### Branch Name Template

Branches are essential for working on isolated features, bug fixes, or experiments. Use a clear naming structure that reflects the purpose of the branch.


#### Branch Types:
- **feature/**: Used for new features or enhancements.
- **bugfix/**: Used for resolving bugs.
- **hotfix/**: Used for urgent, high-priority fixes that need to go directly into production.
- **release/**: Preparing for a new release.
- **test/**: Used for testing purposes or experimentation.

#### Examples:
- `feature/123-user-authentication`
- `bugfix/456-fix-404-error`
- `hotfix/789-critical-bugfix`
- `release/v2.0.0`

### Tag Name Template

Tags mark specific points in the repository’s history, typically for releases or important milestones. Use the following template for tags:

#### Examples:
- `v1.0.0`: First major release.
- `v1.1.0`: Minor feature updates and improvements.
- `v1.1.1`: Patch for bug fixes.

### Commit Message Format

A clear and consistent commit message format ensures that each commit's purpose is easy to understand, making the repository history more readable.

#### Commit Message Template:
```
<type>(<scope>): <subject>

[optional body]
```

#### Commit Types:
- **feat**: New feature or functionality.
- **fix**: Bug fix.
- **docs**: Documentation-only changes.
- **style**: Code style changes (formatting, no code logic changes).
- **refactor**: Code refactoring without adding new features or fixing bugs.
- **test**: Adding or modifying tests.
- **chore**: Miscellaneous tasks, such as build tasks or dependency updates.

#### Example:
```
feat(auth): add OAuth2 login functionality

- Added OAuth2 login integration for Google and Facebook authentication.
- Updated the user authentication flow to support multiple providers.
```

---

## 📚 Detailed Documentation

For more detailed documentation on setting up and following the VCS policies in this project, please refer to the following sections in the repository's documentation:

- **VCS Workflow Guide**: Instructions on how to create branches, submit merge requests, and manage releases.
- **Commit Message Guidelines**: In-depth guidelines on writing effective commit messages.
- **Branch Management**: Best practices for managing branches and merging.
- **Release Process**: Step-by-step guide for creating and tagging releases.

Documentation can be found [here](link-to-detailed-docs).



## 📧 Contact Information

For any questions or concerns regarding these VCS policies or how to apply them, please contact:

- **Project Manager:** John Doe - [john.doe@example.com](mailto:john.doe@example.com)
- **Development Lead:** Jane Smith - [jane.smith@example.com](mailto:jane.smith@example.com)



## 📚 References

- [Git Branching Naming Best Practices](https://git-scm.com/book/en/v2/Git-Branching-Branching-Workflows)
- [Semantic Versioning](https://semver.org/)
- [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)


### Breakdown:

- **Naming Conventions**: Provides clear guidelines for naming branches, tags, and structuring commit messages to improve project organization.
- **Branch Name Template**: A standardized format for branches, with common types (feature, bugfix, hotfix, etc.).
- **Tag Template**: Follows semantic versioning for marking important points in the repository.
- **Commit Message Format**: Ensures that each commit clearly states its purpose with a consistent format.
- **Detailed Documentation**: Links to further documentation within the project for those seeking in-depth guidance.
- **Contact Information**: Contacts for support or questions about the VCS policies.
- **References**: External resources for deeper understanding of Git workflows, semantic versioning, and commit conventions.

You can replace the placeholder links (e.g., `link-to-detailed-docs`) with actual URLs to your project's documentation or additional resources.
