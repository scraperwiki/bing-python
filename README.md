Bing Search API
---------------

Usage:

```python

import bing

api = bing.API('your-key')

web_results = api.query('hello world')
news_results = api.query('hello world', srctype='News')

```