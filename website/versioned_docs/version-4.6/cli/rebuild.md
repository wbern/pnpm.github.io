---
id: version-4.6-rebuild
title: pnpm rebuild
original_id: rebuild
---

Aliases: `rb`

Rebuild a package.

## Synopsis

```text
pnpm rebuild [-r [--workspace-concurrency=&lt;number>] [--no-sort]]
     [&lt;pkg>...]
```

## Options

### --recursive, -r

This command runs the **pnpm build** command in every package of the monorepo.

### --filter &lt;package_selector>

[Read more about filtering.](../filtering)
