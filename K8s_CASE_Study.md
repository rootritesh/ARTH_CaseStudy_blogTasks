# K8s Case Study
## What is Kubernetes(k8s)?
Kubernetes, also known as K8s, is an open-source system for automating deployment, scaling, and management of containerized applications.

## Why K8s?
✅ Automated rollouts and rollbacks
k8s provides rollouts and rollbacks in a very easy way by using strategy Deployment. If anyone goes wrong u just need to rollback

✅ Self-healing
if a container fails, k8s automatically retry multiple times, because k8s, behind the scene, monitor the containers 👊.

✅Horizontal scaling
In an easy way, u can create replicas of existing pods, without any issue.

✅ Service discovery and load balancing
k8s provides 3 main services, cluster IP, Nodeport, and Loadbalancer 💡. Cluster IP is just for the private one, if u want to make your pod accessible from anywhere there is an option called NodePort, In k8s u will get the inbuilt feature of Loadbalancer here u don't need any third-party software for creating Loadbalancer 💪.

## Case Studies of Companies
### Babylon

#### **Challenge**
A large number of Babylon’s products leverage machine learning and artificial intelligence, and in 2019, there wasn’t enough computing power in-house to run a particular experiment. The company was also growing (from 100 to 1,600 in three years) and planning an expansion into other countries.

**Solution**

Babylon had migrated its user-facing applications to a Kubernetes platform in 2018, so the infrastructure team turned to Kubeflow, a toolkit for machine learning on Kubernetes. “We tried to create a Kubernetes core server, we deployed Kubeflow, and we orchestrated the whole experiment, which ended up being a really good success,” says AI Infrastructure Lead Jérémie Vallée. The team began building a self-service AI training platform on top of Kubernetes.

**Impact**
Instead of waiting hours or days to be able to compute, teams can get access instantaneously. Clinical validations used to take 10 hours; now they are done in under 20 minutes. The portability of the cloud-native platform has also enabled Babylon to expand into other countries.

Learn more about [Babylon](https://kubernetes.io/case-studies/babylon/)

