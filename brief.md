Version: NAFATH-V2
Track:  Networking 
## Overview
Nowadays, advanced network technologies such as 5G have become essential for supporting critical services, including emergency response and remote medical procedures. The reliability of these networks is vital, as any interruption may affect communication, coordination, and the delivery of essential services. Therefore, maintaining network performance, availability, and security during congestion, outages, and cyberattacks is a key priority. Six IT fields contribute to achieving this goal: Software, Artificial Intelligence (AI), Mobile Technology, Networking, Cybersecurity, and Data. Each field plays a specific role, but their effectiveness depends on how well they work together. By integrating these technologies, telecom operators can detect potential problems, manage network traffic efficiently, protect sensitive information, and maintain reliable connections. This integrated approach helps ensure that emergency responders can communicate securely and effectively when reliable connectivity matters most.

## Software
HTTP safe methods include GET, HEAD, OPTIONS, and TRACE, because they are intended to retrieve information without changing server state. Idempotent methods include GET, HEAD, OPTIONS, TRACE, PUT, and DELETE, because repeating the same request has the same intended effect as making it once. This matters when clients retry failed requests: idempotent methods can generally be retried safely, while retrying non-idempotent methods, such as POST, may create duplicate actions or transactions.

Resource: MDN Web Docs: HTTP Request Methods-https://developer.mozilla.org/en-US/docs/Web/HTTP/Reference/Methods

## AI
Overfitting occurs when an AI model learns the training data too closely, including noise and irrelevant patterns, making it less accurate when predicting congestion under new network conditions. Cross-validation helps detect overfitting by dividing the dataset into multiple subsets, training the model on some subsets and evaluating it on others. If the model performs well on training data but poorly on validation data, it may be overfitting.

Resource: Scikit-learn – Cross-validation-https://scikit-learn.org/stable/modules/cross_validation.html

## Mobile
Mobile devices for emergency responders should be compact, lightweight, and energy-efficient for easy use in critical situations. Semiconductor technology enables the integration of communication components into small chips, reducing device size and power consumption. The devices should support 5G connectivity and seamless handover between cellular base stations to maintain communication while responders are moving. They should also reconnect to available networks when coverage is lost, minimizing service interruptions. These features help ensure reliable connectivity, portability, and efficient communication during emergencies.

Resource: 3GPP – Mobile Network Standards- https://www.3gpp.org

## Networking
5G network slicing is a technology that creates multiple virtual networks on shared physical infrastructure, each configured for specific service requirements. A dedicated slice for emergency responders can prioritize critical communications, provide guaranteed quality of service, and allocate resources to reduce delays during network congestion. This helps maintain reliable communication for emergency teams. However, its effectiveness depends on proper configuration, sufficient resources, and resilient network infrastructure.

Resource: GSMA – Network Slicing- https://www.gsma.com/get-involved/gsma-foundry/gsma_resources/5g-maturity-and-adoption-in-asia-pacific-hospitals-from-readiness-to-implementation/ 

## Cybersecurity
The incident response lifecycle is essential for protecting the 5G network and ensuring reliable communication for emergency responders. It involves preparing security measures, detecting and analyzing cyberattacks, containing threats, removing malicious activity, restoring services, and reviewing incidents to prevent recurrence. The telecom operator should also implement strong authentication, secure passwords, and cryptographic keys to verify network components and prevent unauthorized access. Continuous network monitoring and timely incident response help minimize service disruptions, protect sensitive information, and maintain the availability and security of critical emergency communications. 

Resource: 3GPP – 5G Security Standards-https://www.3gpp.org

## Data
A star schema uses a central fact table connected directly to denormalized dimension tables, making queries simpler and faster. A snowflake schema normalizes dimension tables into related sub-tables, reducing data redundancy but increasing query complexity. For reporting 5G service usage by region and day, a star schema is more suitable because it supports straightforward queries, efficient aggregation, and clear reporting for project managers.

Resource: Microsoft Learn – Star Schema-https://learn.microsoft.com/en-us/power-bi/guidance/star-schema

## Misconception in My Track
Common wrong belief: A dedicated 5G network slice guarantees uninterrupted communication for emergency responders during network congestion and outages.
Correct version: Network slicing allows a 5G network to create virtual networks with specific performance requirements and prioritize critical emergency traffic. However, it cannot guarantee uninterrupted service on its own. Network reliability also depends on sufficient resources, redundant connections, backup power, alternative routes, and effective failover mechanisms. These measures help maintain connectivity when network components fail or traffic increases. Therefore, network slicing should be combined with network redundancy and resilience strategies to support reliable emergency communications.

Resource: RFC 9543 – A Framework for Network Slices in Networks Built from IETF Technologies-https://www.rfc-editor.org/rfc/rfc9543.html

## Open Question

One thing I would investigate further is how 5G networks can support emergency communication during natural disasters and improve healthcare services. I would explore how network redundancy and backup connections maintain connectivity when infrastructure is damaged by floods, storms, or earthquakes. I would also learn how 5G supports remote medical consultations, real-time patient monitoring, and the rapid sharing of medical information. Understanding these technologies is important because reliable network connectivity helps emergency teams coordinate rescue operations, enables healthcare professionals to respond quickly, and supports the delivery of essential medical care during critical situations.
