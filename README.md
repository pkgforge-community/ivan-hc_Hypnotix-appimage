This repository creates and distributes the unofficial Appimage of Hypnotix.

From here you can download the scripts to build on top of [JuNest](https://github.com/fsquillace/junest), the lightweight Arch Linux based distro that runs, without root privileges, on top of any other Linux distro.

### NOTE: this is still an EXPERIMENTAL BUILD, don't use it daily. It is not ready yet!

---------------------------------

# Known issue
- After 1-2 times you change the channel, it crashes with the following message:
```
[xcb] Unknown sequence number while processing queue
[xcb] You called XInitThreads, this is not your fault
[xcb] Aborting, sorry about that.
xcb_io.c:278: poll_for_event: Assertion `!xcb_xlib_threads_sequence_lost' failed.
```
