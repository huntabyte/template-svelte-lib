# Template - Svelte (Library)

A personal template I use to start a fresh Svelte library. This is _always_ used within my [monorepo template](https://github.com/huntabyte/template-monorepo) which contains all the tools like pnpm workspaces, ESLint, Prettier, Changesets, GitHub Workflows, etc.

## Why Monorepo?

After creating a number of Svelte libraries, I've found it more problematic to have your playground / integration tests / docs and the library itself in the same Svelte project. You get a distorted view of what your library looks like when it's imported into another project. This is because the Svelte project is not a consumer of the library, it's the library itself.

Instead of having a single Svelte project with both the library and the docs, I use a monorepo setup with [pnpm workspaces](https://pnpm.io/workspaces). This allows me to use the library in a separate project as a dependency, while still being able to work on the library and docs in the same repository.


## Placeholders

- `pkg-placeholdr` - the package name
- `__DESCRIPTION__` - the package description
- `__AUTHOR__` - the package author's github username
- `__REPO__` - the repository URL


