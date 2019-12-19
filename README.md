# memo-sync-plugins

## Install
```
$ cp pull $(memo config --cat | grep pluginsdir | awk -F\" '{print $2}')
$ cp push $(memo config --cat | grep pluginsdir | awk -F\" '{print $2}')
$ cp status $(memo config --cat | grep pluginsdir | awk -F\" '{print $2}')
```
