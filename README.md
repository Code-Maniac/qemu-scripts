# qemu-scripts

## Installation
Run the installation script  
```bash
sudo ./install
```

## Usage
```bash
start-qemu [IMAGE]
```
Start a vm for the image. If no image is specified then default to qemux86-64
```bash
connect-qemu  
```
Connect to the currently running qemu vm at root@localhost
```bash
kill-qemu  
```
Kill all running qemu vms
```bash
restart-qemu [IMAGE]
```
Kill all running qemu vms then start a vm for the given image  

Note: Scripts only work within a sourced yocto environment

# License
[MIT](hhttps://choosealicense.com/licenses/mit/)
