my-ubuntu
=========
### Upload
```bash
export INPUT_PATH=./upload-artifact/dist && export INPUT_NAME=files && export INPUT_OVERWRITE=true
env 'INPUT_INCLUDE-HIDDEN-FILES=true' node ./upload-artifact/
```
