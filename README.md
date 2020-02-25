# TravisGrader

``` bash
virtualenv venv
source venv/bin/activate
pip install -r requirements.txt
patch venv/lib/python3.6/site-packages/travispy/_helpers.py <travis.patch
```

