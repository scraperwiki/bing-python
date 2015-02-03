# Python wrapper for Bing API

## Getting an API key

1. Make a Microsoft account.
2. Visit the [Bing Search API page](https://datamarket.azure.com/dataset/bing/search).
3. Log into your Microsoft account there.
4. Return to the search API page and select an appropriate tier.
   (currently, the 5,000 transactions per month tier is free; one
   transaction is one page of results).
5. Go to "My Account" and your Primary Account Key is shown there; this
   is the API key you need to use here.

## Usage

```python

import bing

api = bing.Api('your-key')

web_results = api.query('hello world')
news_results = api.query('hello world', srctype='News')

```
