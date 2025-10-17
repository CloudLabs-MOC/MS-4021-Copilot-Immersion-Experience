---
demo:
    title: 'IT Demo'
---

[Back to Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

# IT Demo

**Scenario:**  

As an IT Infrastructure Manager, you're planning to install a new network security product into your corporate network.

## Demo Setup

The sample documents can be found in the MS-4021 GitHub repository [here](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/tree/master/ResourceFiles):

The specific files needed for this demo are:

- [Contoso_CipherGuard_Product_Specification.docx](https://github.com/MicrosoftLearning/MS-4021-Copilot-Immersion-Experience/raw/master/ResourceFiles/Contoso_CipherGuard_Product_Specification.docx)

    ![](./Images/m3p2t1p1(1).png)

    > **NOTE:** Allow up to 10 minutes for these files to sync to your OneDrive after downloading. To avoid delays during the demo, ensure these files are downloaded and available in your OneDrive well in advance. If the files are not available, open the documents and copy the shared file links to use in the demo.

## Demos

### Copilot Chat

Let’s start by asking Copilot to create a project implementation plan.

1. Open a browser and navigate to [M365copilot.com](https://m365copilot.com/).

    ![](./Images/m3p2t1p1.png)

1. Ensure **Web** mode is selected.

    ![](./Images/m3p2t1p2.png)

1. In the prompt window, paste the following prompt:

    ```text
    You are an IT infrastructure manager at Contoso. Your task is to create a detailed project implementation plan for installing a new network security product in your corporate network. Your plan should include key milestones, resource allocation, potential risks, and a timeline to ensure successful deployment and minimal disruption to operations.
    ```

    > **NOTE:** Role-based prompts help Copilot understand the user's responsibilities and context, improving the relevance and specificity of the output.

1. Now we'll refine the project plan by asking Copilot to add new sections to the project plan. Paste the following prompt:

    ```text
    Please add the following sections to the existing plan: testing and QA, training, communication, documentation and reporting, stakeholder analysis, project timeline, and risk assessment and mitigation. Ensure these sections provide detailed action steps and align with the existing content. Avoid duplicating any items already included in the original plan.
    ```

1. Lastly, have Copilot output the proposed project plan to a Word document. Paste the following prompt and then select the **link** that Copilot provides to the newly created file to **download** it to your Downloads folder.

    ```text
    Please export the project plan to a Word document.
    ```

    ![](./Images/m3p2t1p5.png)

1. Click on the **Apps (1)** from the left navigation pane, and then select **OneDrive (2)** under the Apps section.

    ![](./Images/m3p2t1p6.png)

1. On the OneDrive window, click on **+ Create or upload (1)** and select **Files upload (2)**. Then in Open dialog, select the following files **(3)** and then click on **Open (4)**.

    - `Contoso_CipherGuard_Product_Specification.docx`
    - Select the file you downloaded from Copilot.

        ![](./Images/m3p2t1p7.png)

        ![](./Images/m3p2t1p7(1).png)

### Copilot in Word

We'll now ask Copilot to expand on these strategies and draft proposals on how to implement them.

1. In the left navigation pane of the M365 Copilot homepage, click **Apps (1)**, then select **Word (2)** under the Apps section.

    ![](./Images/m3p2t2p1.png)

1. On the Word homepage, click on **+ Create blank document**.

    ![](./Images/m3p2t2p2.png)

1. In the **What do you want Copilot to draft?** prompt box, paste the prompt **(1)**, then click **+ Add content (2)**. From the list, select the two files **(3)** you uploaded in the previous task, one at a time. Finally, click **Generate (4)** or press **Enter**.

    ```text
    Using the Contoso "CipherGuard Product Specification.docx" and the 'Project Implementation Plan' template provided in "Project_Implementation_Plan.docx", draft a comprehensive project implementation plan for deploying Contoso CipherGuard. Ensure the plan aligns with the product specifications and follows the structure outlined in the template.
    ```

    ![](./Images/m3p2t2p3.png)

1. Select **Keep it** or, if time permits, demonstrate how to tweak the document using Copilot.

    ![](./Images/m3p2t2p4.png)

1. When you’re done, click the **drop-down (1)** icon in the top-left corner of the page. Enter **Contoso_Project_Plan (2)** as the file name, then click anywhere outside the field to save it.

    ![](./Images/m3p2t2p5.png)

1. Click the **Share (1)** drop-down and select **Copy Link (2)** to copy the file link. You’ll need it later in the exercise.

    ![](./Images/m3p2t2p6.png)

### Copilot in PowerPoint

We'll now use Copilot to generate a PowerPoint presentation based on the new proposal to implement the Contoso CipherGuard product.

1. Click on the **Apps (1)** fromt he left navigative apne and then select **PowerPoint (2)** under Apps section.

    ![](./Images/m3p2t3p1.png)

1. Click on **Create blank presentation**.

    ![](./Images/m3p2t3p2.png)

1. Click on the **Copilot (1)** icon and select the **Create a new presentation (2)**.

    ![](./Images/m3p2t3p3.png)

1. Paste the shared link for the **Contoso_Project_Plan.docx** document and then click **Send**.

    The full prompt should look like:

    ```text
    Create a presentation from [Link to Contoso_Project_Plan.docx].
    ```

    ![](./Images/m3p2t3p4.png)

1. Click on **Generate slides**. 

    ![](./Images/m3p2t3p5.png)

1. Copilot begins generating slides based on the project plan, providing an outline along with features like speaker notes, images, slide layouts, and a General sensitivity label.Click **Keep it**.

    ![](./Images/m3p2t3p6.png)

    > **NOTE:** Generating slides may take up to two minutes, depending on the document’s complexity and number of slides.

[Back to Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
