---
title: Best practices to manage assets using AEM
description: Identify and adhere to the best practices that enhances system stability and performance under load, depending on AEM Assets deployment and features used to ingest and process assets.
contentOwner: AG
feature: Asset Management
role: Architect,Admin
exl-id: e2ab924b-53cb-4011-8c0a-9e8e59dd2f16
---
# Best practices for AEM Assets {#best-practices-for-assets}

Adobe Experience Manager (AEM) Assets is a crucial part of delivering high-quality digital marketing experiences that contribute to the achievement of business goals through increasing your content velocity. If you work with a large number of assets within AEM Assets or regularly/periodically upload numerous assets, including videos and dynamic media, optimizing your digital asset management experience is critical for system efficiency.

Depending upon how you have positioned AEM Assets for your organization and the features that you use around asset ingestion, rendition generation, and metadata extraction, identifying and adhering to best practices in different areas greatly enhances system stability and performance under load.

After reviewing the following guides, you will have the knowledge and tools to build and manage an enterprise asset management system that meets your needs.

* [Assets performance tuning guide](performance-tuning-guidelines.md)
Includes a set of best practices that can be followed at any point in your implementation, even after you go live, to ensure that you get the most out of your system.
* [Assets sizing guide](assets-sizing-guide.md)
When drawing up estimates for an Assets implementation, it is important to ensure that there are sufficient resources available in terms of asset storage, CPU, memory, IO and network throughput. Sizing many of these items require understanding how many assets are being loaded into the system. This guide includes best practices that help determine efficient metrics for estimating the infrastructure and resources required for deploying AEM Assets as well as a sizing tool.
* [Assets migration guide](assets-migration-guide.md)
If you want to migrate assets from your legacy system to AEM Assets, there are several steps to consider to streamline the migration process. The Migration guide include best practices around the tasks you perform to bring the assets into AEM in a phase-wise manner. This includes applying metadata, generating renditions, and activating the assets to publish deployment.
* [Assets network considerations](assets-network-considerations.md)
When handling AEM deployment, understanding the network topology is important to understand network performance, identify chokepoints, and describe the expected user experience. The Assets Network Considerations document discusses network considerations when designing your AEM Asset deployment.
* [Assets monitoring guide](assets-monitoring-best-practices.md)
After your AEM deployment is deployed, you should monitor certain tasks and the system in general to ensure system integrity and efficiency of operations. The Monitoring guide includes best practices for monitoring various aspects of your system.
* (Deprecated) [Assets offloading guide](assets-offloading-best-practices.md)
Handling large files and running workflows in AEM Assets can consume considerable CPU, memory, and I/O resources. Offloading these tasks can reduce CPU, memory, and IO overheads. The Assets offloading guide includes recommended use cases and best practices for Assets offloading.
* [AEM desktop app best practices](https://helpx.adobe.com/experience-manager/desktop-app/aem-desktop-app-best-practices.html)
AEM desktop app links your digital asset management (DAM) solution with your desktop so you can open the files that are available in the AEM web UI directly on desktop. AEM desktop app's easy-to-use workflow is enabled using network share technology that desktop operating systems provide. This guide explains key capabilities and recommended use of AEM desktop app.
* [AEM and Creative Cloud integration best practices](aem-cc-integration-best-practices.md)
You can integrate your AEM deployment with Creative Cloud in multiple ways. Following some best practices to streamline your integration and asset transfer workflows helps achieve maximum efficiency. This guide includes best practices around integrating AEM Assets with Adobe Creative Cloud.
* (Deprecated) [AEM to Creative Cloud folder sharing best practices](aem-cc-folder-sharing-best-practices.md)
You can configure AEM to allow users in DAM to share folders with Creative Cloud (CC) users, so they are available as shared folders in the Creative Cloud Assets service. The feature can be used to exchange files between creative teams and DAM users. This guide explains best practices for leveraging the AEM to Creative Cloud folder sharing feature.
