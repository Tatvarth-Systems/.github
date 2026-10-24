# Contributing

Thanks for your interest in Tatvarth Systems projects. Most of our repositories are private;
this guide applies to anyone with access.

## Workflow

1. Branch from the default branch using the commit-type vocabulary: `feat/…`, `fix/…`, `chore/…`.
2. Make small, focused changes.
3. Open a pull request. Merge to the default branch happens only through a pull request with
   passing CI.
4. Never commit secrets, `.env` files, or credentials. If you do by mistake, tell a maintainer
   immediately so the secret can be rotated.

## Commit messages

We follow [Conventional Commits](https://www.conventionalcommits.org/): `type(scope): subject`,
lowercase, imperative, no trailing period. Types: `feat`, `fix`, `refactor`, `chore`, `docs`,
`style`, `test`, `ci`, `build`, `perf`, `revert`.

## Security

Report vulnerabilities privately; see [SECURITY.md](SECURITY.md).

## Conduct

Participation is governed by our [Code of Conduct](CODE_OF_CONDUCT.md).
