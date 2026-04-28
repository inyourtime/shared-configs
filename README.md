# @inyourtime/shared-configs

Shared configuration files for my projects.

## Usage

Install the package with the tools you use:

```sh
npm install --save-dev @inyourtime/shared-configs @biomejs/biome release-it
```

Extend the shared Biome config from your project:

```json
{
  "extends": ["@inyourtime/shared-configs/biome"]
}
```

Use the shared release-it config:

```sh
release-it --config ./node_modules/@inyourtime/shared-configs/.release-it.json
```
