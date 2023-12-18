---
description: Internal page - but useful to all how we operate the group
---

# Workflows

### Advertising

```mermaid
flowchart TD
    C{Advertise}
    C -->|Direct| D[Contact]
    C -->|Email| D[Contact]
    C -->|Online| F[Not yet]
    D -->|Phone or Email| G{Direct to WW}
    G -->|Send info| H[Provide Info]
    G -->|Book consent call| H[Provide Info]

```

### Signing up Members



```mermaid
flowchart TD
    C{Weekly Check New Signups from MS Form}
    C -->|More Info Needed| D[Contact for More Information]
    C -->|Not Suitable| E[Send Polite Decline Message]
    C -->|Suitable| F[Invite to Forum]
    F --> G[Send Welcome Email with Guidelines]
    G --> H[Encourage Profile Completion]
    H --> I[Prompt for Introduction Post]
    I --> J[Offer Assistance and Resources]
    J --> K[Monitor Initial Engagement]
    K -->|No Engagement| L[Follow-Up Contact]
    K -->|Engagement| M[Regular Engagement Monitoring]
    L --> N[Offer Additional Support or Information]
    M --> O[Encourage Ongoing Participation]


```

### Weekly forum management
