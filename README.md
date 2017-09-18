# shared_packages

Add the following to your .bash_profile (where $HOME is where you want your local repo to live):

export PYTHONPATH=$PYTHONPATH:$HOME/shared_packages

If done correctly, you should see the following from the Python interpreter, no matter your current working directory:

```
>>> import helloworld
Hello world
```
