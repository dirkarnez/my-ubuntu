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

### Tools
- libguestfs-tools
  - [如何快捷地修改虚拟机镜像——libguestfs-tools工具集介绍 - frankming - 博客园](https://www.cnblogs.com/frankming/p/16230219.html)
  - `sudo apt update && sudo apt install libguestfs-tools python3-guestfs`
