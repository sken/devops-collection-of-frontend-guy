# nonce example

NGINX configuration found in [nginx.conf](nginx/nginx.conf) will create a variable `$nonceValue` & will replace the placeholder `**CSP_NONCE**` with the value   

```
set $nonceValue $cspNonce;
sub_filter **CSP_NONCE** $nonceValue;
```
```
docker build . -t affe:latest
docker run -p 8080:80 affe:latest
```

This example show how to make use of the lua-nginx-module to create a nonce value to make csp work 


* [Open Resty](https://openresty.org/en/)
* [Lua Module](https://github.com/openresty/lua-nginx-module)
