---
type: entity
aliases: [DTGOV]
relationships:
  - target: iaas
    type: adopted
  - target: storage-area-network
    type: uses
  - target: hypervisor
    type: uses
  - target: virtual-infrastructure-manager
    type: uses
  - target: live-vm-migration
    type: provides
  - target: virtual-server
    type: uses
  - target: sla-monitor-polling-agent
    type: uses
  - target: pay-per-use-monitor
    type: uses
  - target: resilient-virtual-server
    type: uses
  - target: resource-cluster
    type: evaluates
  - target: virtual-private-network
    type: uses
  - target: firewall
    type: uses
  - target: certificate-authority
    type: uses
  - target: remote-administration-system
    type: uses
  - target: sla-management-system
    type: implements
  - target: pricing-models
    type: implements
  - target: on-demand-virtual-machine-instance-allocation-metric
    type: uses
  - target: reserved-virtual-machine-instance-allocation-metric
    type: uses
  - target: service-level-agreement
    type: uses
  - target: dtgov-cloud-services-customer-agreement
    type: uses
tags: [case-study, organization, company, public-sector, cloud-provider, iaas-provider]
sourced_from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content
---

# DTGOV

A public organization specializing in IT infrastructure and technology services for public sector organizations, used as a case study. A public company that provides IT infrastructure and services and initiated a cloud computing initiative by choosing IaaS as its target delivery platform. An organization from a case study that has assembled cloud-aware infrastructures in its data centers, including Tier-3 facilities and clustered Storage Area Networks (SANs). An organization from a case study that established a virtualization platform using hypervisors and a VIM to offer cloud consumers virtual server packages and features like live VM migration. A case study organization that establishes high-availability virtual servers which can be automatically relocated between data centers in response to severe failures. A case study organization that uses SLA and pay-per-use monitoring for its virtual server leasing agreements, which define a minimum IT resource availability of 99.95%. An organization mentioned in a case study that creates a resilient virtual server and considers using a resource cluster for critical applications. A government organization that requires its clients to use certified digital signatures and implements virtual firewalls and VPNs for secure cloud access. A case study example of a cloud provider planning to upgrade its remote administration system to support self-provisioning and incorporate a single sign-on mechanism. A case study organization that structures its pricing model around leasing packages for virtual servers and cloud storage, with both on-demand and reserved resource allocation. An organization that has been outsourcing IT resources for public sector organizations for over 30 years and now offers IaaS services to the government sector.

## Relationships

- **adopted**: [[iaas|Iaas]]
- **uses**: [[storage-area-network|Storage Area Network]]
- **uses**: [[hypervisor|Hypervisor]]
- **uses**: [[virtual-infrastructure-manager|Virtual Infrastructure Manager]]
- **provides**: [[live-vm-migration|Live Vm Migration]]
- **uses**: [[virtual-server|Virtual Server]]
- **uses**: [[sla-monitor-polling-agent|Sla Monitor Polling Agent]]
- **uses**: [[pay-per-use-monitor|Pay Per Use Monitor]]
- **uses**: [[resilient-virtual-server|Resilient Virtual Server]]
- **evaluates**: [[resource-cluster|Resource Cluster]]
- **uses**: [[virtual-private-network|Virtual Private Network]]
- **uses**: [[firewall|Firewall]]
- **uses**: [[certificate-authority|Certificate Authority]]
- **uses**: [[remote-administration-system|Remote Administration System]]
- **implements**: [[sla-management-system|Sla Management System]]
- **implements**: [[pricing-models|Pricing Models]]
- **uses**: [[on-demand-virtual-machine-instance-allocation-metric|On Demand Virtual Machine Instance Allocation Metric]]
- **uses**: [[reserved-virtual-machine-instance-allocation-metric|Reserved Virtual Machine Instance Allocation Metric]]
- **uses**: [[service-level-agreement|Service Level Agreement]]
- **uses**: [[dtgov-cloud-services-customer-agreement|Dtgov Cloud Services Customer Agreement]]

---
*Extracted from: Cloud Computing  Concepts, Technology, Security, And    Thomas Erl, Eric Barcelo    2, 2023    Pears Content*