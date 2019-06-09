# Vendor version manger

simple.

## Commands

- `./bin/install [version]`: install specific version.
- `./bin/installed`: list installed versions.
- `./bin/versions`: list versions that can be installed.


## Requirements

- `curl`: required for `./bin/install` and  `./bin/versions`
- `tar`: required for `./bin/install`


```sh
apt-get update
apt-get install -y curl xz-utils
```
