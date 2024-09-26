
### 1. **`feature/`**
   - **Purpose**: Used for new features or enhancements.
   - **Example**: `feature/user-authentication`
   - **When to use**: When you’re adding new functionality to the codebase.

### 2. **`bugfix/`**
   - **Purpose**: For branches that contain fixes for bugs or issues.
   - **Example**: `bugfix/fix-login-error`
   - **When to use**: When you're resolving a bug or error in the code.

### 3. **`hotfix/`**
   - **Purpose**: For urgent fixes that need to be made to the production environment.
   - **Example**: `hotfix/critical-security-patch`
   - **When to use**: For critical changes that need to be addressed immediately in production.

### 4. **`chore/`**
   - **Purpose**: For routine tasks or maintenance that don't change functionality.
   - **Example**: `chore/update-dependencies`
   - **When to use**: For tasks like updating dependencies, cleaning up code, or updating configurations.

### 5. **`refactor/`**
   - **Purpose**: For code refactoring without changing the external behavior or adding new features.
   - **Example**: `refactor/optimize-search-algorithm`
   - **When to use**: When you’re improving code structure, readability, or performance without adding features or fixing bugs.

### 6. **`test/`**
   - **Purpose**: For branches that add or modify tests.
   - **Example**: `test/add-integration-tests`
   - **When to use**: When writing new tests or improving existing test coverage.

### 7. **`docs/`**
   - **Purpose**: For documentation changes.
   - **Example**: `docs/update-readme`
   - **When to use**: When adding or updating documentation files.

### 8. **`ci/`**
   - **Purpose**: For changes related to Continuous Integration/Continuous Deployment (CI/CD) configuration.
   - **Example**: `ci/update-github-actions`
   - **When to use**: When updating or adding CI/CD configuration files or scripts.

### 9. **`revert/`**
   - **Purpose**: For branches that revert previous changes.
   - **Example**: `revert/revert-bugfix-login-error`
   - **When to use**: When you need to undo a previous commit or merge.

### 10. **`release/`**
   - **Purpose**: For preparing a release version.
   - **Example**: `release/v1.2.0`
   - **When to use**: When you’re preparing for a new version release of your software.




### Dependencies

`standard-version`
Automates versioning and changelog generation based on commits.

`Semantic Release` 
an automated versioning and package publishing tool that helps streamline the release process for software projects.


`Semantic Release` automatically determines the next version number (`major`, `minor`, or `patch`) based on the commit messages in your repository

- `Major version`: Introduces breaking changes (e.g., `1.0.0` → `2.0.0`)
- `Minor version`: Adds new features in a backwards-compatible manner (e.g., `1.0.0` → `1.1.0`)
- `Patch version`: Bug fixes that are backwards-compatible (e.g., `1.0.0` → `1.0.1`)



`semantic-release/git`
Responsible for handling version tagging and Git-related tasks. Here are its main functionalities:

`semantic-release/github`
Responsible for automating the creation and management of GitHub releases. 

`semantic-release/commit-analyzer` 
Determines the version number for a release based on the commit messages in your repository.

