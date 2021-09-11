# docker-cli-windows
![build status](https://github.com/ionash/docker-cli-windows/actions/workflows/merge-job.yml/badge.svg)

Build windows binary from [source](https://github.com/docker/cli). The following command is used to make binary.

```bash
docker buildx bake --set binary.platform=windows/amd64
```

The release binary is built by [a workflow of GitHub Actions](.github/workflows/create-release.yml).
