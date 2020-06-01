# smi-docker-memcached

## Publish
Publish to `strathcom/memcached` on Docker Hub. This image will be consumed by `go-ops`.
- Be on `master`
- Run: `docker build -t strathcom/memcached:latest -t strathcom/memcached:<SEMVER> .`
- (First time) Run: `docker login`
- Run: `docker push strathcom/memcached:latest`
- Run: `docker push strathcom/memcached:<SEMVER>`
- Run: `git tag -a <SEMVER>`
- Run: `git push --follow-tags`
