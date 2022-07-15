# nonce example

```
docker build . --tag affe:latest
docker run -p 8080:80 --name nginx-nonce-example affe:latest
```

This example show how to make use of the lua-nginx-module to create a nonce value to make csp work 


* [Open Resty](https://openresty.org/en/)
* [Lua Module](https://github.com/openresty/lua-nginx-module)
