# nginx-echo-ip
Simple "What is my IP address" container image based on nginx

HTTP, Plain text body, No access log

```shell
docker run --detach --rm -p 8080:80 edxsh/nginx-echo-ip:latest
```
```shell
curl http://127.0.0.1:8080/anything
```
```text
172.17.0.1
```
