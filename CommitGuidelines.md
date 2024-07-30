**Company Commit Guideline**
-
**Types of commits**

-   `feat`  – a new feature is introduced with the changes
-   `fix`  – a bug fix has occurred
-   `chore`  – changes that do not relate to a fix or feature and don't modify src or test files (for example updating dependencies)
-   `refactor`  – refactored code that neither fixes a bug nor adds a feature
-   `docs`  – updates to documentation such as a the README or other markdown files
-   `style`  – changes that do not affect the meaning of the code, likely related to code formatting such as white-space, missing semi-colons, and so on.
-   `test`  – including new or correcting previous tests
-   `perf`  – performance improvements
-   `ci`  – continuous integration related
-   `build`  – changes that affect the build system or external dependencies
-   `revert`  – reverts a previous commit

You can append a type like so ex:
-   `test-red`  –  a failing test that requires implementation

**Structure of Commit**
```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```
Ex:
```
feat : a student can be added to the database

This allows us to persist the registration of a student

Completes User Story #321
```

**Tips**

- Commit frequently, add a commit for every small change/block of change you make

**Code Reviewers**
- Squash and merge changes into well wrapped user story completion

**Example Commit History**
**Company Commit Guideline**
-
**Types of commits**

-   `feat`  – a new feature is introduced with the changes
-   `fix`  – a bug fix has occurred
-   `chore`  – changes that do not relate to a fix or feature and don't modify src or test files (for example updating dependencies)
-   `refactor`  – refactored code that neither fixes a bug nor adds a feature
-   `docs`  – updates to documentation such as a the README or other markdown files
-   `style`  – changes that do not affect the meaning of the code, likely related to code formatting such as white-space, missing semi-colons, and so on.
-   `test`  – including new or correcting previous tests
-   `perf`  – performance improvements
-   `ci`  – continuous integration related
-   `build`  – changes that affect the build system or external dependencies
-   `revert`  – reverts a previous commit

You can append a type like so ex:
-   `test-red`  –  a failing test that requires implementation

**Structure of Commit**
```
<type>[optional scope]: <description>

[optional body]

[optional footer(s)]
```
Ex:
```
feat : a student can be added to the database

This allows us to persist the registration of a student

Completes User Story #321
```

**Tips**

- Commit frequently, add a commit for every small change/block of change you make

**Code Reviewers**
- Squash and merge changes into well wrapped user story completion

**Example Commit History**



**Tools**

To help enforce good commit messages we can use [commitizen](https://commitizen-tools.github.io/commitizen/)

**Ressources**

https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/


**Tools**

To help enforce good commit messages we can use [commitizen](https://commitizen-tools.github.io/commitizen/)

**Ressources**

https://www.freecodecamp.org/news/how-to-write-better-git-commit-messages/
