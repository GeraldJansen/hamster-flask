# hamster-flask

Cloned from  https://github.com/projecthamster/flask-hamster on 2019-09-02.

Experimental hamster flask app. Right now it's super rough and can only list your current activites and start new activities. Toma Bauģis started the original project "merely to pick up flask and advanced javascript, but the general direction makes sense, methinks!"

This version works again with python3 and python3-flask.

## Installing

On first usage an empty sqlite3 DB will be created in `~/.config/hamster-flask/hamster.db`. The DB is fully compatible with [legacy hamster](https://github.com/projecthamster/hamster) so you can copy an existing hamster.db (eg. from `~/.local/share/hamster-applet`) over it.

You should probably create a python3 virtualenv for this project, then: `pip3 install flask`.
Alternatively, use your linux distribution's tools to install python3-flask system wide.

Run the app from your git clone directory as:
`./hamster-flask.py`
and point your browser at: http://localhost:5000/ .
