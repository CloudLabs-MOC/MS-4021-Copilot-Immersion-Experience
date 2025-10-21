---
demo:
    title: 'Build an Agent with Copilot Studio lite'
---

[Back to Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)

---

# Build and Publish an Agent using Copilot studio lite

This demo walks through how to build a virtual assistant using Copilot Studio lite via Copilot Chat and publish it to Microsoft 365 Copilot.

## Demo Setup

In order to complete these demos, you will need to download the following files:

- [**Delivery Drone Press Release.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_Press_Release.docx)
- [**Delivery Drone Troubleshooting.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_Troubleshooting.docx)
- [**Delivery Drone SOP.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_SOP.docx)
- [**Upselling Opportunities.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Upselling_Opportunities.docx)
- [**Delivery Drone FAQ.docx**](https://github.com/MicrosoftLearning/MS-4008-Microsoft-365-Copilot-Interactive-Experience-for-Executives/raw/master/ResourceFiles/Delivery_Drone_FAQ.docx)

    ![](./Images/m5p2t1p1(1).png)

> **TIP:** Before delivering the demo, you can create a SharePoint site in your demo environment to store all the files for easy access. Alternatively, you can store the files locally and reference them directly in your prompts using **/**.

## Talking Points

Copilot Studio lite lets us build custom copilots, tailored to specific projects, departments, or knowledge bases. We can give them a personality, set their boundaries, and feed them specific documents to ensure high-quality, grounded responses.

In this demo, we’ll create a virtual assistant for the ReleCloud drone delivery project. The assistant will know everything we’ve uploaded and will help answer team questions, saving time and improving productivity.

## Demo Steps

### Step 1 – Navigate to Copilot Studio lite

1. Go to [https://m365.cloud.microsoft/chat](https://m365.cloud.microsoft/chat) and from the left navigation pane, select **Create agent (1)** under **Chat** section. Select **Describe (2)** tab, under **Copilot Studio**.

    ![](./Images/m5p2t1p1.png)

### Step 2 – Define Your Agent

1. When prompted, enter the following description and press Enter.

    ```text
    You're a virtual project manager assistant for our drone delivery project. You know everything about the project from the documents we've shared with you, and are happy to help team members get the information they need.
    ```

   ![](./Images/m5p2t2p1.png)

1. When prompted to provide a name for the agent, enter the following:

    ```text
    Drone Delivery Assistant
    ```

    ![](./Images/m5p2t2p2.png)

1. If asked for confirmation enter the following :

    ```text
    Yes, thank you
    ```

1. If prompted to provide what to avoid or emphasize:

    ```text
    Please be clear and concise and avoid long answers. Where possible, refer primarily to the knowledge shared with you. If you don't know the answer, refer them to the drone delivery project manager.
    ```

    ![](./Images/m5p2t2p3.png)

1. If you're asked to specify a particular tone of voice, provide the following:

    ```text
    Friendly and professional
    ```

> **IMPORTANT:**  You may not be prompted for all of these options, depending on your environment. If you are not prompted, you can add this information using the **Configure** tab within Copilot Studio lite.

### Step 3 – Configure the Agent

1. Select the **Configure** tab from the top.

    ![](./Images/m5p2t3p1.png)

1. Review and optionally update the **Instructions** section by adding the below instruction:

    ```text
    Your name is Drone Delivery Project Manager Assistant. You serve as a virtual project manager for the ReleCloud drone delivery project, with comprehensive knowledge from shared documents. Be clear and concise, avoiding long answers. If the answer is unknown, refer to the drone delivery project manager.
    ```

    ![](./Images/m5p2t3p2.png)

1. Scroll down to the **Knowledge** section and select **Upload from device (1)** icon. From the Open dialog, select and add the following **documents (2)** to the agent’s knowledge base and then click **Open** **(3)**:

    - **`Delivery Drone Press Release.docx`**
    - **`Delivery Drone Troubleshooting.docx`**
    - **`Delivery Drone SOP.docx`**
    - **`Upselling Opportunities.docx`**
    - **`Delivery Drone FAQ.docx`**

        ![](./Images/m5p2t3p3(11).png)

        ![](./Images/m5p2t3p3(12).png)

### Step 4 – Test Your Agent

1. Select **Try it** from the top.

    ![](./Images/m5p2t4p1.png)

1. Using the prompt box, try asking a few of the following questions:

    - `Tell me about the ReleCloud Delivery Drone.`
    - `How do I fix the drone error code D-101?`

        ![](./Images/m5p2t4p3.png)

    - `What are the upsell opportunities for ReleCloud?`
    - `What’s the duration of Phase 1 of the delivery drone project?`

        ![](./Images/m5p2t4p5.png)

> **IMPORTANT:**   It can take some time for the agent to process the documents and provide accurate answers. If you receive an error message, wait a few minutes and try again.

> **TIP:** You can also test via Microsoft Teams once the agent is live.

### Step 5 – Publish and Share

1. From the top right corner, select **Create** to publish the agent.

    ![](./Images/m5p2t5p1.png)

1. On **Your agent was created successfully!** pop-up, click on **Share**.  

    ![](./Images/m5p2t5p2.png)

1. Under the section **This agent is available to:**, select **Anyone in your organization (1)** and then click **Apply (2)**.

    ![](./Images/m5p2t5p3.png)

1. Click the **Copy (1)** icon to copy the URL, then select **Close (2)**. You can paste the link into a Teams chat for convenient access.

    ![](./Images/m5p2t5p4.png)

Once live, you can interact with the agent in Teams chat or via @mentions.

[Back to Index](https://microsoftlearning.github.io/MS-4021-Copilot-Immersion-Experience/)
