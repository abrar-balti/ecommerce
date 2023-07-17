# Pre-Commit Hooks

This repository includes several pre-commit hooks to help enforce code quality and best practices. These hooks will be run automatically when you run git commit.

## Install the following in your system

- pre-commit>=2.0.0

```sh
cd <repo_directory>
pip install pre-commit
```

- shellcheck:
  Visit this [link](https://github.com/koalaman/shellcheck#installing) for detailed installation instructions.
- Terraform-docs:
  Visit this [link](https://terraform-docs.io/user-guide/installation/) for detailed installation instructions.
- Terraform-lint: Visit this [link](https://github.com/terraform-linters/tflint) for detailed installation instructions.

## Usage Instructions

Install the pre-commit hooks in your repository home directory:

```sh
pre-commit install -f --config pre-commit-config/.pre-commit-config.yaml
```

## Hooks

---

<!-- TODO -->