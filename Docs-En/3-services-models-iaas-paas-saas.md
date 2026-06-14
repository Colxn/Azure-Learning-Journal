# Service Models: IaaS, PaaS, and SaaS

## Introduction

A service model defines which responsibilities the cloud provider manages and which remain under the customer's control.

Depending on the chosen model, the customer may be responsible for a large portion of the infrastructure or simply use a ready-to-use application.

The three main service models are:

- Infrastructure as a Service (IaaS)
- Platform as a Service (PaaS)
- Software as a Service (SaaS)

---

## IaaS — Infrastructure as a Service

IaaS is the most flexible category of cloud services. It provides the greatest amount of control over IT resources.

The cloud provider manages the physical infrastructure, while the customer is responsible for configuring and managing the systems running on top of it.

### Provider Responsibilities

- Physical hardware
- Networking and connectivity
- Storage
- Data center

### Customer Responsibilities

- Operating system
- Middleware
- Applications
- Data
- Security configuration

### Characteristics

- Maximum level of control
- High flexibility
- Similar to managing traditional on-premises infrastructure
- On-demand scalability

**Azure example:** Azure Virtual Machines

---

## PaaS — Platform as a Service

PaaS provides a managed environment for developing, testing, and running applications.

The provider manages the underlying infrastructure and platform, allowing the customer to focus on their applications and data.

### Provider Responsibilities

- Physical hardware
- Networking
- Storage
- Operating system
- Middleware
- Development tools

### Customer Responsibilities

- Applications
- Data
- Access configuration

### Characteristics

- Reduces administrative tasks
- Simplifies application development
- Enables rapid deployments
- Built-in scalability

**Azure example:** Azure App Service

---

## SaaS — Software as a Service

SaaS delivers complete, ready-to-use applications over the internet.

It is the model with the lowest operational burden for the customer, as the provider manages virtually all components of the service.

### Provider Responsibilities

- Infrastructure
- Platform
- Application
- Updates
- Service security

### Customer Responsibilities

- Data
- Users
- Account and permission configuration

### Characteristics

- No local installation required
- Minimal administration
- Accessible from anywhere
- Automatic updates

**Azure example:** Microsoft 365

---

## Responsibility Comparison Table

| Resource | IaaS | PaaS | SaaS |
|---|---|---|---|
| Information and data | Customer | Customer | Customer |
| Devices | Customer | Customer | Customer |
| Accounts and identity | Customer | Customer | Customer |
| Identity infrastructure | Customer | Shared | Shared |
| Applications | Customer | Customer | Provider |
| Network controls | Customer | Shared | Provider |
| Operating system | Customer | Provider | Provider |
| Physical servers | Provider | Provider | Provider |
| Storage | Provider | Provider | Provider |

### Quick Summary

| Model | What the customer manages |
|---|---|
| IaaS | Operating system, applications, and data |
| PaaS | Applications and data |
| SaaS | Data, users, and configuration |

---

## Summary

Service models allow organizations to choose the level of control and responsibility they want to assume over their cloud infrastructure.

- **IaaS** is ideal when maximum flexibility and control are needed, at the cost of greater administrative responsibility.
- **PaaS** removes infrastructure management and allows teams to focus on application development.
- **SaaS** offers the lowest operational burden, delivering ready-to-use software without managing anything underneath.

The right model depends on the required level of control, the team's technical capacity, and business objectives.

---

## References

- [Describe cloud service types — Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/describe-cloud-service-types/)

---

[Return to index](../README.md)
