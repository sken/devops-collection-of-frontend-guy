# nonce example

```
docker build . -t affe:latest
docker run -p 8080:80 affe:latest
```

* [HTML Response](http://localhost:8080)
* [JSON Response](http://localhost:8080/data.json)


This example show how to make use of the lua-nginx-module to return static data   


* [Open Resty](https://openresty.org/en/)
* [Lua Module](https://github.com/openresty/lua-nginx-module)
