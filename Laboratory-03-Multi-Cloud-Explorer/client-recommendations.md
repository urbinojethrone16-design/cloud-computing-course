# Cloud Platform Client Recommendations

## Checkpoint 4 – Cloud Platform Recommendation Challenge

CloudNova Technologies must select cloud platforms according to each client's technical environment and business requirements. The following recommendations focus on suitability rather than assuming that one cloud provider is best for every organization.

---

# Client A – Startup Company

## Business Requirement

A startup company wants to launch a mobile application. Its current budget is limited, but the company expects its number of users and infrastructure requirements to increase significantly in the future.

## Recommended Platform: Google Cloud

I recommend **Google Cloud** because the startup can begin with managed and serverless technologies instead of maintaining a large number of virtual servers immediately. **Cloud Run** can host scalable application services, **Firestore** can provide a managed application database, and **Cloud Storage** can store images, uploads, backups, and other application objects. As application demand increases, the company can also adopt Compute Engine, Google Kubernetes Engine, analytics services, and additional managed services without redesigning the entire application immediately.

### Recommended Services

1. **Cloud Run** – serverless application and container hosting.
2. **Cloud Firestore** – managed document database suitable for application data.
3. **Cloud Storage** – object storage for files, images, backups, and application assets.
4. **Compute Engine** – optional virtual-machine computing for workloads requiring more infrastructure control.

---

# Client B – University

## Business Requirement

The university already uses Windows Server, Microsoft 365, and Active Directory and wants to migrate selected systems and services to the cloud.

## Recommended Platform: Microsoft Azure

I recommend **Microsoft Azure** because the university already operates a Microsoft-centered technology environment. **Azure Virtual Machines** can host migrated Windows or Linux servers, **Microsoft Entra ID** can provide cloud identity and access-management capabilities, and **Azure Migrate** can assist with discovering, assessing, planning, and migrating existing workloads. **Azure Blob Storage** can additionally provide cloud-based storage for files, backups, archives, and application data.

### Recommended Services

1. **Azure Virtual Machines** – cloud-hosted Windows and Linux servers.
2. **Microsoft Entra ID** – cloud identity and access management.
3. **Azure Migrate** – migration assessment, planning, and migration tools.
4. **Azure Blob Storage** – cloud object storage.

---

# Client C – AI Research Company

## Business Requirement

An artificial intelligence research company develops machine-learning applications and requires significant computing power for model development and experimentation.

## Recommended Platform: Google Cloud

I recommend **Google Cloud** because its platform provides extensive services for artificial intelligence, machine learning, data processing, GPUs, and containerized computing. **Vertex AI** can support model training and deployment, **Compute Engine** can provide configurable computing resources for demanding workloads, and **Cloud Storage** can store training datasets and model artifacts. The company can also use **Google Kubernetes Engine (GKE)** when research workloads need container orchestration or scalable distributed environments.

### Recommended Services

1. **Vertex AI** – managed AI and machine-learning platform.
2. **Compute Engine** – virtual-machine and high-performance computing resources.
3. **Cloud Storage** – storage for datasets and model artifacts.
4. **Google Kubernetes Engine** – managed Kubernetes for containerized AI/ML workloads.

---

# Client D – Global E-Commerce Company

## Business Requirement

A multinational e-commerce company serves customers around the world. Its infrastructure must remain highly available and must automatically respond when customer traffic increases.

## Recommended Platform: Amazon Web Services

I recommend **AWS** because the company can combine its global infrastructure with services specifically designed for scalable and highly available web applications. **Amazon EC2 Auto Scaling** can adjust application-server capacity, **Elastic Load Balancing** can distribute incoming requests across healthy resources, and **Amazon CloudFront** can deliver content using globally distributed edge locations. The company could also use Amazon S3 for application assets and Amazon Route 53 for DNS as the architecture expands.

### Recommended Services

1. **Amazon EC2 Auto Scaling** – automatically adjusts EC2 capacity.
2. **Elastic Load Balancing** – distributes application traffic across healthy resources.
3. **Amazon CloudFront** – global content delivery.
4. **Amazon S3** – object storage for product images and other application assets.
5. **Amazon Route 53** – DNS and traffic-routing services.

---

# Recommendation Summary

| Client | Primary Requirement | Recommended Platform |
|---|---|---|
| Startup Company | Low initial overhead with future scalability | **Google Cloud** |
| University | Existing Microsoft environment | **Microsoft Azure** |
| AI Research Company | AI/ML and high-performance computing | **Google Cloud** |
| Global E-Commerce Company | Global availability and automatic scaling | **AWS** |

---

## Conclusion

The client scenarios demonstrate why cloud-platform selection should be based on requirements rather than popularity. Existing software investments, application architecture, scaling behavior, technical skills, and the type of workload can make one provider more suitable than another.

---

## References

1. Google Cloud Documentation. **Cloud Run Documentation**.  
   https://docs.cloud.google.com/run/docs

2. Google Cloud Documentation. **Firestore Documentation**.  
   https://docs.cloud.google.com/firestore/docs

3. Google Cloud Documentation. **Cloud Storage Documentation**.  
   https://docs.cloud.google.com/storage/docs

4. Google Cloud. **Vertex AI Documentation**.  
   https://cloud.google.com/vertex-ai/docs

5. Google Cloud Documentation. **Google Kubernetes Engine**.  
   https://docs.cloud.google.com/kubernetes-engine/docs

6. Microsoft Azure. **Azure Virtual Machines**.  
   https://azure.microsoft.com/en-us/products/virtual-machines

7. Microsoft Learn. **Microsoft Entra Product Family**.  
   https://learn.microsoft.com/en-us/entra/fundamentals/what-is-entra

8. Microsoft Learn. **About Azure Migrate**.  
   https://learn.microsoft.com/en-us/azure/migrate/migrate-services-overview

9. AWS Documentation. **What is Amazon EC2 Auto Scaling?**  
   https://docs.aws.amazon.com/autoscaling/ec2/userguide/what-is-amazon-ec2-auto-scaling.html

10. AWS Documentation. **What is Elastic Load Balancing?**  
    https://docs.aws.amazon.com/elasticloadbalancing/latest/userguide/what-is-load-balancing.html

11. AWS Documentation. **What is Amazon CloudFront?**  
    https://docs.aws.amazon.com/AmazonCloudFront/latest/DeveloperGuide/Introduction.html