# navigation
REST API for the N.W.A Smart Gym

Getting Started
---------------

Either use your own brain or follow the following guidelines:

- `mkdir -p ~/env`
- `virtualenv -p python3 ~/env/smart_gym_api` or whatever you want to call your virtual environment
- `mkdir -p ~/projects`
- `git clone git@github.com:NerdsWitAttitudes/RadioLocator.git ~/projects/RadioLocator`
- `source ~/env/smart_gym_api/bin/activate`
- `pip install -e ~/projects/RadioLocator`
- `cp ~/projects/RadioLocator/settings.ini.dist ~/projects/RadioLocator/{yourname}.ini`

Fill in the .ini file you just made. Ask one of your team members for help.

Finally:
- `pserve --reload ~/projects/RadioLocator/{yourname}.ini`
