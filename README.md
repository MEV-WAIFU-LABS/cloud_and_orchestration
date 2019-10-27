# Learning Kubernetes

```
* A Kubernetes cluster consists of **Nodes** (simialr to servers)

* Nodes run **Pods**, which are collections of Docker containers. Containers in a Pod share the same network.

* The Kubernetes object responsible for launching and maintaining the desired number of pods is called a **Deployment**. 

* Kubernetes provides objects called a **Service** so thart Pods to communicate with other Pods. They are tied to Deployments through Selectors and Labels, and they can be exposed to external clients either by exposing a **NodePort** as a static port on each Kubernetes node or by creating a **LoadBalancer** object/

* Kubernetes provides the **Secret** object for managing sensitive information such as passwords, API keys, and other credentials.
```

## Examples in this repository

* [Spin up a node server example](https://github.com/bt3gl/Learning_Kubernetes/tree/master/node-server-example).
* [Use kustomize to organize and combine YAML templates of your services and deployments](https://github.com/bt3gl/Learning_Kubernetes/tree/master/kustomize-example).


-------------

## Tools


- [Minikube](https://github.com/kubernetes/minikube) implements a local Kubernetes cluster on macOS, Linux, and Windows. You can install it following [this instructions](https://minikube.sigs.k8s.io/docs/start/).
- [kubectl](https://kubernetes.io/docs/tasks/tools/install-kubectl/) is a command line interface for running commands against Kubernetes clusters.
- [kubectx](https://github.com/ahmetb/kubectx) is a tool to switch between k8s contexts.



------

## References 


### Learning Resources

* [Google's K8s 101](https://techdevguide.withgoogle.com/paths/cloud/sequence-2/kubernetes-101-pods-nodes-containers-and-clusters/#!).
* [K8s Bootcamp](https://kubernetesbootcamp.github.io/kubernetes-bootcamp/).
* [K8s the Hard Way](https://github.com/kelseyhightower/kubernetes-the-hard-way#labs).
* [Kubernetes Community Overview and Contributions Guide](https://docs.google.com/presentation/d/1JqcALpsg07eH665ZXQrIvOcin6SzzsIUjMRRVivrZMg/edit?usp=sharing) by [Ihor Dvoretskyi](https://twitter.com/idvoretskyi/)
* [Are you Ready to Manage your Infrastructure like Google?](http://blog.jetstack.io/blog/k8s-getting-started-part1/)
* [Google is years ahead when it comes to the cloud, but it's happy the world is catching up](http://www.businessinsider.in/Google-is-years-ahead-when-it-comes-to-the-cloud-but-its-happy-the-world-is-catching-up/articleshow/47793327.cms)
* [An Intro to Google’s Kubernetes and How to Use It](http://www.ctl.io/developers/blog/post/what-is-kubernetes-and-how-to-use-it/) by [Laura Frank](https://twitter.com/rhein_wein)
* [Getting Started on Kubernetes](http://containertutorials.com/get_started_kubernetes/index.html) by [Rajdeep Dua](https://twitter.com/rajdeepdua)
* [Kubernetes: The Future of Cloud Hosting](https://github.com/meteorhacks/meteorhacks.github.io/blob/master/_posts/2015-04-22-learn-kubernetes-the-future-of-the-cloud.md) by [Meteorhacks](https://twitter.com/meteorhacks)
* [Kubernetes by Google](http://thevirtualizationguy.wordpress.com/tag/kubernetes/) by [Gaston Pantana](https://twitter.com/GastonPantana)
* [Key Concepts](http://blog.arungupta.me/key-concepts-kubernetes/) by [Arun Gupta](https://twitter.com/arungupta)
* [Application Containers: Kubernetes and Docker from Scratch](http://keithtenzer.com/2015/06/01/application-containers-kubernetes-and-docker-from-scratch/) by [Keith Tenzer](https://twitter.com/keithtenzer)
* [Learn the Kubernetes Key Concepts in 10 Minutes](http://omerio.com/2015/12/18/learn-the-kubernetes-key-concepts-in-10-minutes/) by [Omer Dawelbeit](https://twitter.com/omerio)
* [Top Reasons Businesses Should Move to Kubernetes Now](http://supergiant.io/blog/top-reasons-businesses-should-move-to-kubernetes-now) by [Mike Johnston](https://github.com/gopherstein)
* [The Children's Illustrated Guide to Kubernetes](https://kubernetes.io/blog/2016/06/illustrated-childrens-guide-to-kubernetes/) by [Deis](https://github.com/deis)
* [The ‘kubectl run’ command](http://medium.com/@mhausenblas/the-kubectl-run-command-27c68de5cb76#.mlwi5an7o) by [Michael Hausenblas](https://twitter.com/mhausenblas)
* [Docker Kubernetes Lab Handbook](https://github.com/xiaopeng163/docker-k8s-lab) by [Peng Xiao](https://twitter.com/xiaopeng163)
* [Curated Resources for Kubernetes](https://hackr.io/tutorials/learn-kubernetes)
* [Kubernetes Comic](https://cloud.google.com/kubernetes-engine/kubernetes-comic/) by [Google Cloud Platform](https://cloud.google.com/)
* [Kubernetes 101: Pods, Nodes, Containers, and Clusters](https://medium.com/google-cloud/kubernetes-101-pods-nodes-containers-and-clusters-c1509e409e16) by [Dan Sanche](https://medium.com/@sanche)
* [An Introduction to Kubernetes](http://www.digitalocean.com/community/tutorials/an-introduction-to-kubernetes) by [Justin Ellingwood](https://twitter.com/jmellingwood)
* [Kubernetes and everything else - Introduction to Kubernetes and it's context](https://rinormaloku.com/introduction-application-architecture/) by [Rinor Maloku](https://twitter.com/rinormaloku)
* [Installation on Centos 7](http://severalnines.com/blog/installing-kubernetes-cluster-minions-centos7-manage-pods-services)
* [Setting Up a Kubernetes Cluster on Ubuntu 18.04](https://mherman.org/blog/2018/08/20/setting-up-a-kubernetes-cluster-on-ubuntu/)
* [Cloud Native Landscape](https://landscape.cncf.io/)
* [Kubernetes Tutorials by Kubernetes Team](http://kubernetes.io/docs/tutorials/)
* [Kubernetes By Example by OpenShift Team](http://kubernetesbyexample.com)
* [Kubernetes Tutorial by Tutorialspoint](http://www.tutorialspoint.com/kubernetes/)
* [Imperative vs. Declarative — a Kubernetes Tutorial](https://medium.com/payscale-tech/imperative-vs-declarative-a-kubernetes-tutorial-4be66c5d8914) by [Adrien Trouillaud](https://github.com/adrienjt/)
* [Learning Kubernetes, The Chinese Taoist Way](https://github.com/caicloud/kube-ladder)
* [Scalable Microservices with Kubernetes at Udacity](http://in.udacity.com/course/scalable-microservices-with-kubernetes--ud615)
* [Introduction to Kubernetes at edX](http://www.edx.org/course/introduction-kubernetes-linuxfoundationx-lfs158x)
