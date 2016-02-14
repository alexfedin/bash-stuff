# bash-stuff

Tired of making a new symlink to your virtualenvwrapper envs every time you create a new one??


Copy these scripts to your $WORKON_HOME directory.

Once a new virtualenv environment is created with the mkvirtualenv command, 
a symlink called 'venv' is created in the project folder pointing to the virtualenv in $WORKON_HOME.
When an environment is removed the 'venv' symlink is removed along with it.
