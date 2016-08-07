# CLI template for nodejs

This is template app for CLI test.  
You can make console application by editing [app/main.js](app/main.js)

## How to get input parameters
main.js has a function `main`.

``` js
function main(args, options) {
}
```

- `args` is array of parameter.
- `options` is command line option specified with `-` prefix.

## How to output result
You can use console.log

``` js
  console.log("HOGE");
```