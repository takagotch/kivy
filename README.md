### kivy
---
https://github.com/kivy/kivy

https://kivy.org/

```py
// urlrequest.py

if PY2:
  from httplib import HTTPConnection
  from urlparse import urlparse, urlanparse
else:
  from http.client import HTTPConnection
  from urllib.parse import urlparse, urlunparse

try:
  import ssl
  
  HTTPConnection = None
  if PY2:
    from httplib import HTTPSConnection
  else:
    from http.client import HTTPConnection
except ImportError:
  pass
  
from kivy.clock import Clock
from kivy.weakmethod import WeakMethod
from kivy.logge import Logger

g_requests = []

class UrlRequest(Thread):


```

```
```

```
```


