Python wrapper for Bing API
----------------------------

Usage:

```python

import bing

api = bing.Api('your-key')

web_results = api.query('hello world')
news_results = api.query('hello world', srctype='News')

```
