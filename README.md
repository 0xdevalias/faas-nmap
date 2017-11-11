# faas-nmap

A basic PoC of using [Nmap](https://nmap.org/) with [OpenFaaS](https://www.openfaas.com/) by [Glenn 'devalias' Grant](http://devalias.net/) ([@_devalias](https://twitter.com/_devalias))

## Usage

```
faas-cli deploy -f stack.yml
echo "example.com" | faas-cli invoke nmap
```

## Inspiration

* Originally inspired by [@h-a-t](https://gist.github.com/h-a-t)'s [gist](https://gist.github.com/h-a-t/b558fac265d7712c4e611aa844f210cd)
