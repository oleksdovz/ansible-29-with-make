# ansible-29-with-make

### Dockerfile

```
  FROM alpine:latest

  MAINTAINER Oleksiy Dovzhanitsya <oleksdovz@gmail.com>
  RUN apk --no-cache add make 'ansible=~2.9'
```
