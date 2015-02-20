nothing special just some edits to source code so you can create KVM machine with auto allocation VNC websocket port starts from 5700.
patch were tested on virt-manager-1.1.0 source code. and it worked with libvirt-1.2.12 and qemu-2.2.0.

Steps :
* download websocket.patch file to virt-manager-1.1.0 source code folder.
* execute patch -i websocket.patch (it may tell you it couldn't find the file and will ask you to add file manually, just answer with virtinst/devicegraphics.py.
* build and install virt-manager-1.1.0 as usual.

