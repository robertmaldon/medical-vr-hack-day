# medical-vr-hack-day

This is an example of rendering medical scans in a virtual reality environment.

Specifically we are experimenting with rendering medical data in [DICOM](https://en.wikipedia.org/wiki/DICOM) format in a Virtual Reality environment built with [A-Frame](https://aframe.io/).

# Getting started

1. Install node

2. Install node modules

    npm install

3. Start an express server

    npm start

4. Open any A-Frame supported browser on the same network

e.g.

    shell> ifconfig -a
    en0: flags=8863<UP,BROADCAST,SMART,RUNNING,SIMPLEX,MULTICAST> mtu 1500
    inet 192.168.1.121 netmask 0xffffff00 broadcast 192.168.1.255
    nd6 options=9<PERFORMNUD,IFDISABLED>
    media: autoselect
    status: active

    shell> chrome http://192.168.1.121:3000/
