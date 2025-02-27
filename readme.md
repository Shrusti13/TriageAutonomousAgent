# Overview of Auto Triage AI Agent solution

## Summary
**Auto Triage AI** is an intelligent, generative AI-powered solution that autonomously handles the entire bug triage process for product issue management. The solution leverages cutting-edge AI to automate the creation, update, and follow-up of bug reports, transforming how customer support teams manage product issues in Azure DevOps. By integrating generative AI into the workflow, Auto Triage AI ensures faster, more accurate, and scalable bug tracking while reducing the manual burden on support staff.

[Demo video]()

### Current Challenges

In the traditional manual triage process, support agents face several challenges:
-	**Time-Consuming Manual Processes**: Manually review each email, extract relevant details, and input them into Azure DevOps. This takes time and delays resolution.
-	**Risk of Human Error**: The manual process is prone to errors, such as missing critical details or incorrectly categorizing bugs, which can lead to miscommunication and delays.
-	**Inconsistent Updates**: When users send follow-up emails with additional information, support agents must manually update bug reports, which can sometimes lead to inconsistent or outdated bug details.
-	**Limited Scalability**: As the number of users and issues grows, the manual triage process becomes increasingly difficult to manage, leading to delays in responding to customer queries.


### Use case Narrative

In today’s fast-paced software development environments, managing and triaging product issues effectively is critical to delivering high-quality products. However, as the volume of incoming bug reports increases, support teams often find themselves overwhelmed by the repetitive and time-consuming task of manually logging and updating bugs. For instance, Sarah, a Product Support Specialist, receives hundreds of emails daily from users reporting product issues. For each email, Sarah needs to manually create bug reports in Azure DevOps, extract relevant information from knowledge documentation, and send follow-up emails to users. This manual process is slow, prone to errors, and not scalable.

Auto Triage AI revolutionizes this process by automating it with the power of generative AI. With two intelligent copilot agents working seamlessly together, Auto Triage AI autonomously handles both the initial bug creation and follow-up updates, ensuring faster resolution times and improving user experience without any manual intervention.

**So. Here our HACK!**

**Agent 1: Autonomous Bug Report Creation**
-	When an email detailing a product issue is received, Agent 1 is triggered. Leveraging generative AI, the agent carefully analyses the email to extract key details, such as the issue title. Using this title, it cross-references product documentation—including specifications, business and technical process flows, installation manuals, error codes, and troubleshooting guides—to generate comprehensive reproduction steps and system information, which are essential for the triage process.
-	The AI autonomously creates a bug in Azure DevOps, populating fields such as the issue description, repro steps, and system information.
-	After creating the bug, the agent sends an email to the user with the tracking number, confirming that the bug has been successfully logged.

**Agent 2: Autonomous Bug Update and Follow-up**
-	When a user replies with additional information or asks for an update on their tracking ID, Agent 2 automatically retrieves the corresponding bug details from Azure DevOps using the tracking ID.
-	Generative AI then analyses the email and updates the bug report accordingly, ensuring the information is always up to date.
-	The agent sends a follow-up email to the user, updating them with the current bug status and confirming that the new information has been added.
This intelligent automation reduces human error, speeds up the process, and ensures that all bug reports are consistent, accurate, and detailed.

**Technical Process Flow**
![Technical Process Flow](/assets/CaseStudyAITriage_TechnicalProcessFlow.jpg)


### Solution Benefits and Value

Auto Triage AI Powered by Generative AI transforms the bug triage process by automating repetitive tasks and introducing intelligence at every step. Here’s how AI brings significant value:

**Generative AI-Driven Intelligence**:
-	The solution uses generative AI to intelligently analyse bug reports and generate structured, relevant bug information based on issue descriptions. This AI-driven automation ensures that every bug report is accurate, consistent, and comprehensive without requiring manual intervention.

**Knowledge Integration**:
-	Generative AI uses the knowledge base to automatically populate fields in the bug report. This ensures that all bugs are described with the latest information and context, reducing manual knowledge checks and ensuring accurate details.

**Faster Bug Creation & Updates**:
-	By automating bug creation and updates, the solution reduces the time it takes to log and triage bugs. What previously took hours of manual work is now completed in minutes, freeing up support staff to focus on higher-priority tasks.

**Real-Time Updates**:
-	When a user provides new information, Agent 2 autonomously updates the bug report with relevant details. The AI interprets the input, analyses the context, and ensures the bug report is always up to date, preventing issues from being overlooked or misunderstood.

**Consistent, Scalable Workflow**:
-	The AI-powered agents operate seamlessly at scale. Whether handling 10 or 1,000 issues, Auto Triage AI can process them all with equal efficiency, reducing bottlenecks and improving support team productivity.

**Improved Accuracy**:
-	Generative AI ensures that all bug reports and user communications are generated with high accuracy, eliminating the possibility of human error and ensuring that the right information is always captured and communicated.
Enhanced User Experience:
-	By automating responses and updates, Auto Triage AI delivers faster, more consistent communication with users. They receive timely feedback without waiting for manual intervention, improving customer satisfaction and trust.
Cost Efficiency:
-	By significantly reducing manual work and improving productivity, Auto Triage AI lowers operational costs. It allows support teams to handle more issues with fewer resources, making it a highly cost-effective solution.\

**AI in Action**:
The integration of generative AI plays a crucial role in enabling Auto Triage AI to perform its tasks autonomously and intelligently:
-	**Contextual Understanding**: AI interprets the issue’s context and updates the bug report accordingly, leveraging the knowledge base to fill in missing details.
-	**Automated, Structured Generation**: AI not only generates bug reports but also structures them in a way that aligns with organizational requirements, ensuring consistency.

For more details on the use case, read from here, [case study](/docs/Case%20study%20-%20Auto%20Triage%20AI%20Powered%20by%20Generative%20AI%201.md). 




## Prerequisites

**Licenses & Applications**

1.  Power Automate user license

2.  AI builder credits

3.  Copilot Studio license

4.  Azure DevOps license

5.  Microsoft 365 Outlook



## Version history

Version|Date|Author|Comments
-------|----|----|--------
1.2 |February 27, 2025|Bhushan Gawale, Shrushti Shah|Second release of Auto AI Triage agent

## Disclaimer

**THIS CODE IS PROVIDED *AS IS* WITHOUT WARRANTY OF ANY KIND, EITHER EXPRESS OR IMPLIED, INCLUDING ANY IMPLIED WARRANTIES OF FITNESS FOR A PARTICULAR PURPOSE, MERCHANTABILITY, OR NON-INFRINGEMENT.**

---

## This demo illustrates

- Use of autonomous agents in the Microsoft Copilot Studio
- Use of Instructions for running this autonomously without human interference
- Use of custom AI prompts from AI hub
- Use of actions in Copilot Studio backed by Azure DevOps connectors


## Find solution zip and import the solution in Power Platform environment

Find the solution zip here, [agent solution zip](/AutoAITriageSolution.zip). 


Follow the instructions to [import solution](/docs/Case%20study%20-%20Auto%20Triage%20AI%20-%20User%20Manual.md). 

Use the email templates for testing the autonomous Auto AI Triage agent from this document, [email templates](/docs/Email%20Template%20for%20Copilot%20Agent%20-%20Auto%20Triage%20AI%20Powered%20by%20Generative%20AI%201.md). 


## Working solution snippet

Find the detailed snippets of working solution here, [working solution snippet](/docs/Case%20study%20-%20Auto%20Triage%20AI%20-%20Snippet%20from%20working%20solution.md). 
