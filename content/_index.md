---
title: "Helmholtz Imaging Solutions"
date: 2024-10-14
draft: false
layout: workshop
author: Helmholtz Imaging
description: Summary of ways to contribute Helmholtz Imaging Solutions 
cover: img/betacell.jpg
---

## Helmholtz Imaging Solutions
{{< unlisted >}}
{{< horizontal >}}
{{< block >}}

{{< notes >}}
Solutions are puzzle pieces to successful scientific stories along the imaging pipeline. This includes resources developed and acquired by Helmholtz researchers, but also best practices for utilizing resources from scientific imaging communities worldwide.
{{< /notes >}}

- Developed by the **Helmholtz Imaging team** and the **community**
- Include **software**, **datasets**, **protocols**, and **whitepapers**
- Support imaging research **across all domains**

### Where to find solutions?

**[https://connect.helmholtz-imaging.de](https://connect.helmholtz-imaging.de)**

{{< /block >}}

{{< figure src="img/solutions.jpg">}}

{{< /horizontal >}}

---

## Helmholtz Imaging Solutions on CONNECT

TODO statistics, examples

---

## How to add Helmholtz Imaging Solutions

1. **Upload your solution resources** or collect existing resources
   - **Submit doftware tools**: Have you developed software tools that can be shared?
   - **Share datasets**: Can your datasets be made available to others?
   - **Publish protocols and white papers**: Have you published white papers or protocols or any other form of 
     workflow documentation?
2. Add all solution links to **CONNECT Database**

---


## Upload your resources
### Software

| **Repository Name & URL**                                         | **Advantages**                                         |
|-------------------------------------------------------------------|--------------------------------------------------------|
| [**GitHub**](https://github.com/)                                 | - Largest developer community.<br>- Easy collaboration.<br>- Integration with Zenodo for DOIs. |
| [**GitLab**](https://gitlab.com/)                                 | - Built-in CI/CD pipelines.<br>- Comprehensive project management.<br>- Supports self-hosting. |
| [**Zenodo**](https://zenodo.org/)                                 | - Free archival with DOI assignment.<br>- Integrates with GitHub.<br>- Open access to datasets and software. |
| [**SourceForge**](https://sourceforge.net/)                       | - Established platform for open-source.<br>- Project management tools.<br>- Wide visibility for research projects. |

---

## Upload your resources
### Datasets (across domains)

| **Repository**                                      | **Advantages**                                                                                          |
|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| [**Kaggle Datasets**](https://www.kaggle.com/datasets)         | - Diverse datasets across disciplines.<br>- Active community and competitions.<br>- User-friendly tools. |
| [**Open Science Framework (OSF)**](https://osf.io/)           | - Multidisciplinary support.<br>- Collaboration and project management.<br>- Promotes open access.      |
| [**Open Images Dataset**](https://storage.googleapis.com/openimages/web/index.html) | - Millions of annotated images.<br>- Rich annotations (bounding boxes, segmentation).<br>- Regular updates. |
| [**Figshare**](https://figshare.com/)                           | - Supports various data types.<br>- Easy sharing with privacy options.<br>- DOI for citation.           |
| [**Zenodo**](https://zenodo.org/)                               | - Free and open access.<br>- GitHub integration.<br>- Assigns DOIs for datasets.                       |

---

## Upload your resources
### Datasets (BioImaging)

| **Repository**                                      | **Advantages**                                                                                          |
|----------------------------------------------------------------|---------------------------------------------------------------------------------------------------------|
| [**The Cancer Imaging Archive (TCIA)**](https://www.cancerimagingarchive.net/) | - Extensive cancer-related images.<br>- High-quality annotations.<br>- Supports clinical research.       |
| [**BioImage Archive**](https://www.ebi.ac.uk/bioimage-archive/) | - Focused on biological images.<br>- Standardized data formats.<br>- Integrates with EBI resources.     |

---

## Upload your resources
### White Papers and Protocols

{{< notes >}}
Documenting methodologies and sharing best practices is vital for advancing imaging science.
{{< /notes >}}

- **White Papers**:
  - Contribute to scientific knowledge and best practices.
- **Protocols**:
  - Provide detailed methods for replication and validation.

### Where to publish

- **Open Access Journals**: Publish your white papers in journals supporting open science.
- **Preprint Servers**: Share preliminary findings on platforms like **arXiv** or **bioRxiv**.
- **Protocol Repositories**: Use platforms like **protocols.io** for sharing detailed protocols.
  
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
