# gh-exec

Use remote github repositories as easily executable modules.

## Requirements

- Bash
- Git

## Usage

> gh_exec [options] \<github-repo-path\>

### Example

```bash
gh_exec -e git_github/init_repo.sh yennanliu/utility_shell "my-repo"
```

```bash
gh_exec getlicense MIT >> LICENSE
```

## License

This repository is released under [MIT License](LICENSE).