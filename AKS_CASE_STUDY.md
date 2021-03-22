# AKS(Azure Kubernetes Service) Use Case
## What is AKS?
So, let talk about AKS(Azure K8s Service), which Highly available, secure, and fully managed Kubernetes(container management tool)services.

## Why use AKS?
* Easy to use.
* CI/CD support to AKS cluster.
* Lots of Monitoring features (logs, metrics, health, etc).
* You can use AKS for Microservices.
* and a lot more

Learn More about [AKS](https://azure.microsoft.com/en-in/services/kubernetes-service/#solution-architectures)

## Use Cases
Here I am going to share one company case study, name BOSCH, the problem statement of this company is the driver going the wrong way on highways, So they want a solution for Wrong-Way Driver, so they want one App/platform for this issue, So they used AKS in tandem with azure HDInsight tools and integrate with Apache Kafka.

“When we started our journey on Azure, we were a really small team — just one or two developers. Our partnership with Microsoft, the support from their advisory teams, the great AKS documentation and enterprise expertise — it all helped us very much to succeed.”

— Bernhard Rode: software engineer
So how they really solve their problem, let me talk more about, after that this company invests more and more in research and Development.
Basically, the WDW SDK to use of the service, The SDK maintains a list of hotspots within which GPS data is collected anonymously. These hotspots include specific locations, such as segments of divided highways and on-ramps. Every time a driver enters a hotspot, the client generates a new ID, so the service remains anonymous. When SDK used by the driver its uses a car system hotspot and collects the signal, sensor, etc.

If a driver is using WDW SKD and the driver is going in the wrong direction, it sends a notification to the originating device and to other drivers in the vicinity who are also running an app with the WDW SDK.

For more info [LINK](https://customers.microsoft.com/en-in/story/765209-bosch-increases-vehicle-safety-using-map-matching-algorithms-and-azure-kubernetes-service)
