## Prerequisits

1. [Install hugo](https://gohugo.io/getting-started/installing/)
2. Install rst2html ` pip install docutils`

## Develop

```
make watch
```

## Deploy

Currently the static content lives in a bucket on
[GCS](https://cloud.google.com/storage/).In order to deploy build the latest
version of the content you need access to that bucket through a google account
and then run:

```
make deploy
```
