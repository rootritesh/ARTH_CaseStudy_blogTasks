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

**Challenge**<br>
A large number of Babylon’s products leverage machine learning and artificial intelligence, and in 2019, there wasn’t enough computing power in-house to run a particular experiment. The company was also growing (from 100 to 1,600 in three years) and planning an expansion into other countries.

**Solution**<br>
Babylon had migrated its user-facing applications to a Kubernetes platform in 2018, so the infrastructure team turned to Kubeflow, a toolkit for machine learning on Kubernetes. “We tried to create a Kubernetes core server, we deployed Kubeflow, and we orchestrated the whole experiment, which ended up being a really good success,” says AI Infrastructure Lead Jérémie Vallée. The team began building a self-service AI training platform on top of Kubernetes.

**Impact**<br>
Instead of waiting hours or days to be able to compute, teams can get access instantaneously. Clinical validations used to take 10 hours; now they are done in under 20 minutes. The portability of the cloud-native platform has also enabled Babylon to expand into other countries.

Learn more about [Babylon](https://kubernetes.io/case-studies/babylon/)

### Ancestry
**Challenge**<br>
Ancestry, the global leader in family history and consumer genomics, uses sophisticated engineering and technology to help everyone, everywhere discover the story of what led to them. The company has spent more than 30 years innovating and building products and technologies that at their core, result in real and emotional human responses. Ancestry currently serves more than 2.6 million paying subscribers, holds 20 billion historical records, 90 million family trees, and more than four million people are in its AncestryDNA network, making it the largest consumer genomics DNA network in the world. The company’s popular website, ancestry.com, has been working with big data long before the term was popularized. The site was built on hundreds of services, technologies, and a traditional deployment methodology. “It’s worked well for us in the past,” says Paul MacKay, software engineer, and architect at Ancestry, “but had become quite cumbersome in its processing and is time-consuming. As a primarily online service, we are constantly looking for ways to accelerate to be more agile in delivering our solutions and our products.”

**Solution**<br>
The company is transitioning to cloud-native infrastructure, using Docker containerization, Kubernetes orchestration, and Prometheus for cluster monitoring.

**Impact**<br>
“Every single product, every decision we make at Ancestry, focuses on delighting our customers with intimate, sometimes life-changing discoveries about themselves and their families,” says MacKay. “As the company continues to grow, the increased productivity gains from using Kubernetes has helped Ancestry make customer discoveries faster. With the move to Dockerization for example, instead of taking between 20 to 50 minutes to deploy a new piece of code, we can now deploy in under a minute for much of our code. We’ve truly experienced significant time savings in addition to the various features and benefits from cloud-native and Kubernetes-type technologies.”

Learn more about [ancestry](https://kubernetes.io/case-studies/ancestry/)