Azure Integration Serives (AIS) offer a modern hybrid integration solutions. They integrate apps, data and processes across on-prem and cloud environments. To help create well-architected AIS solutions, this guide will highlight:
1. The main components and interactions of an AIS solution
2. The key design areas and decisions for AIS

## 1. AIS in motion

<img src='images/motion.svg'>

## 2. Key Design Areas
### Resource Organization and Centricity
Resources within Azure are ideally grouped into different Resource Groups or different Subscriptions depending on level of isolation and autonomy required. This in fact is dictated by how centric the organization is. Many organizations are moving from more traditional central approach of integration, into a more decentralized one. Business teams are usually working on different contexts/microservices owning their own integration workloads. Yet there is always a hybrid position where customers could have some centralized integration workloads and other ones pushed down to business teams.
Here are the pro/cons of each approach:
- Centralized Integration
- Decentralized Integration
### Roles
- Cloud Engineers
- API Developers
- Integration Specialists
- Platform Engineers
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
