runemadsen.com
==============

The following is the jekyll setup running on runemadsen.com. 


Deployment
----------

Run this to deploy to S3:

```bach
s3cmd sync --delete —cf-invalidate --acl-public _site/ s3://runemadsen.com
```

TODO
----

- Rewrite waza talk description