# clashctl

a cli tool for clash

## usage

``` bash
# clone to /some/path/
git clone https://github.com/Youtirsin/clashctl.git

# 1. copy your config.yaml to config/config.yaml
# or update with url
bash ~/some/path/clashctl/clasctl update <your-url>

# to get help, run with no args or 'help'
bash ~/some/path/clashctl/clashctl [help]

# set and unset http(s)_proxy with shortcuts
. ~/some/path/clashctl/set_proxy
. ~/some/path/clashctl/unset_proxy
```

## issue
``` bash
# one possible reason for it not working
chmod 777 clash-core
```
