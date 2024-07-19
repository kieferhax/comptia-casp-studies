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

### Shared Responsibilities Chart
![The shared responsibility model describes the relationship between customer and CSP.](https://github.com/kieferhax/comptia-casp-studies/blob/main/assets/1634-1627653739958-cas_fig01_05.png?raw=true)

### Security Responsibilities
In general terms, the responsibilities between customer and cloud provider include the following areas:

#### Cloud Service Provider 
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

## Performing Vendor Assessment
It is essential to take the time to research vendors prior to entering into any sort of agreement. 

Researching a vendor can include everything from simple checks, such as reviewing the vendor's website, social media pages, and employer review sites, to more formal requirements such as requesting evidence of independent third-party audits of the vendor's operations, finances, and cybersecurity capabilities.

*Ultimately, it is important to select a vendor service or product based on an evaluation of the vendor's integrity and the presence of well-matched product or service features and functionality and not to select vendor products and services based solely on cost.*

- Vendor Lock-in -Describes when a customer is completely dependent on a vendor for products or services because switching is either impossible or would result in substantial complexity and costs. Vendor lock-in is sometimes referred to as proprietary lock-in.

- Vendor Lockout - Describes when a vendor's product is developed in a way that makes it inoperable with other products, the ability to integrate it with other vendor products is not a feasible option, or does not exis

- Vendor Viability - Is an important measurement used to determine if a vendor will be in-business on an on-going basis. This can be accomplished by establishing that the vendor provides a viable and in-demand product and the financial means to stay afloat. Additionally, legal contracts should include language identifying notification requirements in regard to merger and acquisition activity. If a vendor is on either side of acquisition activity (meaning that they are either acquiring or being acquired), vendor viability assessment processes will need to be re-administered to accommodate these changes. The security of an integrated IT between two organizations will amount to the least secure between the two!

- Source Code Escrow - Identifies that a copy of vendor-developed source code is provided to a trusted third party in case the vendor ceases to be in business. The requirement for source code escrow needs to be formally defined within a contract, and the presence of up-to date source code at the escrow location is periodically verified.

- Support Availability - Defines the steps taken to verify the type and level of support to be provided by the vendor in support of their product or service. It is common for support performance and maintenance fees to be defined via a service level agreement (SLA.) Definitions contained within the description of support services should include details regarding how to obtain support, response times, level of support (for example the boundary between product support and professional services engagements), from what location support services will be provided, descriptions regarding escalation, the use of account managers, and other related items.

- Meeting Client Requirements - Describes the formal measures taken to validate that the vendor's delivered service or product offering aligns to established requirements. Vendors should operate in accordance to the client's legal and regulatory mandates as well as to internal policy requirements. Some examples include performing work in accordance to the client's established change management policy, deploying and configuring services in accordance to baseline security requirements, and complying to at least the same level of expectations described in the client's acceptable use policy. Additionally, the vendor contract should include language requiring notice for any staff turnover that impacts the delivery of their service or product. Timely removal of user access is dependent on early notification of termination - which can only occur with knowledge of the change.

- Incident Reporting Requirements - Legal contracts should clearly identify the requirement for vendors to provide timely notification regarding any security incidents. As has been seen in recent years, many organizations fall victim to attack through vendor relationships. If a vendor suffers an incident, the client should be made aware in order to take additional steps to protect any potential impacts they may face as a result.

## Globalization
Organizations are very likely to use multiple vendors located in many geographically diverse locations across the world. 

Globalization of the economy is a fascinating and dynamic topic, and in terms of cybersecurity presents many unique challenges. 

The most apparent issues when working with a vendor located in a different country include time zone differences, language barriers, social and moral norms, as well as legal jurisdiction. 

It is the latter issue that becomes much more pressing when considering the use of cloud service providers. 

While a more straightforward vendor relationship requires careful management of team interactions and the governance of data access, remote access, contracts and service level agreements, cloud service providers increase the complexities and risk of geographical considerations in a very unique way.

A cloud service provider arrangement requires an organization to relocate its core information technology applications, data, and infrastructure to the CSP. 

Handing over much of the control of these items presents many tactical risks, but from a geographic viewpoint, legal jurisdiction becomes much more complicated as the customer and CSP are most often located in different cities, regions, and/or countries. 

Determining which laws are applicable in various scenarios, defining boundaries around how and where cloud services can be provisioned, and training staff on these requirements becomes much more critical.

The United States, Europe, Asia, South and Central America, Australia, and New Zealand all have divergent laws protecting intellectual property, privacy, the use of encryption, and law enforcement cooperation.

## Ongoing Vendor Assessment Tools
### Vendor Policies
Establishing the maturity of vendor security operations and defining the minimum set of requirements and expectations in a policy is essential. 

In addition, it is imperative that vendors, at a minimum, adhere to the same policies and procedures in place at the organization, and that they are monitored for compliance.

### Ongoing Assessment and Compliance
As is done for risk management in general, vendor compliance must be verified on an ongoing basis. 

Some examples include, but are not limited to, evaluating software, validating vendor policy compliance, checking third-party assessment reports, paying attention to social media, website and employer review sites.