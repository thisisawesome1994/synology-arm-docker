# synology-arm-docker

How to install docker on recent ARM based synology diskstation personal NAS?

1. Enable SSH access in the webui.
2. Connect over SSH and login using your normal useraccount.
3. Become root. 

sudo -i

and type your password to confirm.

4. Type this command.

curl https://gist.githubusercontent.com/ta264/2b7fb6e6466b109b9bf9b0a1d91ebedc/raw/b76a28d25d0abd0d27a0c9afaefa0d499eb87d3d/get-docker.sh | sh

5. Wait till it finishes, and go back to the webui, and add all users including admih/root to the docker group. Make sure to give docker(group) access to the shares.

6. Reboot.
