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
Building the meteor-kubernetes base image
-----------------------------------------

As a normal user you don't need to do this since the image is already built and pushed to Docker Hub. You can just use it as a base image. See [this example](https://github.com/Q42/meteor-gke-example/blob/master/Dockerfile).

To build and push the base meteor-kubernetes image:

    docker build -t chees/meteor-kubernetes .
    docker push chees/meteor-kubernetes


<!-- BEGIN MUNGE: GENERATED_ANALYTICS -->
[![Analytics](https://kubernetes-site.appspot.com/UA-36037335-10/GitHub/examples/meteor/dockerbase/README.md?pixel)]()
<!-- END MUNGE: GENERATED_ANALYTICS -->
