# Runtimes

https://vercel.com/docs/runtimes

Officially supported runtimes

1. [Node.js](https://www.npmjs.com/package/@vercel/node)
```
{
  "functions": {
      "api/*.js": { "runtime": "@vercel/node@1.8.5" }
  }
}
```

2. [Go](https://www.npmjs.com/package/@vercel/go)
```
{
  "functions": {
      "api/*.go": { "runtime": "@vercel/go@1.1.6" }
  }
}
```

3. [Python](https://www.npmjs.com/package/@vercel/python)
```
{
  "functions": {
      "api/*.py": { "runtime": "@vercel/python@1.2.3" }
  }
}
```

4. [Ruby](https://www.npmjs.com/package/@vercel/ruby)
```
{
  "functions": {
      "api/*.rb": { "runtime": "@vercel/ruby@1.2.4" }
  }
}
```

Community Runtime

1. [PHP](https://www.npmjs.com/package/vercel-php)

```
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

```
{
  "functions": {
      "api/*.sh": { "runtime": "vercel-bash@3.0.7" }
  }
}
```
3. [Deno](https://www.npmjs.com/package/vercel-deno)
```
{
  "functions": {
      "api/**/*.[jt]s": { "runtime": "vercel-deno@0.7.6" }
  }
}
```

4. [Rust](https://www.npmjs.com/package/vercel-rust)
```
{
  "functions": {
      "api/*.rs": { "runtime": "@vercel/vercel-rust@0.0.35" }
  }
}
```
