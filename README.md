osx-proxy
========

**This should work with any remote SSH server!**

Move `proxy` to somewhere in your PATH and make sure to `chmod +x`.

Edit settings in `proxy`:

```
remoteuser="SSH_USER_HERE"
remoteproxy="IP_OR_HOSTNAME_HERE"
remoteport="22"
```

Run like this:

```
proxy <on|off|killall>
```
