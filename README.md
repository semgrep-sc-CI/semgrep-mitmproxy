# semgrep-mitmproxy

## Start mitmproxy first
```
docker-compose up mitmproxy
cp mitmproxy-data/mitmproxy-ca-cert.pem .
docker-compose build
docker-compose up -d
```

## visit mitmproxy web UI (login password is set at https://github.com/semgrep-sc-CI/semgrep-mitmproxy/blob/de294c1a152b99e3fc42ea622717c5f2ffad4e34/docker-compose.yml#L7)
```
http://localhost:8081
```
