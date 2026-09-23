AWS Shared Responsibility Model
Introduction

The AWS Shared Responsibility Model explains how security responsibilities are divided between Amazon Web Services (AWS) and the customer. AWS is responsible for the security of the cloud, including the physical data centers, hardware, networking, and infrastructure that run AWS services. The customer is responsible for security in the cloud, which includes properly configuring the AWS services they use, protecting their data, managing access permissions, and applying appropriate security controls. The exact responsibilities can vary depending on the AWS service being used.

Reflection Questions
Q1 — Amazon S3

For Amazon S3, AWS is responsible for securing the underlying infrastructure, hardware, networking, and the S3 service itself, while I am responsible for securing the data I store in S3. This includes controlling who can access my data, managing permissions, and using appropriate encryption and security settings.

Q2 — Capital One Breach

In the 2019 Capital One breach, an attacker exploited a misconfigured web application firewall that allowed unauthorized access to data stored in Capital One's cloud environment. The security configuration was part of the customer's responsibility under the shared responsibility model, while the attacker was responsible for the unauthorized intrusion; AWS's underlying cloud infrastructure was not the issue identified in the incident.

Q3 — Security OF the Cloud vs Security IN the Cloud

I would compare cloud security to renting a house: the landlord is responsible for securing the building itself, while the person renting it is responsible for locking their doors, protecting their belongings, and deciding who is allowed inside. In the same way, AWS protects the infrastructure ("security OF the cloud"), while the customer protects and correctly configures what they put inside the cloud ("security IN the cloud").

Why the Shared Responsibility Model Matters

The Shared Responsibility Model matters to real businesses because understanding who is responsible for each part of security helps prevent configuration mistakes, protect business data, and reduce the risk of security incidents.

Conclusion

The AWS Shared Responsibility Model shows that moving systems to the cloud does not mean that AWS handles every aspect of security. AWS provides and protects the underlying cloud infrastructure, while customers must securely configure and manage the services, data, identities, and applications they use.

References
AWS — Shared Responsibility Model
AWS — Security in Amazon S3
U.S. Department of Justice — Capital One Data Theft Case
