## Module 2: Compute in the Cloud
Cloud computing is the on-demand delivery of IT resources over the Internet with pay-as-you-go pricing. Instead of buying, owning, and maintaining physical data centers and servers, you can access technology services, such as computing power, storage, and databases, on an as-needed basis from a cloud provider like Amazon Web Services (AWS).

### Elastic Cloud Computing (EC2)
EC2 runs on top of physical host machines managed by AWS using virtualization technology. Provides secure, resizable compute capacity in the cloud as Amazon EC2 instances. Instance types are optimal for different tasks.

#### EC2 characteristics
* **Multitenancy**: A hypervisor running on the host machine is responsible for <ins>sharing the underlying physical resources between the virtual machines</ins>.  
* **Vertical Scaling**: EC2 instances are also resizable. You can increase or decrease memory and CPU.  
* **Compute as a Service (CaaS)**: AWS made it easier and more cost effective for you to acquire virtual machines.

#### EC2 instance types
* **General Purpose**: Provide a balance of compute, memory and networking resources.  
You can use them for a variety of workloads, such as: 
    * Application Servers.
    * Gaming Servers.
    * Backend Servers for enterprise applications.
    * Small and medium databases.
* **Compute Optimized**: Are ideal for compute bound applications that benefit from high performance processors.  
  * High-performance web servers.
  * Compute-intensive applications servers.
  * Dedicated gaming servers.
  * Batch processing workloads.
* **Memory-Optimized**: Are designed to deliver fast performance for workloads that process large datasets in memory.
* **Accelerated Computing**: Use hardware accelerators, or coprocessors to perform some functions more efficiently than is possible in software running on CPUs.
  * Floating-point number calculations.
  * Graphics processing.
  * Data pattern matching.
* **Storage Optimized**: Are designed for workloads that require high, sequential read and write access to large datasets on local storage.
  * Distributed file systems.
  * Data warehousing.
  * High-frequency online transaction processing.
* **HPC Optimized**: High performance computing (HPC) instances are ideal for applications that benefit from high-performance processors such as large, complex simulations and deep learning workloads.

#### EC2 Pricing

* **On-Demand**
   * Are ideal for short-term, irregular workloads that cannot be interrupted.
   * The instance runs continuously until you stop them, and you pay for only the compute time you use.
   * No longer-term commitments or upfront payments are needed.
   * You can increase or decrease your compute capacity depending on the demands of your application and only pay the specified per hourly rates for the instance you use.
* **Savings Plans**
   * Enable you to reduce your compute costs by committing to a consistent amount of compute usage for a 1-year or 3-year term. This term commitment results in savings of up to 72% over On-Demand costs.
   * Any usage up to the commitment is charged at the discounted Saving Plan rate.
   * Any usage beyond the commitment is charged at regular On-Demand rates.
   * They apply to Fargate, Lambda and EC2.
* **Spot Instances**: Are ideal for workloads with flexible start and end times, or that can withstand interruptions. Spot instances use unused Amazon EC2 computing capacity and offer you cost savings at up to 90% off of On-Demand prices.
* **Dedicated Hosts**: Are physical servers with Amazon EC2 instances capacity that is fully dedicated to your use. You can use your existing oer-socket, per-core, or per-VM software licenses to help maintain license compliance. Dedicated Hosts are the most expensive.
* **Reserved Instances (RI)**
   * Are billed discounts <ins>applied to the use of On-Demand instances</ins> in your account.
   * Can apply to usage across all Availability Zones in an AWS region, or can provide a capacity reservation when assigned to a specific Availability Zone.
   * At the end of the reserved instance term, you can continue using the Amazon EC2 instance without interruption. However, you are charged On-Demand rates until you either terminate the instance or purchase a new reserved instance that matches the instance attributes (type, region, platform).
   * You can purchase **Standard RIs** and **Convertible RIs** for a 1-year or 3-year term, and **Scheduled RIs** for a 1-year term.
   
##### Amazon EC2 RI instance types   
   * **Standard RIs**: These provide the most significant discount (up to 72% off On-Demand) and are best suited for steady-state usage.
   * **Convertible RIs**: Change instance families, operating system, tenancy, and payment option as long as the exchange results in the creation of Reserved Instances of equal or greater value.
   * **Scheduled RIs** These are available to launch within the time windows you reserve. This option allows you to match your capacity reservation to a predictable recurring schedule that only requires a fraction of a day, a week, or a month.
  
