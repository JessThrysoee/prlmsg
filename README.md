prlmsg
======

Send a message to a Parallels VM console.

`prlmsg` emulates typing a message on the keyboard to a Parallels VM console. It requires that the [Parallels Virtualization SDK](http://www.parallels.com/eu/products/desktop/download/) be installed.

This is especially useful for typing boot commands during unattended ISO installs.

```
Usage  : prlmsg VM_NAME MESSAGE"
Example: prlmsg 'CentOS VM' '<tab> text ks=http://localhost:1234/ks.cfg<enter><wait10>'"
```

