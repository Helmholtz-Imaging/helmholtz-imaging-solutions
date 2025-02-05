---
title: "Helmholtz Imaging Solutions"
date: 2024-10-14
draft: false
layout: workshop
author: Helmholtz Imaging
description: An introduction to Helmholtz Imaging Solutions and how to contribute. 
cover: img/betacell.jpg
---

## Helmholtz Imaging Solutions

{{< notes >}}
Solutions are puzzle pieces to successful scientific stories along the imaging pipeline. This includes resources developed and acquired by Helmholtz researchers, but also best practices for utilizing resources from scientific imaging communities worldwide.
{{< /notes >}}

- Developed by the **Helmholtz Imaging team** and the **community**
- Include **software**, **datasets**, **protocols**, and **whitepapers**
- Support imaging research **across all domains**

### Where to find solutions?

**[https://connect.helmholtz-imaging.de/solution](https://connect.helmholtz-imaging.de)**

---

## Helmholtz Imaging Solutions on CONNECT

{{<connect-solution-highlights>}}

---

## How to add a Helmholtz Imaging Solution

1. **Upload your solution resources** or collect existing resources.
   - **Submit software tools**: Have you developed software tools that can be shared?
   - **Share datasets**: Can your datasets be made available to others?
   - **Publish protocols and white papers**: Have you published white papers or protocols or any other form of 
     workflow documentation?
2. Add all solution links to the **CONNECT Database**.

---


## Where to upload your resources
### Software

{{<repository-table category="software">}}

---

## Where to upload your resources
### Image Datasets Across Domains
{{<repository-table category="image_datasets_across_domains" >}}

---

## Where to upload your resources
### Image Datasets in Health

{{<repository-table category="image_datasets_health">}}

---

## Where to upload your resources
### Image Datasets in Earth & Environment

{{<repository-table category="image_datasets_earth_environment">}}

---

## Where to upload your resources
### Image Datasets in Energy

{{<repository-table category="image_datasets_energy">}}

---

## Where to upload your resources
### Image Datasets in Aeronautics, Space, and Transport

{{<repository-table category="image_datasets_aeronautics_space_transport">}}

---

## Where to upload your resources
### Image Datasets in Matter

{{<repository-table category="image_datasets_matter">}}

---

## Where to upload your resources
### White Papers and Protocols

{{< notes >}}
Documenting methodologies and sharing best practices is vital for advancing imaging science. 
**White Papers** contribute to scientific knowledge and best practices. **Protocols** provide detailed methods for 
replication and validation.
{{< /notes >}}

{{<repository-table category="white_papers_protocols">}}

---

## Related services of the Helmholtz Information and Data Science Platforms 

Researchers working at Helmholtz can contact our sister platforms regarding the following topics: 

- [Contact HIFIS](https://hifis.net/contact.html) for software development questions, for 
  example regarding FAIR principles, code refactoring, or  cloud computing.
- [Contact HMC](https://helmholtz-metadaten.de/en/hmc-helpdesk) for metadata related questions.
- [Consult Helmholtz AI](https://www.helmholtz.ai/you-helmholtz-ai/ai-consulting/) for AI related method development.
- [Check out the HIDA Course Catalog](https://www.helmholtz-hida.de/course-catalog/en/) for data science related 
  trainings.

---

## Adding Solution to CONNECT

### 1. Visit **[connect.helmholtz-imaging.de](https://connect.helmholtz-imaging.de)** and click on *Login*.

{{<figure src="img/connect/connect-login.png" width="800" class="center">}}

---

## Adding Solution to CONNECT

### 2. Login using your Helmholtz ID.

{{<figure src="img/connect/connect-helmholtzid.png" width="800" class="center">}}

---

## Adding Solution to CONNECT

### 3. Click on *Add Data*.

{{<figure src="img/connect/connect-adddata.png" width="800" class="center">}}

---

## Adding Solution to CONNECT

### 4. Under *Solutions*, click on *Add Solution*.

{{<figure src="img/connect/connect-addsolution.png" width="800" class="center">}}

---

### Flowchart

{{ <hidden> }}

```mermaid
graph LR
    B{Which resources like software, datasets, protocols, and white papers did you use or develop during the project?}
    
    B --> D[Software]
    B --> E[Dataset]
    B --> F[White Papers & Protocols]
    
    D -- Newly developed --> G[Publish Software - on GitHub, GitLab, PyPi, conda-forge, ..]
    D -- Existing --> J{Resource for describing the software use case?}
    J -- No, but I want to --> H[Describe specific use case - with Album, Protocol, Blog Post, ..]
    J -- Yes --> Q
    J -- No, and I don't want to --> Q
    G --> H
    H --> Q
    E -- Newly acquired --> I[Upload Data - on Zenodo, DESY dCache, Omero, BioImage Archive, ..]
    F -- Newly developed --> N[Publish protocol / whitepaper - Protocol Journals, Preprint Servers, github / gitlab, ..]

    G --> Q[Add to CONNECT Database]
    N --> Q
    
    I --> Q
    E -- Existing Resource --> Q
    F -- Existing Resource --> Q
    
```

---

## Questions?

{{< notes >}}
Feel free to reach out if you have any questions or need assistance with contributing to Helmholtz Imaging Solutions.
{{< /notes >}}

- **Contact Us**: [support@helmholtz-imaging.de](mailto:support@helmholtz-imaging.de)
- **Visit**: [helmholtz-imaging.de](https://helmholtz-imaging.de)
