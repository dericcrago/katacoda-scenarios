## Building all alpha releases and the first beta

```
antsibull-build new-ansible 2.11.0a1 --data-dir ansible-build-data/2.11
```{{execute}}

```
mkdir built
antsibull-build single 2.11.0a1 --data-dir ansible-build-data/2.11 --sdist-dir built
ls built
```{{execute}}