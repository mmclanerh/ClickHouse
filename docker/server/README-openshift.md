# OpenShift build
This flavor of the build helps make sure clickhouse-server image will run in a 
non-elevated privilege mode, under OpenShift.

# building
```
$ make -f Makefile.openshift build
```

# testing
```
$ make -f Makefile.openshift test
```
