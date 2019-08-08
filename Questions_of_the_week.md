# Week 1
## As you prepare to move your company's application to the AWS cloud. Which design principle below would be the best choice to ensure the application continues to serve requests even if some components fail?
Select one answer:

A) Scalable design

B) Disaster recovery design

C) Elastic design

D) Fault-tolerant design

# Week 2
## As you prepare to migrate part of your infrastructure to the AWS cloud from your on-prem data center, your manager asks you which of the following would be AWS' responsibility in the Shared Responsibility Model
A) Server-side data encryption

B) Networking traffic encryption protection

C) Decommissioning of your data 

D) Your customer's data hosted on AWS servers


_Hint: Remember, the Shared Responsibility Model states that AWS is responsible for security 'of' the cloud, while customers are responsible for security 'in' the cloud._

_Hint #2: Documentation & visual graphic: https://aws.amazon.com/compliance/shared-responsibility-model/_



---
# Correct answers
Week #1: D) Fault-tolerant design

Explanation: One keyword to look out for is "fail" or "failure." Components will fail, but the design principle of fault tolerance dictates that a system is able to continue working through a failure.

Week #2: C) Decommissioning of your data

Explanation: The term "decommissioning data" comes from decommissioning data in data centers, which refers to wiping out data and/or destroying physical devices that could still hold traces of data. That way, if someone were to gain access to the physical devices, there would be no way of recovering the data to reconstruct it. One example of this is completely formatting and physically destroying a hard drive.
