# nginx-ssrf
use nginx do ssrf stuff

test
```
curl -k  'https://127.0.0.1/ssrf/https://postman-echo.com/post?haha=c&fafa=c' -d '{"key1":"value1", "key2":"value2"}'
```
