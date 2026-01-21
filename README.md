# Cloud-IaaS-and-PaaS-Security


❌ Resources that DO NOT live in a subnet / VPC

<img width="1720" height="1478" alt="image" src="https://github.com/user-attachments/assets/a480a8bd-7f5d-4555-9eaa-b3543759086e" />

🔑 Key takeaway:

These services are PaaS, live in provider-managed networks, and cannot have NSGs or Security Groups attached.




✅ Resources that DO live in a subnet / VPC

<img width="1580" height="1632" alt="image" src="https://github.com/user-attachments/assets/8c7762bc-9d10-408f-9283-32f4a0299e8c" />


🧠 The universal rule (memorize this)

No NIC / ENI → No NSG / Security Group
NIC / ENI in subnet/VPC → NSG / Security Group applies

Executive-safe summary

Most PaaS services (Azure & AWS) do NOT live in a subnet/VPC
