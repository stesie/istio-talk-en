---
title: Stairway to Service Mesh
separator: <!--s-->
verticalSeparator: <!--v-->
---

# Stairway to <br> Service Mesh

Stefan Siegl (@stesie23, <rolf@mayflower.de>)

<!--s-->

# Agenda

* (brief) Kubernetes Refresher
* Why Service Mesh?
* Why Istio?
* Traffic control & mTLS
* How does it work?
* Moar goodness

<!--s-->

# Kubernetes Refresher

<!--v-->

![Kubernetes Basic Structure](images/01-kube-basics.png)

<!--v-->

![Multiple Pods in Deployment, Service pointing towards them](images/02-multiple-pods.png)

<!--v-->

![Pods may consist of multiple containers, including init containers](images/03-multi-container-pod.png)
