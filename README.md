# SvelteKit example: route matching

How does SvelteKit match routes to the requested path?

SvelteKit matches path segments left to right. Path segements can be static (`.../static/...`) or dynamic (`.../[dynamic]/...`). For each path segement, SvelteKit applies the following rules to eliminate routes:

1. Index routes take precedence over non-index routes, e.g. `src/routes/red/index.svelte` takes precedence over `src/routes/red.svelte`.
1. Static path segments take precedence over dynamic segments, e.g. `src/routes/green.svelte` takes precedence over `src/routes/[color].svelte`.
1. Dynamic path segments take precedence over spread routes, e.g. `src/routes/color/[color].svelte` takes precedence over `src/routes/color/[...rest].svelte`.
1. Spread routes take precedence over error routes, e.g. `src/routes/color/[...rest].svelte` takes precedence over `src/routes/__error.svelte`.
1. For two path segements of the same type, the first one in alphabetical order takes precedence, e.g. `src/routes/[color].svelte` takes precedence over `src/routes/[nocolor].svelte`.

Launch the example with `npm run dev` and try to match routes for each link.

