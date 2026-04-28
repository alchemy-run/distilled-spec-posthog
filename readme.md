# distilled-spec-posthog

A git mirror of Posthog's API spec. The spec is fetched and committed as a JSON file so the repo serves as a versioned snapshot.

The mirror is updated every 24 hours and is designed to be used as a stable git submodule.

## Spec source(s)

- https://app.posthog.com/api/schema/

## Usage as a submodule

```sh
git submodule add https://github.com/alchemy-run/distilled-spec-posthog.git
```

## Updating specs

From `.meta/`:

```sh
bun install
bun run fetch-specs
```
