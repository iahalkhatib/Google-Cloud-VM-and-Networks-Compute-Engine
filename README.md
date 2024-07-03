# Google-Cloud-VM-and-Networks-Compute-Engine

![image](https://github.com/iahalkhatib/Google-Cloud-VM-and-Networks-Compute-Engine/assets/170050432/1ed8a3da-de2f-4e91-93ef-7e7ad7e51b73)

# What is Compute Engine?

Google Cloud's Infrastructure as a Service (IaaS) solution.

Allows you to create and run virtual machines (VMs) on Google's infrastructure.

No upfront costs, pay-as-you-go approach.

# Benefits of Compute Engine VMs:

Scalability: Run thousands of VMs with consistent performance.

Customization: Configure VMs like physical servers (CPU, memory, storage, OS).

Flexibility: Create VMs via web console, command-line, or API.

Choice of Operating Systems: Use pre-built Linux/Windows images or custom versions.

Quick Deployment: Launch pre-configured solutions from the Cloud Marketplace.

Cost-Effectiveness: Many solutions are free, with usage-based pricing for others.

# Compute Engine Pricing:

Per-second billing: Pay for VM usage with a one-minute minimum.

Sustained-use discounts: Automatic discounts for VMs running longer than 25% of a month.

Committed-use discounts: Up to 57% off for committing to vCPUs and memory for 1 or 3 years.

Preemptible & Spot VMs: Significant savings (up to 90%) for interruptible workloads (batch jobs).

Preemptible VMs: Can be terminated by Google if resources are needed elsewhere. Run for up to 24 hours.

Spot VMs: Similar savings to Preemptible VMs, but no maximum runtime.

Storage: High-throughput connection between VMs and persistent disks included by default, at no extra cost.

Custom Machine Types: Pay only for the resources you need by specifying CPU, memory, etc.


# Which of the following is NOT a benefit of using Google Compute Engine VMs?

(a) Scalability to run a large number of virtual machines 
This is a benefit 
*Example: A company can easily scale its compute resources up or down to handle fluctuations in website traffic by adding or removing VMs in Compute Engine.

(b) Cost-effectiveness with pay-as-you-go pricing 
This is a benefit 
*Example: A developer can test a new application on a small VM for a short period without incurring significant costs.

(c) Pre-configured solutions for quick deployment from the Cloud Marketplace 
This is a benefit 
*Example: Instead of manually configuring a web server environment, a developer can launch a pre-configured WordPress solution from the Cloud Marketplace in minutes.

(d) Limited customization options for virtual machine configurations 
This is not a benefit 
*Example: Compute Engine allows users to specify the exact amount of CPU, memory, and storage required for their VMs, offering a high degree of customization.

# For workloads that can be interrupted, which Compute Engine VM option offers the most significant cost savings?

(a) Standard VM with sustained-use discount 
This offers some savings, but not the most significant. 
*Example: While sustained-use discounts can provide some cost reduction for long-running standard VMs, they might not be the most economical choice for highly interruptible workloads.

(b) Committed-use discounts for long-term use 
This is for predictable workloads, not the most significant for interruptible tasks.
*Example: Committed-use discounts are ideal for predictable workloads that run continuously, not for tasks that can be paused or restarted without impacting the outcome.

(c) Preemptible VM with the possibility of termination by Google 
This is the most significant cost savings for interruptible workloads. 
*Example: Preemptible VMs offer significant cost savings (up to 90%) for batch jobs or other tasks that can be interrupted and restarted without losing progress. Google might terminate these VMs if resources are needed elsewhere, but the upfront savings are substantial.

(d) Spot VM with variable pricing but no maximum runtime 
Savings are similar to Preemptible VMs, but consider trade-offs. 
*Example: Spot VMs offer similar cost savings to Preemptible VMs, but without a maximum runtime limit. However, their pricing can fluctuate more significantly.

# What is the default storage option for Compute Engine VMs, and is there an additional cost associated with it?

(a) Limited storage with a separate pricing plan 
This is not the default option.

(b) High-throughput connection to persistent disks, included at no extra cost 
This is the default option. 
*Example: By default, Compute Engine VMs have a high-throughput connection to persistent disks, allowing them to access and store data efficiently. There's no additional cost for this functionality.

(c) No default storage option, must be configured separately 
This is not the default.

(d) Temporary storage that disappears when the VM is stopped 
This is not the default option.
