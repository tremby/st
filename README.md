This is a fork of [suckless terminal](https://st.suckless.org/) with some patches applied.

None of the main patches are my own code;
see each patch's page for author information.

- [alpha](https://st.suckless.org/patches/alpha/)
- [anysize](https://st.suckless.org/patches/anysize/)
- [scrollback](https://st.suckless.org/patches/scrollback/) and
  scrollback-mouse
- [visualbell](https://st.suckless.org/patches/visualbell/) (basic version)

Original readme follows:

---

st - simple terminal
====================
st is a simple terminal emulator for X which sucks less.


Requirements
------------
In order to build st you need the Xlib header files.


Installation
------------
Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install


Running st
----------
If you did not install st with make clean install, you must compile
the st terminfo entry with the following command:

    tic -sx st.info

See the man page for additional details.

Credits
-------
Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

