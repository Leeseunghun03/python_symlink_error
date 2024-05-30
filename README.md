# python_symlink_error

## Error

  python
  usage: /usr/bin/python --prefix|--exec-prefix|--includes|--libs|--cflags|--ldflags|--extension-suffix|--help|--abiflags|--configdir|--embed

## Solution

  1. find your available python version

     ls /usr/bin/python*


  2. select need python version and add symlink

     sudo ln -sf /usr/bin/python{version} /usr/bin/python

     ex) sudo ln -sf /usr/bin/python3.8 /usr/bin/python
