# Assess & Mitigate Vendor Risk
All organizations, regardless of size, depend upon a complicated network of suppliers and contractors. Some of these relationships are obvious, but many are not. 

This complicated, and in many ways hidden, network of people, technology, and products provides a unique and incredibly damaging threat. 

This dynamic and complicated arrangement is referred to simply as Vendor Risk.

Many high-profile and far-reaching cyberattacks in recent years have been the result of exploiting this vast and complicated vendor network. 

Vendors provide hardware and software, access the technology resources of their customers, and frequently provide software and hosting services. 

For these reasons, it is imperative to understand what security measures are in place with all vendors and to identify ways to measure the effectiveness of these measures. 

In addition, a clear map of all vendor relationships is needed in order to fully document specific vendor risks.

## Shared Responsibility Model
The Cloud Service Provider (CSP) forms a very common, and high-profile, vendor relationship for organizations spanning many diverse sizes and industries. 

This relationship is unique as it establishes a very distinct requirement to share the implementation of security. 

This arrangement is commonly referred to as the shared responsibility model .

Shared responsibility model

Identifies that responsibility for the implementation of security as applications, data and workloads are transitioned into a cloud platform are shared between the customer and the cloud service provider (CSP.)
identifies that responsibility for the implementation of security as applications, data, and workloads are transitioned into a cloud platform are shared between the customer and the cloud service provider (CSP).

*Identifying the boundary between customer and cloud provider responsibilities, in terms of security, is imperative for reducing the risk of introducing vulnerabilities into your environment.*

### Cloud Service Types
**Software as a Service (SaaS)** represents the lowest amount of responsibility for the customer as the facilities, utilities, physical security, platform, and applications are the responsibility of the provider.

**Platform as a Service (PaaS)** provides a selection of operating systems that can be loaded and configured by the customer, the underlying infrastructure, facilities, utilities, and physical security are the responsibility of the provider.

**Infrastructure as a Service (IaaS)** provides hardware hosted at a provider facility using the provider's physical security controls and utilities, such as power.

### Share Responsibilities Chart
![The shared responsibility model describes the relationship between customer and CSP.](https://github.com/kieferhax/comptia-casp-studies/blob/main/assets/1634-1627653739958-cas_fig01_05.png?raw=true)

### Security Responsibilities
In general terms, the responsibilities between customer and cloud provider include the following areas:

####  Cloud Service Provider 
- Physical security of the infrastructure
- Securing compute, storage, and network equipment
- Securing foundational elements of networking, such as DDoS protection
- Cloud storage backup and recovery
- Security of cloud infrastructure resource isolation between tenants
- Tenant resource identity and access control
- Security, monitoring, and incident response for the infrastructure
- Securing and managing the data centers located in multiple geographic regions

#### Cloud Service Customer
- User identity management
- Configuring the geographic location for storing data and running services
- User and service access controls to cloud resources
- Data and application security configuration
- Protection of operating systems, when deployed
- Use and configuration of encryption, especially in regard to the protection of keys

The division of responsibility becomes more or less complicated based on whether the service model is SaaS, PaaS, or IaaS. 

For example, in a SaaS model the configuration and control of networking is performed by the CSP as part of the service offering, but in an IaaS model the responsibility for network configuration is shared between the CSP and the customer.

An important core concept when using cloud resources is that the implementation and management of security controls is not a "hands-off" endeavor, that identifying the boundary between customer and CSP responsibilities requires a conscious effort.

**Additional Resources**
[**NIST Cloud Computing Reference Architecture SP 500-212**](https://www.nist.gov/publications/nist-cloud-computing-reference-architecture)

[**Microsoft Share Responsibility Model**](https://azure.microsoft.com/en-us/resources/shared-responsibility-for-cloud-computing/)

[**Cloud Security Alliance Responsibility Model Explained**](https://cloudsecurityalliance.org/blog/2020/08/26/shared-responsibility-model-explained/)