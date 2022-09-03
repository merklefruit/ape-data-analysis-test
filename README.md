# ape nft data analysis test

## how to run

```bash
git clone //todo
cd //todo
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt

# setup environment vars required
cat .envrc.example > .envrc
# if you already have direnv installed:
direnv allow

# install ape plugins
ape plugins install .

# open the notebook via ape-console
ape console
In [1]: from notebook import notebookapp as app
In [2]: app.launch_new_instance()

```
