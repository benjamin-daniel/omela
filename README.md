# OMELA

Omela is a simple file server like python's
I was just really tired of typing the long version in python.

```python
python3 -m http.server 3333
or
python -m SimpleHTTPServer 3333
```

Usage:
  * -p="8100": port to serve on
  * -d=".": the directory of static files to host
  

Navigating to http://localhost:8100 will display the index.html or directory

Heavily influenced by [https://gist.github.com/paulmach/7271283](https://gist.github.com/paulmach/7271283)
