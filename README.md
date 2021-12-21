Azure Integration Serives (AIS) offer a modern hybrid integration solution. They integrate apps, data and processes across on-prem and cloud environments. To help create well-architected AIS solutions, this guide will highlight:
1. The main components and interactions of an AIS solution
2. The key design areas and decisions for AIS

## 1. AIS in motion

<img src='images/motion.svg'>

These are typical roles within an AIS solution:
- Cloud Engineers
- API Developers
- Integration Specialists
- Platform Engineers

## 2. Key Design Areas
### Resource Organization and Centricity
Consideration 1: Do I want integration workloads to be centrally operated and managed in one subscription?
Here are the pro/cons:
- Centralized Integration
- Decentralized Integration
### Roles
Consideration 1: Which teams/people will play the above mentioned roles?
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
