## Building any subsequent rcs and final

```
cp ansible-build-data/2.11/ansible-2.11.0rc1.deps ansible-build-data/2.11/ansible-2.11.0rc2.deps
```{{execute}}

```
antsibull-build rebuild-single 2.11.0rc2 --data-dir ansible-build-data/2.11 --build-file ansible-2.11.build --deps-file ansible-2.11.0rc2.deps --sdist-dir built
ls built
```{{execute}}