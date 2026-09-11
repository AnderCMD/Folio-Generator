# Contributing to Folio Generator

Thanks for taking the time to contribute! This repository hosts two npm packages:

-   [`folio-generator-js`](Languages/JavaScript) — plain JavaScript implementation.
-   [`folio-generator-ts`](Languages/TypeScript) — TypeScript implementation.

Both packages are already used in production projects, so backward compatibility matters. Please keep that in mind when proposing changes.

## Getting started

1. Fork the repository and clone your fork.
2. Pick the package you want to work on and install its dependencies:

    ```bash
    cd Languages/JavaScript && npm install
    # or
    cd Languages/TypeScript && npm install
    ```

3. Make your changes, keeping the two implementations in sync when a change applies to both (fixing a bug in one usually means fixing it in the other).

## Running tests

```bash
# JavaScript
cd Languages/JavaScript
npm test

# TypeScript
cd Languages/TypeScript
npm run build
npm test
```

All pull requests are automatically tested against multiple Node.js versions via GitHub Actions (see `.github/workflows/ci.yml`).

## Submitting changes

1. Create a branch for your change: `git checkout -b fix/my-fix`.
2. Add or update tests for any behavior you change.
3. Update the relevant `README.md` if you change the public API.
4. Open a pull request describing the motivation and the change. Link any related issue.

## Reporting bugs / requesting features

Please use the issue templates when opening a new issue — they help us gather the information needed to triage quickly.

## Code style

-   Keep the code dependency-free (no runtime dependencies).
-   Favor small, well-tested, pure functions.
-   Match the existing formatting (tabs for indentation, single quotes) used in each package.

## Reporting security issues

Please do not open a public issue for security vulnerabilities — see [SECURITY.md](SECURITY.md) instead.
