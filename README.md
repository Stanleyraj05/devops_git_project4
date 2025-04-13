# DevOps Git Project

This project demonstrates Git best practices including branching, pull requests, tagging, and version control workflows.

## Branches
- `main`: Stable release branch
- `dev`: Integration branch for new features
- `feature/<feature-name>`: For individual features

## Usage
- Clone the repo
- Create feature branches from `dev`
- Use pull requests to merge into `dev`, then into `main`
- Use tags for version releases

## Tools Used
- Git
- GitHub

- # DevOps Git Project

This project demonstrates Git best practices including branching strategies, pull requests, tagging, and effective version control workflows. The goal is to simulate a real-world DevOps workflow using Git and GitHub.

## 🔧 Git Best Practices Followed

### 1. 🗃️ Repository Initialization
- The Git repository was initialized with a `.gitignore` to avoid tracking unnecessary files.
- Initial commits contain essential documentation files like `README.md` and `documentation.md`.

### 2. 🌿 Branching Strategy
- **main**: Stable production-ready code.
- **dev**: Integration branch where features are tested before going live.
- **feature/<feature-name>**: Dedicated branches for individual features or tasks.

> Feature branches are always created from `dev`.

### 3. 🔁 Pull Requests
- Pull Requests (PRs) are used to merge `feature/*` branches into `dev`.
- After successful testing, `dev` is merged into `main`.
- PRs include detailed descriptions and are reviewed before merging.

### 4. 🏷️ Git Tags
- Annotated tags are used to mark important releases.
```bash
git tag -a v1.0 -m "First stable release"


## Author
Stanley Raj Kumar
## Sample Feature Update
