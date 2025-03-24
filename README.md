# Tabular Model Meta Data Analyzer (TMMDA)

It is an **Engine Level Analyzer** Report module within FUAM and provides advanced analytical possibilities to a given semantic model.
![image](https://github.com/GT-Analytics/fuam-basic/blob/main/media/tmmda_assets/TMMDA_cover.png)

## Purpose & Focus

This module of FUAM has a goal to increase the transparency of semantic models in Microsoft Fabric. 
Great features like the new [INFO DAX functions](https://powerbi.microsoft.com/en-us/blog/dax-query-view-introduces-new-info-dax-functions/) or [enhanced semantic model metadata](https://learn.microsoft.com/en-us/power-bi/connect-data/desktop-enhanced-dataset-metadata) inspired us to create this report, which helps Fabric users to analyze meta data from a selected semantic model.

TMMDA focuses on Power BI semantic models with 'Import', 'Mixed' and 'Dual' storage modes in Microsoft Fabric.

## How does it work
Based on Tabular Model Object documentation ([Tabular Object Model (TOM) | Microsoft Learn](https://learn.microsoft.com/en-us/analysis-services/tom/introduction-to-the-tabular-object-model-tom-in-analysis-services-amo?view=asallproducts-allversions#tabular-object-model-hierarchy))

_"From a logical perspective, all tabular objects form a tree, the root of which is a Model..."_ - in other words, we could say that each object of a semantic model such as measure, table, column, etc. is defined in a structured way, which we can retrieve for different purposes. This brings us to the main idea of TMMDA.

## Analytical Pathways in FUAM

In FUAM Basic and Plus, Analytical Pathways are predefined diagnostic steps, which help Users in common troubleshooting scenarios, which saves time and increase transparency. 

### Analytical Pathways with TMMDA:

The **"Refresh to Details"** Analytical Pathway is scenario, where a semantic model cause a long refresh duration.
![image](https://github.com/GT-Analytics/fuam-basic/blob/main/media/analytical_pathway_assets/ap_sm_refresh_to_details.png)

- Step 1) Navigate to 'Refreshables' report page
- Step 2) Identify the semantic models with the longest refresh duration
- Step 3) Configure TMMDA for that semantic model
- Step 4) Explore TMMDA to understand, why the refresh takes unexpectedly long


-------------------------------------------
The **“Is my semantic model healthy after deployment?”** Analytical Pathway is a scenario, where a semantic model needs to be checked after deployment.
![image](https://github.com/GT-Analytics/fuam-basic/blob/main/media/analytical_pathway_assets/ap_sm_healthiness.png)

- Let's assume the semantic model has been recently deployed
- Step 1) Configure TMMDA for that semantic model
- Step 2) Navigate to the 'Home' page in TMMDA and evaluate the healthiness of the model
- Step 3) Once you are facing errors, navigate to the 'Error Analyzer' page for more details

## FUAM Reporting | Semantic Model Insights

![image](https://github.com/GT-Analytics/fuam-basic/blob/main/media/tmmda_assets/TMMDA_screenshot_1.png)
![image](https://github.com/GT-Analytics/fuam-basic/blob/main/media/tmmda_assets/TMMDA_screenshot_2.png)
![image](https://github.com/GT-Analytics/fuam-basic/blob/main/media/tmmda_assets/TMMDA_screenshot_3.png)
![image](https://github.com/GT-Analytics/fuam-basic/blob/main/media/tmmda_assets/TMMDA_screenshot_4.png)
![image](https://github.com/GT-Analytics/fuam-basic/blob/main/media/tmmda_assets/TMMDA_screenshot_5.png)
![image](https://github.com/GT-Analytics/fuam-basic/blob/main/media/tmmda_assets/TMMDA_screenshot_6.png)
![image](https://github.com/GT-Analytics/fuam-basic/blob/main/media/tmmda_assets/TMMDA_screenshot_7.png)
![image](https://github.com/GT-Analytics/fuam-basic/blob/main/media/tmmda_assets/TMMDA_screenshot_8.png)
![image](https://github.com/GT-Analytics/fuam-basic/blob/main/media/tmmda_assets/TMMDA_screenshot_9.png)
![image](https://github.com/GT-Analytics/fuam-basic/blob/main/media/tmmda_assets/TMMDA_screenshot_10.png)

## How to configure
![image](https://github.com/GT-Analytics/fuam-basic/blob/main/media/tmmda_assets/TMMDA_how_to_connect.png)

