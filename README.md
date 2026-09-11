# ci-workflows

Shared GitHub Actions workflows for the cear12 repositories.

| Workflow | Used by |
|---|---|
| `.github/workflows/cmake.yml` | idioms-cpp, parallel-cpp, cryptographic-techniques-cpp, ai-cpp, code-snippets-cpp |
| `.github/workflows/flutter.yml` | oleenglishbuddy-git, oleprogerbuddy-git, olevoicebuddy-git |
| `.github/workflows/gitleaks.yml` | every private repo |

Callers pin a major tag: `uses: cear12/ci-workflows/.github/workflows/cmake.yml@v1`.
After changing a workflow, move the tag: `git tag -f v1 && git push -f origin v1`.
