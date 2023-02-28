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
