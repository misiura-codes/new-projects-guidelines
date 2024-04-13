# Git Branch Naming Conventions Guide

## Overview

Proper branch naming conventions in Git are essential for maintaining a clean and organized codebase, especially in team environments. This guide outlines best practices for naming branches to ensure clarity, consistency, and efficiency in your development workflow.

## Basic Rules

1. **Lowercase and Hyphen-separated:** Use lowercase letters and hyphens to separate words in branch names. For example: `feature/new-login` or `bugfix/header-styling`.
2. **Alphanumeric Characters:** Stick to alphanumeric characters (a-z, 0–9) and hyphens. Avoid punctuation, spaces, underscores, or any non-alphanumeric characters.
3. **Descriptive:** Make branch names descriptive and concise, reflecting the work done on the branch.

## Branch Prefixes

Using prefixes in branch names helps to quickly identify the purpose of each branch. Here are common prefixes and their meanings:

| Prefix         | Meaning                                           | Example Branch Name                   |
|----------------|---------------------------------------------------|---------------------------------------|
| feature/       | Developing new features                           | `feature/login-system`                |
| bugfix/        | Fixing bugs                                       | `bugfix/issue123-fix-crash`           |
| hotfix/        | Quickly fixing critical issues in production      | `hotfix/urgent-security-patch`        |
| release/       | Preparing for a new production release            | `release/v1.0.0`                      |
| docs/          | Writing, updating, or fixing documentation        | `docs/update-readme`                  |
| experimental/  | Experimenting with new ideas or approaches        | `experimental/new-ui-design`          |
| refactor/      | Refactoring code                                  | `refactor/update-database-schema`     |
| ui/            | For user interface changes                        | `ui/update-login-page`                |

## Additional Best Practices

1. **Use Separators:** Incorporate separators like hyphens or slashes for readability, but maintain consistency across all branch names. For example: `optimize-component-load`.
2. **Start with Category Word:** Begin branch names with a category word to indicate the type of task being solved.
3. **Include Issue ID:** Integrating the ID of related issues in branch names aids in easy tracking, especially when solving specific tasks. For instance, a branch named `bugfix/T-981-optimize-data-analysis` indicates that the task of optimizing data analysis is related to issue/ticket 981.
4. **Avoid Using Numbers Only:** Combine issue IDs with descriptive keywords to avoid confusion and mistakes.
5. **Avoid Long Branch Names:** Keep branch names precise and short to maintain readability and efficiency.
6. **Be Consistent:** Stick to chosen conventions throughout the project for clarity and ease of maintenance.

### Use Separators

| :white_check_mark: How to do         | :x: How not to do                     |
|---------------------------------------|---------------------------------------|
| `feature/user-authentication`        | `featureUserAuthentication`           |
| `bugfix/issue123-fix-crash`          | `bugfix-issue123-fix-crash`           |
| `docs/update-readme`                 |                                       |

### Start with Category Word

| :white_check_mark: How to do         | :x: How not to do                     |
|---------------------------------------|---------------------------------------|
| `feature/new-login`                  | `new-login-feature`                   |
| `bugfix/header-styling`              | `header-styling-bugfix`               |
| `hotfix/critical-security-issue`     |                                       |

### Include Issue ID

| :white_check_mark: How to do         | :x: How not to do                     |
|---------------------------------------|---------------------------------------|
| `T-187-optimize-component-load`      | `optimize-component-load`             |
| `bugfix-1234-broken-link-fix`        | `broken-link-fix`                     |

### Avoid Using Numbers Only

| :white_check_mark: How to do         | :x: How not to do                     |
|---------------------------------------|---------------------------------------|
| `feature/T-456-user-authentication`  | `456-user-authentication`             |
| `bugfix/T-789-fix-header-styling`    | `789-fix-header-styling`              |

### Avoid Long Branch Names

| :white_check_mark: How to do         | :x: How not to do                     |
|---------------------------------------|---------------------------------------|
| `refactor/update-database-schema`     | `refactor/update-database-schema-to-fix-bugs` |
| `hotfix/urgent-security-patch`       | `hotfix-for-fixing-security-issues-in-production` |

### Be Consistent

By following these conventions, you can ensure a clear and structured approach to managing branches in your Git repository, facilitating collaboration and maintaining a well-organized codebase.
