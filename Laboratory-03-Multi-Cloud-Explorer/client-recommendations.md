# Client Cloud Recommendations Report

## Checkpoint 4: Scenario-Based Recommendations

Below are detailed cloud architecture recommendations for four distinct business clients, taking into consideration their technical requirements, scaling needs, budget constraints, and integration goals.

---

### Client A: Tech Startup Launching a Mobile Application
* **Recommended Cloud Platform:** Amazon Web Services (AWS)
* **Justification:** AWS is the ideal platform for a growing tech startup that needs high scalability with low upfront operational costs. Through programs like AWS Activate, startups can access cloud credits and technical support. AWS offers managed services like AWS Amplify and Amazon ECS/App Runner, which allow developers to launch and scale mobile backend APIs effortlessly without worrying about server maintenance.
* **Recommended Core Services:** * Amazon ECS / AWS App Runner (Backend Container Hosting)
  * Amazon DynamoDB (NoSQL Database for fast mobile data access)
  * AWS Amplify (Mobile and Web Application Lifecycle Management)

---

### Client B: Regional University Migrating On-Premises Infrastructure
* **Recommended Cloud Platform:** Microsoft Azure
* **Justification:** Universities typically rely heavily on Microsoft technologies such as Active Directory, Windows Server, and Microsoft 365 for staff and student accounts. Azure provides native integration with Microsoft Entra ID (formerly Active Directory), making identity synchronization seamless. Additionally, Azure Hybrid Benefit allows the university to reuse existing software licenses to significantly reduce cloud migration costs.
* **Recommended Core Services:**
  * Azure Virtual Machines (Hosting legacy university applications)
  * Microsoft Entra ID (Centralized identity and single sign-on access)
  * Azure Blob Storage (Archival of academic records and media)

---

### Client C: AI Startup Developing Healthcare Predictive Models
* **Recommended Cloud Platform:** Google Cloud Platform (GCP)
* **Justification:** Google Cloud is widely recognized as the industry leader in artificial intelligence and machine learning infrastructure. For an AI startup processing complex medical data, GCP provides specialized hardware like Tensor Processing Units (TPUs) alongside Vertex AI—an end-to-end platform for building, training, and deploying custom machine learning models efficiently.
* **Recommended Core Services:**
  * Vertex AI (End-to-end ML workflow and model management)
  * Compute Engine with Cloud TPUs/GPUs (High-performance model training)
  * BigQuery (Serverless data warehouse for analyzing large healthcare datasets)

---

### Client D: Global E-Commerce Company Preparing for High-Traffic Events
* **Recommended Cloud Platform:** Amazon Web Services (AWS)
* **Justification:** Global e-commerce operations demand zero downtime, low latency across continents, and seamless auto-scaling to handle unpredictable flash sales or holiday traffic spikes. AWS offers the largest global cloud footprint with Amazon CloudFront (CDN) for content delivery, Route 53 for high-availability DNS, and EC2 Auto Scaling to automatically adjust compute capacity based on live traffic.
* **Recommended Core Services:**
  * Amazon EC2 Auto Scaling & Elastic Load Balancing (Traffic handling)
  * Amazon CloudFront (Global Content Delivery Network for fast image/asset loading)
  * Amazon Aurora (High-performance relational database with global read replicas)

---

## Checkpoint 6: Multi-Cloud Decision Matrix

This matrix provides a quick consulting guide for matching core business requirements to the optimal cloud provider.

| Business Requirement | Recommended Platform | Justification |
| :--- | :--- | :--- |
| **Startup Company** | AWS / GCP | Offers low startup costs, credits, flexible compute scaling, and fast deployments. |
| **Enterprise Organization** | AWS / Azure | Robust governance, security compliance, hybrid cloud features, and global footprint. |
| **Microsoft Environment** | Microsoft Azure | Native integration with Windows Server, Active Directory, and existing enterprise licensing. |
| **AI / Machine Learning** | Google Cloud Platform | Native integration with TensorFlow, Vertex AI, and high-performance TPU/GPU support. |
| **Kubernetes Deployment** | Google Cloud Platform | Google created Kubernetes; GKE is widely recognized as the most advanced managed Kubernetes engine. |
| **Global Web Application** | AWS | Massive global footprint with Route 53, CloudFront CDN, and Edge Locations for low latency. |
