# Contributing to Cipher Units

Thanks for your interest in contributing! This guide applies to every repository under the **Cipher Units** organization unless a specific repo has its own `CONTRIBUTING.md`.

## Before you start

- Check open [Issues](../../issues) and [Pull Requests](../../pulls) to avoid duplicating work.
- For anything non-trivial (new features, breaking changes), open an issue first to discuss the approach before writing code.
- Small fixes (typos, docs, obvious bugs) can go straight to a PR.

## Getting set up

1. **Fork** the repository you want to contribute to.
2. **Clone** your fork:
   ```bash
   git clone https://github.com/<your-username>/<repo-name>.git
   cd <repo-name>
   ```
3. **Add the upstream remote** so you can keep your fork in sync:
   ```bash
   git remote add upstream https://github.com/cipherunits/<repo-name>.git
   ```
4. **Install dependencies** using the method documented in that repo's `README.md` (most use `pnpm install` or `make install`).
5. **Create a branch** for your work:
   ```bash
   git checkout -b feat/short-description
   ```

## Branch naming

| Prefix      | Use for                          |
| ----------- | --------------------------------- |
| `feat/`     | New features                      |
| `fix/`      | Bug fixes                         |
| `docs/`     | Documentation-only changes        |
| `chore/`    | Tooling, CI, dependency bumps     |
| `refactor/` | Code changes with no behavior change |

## Commit messages

We loosely follow [Conventional Commits](https://www.conventionalcommits.org/):

```
type(scope): short summary

Optional longer description.
```

Examples: `feat(header): add responsive dropdown`, `fix(otp): correct input sizing at 6 digits`.

## Before opening a pull request

- Run the linter: `pnpm lint` or `make lint`
- Run the build to make sure nothing is broken: `pnpm build` or `make build-app`
- Run tests if the repo has them
- Keep the PR focused — one logical change per PR is easier to review than a bundle of unrelated fixes
- Update relevant docs (`README.md`, `docs/`) if your change affects usage

## Opening the pull request

1. Push your branch to your fork and open a PR against the repo's `main` branch.
2. Fill out the PR template — describe **what** changed and **why**, and link any related issue.
3. Be ready for review feedback; we may ask for changes before merging.
4. Once approved, a maintainer will merge it.

## Reporting bugs / requesting features

Please use the issue templates provided in this repository (Bug Report / Feature Request) rather than opening a blank issue — it helps us triage faster.

## Code of Conduct

By participating, you agree to follow our [Code of Conduct](./CODE_OF_CONDUCT.md).

## Security issues

Do **not** open a public issue for security vulnerabilities. See [SECURITY.md](./SECURITY.md) instead.

---

Questions? Reach out at **cipherunit.dev@gmail.com**.
