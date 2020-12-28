# Runtimes

https://vercel.com/docs/runtimes

Officially supported runtimes

1. Node.js
https://www.npmjs.com/package/@vercel/node
```
@vercel/node@1.8.5
```

2. Go
https://www.npmjs.com/package/@vercel/go
```
@vercel/go@1.1.6
```
3. Python
https://www.npmjs.com/package/@vercel/python

```
"runtime": "@vercel/python@1.2.3"
```

4. Ruby
https://www.npmjs.com/package/@vercel/ruby
```
@vercel/ruby@1.2.4
```

Not officially supported runtimes

1. PHP
https://www.npmjs.com/package/vercel-php
```
"runtime": "vercel-php@0.3.1"
```

```
{
  "functions": {
    "api/*.php": {
      "runtime": "vercel-php@0.3.1"
    }
  },
  "routes": [
    { "src": "/(.*)",  "dest": "/api/index.php" }
  ]
}
```

