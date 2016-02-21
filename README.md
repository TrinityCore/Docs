Serving the docs locally
------------------------

```bash
$ pip install -r requirements.txt
$ make html
$ cd _build && python -m SimpleHTTPServer 8000 # Python 2
$ cd _build && python -m http.server 8000 # Python 3
# Browse to http://localhost:8000
```
