# kingpin-backend

Backend for Kingpin app using Python and PostgreSQL.

# Setup

Uses Python 3 - (I'm on `v3.9.0`) and Python virtual environments via `virtualenv`. I have `virtualenv` installed globally on my machine.

> [For full explanation/detailed steps to install Python 3, pip, virtual env (and Windows steps), you can follow this tutorial.](https://docs.python-guide.org/starting/install3/osx/)

1. Install `virtualenv` globally, `pip install virtualenv`. (Restart terminal and test install by running `virtualenv --version`)
1. Create a virtual environment called "venv" by running: `virtualenv venv`
1. Install all dependencies `pip install -r requirements.txt`.
1. Now activate it by running: `source venv/bin/activate`

You'll notice your terminal's prompt probably will look like `(venv)Your-Computer:project_folder UserName$)`, you are now in the virtual environment and should be able to start developing!

To go deactivate/return to your system's local setup, just run `deactivate`.

> Hopefully `virtualenv` keeps things all isolated, packaged up and ready to go for dev. I'm new to Python right now.
