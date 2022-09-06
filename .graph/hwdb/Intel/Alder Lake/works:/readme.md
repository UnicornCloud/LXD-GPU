discussion: https://www.reddit.com/r/Proxmox/comments/vv123d/i512600k_igpu_passthrough_on_unprivileged_lxc/

quote:
'''So after hours of trial and error and research I managed to get my i5-12400 iGPU passed through to a Plex LXC and confirmed HW transcoding is working, however, my container is privileged so if it doesn't work for you, you may need a privileged LXC .

Here is everything I did, some steps may not be necessary but the combination of all this worked for me:

Intel 12th gen Gpu passthrough for LXC containers in Proxmox VE

Install the latest Proxmox edge Kernel here:

https://github.com/fabianishere/pve-edge-kernel'''

source: https://github.com/fabianishere/pve-edge-kernel
