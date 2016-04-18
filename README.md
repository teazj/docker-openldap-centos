### docker-openldap-centos

Docker image for running an openldap service.

Based on ```centos:6```, with openldap packages from [ltb-project](http://ltb-project.org/).

Includes patch from [ITS 7345](https://openldap.org/its/index.cgi/Incoming?id=7345)
which adds a ```reqConnInfo ``` field to ```auditObject``` entries generated by 
slapo-accesslog contraining connection source informations (e.g. ```IP=192.168.0.1```)

See [docker-compose.yml](./docker-compose.yml) for examples.
