<!-- BEGIN MUNGE: UNVERSIONED_WARNING -->

<!-- BEGIN STRIP_FOR_RELEASE -->

![WARNING](http://kubernetes.io/img/warning.png)
![WARNING](http://kubernetes.io/img/warning.png)
![WARNING](http://kubernetes.io/img/warning.png)

<h1>PLEASE NOTE: This document applies to the HEAD of the source
tree only. If you are using a released version of Kubernetes, you almost
certainly want the docs that go with that version.</h1>

<strong>Documentation for specific releases can be found at
[releases.k8s.io](http://releases.k8s.io).</strong>

![WARNING](http://kubernetes.io/img/warning.png)
![WARNING](http://kubernetes.io/img/warning.png)
![WARNING](http://kubernetes.io/img/warning.png)

<!-- END STRIP_FOR_RELEASE -->

<!-- END MUNGE: UNVERSIONED_WARNING -->
# How to generate the bps-data-generator container #

This container is maintained as part of the apache bigtop project.

To create it, simply 

`git clone https://github.com/apache/bigtop`

and checkout the last exact version (will be updated periodically).

`git checkout -b aNewBranch 2b2392bf135e9f1256bd0b930f05ae5aef8bbdcb`

then, cd to bigtop-bigpetstore/bigpetstore-transaction-queue, and run the docker file, i.e. 

`Docker build -t -i jayunit100/bps-transaction-queue`.


<!-- BEGIN MUNGE: GENERATED_ANALYTICS -->
[![Analytics](https://kubernetes-site.appspot.com/UA-36037335-10/GitHub/examples/k8petstore/bps-data-generator/README.md?pixel)]()
<!-- END MUNGE: GENERATED_ANALYTICS -->
