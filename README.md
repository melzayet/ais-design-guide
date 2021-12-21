Azure Integration Serives (AIS) offer a modern hybrid integration solution. They integrate apps, data and processes across on-prem and cloud environments.

To help create well-architected AIS solutions, this guide will highlight:
1. The main components and interactions of an AIS solution
2. The key design areas and decisions for AIS

## 1. AIS in motion

<img src='images/motion.svg'>

##### Provision infrastructure, policy and config as code [Cloud Engineers]
  - Infrastructure as Code templates: ARM, Bicep or Terraform
  - Azure Policies to govern which connectors to allow, and what configuration APIs or Logic Apps should have
  - Configure settings and parameters for dev, staging and prod environments
  - Central role or embedded in several project/product teams

##### Build and Publish APIs [API Developers]

##### Build Workflows [Integration Specialists]

##### Discover and use APIs [Partners and App Developers]

##### Provide a secure Landing Zone [Platform Engineers]

## 2. Key Design Areas
### Resource Organization and Centricity
- Consideration: Do I want integration workloads to be centrally operated and managed in one subscription?
Here are the pro/cons:
    - Centralized Integration
    - Decentralized Integration

### Roles
- Consideration: Which teams/people will play the above mentioned roles?

- Consideration: What permissions will each role need?

### Connectivity
- Internal
  - Private Link
  - Private DNS
  - VNET integration
- Outside Azure
  - VPN
  - Firewall

### Governance and patterns
- Azure Policies
- Approved Connectors
- Following design patterns

### Observability
- System Monitoring
- Alerting
- Business Activity Monitoring
