# felipesauer.github.io

The root of [felipesauer.github.io](https://felipesauer.github.io/): an entry page that lists my open source projects,
and the `robots.txt` that every project site under this host shares.

## Project sites under this host

| Site | Repository |
|---|---|
| [felipesauer.github.io/monitor-sefaz](https://felipesauer.github.io/monitor-sefaz/) | [felipesauer/monitor-sefaz](https://github.com/felipesauer/monitor-sefaz) |

Each project publishes its own site from its own repository. This repository holds only the root of the host.

mnema moved to the [mnema-work](https://github.com/mnema-work) organization and lives at [mnema.work](https://mnema.work/).
The pages under `mnema/` and the `404.html` keep its old addresses here alive: each old page sends the reader to the
same page at mnema.work, and any other path under `/mnema/` lands on the same path there.

## robots.txt

Search engines read `robots.txt` only at the root of a host, so a project site cannot point at its own sitemap from
its own path. The `robots.txt` here lists the sitemap of every project site above; a new project site adds its line.
