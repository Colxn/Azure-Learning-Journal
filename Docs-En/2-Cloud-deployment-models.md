# Cloud Deployment Models

## Introduction

A deployment model defines how Cloud Computing resources are implemented and organized.
It determines who has access to the resources, who manages them, and where they are physically located.

Microsoft Azure offers three main deployment models:

- Public Cloud
- Private Cloud
- Hybrid Cloud

---

## Public Cloud

The public cloud uses infrastructure owned by a cloud provider such as Microsoft Azure.
Resources are shared among multiple customers, although each organization keeps its data and services isolated.

### Characteristics

- No upfront hardware investment required
- Virtually unlimited scalability
- Rapid resource deployment
- Pay-As-You-Go pricing

**Example:** a company creates virtual machines in Azure without purchasing physical servers.

---

## Private Cloud

The private cloud is dedicated exclusively to a single organization.
Resources are not shared with other customers and the organization maintains a higher level of control over the infrastructure.

### Characteristics

- Greater control over resources and security
- Dedicated infrastructure
- Advanced customization
- Requires investment and maintenance

**Example:** an organization deploys a virtualized environment with VMware to host its internal applications without relying on external providers.

---

## Hybrid Cloud

The hybrid cloud combines local (on-premises) infrastructure with public cloud services.
It allows data and applications to move between both environments based on business needs.

Microsoft Azure extends the hybrid model through **Azure Arc**, which enables managing on-premises and multicloud resources from a single control panel in Azure.

### Characteristics

- Maximum flexibility
- Allows keeping critical systems on-premises
- Leverages the scalability of the public cloud
- Facilitates gradual migration to the cloud

**Example:** a company stores sensitive information on-premises while running web applications in Azure.

---

## Deployment Model Comparison

| | Public Cloud | Private Cloud | Hybrid Cloud |
|---|---|---|---|
| **Initial investment** | No CAPEX required | Requires infrastructure investment | Combines local investment and cloud services |
| **Scalability** | Fast and virtually unlimited | Limited to available hardware | Flexible depending on the environment |
| **Resources** | Shared among customers | Dedicated to one organization | Local and cloud based on need |
| **Management** | Less responsibility for the customer | Greater administrative responsibility | Shared administration |
| **Cost model** | Pay per consumption (OPEX) | Own operation costs | Combined costs |

---

## Summary

Deployment models allow organizations to choose how to consume cloud services based on their specific needs.

- **Public Cloud** prioritizes speed and cost reduction.
- **Private Cloud** offers greater control and customization.
- **Hybrid Cloud** combines the advantages of both models.

The choice will depend on factors such as security, budget, regulatory compliance, and operational flexibility.

---

## References

- [Define cloud models — Microsoft Learn](https://learn.microsoft.com/en-us/training/modules/describe-cloud-compute/5-define-cloud-models)

---

[Return to index](../README.md)
