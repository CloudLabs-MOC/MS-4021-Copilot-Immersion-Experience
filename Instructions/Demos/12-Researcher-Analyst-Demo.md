# Lab 02: Researcher and Analyst Demo

### Estimated Duration: 40 Minutes

## Overview

In this lab, you’ll explore how to use **Researcher** and **Analyst**, two expert agents built into the Microsoft Copilot app. You’ll learn how **Researcher** combines internal and web-based knowledge to build structured, well-supported marketing plans, and how **Analyst** applies data science techniques to uncover insights, perform modeling, and create visualizations. By the end, you’ll understand how both agents work together to accelerate decision-making, strategy development, and data analysis.

## Objectives

- Task 1: Using Researcher build a Marketing Plan
- Task 2: Using Analyst for Customer Segmentation & Financial Modeling

## Task 1: Using Researcher to build a Marketing Plan

In this task, you’ll use the **Researcher** agent to create a comprehensive marketing plan for the SprintCycle EV charger launch. You’ll upload internal files, integrate competitor and campaign insights, and let Researcher generate a structured, well-cited plan that includes digital channel and content strategy recommendations.

1. Download the following files by clicking on the **Download file** button:

    - [BoulderEV_Internal_Market_Forecast.xlsx](https://github.com/CloudLabs-MOC/MS-4021-Copilot-Immersion-Experience/raw/refs/heads/prod/ResourceFiles/BoulderEV_Internal_Market_Forecast.xlsx)

    - [SprintCycle_Charger_Product_Launch.docx](https://github.com/CloudLabs-MOC/MS-4021-Copilot-Immersion-Experience/raw/refs/heads/prod/ResourceFiles/SprintCycle_Charger_Product_Launch.docx)

    - [Contoso-PedalPerks GTM Plan.docx](https://github.com/CloudLabs-MOC/MS-4021-Copilot-Immersion-Experience/raw/refs/heads/prod/ResourceFiles/Contoso-PedalPerks%20GTM%20Plan.docx)

1. Open a new tab and navigate to [M365copilot.com](https://m365copilot.com/).

    ![](./Images/m3p2t1p1.png)

1. From the left navigation menu, click on **Apps (1)** and then select **OneDrive (2)**.

    ![](./Images/m4p3t1p1(1).png)

1. Click on **+ Create or upload (1)** and then select **Files upload (2)**. On the Open dialogue, select the following files:

    - `BoulderEV_Internal_Market_Forecast.xlsx`, `SprintCycle_Charger_Product_Launch.docx` and `Contoso-PedalPerks GTM Plan.docx` **(3)**
    - Click **Open (4)**.

        ![](./Images/m4p3t1p1(2).png)

        ![](./Images/m4p3t1p1(3).png)

1. From the left navigation menu, go to **Agents (1)** and then select **Researcher (2)**. 

    ![](./Images/m4p3t1p1.png)

1. Enter the following prompt **(1)**:

    ```text
    Create a marketing plan for our newest SprintCycle EV charger launch. 
    Emphasize its AI-powered adaptive charging, modular design, and biometric access control. 
    Make sure to include recommendations on the right digital channels and content strategy. 
    Include insights from competitors and our past GTM campaigns.
    ```
1. Click on **+ (2)** icon to add content and select **Attach cloud files (3)**. Click on **My files (4)** from the left menu, and select the following files:

    - `SprintCycle_Charger_Product_Launch.docx` and `Contoso-PedalPerks GTM Plan.docx` (Optional) **(5)**.
    - Click **Select (6)**.

        ![](./Images/m4p3t1p3.png)

        ![](./Images/m4p3t1p3(1).png)

        ![](./Images/m4p3t1p3(2).png)


1. When prompted by the Researcher to proceed, type `go ahead` and press **Enter**.

    ![](./Images/m4p3t1p3(3).png)

    >**Note:** It will take few minutes to generate proper responce.

1. Researcher will:  

    - Combine insights from both internal files and the web.  
    - Structure a marketing plan with recommendations on channels and content strategy.  
    - Cite sources so you can validate its work.  

        > **Note:** Researcher shows its reasoning path (“chain of thought”), and can call other agents when needed.  

## Task 2: Using Analyst for Customer Segmentation & Financial Modeling

In this task, you’ll use the **Analyst** agent to analyze market data, identify high-value customer segments, and visualize how targeting them can maximize market opportunities. You’ll also explore additional prompts to perform financial projections, sales performance reviews, and campaign analysis using uploaded datasets.

1. Open **Analyst** from the navigation pane under **Agents** section.

    ![](./Images/m4p3t2p1(3).png)
  

1. Enter the following prompt **(1)**:

    ```text
    Find the right customer segment and demographic to sell our new EV charger, 
    include a graph to show how this will maximize our market opportunity.
    ```

1. Click on **+ (2)** icon to attach content, then seelct **Attach cloud files (3)**. Then go to the My files (4) from the left menu and select the file `BoulderEV ebike Internal Market Forecast.xlsx` **(5)** and click on **Select (6)**. 

    ![](./Images/m4p3t2p1.png)

    ![](./Images/m4p3t2p1(1).png)

1. Once the prompt is submitted, the analyst will return a response similar to the one shown in the image below.

    ![](./Images/m4p3t2p2.png)

1. Analyst will:  

    - Analyze the dataset.  
    - Identify high-value customer segments.  
    - Provide visualizations to back up recommendations.  

### Additional Analyst Scenarios

You can run these additional prompts for variety. Each follows the same pattern: **Prompt → Attach file → Submit → Review results.**

- **Financial Projection**  

    ```text
    Build a 5-year financial projection from this data along with a graph to view revenue growth over time.
    ```  

    File: **`BoulderEV ebike Internal Market Forecast.xlsx`**  

    ![](./Images/m4p3t3p1.png)

- **Sales Performance**  

    ```text
    Analyze sales volume across locations to identify our highest and lowest performing stores, 
    along with a visualization of the best-selling products.
    ```  

    File: **`BoulderEV ebike Internal Market Forecast.xlsx`**  

- **Campaign Performance**  

    ```text
    Analyze and visualize how the marketing campaign performed across each target segment 
    and help me decide where to re-target our next campaign.
    ```  

    File: **`BoulderEV ebike Internal Market Forecast.xlsx`**  

## Summary
In this lab, you used **Researcher** to create a detailed marketing plan for the SprintCycle EV charger by combining company documents and online insights. You then used **Analyst** to perform customer segmentation, financial modeling, and data visualization to identify key market opportunities. Together, these exercises demonstrated how Copilot’s built-in agents help you move from research to actionable insights quickly and confidently.

### Congratulations! You've successfully completed the Hands-on lab.
