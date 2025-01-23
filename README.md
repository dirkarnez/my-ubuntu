my-ubuntu
=========
### Upload (`INPUT_NAME=files` && `INPUT_OVERWRITE=true` is hardcorded)
```
env 'INPUT_INCLUDE-HIDDEN-FILES=true' INPUT_PATH=./upload-artifact/dist node ./upload-artifact/
```

### Print OS info
```
lsb_release -a
```

### DD sample
- `dd if=/dev/zero of=export.img bs=128K conv=noerror,sync status=progress`
