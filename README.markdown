This is the Victory Chat

In order to run it, you need to install a few things

 - Python 2.7
 - CherryPy 3
 - Mako Templates

On Ubuntu 11.04, to install it just run the following in a terminal:

`sudo apt-get install python-markdown python-cherrypy3 python-mako`

Once that's done, cd to the directory where this is (so the `Victory-Chat` directory) and then run `python test.py`

If everything is in order, you can go through the files, change a few
things and just run test.py.

You might want to change a few things at the bottom of test.py:

 - Make 'log.screen': True
 - Change the port numer

To run Victory Chat as an init.d service move `victory` to `/etc/init.d/` and update the `VICTORY_BIN` in `victory` to the `test.py` file or create a symlink to `test.py` at `/usr/bin/victory-chat`


