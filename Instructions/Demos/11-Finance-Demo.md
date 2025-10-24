# Finance Demo

### Estimated Duration: Minutes

## Overview 

In this lab, you’ll use Microsoft Copilot across Excel, Copilot Chat, and Word to analyze financial data for EV chargers. You’ll learn how to generate insights, perform data analysis, compare performance against industry benchmarks, and create professional summaries. The lab demonstrates how natural language prompts can streamline data analysis, reporting, and communication, helping financial analysts make informed decisions efficiently.

## Objectives

- Task 1: Copilot in Excel  
- Task 2: Copilot Chat
- Task 3: Copilot in Word

## Task 1: Copilot in Excel  

In this task, you’ll use Copilot in Excel to analyze EV charger sales data. You’ll identify revenue trends, calculate totals and averages, and highlight best-selling products. The goal is to practice using natural language prompts to generate insights and summaries directly within Excel.

1. Download the following file by clicking on the **Download** button:

    - [EV_Charger_Sales_Analysis_v1.xlsx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/EV_Charger_Sales_Analysis_v1.xlsx)

        ![](./Images/m4p2t1p1.png)
        
1. Open a new tab and navigate to [M365copilot.com](https://m365copilot.com/).

    ![](./Images/m3p2t1p1.png)
    
1. Click on the **Apps (1)** from the left navigative pane and then select **Excel (2)** under Apps section.

    ![](./Images/p5t3p1.png) 

1. Click on the **Upload a file** button, and from the Open dialog, select the file `EV_Charger_Sales_Analysis_v1.xlsx` **(1)** and click on **Open (2)**.

    ![](./Images/m4p2t1p2.png)

    ![](./Images/m4p2t1p2(1).png)

1. Navigate to the **"Sales by Product"** tab.
    
    ![](./Images/m4p2t1p3.png)

1. From the **Home (1)** tab, select **Copilot (2)** from the excel ribbon, then select **App skills (3)** to open the Copilot pane.

    ![](./Images/m4p2t1p4.png)

1. Use Copilot to sort the table by entering the following prompt:  

    ```text
    Sort the table by date in descending order, from the most recent to the oldest entry.
    ```  

    ![](./Images/m4p2t1p5.png)

    - Copilot sorts the table and updates the dataset.  
    - Select **"Apply"** after sorting.

        ![](./Images/m4p2t1p5(1).png)

        >**Note:** If Copilot doesn't return the expected result, please refresh the tab and try again.

1. To Insert a ‘Total Revenue’ Column, use the following prompt in the Copilot pane:  

    ```text
    Add a new column named 'Total Revenue'. Populate it by multiplying 'Units Sold' by 'Product Price' for each row.
    ```  

    - Copilot creates the new column and applies the formula.  
    - Select **Insert Column**.

        ![](./Images/m4p2t1p6.png)  

1. Generate a Sales Summary Table for 2024. Enter the following prompt in the Copilot pane:  

    ```text
    Create a summary table for total sales in 2024. The table should include Product ID, total units sold, and total revenue.
    ``` 

     

    - Copilot generates a summary table.  
    - Select **Insert a new sheet** to store the table separately.

        ![](./Images/m4p2t1p7.png)  

    - Ensure the table includes **only 2024 data**.

        ![](./Images/m4p2t1p7(1).png)

    - Navigate back to the **"Sales by Product"** tab.

        >**Note:** If Copilot doesn't return the expected result, please refresh the tab and try again.

1. Identify the Best-Selling Product. Enter the following prompt in the Copilot pane:  

    ```text
    Identify the product ID with the highest total revenue in 2024. Provide both total revenue and total units sold for better comparison.
    ```

    ![](./Images/m4p2t1p8.png)   
  
    Copilot analyzes the dataset and provides the top-selling product.

1. Sort Customers by Revenue:

    - Navigate to the **Customers** sheet in Excel. Enter the following prompt in the Copilot pane:  

        ```text
        Sort the 'Customers' tab by annual revenue in descending order.
        ```  

    - Copilot sorts the customers by **annual revenue**.  
    - Select **"Apply"** after sorting.

        ![](./Images/m4p2t1p9.png)   
  
1. Calculate Average Revenue Per Customer. Enter the following prompt:  

    ```text
    Calculate the average revenue per customer.
    ```  

    - Copilot calculates the average and adds the result.  
    - Select **Insert cell** to store the average revenue value.

        ![](./Images/m4p2t1p10(1).png)   
  
1. Find the Industry Using the Most Power. Enter the following prompt in the Copilot pane:  

    ```text
    Analyze the data to determine which industry has the highest total power consumption. Provide the industry name and total power usage.
    ```  

    - Copilot processes the data and returns the industry with the highest power consumption.

        ![](./Images/m4p2t1p11.png) 

1. Click on the **Share (1)** drop-down and select **Copy link (2)**.

    ![](./Images/m4p2t1p12.png)

1. On the **Link created** pop-up, click on **Copy** to copy the URL.

    ![](./Images/m4p2t1p12(1).png)

## Task 2: Copilot Chat

In this task, you’ll use Copilot Chat to compare your company’s financial performance with industry benchmarks and competitors. You’ll analyze revenue patterns, discuss key findings, and export your results to a Word document for reporting.

1. Open a browser and navigate to [M365copilot.com](https://m365copilot.com/).

1. Ensure **Web** Mode is selected.

    ![](./Images/p6t2p2.png)

1. In the prompt window, type the following:

    ```text
    Our total revenue for [EV chargers] exceeded $50,000,000 for firth half of 2024. Compare this to the industry average and provide insights on whether we are above or below industry standards. If possible, include market share estimates and trends
    ```

1. Now ask Copilot Chat to compare this to competitors:

    ```text
    Summarize the key financial statements of two major competitors in the [EV charging] industry. Include revenue, net profit, and any other relevant financial insights. If available, provide comparisons to our financial performance.
    ```

1. Lastly, ask copilot to export the chat history to date to a Word document:

    ```text
    Export this conversation, including financial insights, to a Word document for further review.
    ```

1. Select the linked file to download and then open the document.

    ![](./Images/m4p2t2p5.png)

1. From the left navigation pane, select **Apps (1)** and then click on **Word (2)**.

    ![](./Images/m4p2t2p6.png)

1. On the Word homepage, click on **Upload a file (1)**, and from the Open dialogue, select the **`EV_Charger_Sales_Analysis_v1.xlsx` (2)** and click on **Open (3)**.

    ![](./Images/m4p2t2p7.png)

    ![](./Images/m4p2t2p8.png)

1. Change the name of the file by clicking **drop-down (1)** from the top and provide the name as **`Charging_industry_Financial_Summary` (2)**.

    ![](./Images/m4p2t2p9.png)

1. Click on the **Share (1)** drop-down and select **Copy link (2)** to copy the URL.

    ![](./Images/m4p2t2p10.png)

## Task 3: Copilot in Word

In this task, you’ll use Copilot in Word to summarize your financial analysis into a professional email. You’ll refine tone, clarity, and structure with Copilot’s suggestions to create a polished summary ready to share with your team.

1. Open a new **Word** homepage and select **+ Create blank document**.

    ![](./Images/m4p2t3p1.png)

1. In the **What you want Copilot to draft?** prompt box, type the following:

    ```text
    Draft an email to my team summarizing the key insights from [Charging_industry_Financial_Summary.docx].
    ```

    ![](./Images/m4p2t3p2.png)

    > **NOTE:** Attach the Charging_industry_Financial_Summary.docx file created in the previous task or paste the shared link directly into the prompt to ensure Copilot has access to the relevant content.

1. Review Copilot’s output. Before selecting **Keep it**, refine the response by asking Copilot:

    ```text
    Shorten this email draft
    ```

    ![](./Images/m4p2t3p3.png)

1. Other optional Refinements:

    - ask Copilot to reword sections for a more professional tone.
    - Expand with additional sections.
    - Make it less formal

1. Once finished, you can select **Keep it**.

    ![](./Images/m4p2t3p4.png)

## Summary

In this lab, you analyzed EV charger sales data using Copilot in Excel, identifying trends, calculating totals and averages, and finding top-performing products and customers. You then used Copilot Chat to benchmark your company’s financial performance against competitors and export insights to a Word document. Finally, you leveraged Copilot in Word to summarize these insights into a professional email for your team. The lab highlights how Copilot can accelerate financial analysis, reporting, and decision-making by combining data processing with clear communication.

### You have successfully completed the exercise. Click on Next >> to proceed with the next exercise.

![](./Images/nextpagem1.png)