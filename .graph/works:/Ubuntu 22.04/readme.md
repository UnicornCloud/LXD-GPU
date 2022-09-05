This guide works! Follow it exactly.
https://blog.simos.info/how-to-easily-run-graphics-accelerated-gui-apps-in-lxd-containers-on-your-ubuntu-desktop/

source:
```
lxc profile create gui
wget https://blog.simos.info/wp-content/uploads/2018/06/lxdguiprofile.txt
cat lxdguiprofile.txt | lxc profile edit gui
lxc launch --profile default --profile gui ubuntu:18.04 gui1804
```
