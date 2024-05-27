# st - simple terminal

st is a simple terminal emulator for X which sucks less.

## Requirements

In order to build st you need the Xlib header files.

## Installation

Edit config.mk to match your local setup (st is installed into
the /usr/local namespace by default).

Afterwards enter the following command to build and install st (if
necessary as root):

    make clean install

## Applied patches

- st-alpha-20220206-0.8.5.diff
- st-dracula-0.8.5.diff

## Note

Even though `dracula` theme patch is applied i have configured it to just use colors from `pywal`

## Running st

usage: st [-aiv] [-c class] [-f font] [-g geometry] [-n name] [-o file]
          [-T title] [-t title] [-w windowid] [[-e] command [args ...]]
       st [-aiv] [-c class] [-f font] [-g geometry] [-n name] [-o file]
          [-T title] [-t title] [-w windowid] -l line [stty_args ...]

See the man page for more additional details.

## Credits

Based on Aurélien APTEL <aurelien dot aptel at gmail dot com> bt source code.

