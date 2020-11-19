## Building new patch releases (2.11.Z)

```
rm -rf built
mkdir built
```{{execute}}

```
antsibull-build single 2.11.1 --data-dir ansible-build-data/2.11 --sdist-dir built
ls built
```{{execute}}

```
rm -rf built
mkdir built
```{{execute}}

```
antsibull-build rebuild-single 2.11.1 --data-dir ansible-build-data/2.11 --build-file ansible-2.11.build --deps-file ansible-2.11.1.deps --sdist-dir built
ls built
```{{execute}}