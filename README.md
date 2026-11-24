# Nuxt SSR on Deno

Example [Nuxt](https://nuxt.com/) app with server-side rendering (SSR) running on [Deno](https://deno.com/). Nuxt is a Vue framework for building full-stack web applications. Deno is a secure JavaScript and TypeScript runtime with built-in tooling and Node.js compatibility.

## Deploy settings

| Field | Value |
| --- | --- |
| Build | Railpack |
| Project directory | `/` |
| Install command | leave empty |
| Build command | `deno task build` |
| Start command | `deno task start` |
| Application port | `3000` |
| Health check path | `/` |

## <a name="dev"></a>Run locally

```bash
# install dependencies
deno install --allow-scripts

# build for production
deno task build

# run the built server app
deno task start
```
