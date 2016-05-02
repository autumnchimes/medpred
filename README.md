# medpred

In a directory of your choosing, run the following commands to create the virtualenv, install requirements, and start the notebook server.

```
git clone https://github.com/autumnchimes/medpred.git
cd medpred
virtualenv env
source env/bin/activate
pip install -r requirements-bootstrap.txt
pip install -r requirements.txt
jupyter notebook --no-browser
```

Open http://localhost:8888/ in a browser and navigate to desired notebook.

If you run into the pip install error `NameError: name 'sys_platform'
is not defined`, try the following.

```
pip install --upgrade setuptools
pip install --upgrade distribute
```
