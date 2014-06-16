# Usage

## trusty-ruby2.1.2

- Ubuntu 14.04 LTS (Trusty Tahr)
- Ruby 2.1.2
- ubuntu/ubuntu

```
curl -o Dockerfile https://raw.githubusercontent.com/usutani/dockerfiles/master/trusty-ruby2.1.2
docker build -t usutani/trusty-ruby:2.1.2 .
docker run -it usutani/trusty-ruby:2.1.2 /bin/bash
```
