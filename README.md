# AWS Cloud Practitioner Study Notes 2023
What you need to know to successfully pass your AWS Cloud Practitioner Certification.

## Module 1: Introduction to AWS
Amazon Web Services (AWS) is the world’s most comprehensive and broadly adopted cloud platform, offering over 200 fully featured services from data centers globally.

### Cloud Computing Deployment Models

**1. Cloud-Based**
* Run all parts of the application in the cloud.
* Migrate existing applications to the cloud.
* Design and build new applications in the cloud.

**2. On-Premises (AKA private cloud deployment)**

* Deploy resources by using virtualization and resource management tools.
* Increase resources utilization by using application management and virtualization technologies.

**3. Hybrid**

* Connect cloud-based resources to on-premises infrastructures.
* Integrate cloud-based resources with legacy IT applications.


### Benefits of Cloud Computing

1. Trade fixed expense for variable expense 
2. Benefit from massive economies of scale
3. Stop guessing capacity
4. Increase speed and agility
5. Stop spending money running and maintaining data centers
6. Go global in minutes

Q: How does the scale of cloud computing help you to save costs?  
A: The aggregated cloud usage from a large number of customers results in lower pay-as-you-go prices.

## Module 2: Compute in the Cloud
Cloud computing is the on-demand delivery of IT resources over the Internet with pay-as-you-go pricing. Instead of buying, owning, and maintaining physical data centers and servers, you can access technology services, such as computing power, storage, and databases, on an as-needed basis from a cloud provider like Amazon Web Services (AWS).

### Elastic Cloud Computing (EC2)
EC2 runs on top of physical host machines managed by AWS using virtualization technology.

#### EC2 characteristics
* **Multitenancy**: A hypervisor running on the host machine is responsible for <ins>sharing the underlying physical resources between the virtual machines</ins>.  
* **Vertical Scaling**: EC2 instances are also resizable. You can increase or decrease memory and CPU.  
* **CaaS**: Compute as a Service model: AWS made it easier and more cost effective for you to acquire virtual machines.
