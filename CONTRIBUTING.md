# Contributing to TruthChat

## The "Verifier" Philosophy
Every line of code committed to TruthChat is a claim. Our CI system is the Verifier.
**Do not bypass the verifier.**

## Pull Request Standards
1. **Linear History:** We use "Squash and Merge". Ensure your PR title is descriptive.
2. **Signed Commits:** All commits MUST be signed. Unsigned commits are rejected.
3. **Tests:** New features require new unit tests (pytest).
4. **Documentation:** Update the docs/ folder. Evidence of functionality is required.

## Development Environment
To ensure reproducibility:
1. Use the provided devcontainer.json.
2. Do not introduce dependencies not locked in poetry.lock.
