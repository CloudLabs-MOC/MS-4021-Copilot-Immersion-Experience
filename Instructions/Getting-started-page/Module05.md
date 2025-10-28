# MS-4021 : Building Custom AI Experiences with Copilot Studio

Welcome to your MS-4021: Building Custom AI Experiences with Copilot Studio workshop! We’re excited to guide you through hands-on learning with Microsoft 365 Copilot across Word, PowerPoint, Outlook, Teams, and Copilot Chat. In this lab, you’ll experience how Copilot can research business ideas, generate strategic plans, create impactful presentations, and streamline communication, helping you transform executive workflows into intelligent, efficient, and insight-driven actions.

### Overall Estimated Duration: 45 Minutes

## Lab Overview

In this lab, you will explore how Microsoft 365 Copilot and Copilot Studio Lite empower users to create, customize, and deploy their own AI-powered assistants. You’ll design a specialized Copilot agent by defining its role, tone, and purpose, then connect it to relevant business data for grounded responses. 

## Lab Objectives

By the end of this lab, you will be able to:

- **Access and navigate Copilot Studio Lite:** Launch the Copilot Studio environment and locate the tools needed to build and manage custom Copilot agents.

- **Define and customize a Copilot agent:** Specify your agent’s name, role, tone, and behavioral instructions to align with project or organizational needs.

- **Configure a knowledge-grounded agent:** Upload relevant project documents to create a connected knowledge base that enables accurate, context-aware responses.

- **Test and validate agent performance:** Interact with your custom agent to verify that it understands uploaded content, responds accurately, and maintains the defined tone and purpose.

- **Understand how Copilot Studio Lite supports enterprise productivity:** Learn how custom Copilot agents can enhance collaboration, automate domain-specific knowledge sharing, and extend Copilot capabilities within Microsoft 365.

## Prerequisites

Basic understanding of Microsoft 365 apps, particularly Word, Teams, and Copilot Chat.
Familiarity with conversational AI concepts, business workflows, or using Copilot for task automation will be helpful but not mandatory.

## Architecture

This lab demonstrates how **Copilot Studio Lite** integrates with **Microsoft 365 Copilot** to build, train, and deploy custom AI agents that enhance collaboration and knowledge sharing across organizational workflows. The architecture connects content, context, and interaction within the Microsoft 365 environment to create an adaptive, knowledge-driven assistant.

* **Copilot Studio Lite:** Serves as the design and configuration layer where the agent’s personality, scope, and knowledge base are defined. It connects the agent to structured and unstructured data sources like project documents and FAQs.

* **Knowledge Base Integration:** Acts as the grounding layer for the agent. Uploaded files provide factual context that the agent uses to generate accurate, relevant responses to user queries.

* **Copilot Chat Interface:** Functions as the interaction layer where users communicate directly with the agent, asking questions or requesting information derived from the shared knowledge base.

* **Microsoft 365 Ecosystem (Word, Teams, Outlook):** Provides the collaboration and productivity environment where the published Copilot agent can be accessed, shared, and used in real scenarios, enabling contextual assistance within existing workflows.

* **Publishing and Access Layer:** Once the agent is created, it is published and shared organization-wide, allowing team members to interact with it through a unified link. This ensures consistent, AI-driven support across projects and departments.

## Architecture Diagram: 

![](../Demos/Images/archmod05.png)

## Explanation of Components

* **Copilot Studio Lite:** A lightweight web-based environment within Microsoft 365 Copilot used to create, configure, and publish custom AI agents. It provides an intuitive interface for defining an agent’s purpose, tone, and behavior, and for connecting it to knowledge sources like project documents.

* **Copilot Agent:** A customizable AI assistant built within Copilot Studio Lite. It can be trained on project-specific documents and instructions to assist users with domain-specific queries, automate information retrieval, and enhance collaboration.

* **Knowledge Base:** The collection of uploaded documents (like SOPs, FAQs, and troubleshooting guides) that form the factual foundation of the agent’s responses. The quality and relevance of these documents directly impact the agent’s accuracy and usefulness.

* **Instructions Section:** The configuration area where you define the agent’s role, behavior, and tone. These act as guiding principles for how the agent interprets queries and structures its responses.

* **Try It Panel:** The testing interface within Copilot Studio Lite where users can interact with the configured agent in real time, verify its understanding of uploaded knowledge, and refine its behavior before publishing.

* **Publish and Share:** The final deployment step that makes the agent accessible to others within the organization. Once published, the agent can be shared via a link and embedded into collaborative tools like Microsoft Teams or Copilot Chat.

* **Microsoft 365 Copilot Integration:** The underlying ecosystem that connects the custom Copilot agent to productivity apps like Word, Excel, and Teams—enabling contextual assistance, content generation, and project support within familiar workflows.

## Getting Started with the Lab

Welcome to your MS-4021: Building Custom AI Experiences with Copilot Studio Workshop! We've prepared a seamless environment for you to explore and learn.

## Accessing Your Lab Environment
 
Once you're ready to dive in, your virtual machine and **Guide** will be right at your fingertips within your web browser.
 
![](../Demos/Images/labguidetab.png)

### Virtual Machine & Lab Guide
 
Your virtual machine is your workhorse throughout the workshop. The lab guide is your roadmap to success.

## Exploring Your Lab Resources
 
To get a better understanding of your lab resources and credentials, navigate to the **Environment** tab.
 
![](../Demos/Images/AI-3025-g1.png)

## Lab Guide Zoom In/Zoom Out
 
To adjust the zoom level for the environment page, click the **A↕: 100%** icon located next to the timer in the lab environment.

![](../Demos/Images/AI-3025-g2.png)

## Utilizing the Split Window Feature
 
For convenience, you can open the lab guide in a separate window by selecting the **Split Window** button from the Top right corner.
 
![](../Demos/Images/AI-3025-g3.png)

## Managing Your Virtual Machine
 
Feel free to **Start, Stop, or Restart (2)** your virtual machine as needed from the **Resources (1)** tab. Your experience is in your hands!
 
![](../Demos/Images/AI-3025-g4.png)

## Let's Get Started with Microsoft 365 Copilot Portal
 
1. On your virtual machine, click on the M365-Copilot icon as shown below:

     ![](../Demos/Images/m365-copilot-shortcut.png)

2. You'll see the **Sign into Microsoft Azure** tab. Here, enter your credentials:
 
   - **Email/Username:** <inject key="AzureAdUserEmail"></inject>
 
      ![](../Demos/Images/sign-in.png)
 
3. Next, provide your password:
 
   - **Password:** <inject key="AzureAdUserPassword"></inject>
 
     ![](../Demos/Images/tap-password.png)
 
4. If prompted to **Stay signed in**, you can click **No.**

    ![](../Demos/Images/stay-signed-in.png)

## Support Contact
 
The CloudLabs support team is available 24/7, 365 days a year, via email and live chat to ensure seamless assistance at any time. We offer dedicated support channels explicitly tailored for both learners and instructors, ensuring that all your needs are promptly and efficiently addressed.
 
Learner Support Contacts:
 
- Email Support: cloudlabs-support@spektrasystems.com
- Live Chat Support: https://cloudlabs.ai/labs-support

Click on **Next** from the lower right corner to move on to the next page.

   ![](../Demos/Images/nextpagem5.png)

## Happy Learning !!