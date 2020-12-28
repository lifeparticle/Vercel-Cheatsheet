# Introduction

1. [Vercel CLI](https://vercel.com/download)
  - [Documentation](https://vercel.com/docs/cli)
2. [Configuration](https://vercel.com/docs/configuration)
3. [Runtimes](https://vercel.com/docs/runtimes)

- [Officially supported runtimes](https://vercel.com/docs/runtimes#official-runtimes)

1. [Node.js](https://www.npmjs.com/package/@vercel/node)
```json
{
  "functions": {
      "api/*.js": { "runtime": "@vercel/node@1.8.5" }
  }
}
```

2. [Go](https://www.npmjs.com/package/@vercel/go)
```json
{
  "functions": {
      "api/*.go": { "runtime": "@vercel/go@1.1.6" }
  }
}
```

3. [Python](https://www.npmjs.com/package/@vercel/python)
```json
{
  "functions": {
      "api/*.py": { "runtime": "@vercel/python@1.2.3" }
  }
}
```

4. [Ruby](https://www.npmjs.com/package/@vercel/ruby)
```json
{
  "functions": {
      "api/*.rb": { "runtime": "@vercel/ruby@1.2.4" }
  }
}
```

- [Community Runtimes](https://vercel.com/docs/runtimes#advanced-usage/community-runtimes)

1. [PHP](https://www.npmjs.com/package/vercel-php)

```json
{
  "functions": {
    "api/*.php": { "runtime": "vercel-php@0.3.1" }
  },
  "routes": [
    { "src": "/(.*)",  "dest": "/api/index.php" }
  ]
}
```

2. [Bash](https://www.npmjs.com/package/vercel-bash)

```json
{
  "functions": {
      "api/*.sh": { "runtime": "vercel-bash@3.0.7" }
  }
}
```

3. [Deno](https://www.npmjs.com/package/vercel-deno)
```json
{
  "functions": {
      "api/**/*.[jt]s": { "runtime": "vercel-deno@0.7.6" }
  }
}
```

4. [Rust](https://www.npmjs.com/package/vercel-rust)
```json
{
  "functions": {
      "api/*.rs": { "runtime": "@vercel/vercel-rust@0.0.35" }
  }
}
```

# Examples
1. [Ruby](https://github.com/lifeparticle/vercel-cheatsheet/tree/main/ruby)
2. [Python](https://github.com/lifeparticle/vercel-cheatsheet/tree/main/python)
3. [PHP](https://github.com/lifeparticle/vercel-cheatsheet/tree/main/php)

Bug Reports and Feature Requests
============
Please create an issue with as much information you can. Thank you.

Author
============
Mahbub Zaman (https://mahbub.ninja)

License
============
MIT License
