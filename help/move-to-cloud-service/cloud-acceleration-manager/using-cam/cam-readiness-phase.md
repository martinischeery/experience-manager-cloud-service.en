---
title: Readiness Phase in Cloud Acceleration Manager
description: This page provides an overview on the Readiness phase in Cloud Acceleration Manager.
---

# Readiness Phase in Cloud Acceleration Manager {#readiness-phase-cam}

Once you have created a project in Cloud Acceleration Manager, you can now start the assessment of your current AEM implementation in the Readiness phase.

The Readiness Phase includes:

* [Best Practices Analysis](#best-practices-analysis)
* [Planning and Setup](#planning-setup) 

Follow the steps below to navigate to the Readiness Phase:

1. Click on your project card to open the project landing page.

   ![image](/help/move-to-cloud-service/cloud-acceleration-manager/assets/cam-landing1.png)

1. Navigate to the **Readiness** section, as shown in the figure below.

   ![image](/help/move-to-cloud-service/cloud-acceleration-manager/assets/readiness-1.png)

   >[!NOTE]
   >Refer to Creating and Managing a Project in Cloud Acceleration Manager to learn more.

## Using Best Practices Analysis Card {#best-practices-analysis}

Follow the steps below to use Best Practices Analysis card:

1. Click on the **Review** button from the **Best Practices Analysis** card. 

   ![image](/help/move-to-cloud-service/cloud-acceleration-manager/assets/readiness-2.png)

1. Follow these steps to download Best Practices Analyzer (BPA).

      >[!NOTE]
      >In order to avoid an impact on business critical instances, it is recommended that you run BPA on an Author environment that is as close as possible to the Production environment in the areas of customizations, configurations, content and user applications. Alternatively, it can be run on a clone of the production Author environment.

   1. Navigate to [Software Distribution](https://experience.adobe.com/#/downloads/content/software-distribution/en/aemcloud.html) portal and download the Best Practices Analyzer as a zip file.

      >[!NOTE]
      >Review [Using Best Practices Analyzer](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/cloud-migration/best-practices-analyzer/using-best-practices-analyzer.html?lang=en#imp-considerations) to learn how to run BPA.

   1. Export the report in a CSV format 

1. Click on **Upload new report** to upload BPA report in CAM.

   ![image](/help/move-to-cloud-service/cloud-acceleration-manager/assets/readiness-3.png)

1. Once you have uploaded a new report, you will see the Best Practices Analysis report.

   ![image](/help/move-to-cloud-service/cloud-acceleration-manager/assets/cam-bpareport.png)

1. Review and explore the Best Practices Analysis dashboard in CAM. Refer to the section below [Reviewing Best Practices Analysis Report](#analysis-report) for more details.

   >[!NOTE]
   >Uploading a new report resets all the assessments.

### Reviewing Best Practices Analysis Report {#analysis-report}

Explore the following cards available in Best Practices Analysis Report page:

![image](/help/move-to-cloud-service/cloud-acceleration-manager/assets/cam-bpareport.png)

>[!NOTE]
> With each card, you have the capability to:
>* click on each card to open its associated tab
>* bookmark all report tabs (including filtering) for sharing or future retrieval
>* use the details icon to view the details of each report finding

#### Report Properties {#report-properties}

The **Report Properties** card provides information about report properties such as report date, duration, filters, upload date, and Adobe Experience Manager (AEM) details.

![image](/help/move-to-cloud-service/cloud-acceleration-manager/assets/report-properties.png)

#### Report Overview {#report-overview}

This **Report Overview** card provides the report findings and severity levels that apply when assessing the readiness to move to AEM as a Cloud Service, as shown in the figure below.

![image](/help/move-to-cloud-service/cloud-acceleration-manager/assets/report-overview.png)

Clicking on this report opens the **Report** tab.

![image](/help/move-to-cloud-service/cloud-acceleration-manager/assets/report-overview2.png)

You can filter the report based on importance, sub-type, or count.

![image](/help/move-to-cloud-service/cloud-acceleration-manager/assets/report-overview3.png)

>[!NOTE]
>Refer to [Interpreting the Best Practices Analyzer Report](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/cloud-migration/best-practices-analyzer/using-best-practices-analyzer.html?lang=en) to learn about findings categories and importance levels.

#### Best Practices Assessment {#best-practices-assessment}

The Best Practices Assessment option provides an assessment of your current AEM instance and provides guidance on next steps to adopt AEM best practices. You can review the following information from this tab:

* AEM Instance Overview
* Custom Components and Templates
* Additional Findings
* Slow Queries
* Maintenance Tasks

#### Migration Complexity Assessment {#migration-complexity-assessment}

The Migration Complexity Assessment option provides an assessment of the complexity to migrate the existing AEM implementation to AEM as a Cloud Service. 

You can review the following information from this tab:

* AEM Instance Overview
* Assessment
* Content Migration Considerations

   ![image](/help/move-to-cloud-service/cloud-acceleration-manager/assets/migration-complexity-1.png)

## Using Planning and Setup Card {#planning-setup}

Follow this section to explore the Planning and Setup activity card.

1. Click on the **View** button from the **Planning And Setup** card. This card provides all the relevant content that will help you plan and setup your AEM migration.

   ![image](/help/move-to-cloud-service/cloud-acceleration-manager/assets/readiness-view.png)

1. A content carousel displays all the relevant information for this phase of the migration journey.

   ![image](/help/move-to-cloud-service/cloud-acceleration-manager/assets/readiness-5-planning.png)

## What's Next {#whats-next}

Once you have learnt how to log into Cloud Acceleration Manager and how to create a project, you are now ready to move on to reviewing the next step in the [Implementation Phase](https://experienceleague.adobe.com/docs/experience-manager-cloud-service/moving/cloud-acceleration-manager/using-cam/cam-implementation-phase.html?lang=en).
