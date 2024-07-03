# Performing Risk Management Activities

## Lesson Introduction
Risk is all around.

As organizations grow and adapt to changing needs and strategic objectives, these adaptations present new and evolving risk challenges.

It is imperative to understand how to identify and measure risk in order to formulate prioritized approaches for managing it.

In this lesson, we will frame risk from the viewpoint of an advanced security practitioner and explore various mechanisms designed to assist us in the identification and evaluation of risk and the essential components of a risk management strategy.

## Lesson Objectives
In this lesson, you will:
- Understand the role of Risk Management.
- Understand the Risk Management Life Cycle.
- Compare and contrast common policies and best practices.
- Learn about the importance of vendor management.
- Learn about effective vendor management practices.
- Understand risks introduced in an organization's supply chain.


## Topic 1A: Explain Risk Assessment Methods
Performing risk management helps organizations better formulate protections for its employees, partners, and assets. Risk management programs should be rooted in industry frameworks and use standard terminology when describing elements of the program.

## Understanding Risk Management
As security practitioners, we describe risk management as the process for identifying, assessing, and mitigating vulnerabilities and threats to the essential functions of an organization.

**Risk Management** is complex and treated differently from one organization to another.  Many companies institute **Enterprise Risk Management (ERM)** policies and procedures, based on frameworks such as NIST's **Risk Management Framework (RMF)** and **ISO 31000**.

In order to better understand risk management, it is helpful to deconstruct it into five distinct phases:

1) **Identification of mission critical functions** - mitigating risk can involve large expenditures so it is important to focus and prioritize our approach. Effective risk management begins with the identification of mission essential functions that could cause the whole business to fail if they are not performed.

2) **Identification of known vulnerabilities** - for each function or workflow (starting with the most critical), analyze systems and assets and list any vulnerabilities or weaknesses to which they may be susceptible.

3) **Identification of potential threats** - for each function or workflow, identify the threat sources and actors that may exploit or accidentally expose vulnerabilities.

4) **Analysis of business impacts** - use qualitative and quantitative methods to analyze impacts and likelihood

5) **Identification of risk responses** - for each risk, identify possible countermeasures. Most risks require some sort of mitigation, but other types of response might be warranted depending on the types of risk.

## Measuring Risk
**Risk** is a measure of the impact (or consequence) and likelihood of a threat exploiting a vulnerability. To measure risk, it is essential to first identify known, existing vulnerabilities and then evaluate the impacts realized by their exploitation.

Two additional, and critically important, variables considered in evaluating risk are likelihood and impact. Some risks may be highly likely, or very probable, but minimally impactful, and yet others may be incredibly impactful but very unlikely, sometimes described as "statistically improbable" or as a "black swan event." These considerations play an important part in ranking and prioritizing risks in order to appropriately focus financial and human resources in the most effective way

**Likelihood** of occurrence is the probability of the threat being realized.

**Impact** is the severity of the risk if realized.  This may be determined by factors such as the scope, the value of the asset, or the financial impacts of the event.

## Understand Risk Assessment Methods
Quantitative risk analysis involves the use of numbers (generally in dollars $$$) to evaluate impacts.

#### Quantitative Risk Analysis
The variable used in quantitative analysis include the following:

**Single Loss Expectancy (SLE)** - The amount that would be lost in a single occurrence of the risk factor. Another way to think of SLE is "the cost of a single event," such a downtime.

**Annual Rate of Occurrence (ARO)** - The number of times in a year that the single loss occurs. For example, if a server outage is identified as an SLE event, and the outage occurs twice a month, then the ARO would be: 2 times per month x 12 months in a year to result in an ARO of "24."

**Annual Loss Expectancy (ALE)** - The amount that would be lost over the course of a year, or the sum-total of all single loss events over the span of 12 months.

ALE = SLE x ARO

Single Loss Expectancy can be further broken down into the following components:

**Asset Value(AV)** - The value of an asset, such as a server or even an entire building

**Exposure Factor (EF)** - EF is the percentage of the asset value that would be lost. For example, if a building is exposed to a severe weather event, like a hurricane, tornado, or earthquake, only part of the building may be lost and this would be described as its "exposure factor."

SLE = AV x EF

When component costs can be easily determined, quantitative assessment can quickly identify appropriate courses of action.

The challenge of quantitative risk analysis becomes apparent when component costs are not clear.  Sometimes, the value of component costs can be difficult to determine without historical data and this results in subjective guesswork. Despite this potential challenge, quantitative risk assessment frequently yields an effective description of assets and risks resulting in a sound basis for decision making.

Some additional quantitative measures include the following:

**Total Cost of Ownership (TCO)** - this includes all associated costs of an asset to include not only purchase (acquisition) costs but also the costs to maintain and safely operate the asset over its entire lifespan.

**Return on Investment (ROI)** - A performance measure that compares the cost of an item to the benefit it provides. Traditionally, ROI identifies the amount of money generated and/or saved after investing in an asset.

**Mean Time To Recovery (MTTR)** - this is a measure of downtime duration, the time elapsed between when a service or device fails and when it's functionality is restored.

**Mean Time Between Failures (MTBF)** - this metric can be associated with hardware lifespan, for example the estimated write/erase cycles that SSD can perform before failure can be expected, but the concept extends to other areas within information technology such as the amount of time a service can be expected to run before it experiences an outage.

**Gap Analysis** - A gap analysis measures the difference between current state and desired state. Developing measures such as ALE, MTTR, MTBF, TCO, and others, allows an organization to identify how closely it is performing in relation to desired outcomes. When considering regulatory and/or legal requirements, gap analysis is a useful measure to determine compliance levels.

#### Qualitative Risk Analysis
Qualitative Risk Analysis describes the evaluation of risk through the use of words. For this reason, qualitative risk analysis is much more subjective than quantitative analysis. Qualitative risk analysis is well-suited to the analysis of intangible assets, for example an organization's reputation or brand image. These things are far more complicated to assess numerically and so quantitative analysis is often avoided. Qualitative risk analysis requires significant contributions from the marketing, sales, and communications departments as these groups are best-suited, based on their unique insights, to assess the value of many intangible business assets and the impacts that various risk events can have on them.

## Explain Risk Responses
After identifying risks, the next step is to decide how to response to them. There are four risk responses as shown in the following diagram:

#### Risk Responses
![The four types of risk responses](https://s3.amazonaws.com/wmx-api-production/courses/17541/images/7688-1626186242105-cas_fig01_01.png)

#### Avoid
**Risk avoidance** means that you stop doing the activity that is risk-bearing. For example, a company uses an in-house web application for managing inventory. If the application is discovered to have numerous high-severity vulnerabilities, the company may decide that the cost of maintaining the application is not worth the benefit it provides and decide to decommission it.

#### Accept
**Risk acceptance** means that an identified risk area has been evaluated and this resulted in an agreement to continue operating the software, hardware, processes, actions, or other type of similar tasks, despite the identified risks.

There is risk in all we do, even simple tasks in day to day life involve risks, but despite this, we are still productive and largely safe so long as we are aware of risks and act within safe limitations. At some point, identified risks must all be accepted. It is the task of risk management to help contain risks within carefully constructed and mutually agreed-upon boundaries because risk cannot be eliminated.

#### Mitigate
**Risk Mitigation** is the overall process of reducing exposure to, or the effects of, risk factors.  This is where the work of risk management really comes into focus. As risks are identified, we must address them in a measured way. As security practitioners, we are tasked with making technical business operations safe. This is accomplished through the implementation of mitigating controls. For example, when considering web applications, the number of potential security issues is long but the need for the web application is identified as essential or critical to the business, and so we must determine ways in which the web application can be operated as safely as possible while still meeting the needs of the business. To do this we use various means to improve the safety and security of the web application through the implementation of mitigating control.

By implementing effective mitigating controls we can reduce the overall risk. We continue to implement mitigating controls until risk is reduced to a level deemed "acceptable."

#### Transfer
**Risk transference** (or sharing) means assigning risk to a third party, which is most typically exemplified through the purchase of an insurance policy. Insurance transfers financial risks to a third party. This is an important strategy as the cost of data breaches, and other cybersecurity events, can be extremely high and result in bankruptcy.

## Understanding Inherent and Residual Risk
#### Inherent Risk
Everything involves risk, to a certain degree. This can be described as inherent risk - the level of risk that exists before any type of mitigation has been implemented.

Some things are inherently risky. For example, operating a website is inherently risky due to the multitude of **attack vectors** present in web applications.  Processing financial transactions, storing and processing personal health information, and protecting military networks are additional examples of inherently risky tasks. It is our job, as security practitioners, to reduce these risks through the implementation of mitigating controls.

#### Residual Risk
Where inherent risk is the risk before mitigation, **residual risk** is the likelihood and impact after specific mitigation, transference, or acceptance measures have been applied. **Risk appetite** is a strategic assessment of what level of residual risk is tolerable for an organization. Some organizations, like a start-up for example, have very high risk appetites.  Everything about a start-up involves risk and so the threshold by which risk is measured will be categorically different than how risk is measured at a 200 year-old insurance company.

###### *It is important to note that residual risk and acceptable risk are not always equivalent. It might be that a certain identified risk area cannot be mitigated to an acceptable level.*

## Understanding Risk Expectations
Despite the presence of mitigating controls, some risks may still be troublesome. It could also be that mitigating controls are not available. IN this situation, when a risk item cannot be mitigated, or if identified mitigation do not reduce risks to an acceptable level, then additional decisions must be made.  For example, a different risk response might be warranted - like avoidance perhaps - if it is determined that the identified risks cannot be contained within the safe boundaries.  If a different risk response is not reasonable or feasible, then a risk exception may be warranted. This decision should not be taken lightly, and it is imperative that this decision include careful documentation identifying the risks, why the risks are concerning, as well as specific justification describing why an exception is warranted.  This exception should include dates for when the decision was made and the signatures of all involved in the decision.