![](/images/ahlsbanner.png)

# A-HLS [Accelerator] Documentation 

## Overview

*A guided decision flow for providers to quickly ingest an appeal request and raise a dispute for care.*

------

## Business Objective

The Medicare Appeal Intake Workflow is a guided workflow for providers to quickly view their claim payment details from a health plan and raise a dispute for a claim payment transaction if needed. The focus is to **lay the foundation** and pathway for a structured and CMS-compliant Medicare Appeal Intake process.

This process typically happens when a patient reaches out to a provider to file an appeal due to any of the reasons allotted in the CMS definition and (or) filling a claim. The flow can be called from a Digital Process Automation (DPA) Action from a Salesforce Lightning Page or an Experience Cloud Community. 

This specific workflow is intended to assist the intake of Appeal [Medicare Parts C & D](https://www.cms.gov/qic-decision-search).

What's included:

- Collect Patient Information;
- Collect Submitter information;
- Collect/Confirm Plan information for coverage verification;
- Collect appeal information/rationale;
- Appeal record creation on a custom SObject.

#### Use Case Scenario

As a provider, I need to be able to intake medicare appeal requests for proper processing.

## Business Objective

Ingest a Medicare Appeal for investigation.

## Business Value and Benefits

- Lays a foundation for a structured and CMS-compliant medicare appeals intake process.
- Easily drives the intake process with a visually guided flow.
- Reduces the implementation time and effort for a CMS-compliant Medicare Appeal intake process.
- Lays a structured path for further customer-tailored process development.
- Easily utilization from a Salesforce Lightning Page or an Experience Cloud Community. 

------

## Industry Focus and Workflow

### Primary Industry:

- Healthcare.

### Primary User Persona:

- Member Services Representative (Call Center)

------

## Package Includes:

### **OmniScript (1)**

- Appeals Intake

### **DataRaptop (11)**

- ProviderTypeAhead
- FacilityTypeAhead
- Ins_ReadProducer
- createCareRequest
- PersonPatientTypeAhead
- AHLSCreateAppealCase
- DRCaseRecordTypeLookupAppeal
- ins_ExtRecordType
- getPersonAccountDetails
- getBusinessAccount
- getProviderDetail

### **Integration Procedure (1)**

- Get Context Details Appeals

------

## Configuration Requirements

### Pre-Install Configuration Steps:

1. Follow the download steps presented on the Accelerate HLS website for this Accelerator. 
2. 1. Alternatively, you may download the Data Pack folder in the following GitHub repository: https://github.com/healthcare-and-life-sciences/Medicare-Appeal-Intake-Workflow

3. Then, complete the following steps to import them into your Salesforce org.

4. 1. To Import, in your destination Salesforce org, Click on **App Launcher** → Search for '**OmniStudio DataPacks**' and click on it.
   2. Click on '**Installed**' and on the right side click on '**Import from**'.
   3. Select '**From File**' - When the window opens, select the Data Pack file that you downloaded and stored on your machine. Click '**Install**'.
   4. When prompted to Activate the OmniScript, choose **Not Now**.

#### Install the Data Pack

1. Follow the download steps presented on the Accelerate HLS website for this Accelerator. 

2. 1. Alternatively, you may download the Data Pack folder in the following GitHub repository: **[INSERT REPO LINK]**

3. Then, complete the following steps to import them into your Salesforce org.

4. 1. To Import, in your destination Salesforce org, Click on **App Launcher** → Search for '**OmniStudio DataPacks**' and click on it.
   2. Click on '**Installed**' and on the right side click on '**Import from**'.
   3. Select '**From File**' - When the window opens, select the Data Pack file that you downloaded and stored on your machine. Click '**Install**'.
   4. When prompted to Activate the OmniScript, choose **Not Now**.

### Post-Install Configuration Steps:

1. Click on **App Launcher** → Search for “OmniScripts”

2. 1. Navigate to the recently installed OmniScript in the list view
   2. Click on the dropdown at the right of the OmniScript and select **Activate**.
   3. For more information regarding activating Omniscripts, please see this article: https://help.salesforce.com/s/articleView?id=sf.os_activating_omniscripts.htm&type=5

3. Add the installed OmniScript to the lightning page layout of your choosing. 

4. 1. Refer to this article for more information regarding adding OmniScripts to a Lightning Page: https://help.salesforce.com/s/articleView?id=sf.os_add_a_standard_omniscript_component_to_a_lighting_page_20263.htm&type=5
   2. Refer to this article for more information regarding adding OmniScripts to an Experience Cloud Page: https://help.salesforce.com/s/articleView?id=sf.os_add_a_standard_omniscript_component_to_an_experience_page_20341.htm&type=5

5. Make sure all the **DataRaptors and Integration Procedure** are pointing to ***valid data sources***.

------

## Assumptions

1. A customer has licenses for Health Cloud, and the HINS Managed Package with OmniStudio. These solutions have all been installed and are functional.
2. A customer is assuming Salesforce Lightning Experience — not Classic.
3. Data Model elements that are part of the HINS (Vlocity) Managed package and Health Cloud are all available.
4. The Accelerator uses the Lightning Design System standards and look. Customers may want to apply their own branding which can be achieved.

------

## Revision History

- **Revision Short Description (Month Day, Year)**
  - December 16, 2022

  - January 23, 2023


