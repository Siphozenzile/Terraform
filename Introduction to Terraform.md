# Terraform (Infrastructure as Code)

### What is Terraform ?

- Terraform is an infrastructure as code tool that lets you build, change, and version infrastructure safely and efficiently.

- It lets you define both cloud and on-premises resources in human-readable configuration files that you can version, reuse, and share.

### The Problem with Manual Configuration.

Manually configuring your cloud infrastructure allows you to easily start using new service offerings to quickly prototype architectures however it comes with many downsides:

1. It’s easy to mis-configure a service through human error.

2. It’s hard to manage the expected state of configuration for compliance.

3. Its hard to transfer configuration to other team members.

## Understand Infrastructure as Code (IaC) Concept :

### What is IaC ?

IaC is Infrastructure (CPUs, memory, disk, firewalls, etc.) defined as code within definition files. Infrastructure as Code (IaC) tools allow you to manage infrastructure with configuration files rather than through a graphical user interface. IaC allows you to build, change, and manage your infrastructure in a safe, consistent, and repeatable way by defining resource configurations that you can version, reuse, and share

IaC makes it easy to provision and apply infrastructure configurations, saving time. It standardizes workflows across different infrastructure providers by using a common syntax across all of them. It makes it easy to understand the intent of infrastructure changes, because it can span multiple files, allowing human operators to organize the code based on the intent.

### Advantages of IaC :

**- IaC makes Infrastructure More Reliable**

IaC makes changes idempotent (the same), consistent, repeatable, and predictable. Without IaC, scaling up infrastructure to meet increased demand may require an operator to remotely connect to each machine and then manually provision and configure many servers by executing a series of commands/scripts. With IaC,

we can test the code and review the results before the code is applied to our target environments. Should a result not align to our expectations, we iterate on the code until the results pass our tests and align to our expectations.

**- IaC makes Infrastructure More Manageable**

Leveraging HashiCorp Terraform IaC provides benefits that enable mutation, when necessary, via code. Consider an environment has been provisioned that contains a couple servers and a load balancer. To address increased load, additional servers are needed. The IaC can be revised, with minimal changes, to bring new servers online using the previously defined configuration.

During execution, Terraform will examine the state of the currently running infrastructure, determine what differences exist between the current state and the revised desired state, and indicate the necessary changes that must be applied. When approved to proceed, only the necessary changes will be applied, leaving existing, valid infrastructure untouched.

**- IaC makes Sense**

Successfully managing the lifecycle of infrastructure is hard, and the impact of poor management decisions can be significant, ranging from financial and reputational losses to even loss of life when considering government and military dependencies on infrastructure. Adopting the use of an IaC tool such as HashiCorp Terraform, in conjunction with related and established tools, processes, and workflows, is a necessary step in mitigating these risks.
