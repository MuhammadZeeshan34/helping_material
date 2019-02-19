# helping_material

How to mount a remote server directory to MAC:

-> Download 'Fuse' and 'sshfs' from https://osxfuse.github.io/ and install

-> Create a local directory: sudo mkdir /somename

-> Run this command sudo sshfs -o allow_other,defer_permissions root@xxx.xxx.xxx.xxx:/ /somename

-> Enter server credentials 
