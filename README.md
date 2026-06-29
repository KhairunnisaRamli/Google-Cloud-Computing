# Google-Cloud-Computing
# Getting Started with Google Cloud Platform (GCP)

An introductory guide to Google Cloud Platform core services, architectural patterns, and practical engineering implementations based on hands-on laboratory exercises.

---

## Introduction

**Google Cloud Platform (GCP)** is a comprehensive suite of cloud computing services offered by Google that runs on the same infrastructure that Google uses internally for its end-user products. It provides highly scalable, secure, and fully managed infrastructure for hosting applications, processing big data, and leveraging advanced machine learning capabilities at a global network edge.

By utilizing software-defined perimeters, serverless runtimes, and automated scaling architectures, GCP enables engineers to shift from heavy capital hardware management to agile, code-driven resource orchestration.

---

## Technical Overview

This documentation compiles the core architectural themes explored across multiple structural learning tracks:

* **Zero-Trust Networking & Access Control:** Securing cloud resources at the network edge using Virtual Private Cloud (VPC) perimeters, Identity-Aware Proxy (IAP), granular Cloud Firewall rules, and custom metadata tagging.
* **Identity & Governance Operations:** Applying the principle of least privilege across cloud infrastructures by enforcing strict Identity and Access Management (IAM) role boundaries, utilizing dedicated service accounts, and managing cryptographic JSON signature credentials.
* **Serverless Platform Provisioning:** Packaging and deploying scalable stateless workloads using serverless container applications via Cloud Run and Compute Engine Managed Instance Groups (MIGs).
* **Distributed Big Data Pipelines:** Orchestrating serverless, cloud-scale batch and streaming pipelines using Cloud Dataproc (Managed Apache Spark/Hadoop) and Cloud Dataflow (Apache Beam SDK).
* **Pre-trained Machine Learning APIs:** Integrating advanced artificial intelligence capabilities into enterprise applications via lightweight REST API handshakes for natural language processing, automated speech recognition, and video computer vision analysis.

---

## Key Learning Outcomes & Lab Summary

### 1. Cloud Security & Software-Defined Networking

* **Perimeter Hardening:** Configured custom mode VPC topologies to ensure complete isolation between private internal routing rings, enforcing ingress firewall paths scoped to specific network metadata tags.
* **Identity-Driven Access:** Shifted user authentication mechanisms from application code up to the managed cloud edge using IAP. Prevented perimeter bypass and header-spoofing risks through cryptographic JSON Web Token (JWT) verification via Google’s public signing keys.
* **Least Privilege Governance:** Evaluated administrative boundaries separating roles like `Compute Network Admin` and `Compute Security Admin`. Verified that IAM policies propagate instantly across live cloud infrastructure to deny or grant structural access.

### 2. High Availability & Cloud Monitoring

* **Traffic Optimization:** Engineered cross-regional failover architectures using auto-scaling Managed Instance Groups (MIGs) bound to a Global External Application Load Balancer supporting dual-stack (IPv4/IPv6) frontends.
* **Edge-Level Defense:** Implemented Layer 7 Web Application Firewall (WAF) rule sets via Google Cloud Armor to intercept malicious traffic distributions and audited security telemetry logs using Cloud Logging.
* **Full-Stack Observability:** Deployed the unified Google Cloud Ops Agent daemon to capture fine-grained log streams and timeseries system metrics, establishing automated HTTP synthetic uptime alerting policies.

### 3. Big Data Engineering & Serverless Analytics

* **Managed Hadoop/Spark Clusters:** Provisioned distributed data nodes with Cloud Dataproc, utilizing horizontal programmatic scaling via the `gcloud` CLI to adjust active worker capacities on demand without infrastructure downtime.
* **Serverless Stream Processing:** Built time-partitioned BigQuery data warehouse tables fed by real-time Cloud Dataflow streaming templates to process high-volume, JSON event streams from public Cloud Pub/Sub topics.
* **Containerized Data Pipelines:** Orchestrated isolated Python development containers via Docker to run Apache Beam data workloads locally using the `DirectRunner`, before executing production-scale distributed tasks in the cloud via the `DataflowRunner`.
* **No-Code Data Wrangling:** Leveraged Alteryx Designer Cloud/Cloud Dataprep to visually clean, type-cast, filter, and join unstructured campaign finance datasets into optimized analytical summaries.

### 4. Applied Machine Learning via REST Gateways

* **Natural Language Processing (NLP):** Utilized the Cloud Natural Language API to run structural syntax models against unstructured text, capturing entity types, Knowledge Graph metadata links, and text salience scores.
* **Automated Speech Recognition:** Processed voice files hosted in Cloud Storage using the Cloud Speech-to-Text API, defining explicit audio codecs (FLAC) and linguistic models to extract transcripts alongside predictive model confidence ratings.
* **Asynchronous Video Analytics:** Dispatched video annotation requests to the Cloud Video Intelligence API to identify visual features, mapping visual assets to standardized entity IDs and tracking their exact timeline offsets.
