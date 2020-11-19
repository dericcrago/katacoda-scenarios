## Building beta2 up to and including rc1

```
rm -rf built
mkdir built
```{{execute}}

```
antsibull-build single 2.11.0rc1 --feature-frozen --data-dir ansible-build-data/2.11 --sdist-dir built
ls built
```{{execute}}