# Sample git repository

```sh
git config --get remote.origin.url # https://github.com/lachrist/sample.git
git rev-parse --abbrev-ref HEAD # main

git describe --abbrev=0 # v0.0.0
git describe --long # v0.0.0-2-XXXXXXXX

git describe --abbrev=0 --tags # v0.0.1
git describe --long --tag # v0.0.0-1-XXXXXXXX
```