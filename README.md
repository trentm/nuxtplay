# Nuxt 3 Minimal Starter

Look at the [Nuxt 3 documentation](https://nuxt.com/docs/getting-started/introduction) to learn more.

Here I played briefly with NuxtJS 3 in an attempt to instrument it
to help answer https://github.com/elastic/apm-agent-nodejs/issues/4143

This is the basic Nuxt 3 app created from https://nuxt.com/docs/getting-started/introduction
Plus I added one server middleware and api handler:

```
% find server -name "*.ts"
server/middleware/log.ts
server/api/hello.ts
```
