# docker-cli-windows
![build status](https://github.com/ionash/docker-cli-windows/actions/workflows/build-test.yml/badge.svg)

Build windows binary from [source](https://github.com/docker/cli). The following command is used to make binary.

```bash
docker buildx bake --set binary.platform=windows/amd64
```
