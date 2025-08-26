my-ubuntu
=========
### Zip all the files inside `my_output_dir` and upload (`INPUT_NAME=files` && `INPUT_OVERWRITE=true` is hardcorded for convenience)
```bash
env 'INPUT_INCLUDE-HIDDEN-FILES=true' INPUT_PATH=./my_output_dir node ./upload-artifact/
```

### Print OS info
```bash
lsb_release -a
```

### DD sample
```bash
dd if=/dev/zero of=export.img bs=128K conv=noerror,sync status=progress
```
