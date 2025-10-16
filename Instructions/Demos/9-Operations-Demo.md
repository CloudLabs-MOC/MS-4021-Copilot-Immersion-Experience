---
demo:
    title: 'Operations Demo'
---

[Back to Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# Operations Demo

## Scenario

You’re an Operations Manager at Contoso, responsible for vendor procurement and project execution. Your goal is to review past RFPs, extract key selection criteria, and draft a new RFP for an upcoming initiative.

## Demo Setup

The sample documents can be found in the MS-4021 GitHub repository [here](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles):

The specific files needed for this demo are:

- [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

- [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

- [Contoso_RFP_Template.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_RFP_Template.docx)

    ![](./Images/p6t1p1.png)

    > **NOTE:** Allow up to 10 minutes for these files to sync to your OneDrive after downloading. To avoid delays during the demo, ensure these files are downloaded and available in your OneDrive well in advance. If the files are not available, open the documents and copy the shared file links to use in the demo.

## Demos

### Copilot in Word

Let’s start by asking Copilot in Word some questions about a Request for Proposal (RFP) document.

1. Open Word (either in your browser or desktop application).

    ![](./Images/p4t2p1.png)

1. Open the following document: [Contoso_Completed_RFP.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_Completed_RFP.docx)

    ![](./Images/p6t1p2.png)

    ![](./Images/p6t1p2(1).png)

1. Select the **Copilot (1)** icon in the Word ribbon to open up the chat pane.

1. In the Chat pane, select or enter **(2)** the prompt:

   ```text
   Summarize this document
   ```

   ![](./Images/p6t1p3.png)

1. Next, enter the following prompt:

   ```text
   Analyze this document and generate a categorized list of required items needed to create an RFP.
   ```

1. Next, ask Copilot to create an RFP template by entering:

   ```text
   Analyze this document and create an RFP template based on the content.
   ```

    > **NOTE:** There is no need to copy the generated content, as we will be using a pre-created template document in the following demo. However, you can showcase how to copy Copilot's response or insert it into the document if relevant to your audience.

### Copilot Chat

Now that we’ve summarized the RFP document and created an RFP template, let’s use Copilot Chat to summarize project requirements for a new RFP.

1. Open a browser and navigate to [M365copilot.com](https://m365copilot.com/).  

1. Ensure **Web Mode** is selected.

    ![](./Images/p6t2p2.png)

1. Enter the following prompt:

   ```text
   Summarize highlighting the key objectives, scope, implementation timeline, budget, compliance needs, and vendor selection criteria in a bulleted list.
   ```

    ![](./Images/p6t2p3.png)

    ![](./Images/p6t2p3(1).png)
    
    > **NOTE:** Brackets indicate that a document is being referenced. Use the link:
    > [Project_Guidelines_Contoso.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Project_Guidelines_Contoso.docx)

    ![](./Images/p6t2p4.png)

1. Next, ask Copilot to extract vendor selection criteria:

   ```text
   Extract and summarize the key vendor selection criteria from this document, including weight percentages and evaluation factors.
   ```

1. Then, ask Copilot to create an RFP based on the project guidelines:

   ```text
   Using the project requirements outlined above, draft an RFP using the following template: [Contoso_RFP_Template.docx].
   ```

    ![](./Images/p6t2p6.png)

    > **NOTE:** Brackets indicate that a document is being referenced.

1. **Copy the generated RFP** to your clipboard for use in the next demo.

    ![](./Images/p6t2p7.png)

1. Optionally, ask Copilot to export the generated RFP to a Word document.

### Copilot in Outlook

Lastly, use Copilot in Outlook to draft an email to potential suppliers summarizing the RFP document.

1. Open Outlook (either in your browser or desktop application).

    ![](./Images/p6t3p1.png)

1. Select **New Email**.

    ![](./Images/p6t3p2.png)

1. Select **Copilot (1)** in the ribbon. From the drop-down menu, choose **Draft (2)**.

    ![](./Images/p6t3p3(1).png)

1. In the **"What do you want this email to say?"** prompt window, type:

   ```text
   Draft an email to potential suppliers summarizing the RFP below:

   [paste contents of RFP]
   ```

   ![](./Images/p6t3p3.png)

    > **NOTE:** Paste the RFP contents that you copied from the previous demo.

1. Once the draft is generated, you can use the **Adjust** feature to modify the tone, length, or level of formality.

    ![](./Images/p6t3p4.png)

[Back to Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
