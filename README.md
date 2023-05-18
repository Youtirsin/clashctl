# clashctl

a cli tool for clash

## usage

``` bash
# clone to /some/path/
git clone https://github.com/Youtirsin/clashctl.git

# 1. copy your config.yaml to config/config.yaml
# or update with url
. ~/some/path/clashctl/clasctl update <your-url>

# to get help, run with no args or 'help'
. ~/some/path/clashctl/clashctl [help]
```

## issue
``` bash
# one possible reason for it not working
chmod 777 clash-core

# or another can be fixed with
# change the line in clashctl
clash_path="$(cd "$(dirname "$0")" && pwd)"
# to where the clashctl directory is
clash_path="/home/youtirsin/clashctl"
```
