# Github Packages hosted built version of [the original](https://github.com/kubernetes-sigs/nfs-subdir-external-provisioner)
- Just a Docker amd64/arm64 build
- Go see [the original](https://github.com/kubernetes-sigs/nfs-subdir-external-provisioner)
- Probably outdated and thus
    - Insecure
- Works, maybe

## Image coordinates
```bash
# :latest there is/should be to master here via Github Actions
docker pull ghcr.io/rpardini/nfs-subdir-external-provisioner:latest

# @TODO: yamls produced by helm chart here. PRs welcome
helm template ...
```
