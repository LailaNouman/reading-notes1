# Class-15:


### Serverless computing
Serverless is a cloud application development and execution model that lets developers build and run code without managing servers.
Function-as-a-service, or FaaS, is a cloud computing service that enables developers to run code or containers in response to specific events or requests, without specifying or managing the infrastructure required to run to code. FaaS is the compute model central to serverless, and the two terms are often used interchangeably. But serverless is much more than FaaS. Serverless is an entire stack of services that can respond to specific events or requests, and scale to zero when no longer in use—and for which provisioning, management and billing are handled by the cloud provider and invisible to developers.

- Provisioning time: Measured in milliseconds for serverless, vs. minutes to hours for the other models.
- Administrative burden: None for serverless, compared to a continuum from light to medium to heavy for PaaS, containers and VMs respectively.
- Maintenance: Serverless architectures are managed 100% by the provider. The same is true for PaaS, but containers and VMs require significant maintenance including updating/managing operating systems, container images, connections.
- Capacity planning: None needed for serverless. The other models require a mix of some automatic scalability and some capacity planning.