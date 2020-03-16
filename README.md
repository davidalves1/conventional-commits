## Summary

The Conventional Commits specification is a lightweight convention on top of commit messages. It provides an easy set of rules for creating an explicit commit history; which makes it easier to write automated tools on top of. This convention dovetails with SemVer, by describing the features, fixes, and breaking changes made in commit messages.

The commit message should be structured as follows:

```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```

#### Example:
```
feat: create a subscription button

Create new subscritpion button on main page

Team: @frontendteam
```

## Types

#### Features - `feat`
A new feature

#### Bug Fixes - `fix`
A bug fix

#### Documentation - `docs`
Documentation only changes

#### Styles - `style`
Changes that do not affect the meaning of the code (white-space, formatting, missing semi-colons, etc)

#### Code Refactoring - `refactor`
A code change that neither fixes a bug nor adds a feature

#### Performance Improvements - `perf`
A code change that improves performance

#### Tests - `test`
Adding missing tests or correcting existing tests

#### Builds - `build`
Changes that affect the build system or external dependencies (example scopes: gulp, broccoli, npm)

#### Continuous Integrations - `ci`
Changes to our CI configuration files and scripts (example scopes: Travis, Circle, BrowserStack, SauceLabs)

#### Chores - `chore`
Other changes that don't modify src or test files

#### Reverts - `revert`
Reverts a previous commit

---
- [Oficial site](https://www.conventionalcommits.org/en/v1.0.0/#summary)
- [Commit types](https://github.com/commitizen/conventional-commit-types/blob/master/index.json)
