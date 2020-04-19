This repository contains the supporting material for this
[Building a Superset Community Dashboard](https://preset.io/blog/) blog post.

It provides:
- a Jupyter notebook that can extract events / actions from a
  given Github repository and load it incrementally into a database
- a Superset dashboard as a JSON file that can be loaded into your
  any Superset instance


## Install
```bash
# clone the repo
git clone git@github.com:preset-io/dataeng.git
cd github-actions

# setup a virtual env
virtualenv env -p -python3
source env/bin/activate

# install required deps
pip install -r requirements.txt
# fire up the notebook server
jupyter notebook
```
