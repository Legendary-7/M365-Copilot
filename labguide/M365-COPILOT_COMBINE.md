# M365 COPILOT

## Exercise 1: Understanding M365 Copilot Architecture (Read Only)

>**Note:** The following exercise is Read-Only to let you understand the architecture of **M365 Copilot** and to get well-versed with its features and the transformative actions it can take.

### Overview

At its core, Copilot for Microsoft 365 isn't merely a feature but an intelligent partner that seamlessly integrates into your daily Microsoft 365 interactions. Whether you're using Outlook, PowerPoint, Word, Excel, Teams, or other applications, Copilot aims to enhance your efficiency by generating content, providing relevant suggestions, and optimizing your processes.

Microsoft Copilot for Microsoft 365 operates through a sophisticated architecture and prompt flow, ensuring that user inputs are not only understood but also generate tailored and contextually relevant responses. In this section, we'll explore the step-by-step process that Copilot follows, from the user prompt to the final response.

### Copilot's Understanding of Context and User Needs

Copilot's effectiveness lies in its unparalleled ability to understand users, achieved through:

- **Analyzing Content:** Scrutinizing documents, emails, and meeting content to discern intent, meaning, tone, structure, and semantics.
- **Gaining Personal Insights:** Utilizing profile information, communication patterns, and activity history to understand user interests, expertise, and preferences.
- **Real-time Monitoring:** Continuously observing user actions to gauge immediate needs and determine how best to assist.

### Transformative Actions

With a deep understanding of user context, Copilot doesn't just observe; it takes action:

- **Search and Retrieval:** Leveraging powerful search capabilities to identify valuable data and content sources for assistance.
- **Natural Phrasing with Large Language Models:** Harnessing Large Language Models (LLMs) to craft naturally phrased recommendations aligned with the user's unique situation.
- **Refining Recommendations:** Focusing on quality over quantity, Copilot evaluates and refines suggestions to ensure contextually relevant and specific results.

### Features and Transformations by Copilot

Copilot for Microsoft 365 is designed to transform the way employees work in the digital age, offering features such as:

- **Reduction in Digital Overload:** By combining LLMs with work content and context, Copilot tackles tasks and alleviates the burden of digital overload
- **Enhanced Meeting Engagement:** Assisting users in staying more engaged in meetings and providing quick catch-ups for missed meetings, ensuring continuous participation.
- **Efficient Email Management:** Summarizing lengthy email threads and aiding in drafting responses, streamlining email communication.
- **Writing Assistance:** Transforming writing processes by drafting, editing, summarizing, and creating alongside users, enhancing document quality and efficiency.
- **Presentation Development:** Simplifying the initiation of presentations with natural language commands, sparking creativity and idea generation.
- **Data Analysis and Visualization:** Assisting in identifying trends, creating visualizations, and providing recommendations to simplify data analysis.
- **Security and Compliance:** Ensuring comprehensive enterprise compliance and security controls for data protection and peace of mind.
- **User Control:** Empowering users with control over AI suggestions, allowing modification or discard, emphasizing the human element in AI interaction.

### Copilot's Architecture and Processing Flow: Step-by-Step

![](./media/copilot-for-microsoft-365-architecture.png)

The following steps outline the processing flow of Copilot for Microsoft 365, from user prompt to Copilot response:

#### User Interaction

1. **User Input:**
   
   - A user provides input or asks a question within a Microsoft 365 app, such as Word or PowerPoint.

#### Grounding and Data Preparation

2. **Grounding:**
   - Copilot prepares the user's input using a method known as "grounding." This step ensures that responses are specific and directly related to the user's task.
   
3. **Consulting Microsoft Graph:**
   - During grounding, Copilot consults Microsoft Graph to gather related data from the organization. It accesses only the data that the user is permitted to see based on their role and permissions in Microsoft 365.

#### Retrieval-Augmented Generation

4. **Retrieval-Augmented Generation:**
   - This step involves combining the user's data with other relevant sources, such as knowledge base articles, to refine the question for a more accurate answer.

#### Large Language Model (LLM) Consultation

5. **Consulting the LLM:**
   - With the improved input, Copilot consults the Large Language Model (LLM) to generate an initial answer.

#### Answer Refinement

6. **Refinement Process:**
   - Copilot further refines the initial answer by conducting additional checks against Microsoft Graph.
   - Evaluations for responsible AI practices, security assessments, and compliance checks are performed.
   - The answer may be converted into actionable commands, ensuring practicality and usability.

#### User Response

7. **Offering Suggestions:**
   - Finally, Copilot offers a well-formed, relevant suggestion back to the user, accompanied by any actionable commands.
   - The results are closely tied to the organization's specific data, ensuring relevance and context.

## Exercise 2: Understand Semantic Index (Read Only)

>**Note**: The following exercise is Read-Only to let you understand the key role played by the Semantic Index.

Microsoft technologies underpin **Copilot for Microsoft 365**, with a key role played by the Semantic Index. This vast knowledge graph, connecting billions of objects, concepts, and relationships, introduces a new dimension to data understanding within Microsoft 365.

The Semantic Index for Copilot constructs an intricate map of your personal and company data, establishing important connections and identifying significant relationships. This design is much like the inner workings of the human brain. It goes beyond the confines of keyword search by interpreting and encoding the conceptual relationships between data elements. By analyzing your Microsoft Graph data - encompassing emails, documents, calendars, chats, and more - and working synergistically with LLMs, it delivers personalized, relevant, and actionable responses.

The Semantic Index stands at the forefront of Copilot for Microsoft 365, revolutionizing data understanding and contextual comprehension within the ecosystem. We will unravel the intricate workings of the Semantic Index, elucidating its role in connecting billions of objects, concepts, and relationships. By parsing intent beyond literal words and continuously expanding its knowledge graph, the Semantic Index empowers Copilot to deliver personalized and actionable responses. This exercise underscores the transformative impact of the Semantic Index in driving deeper contextual understanding and fostering continuous improvement within Microsoft 365.

### Key Features

1. **Rich Knowledge Base:**
   - The Semantic Index is powered by Microsoft Graph, enhancing Microsoft 365 search capabilities.
   - Security is paramount, ensuring that users only access data within their designated permissions.

2. **Contextual Responses:**
   - Leveraging individual and company data, Semantic Index enables Copilot to provide pertinent and actionable responses.
   - Through a secure and compliant process, it constructs a sophisticated map of relationships, respecting user privacy.

### How Copilot Uses Semantic Index

1. **Vectorized Indices:**
   - Advances keyword matching with vectorized indices, fostering conceptual understanding.
   - Multi-dimensional spaces facilitate semantic similarity, moving beyond rigid exact matches. These vectors enable Copilot to handle a broader set of search queries beyond “exact match.”

2. **Semantic Search:**
   - Captures semantic meaning, comprehending relationships between diverse forms of words.
   - Enhances understanding of sentences, snippets, and documents, broadening search capabilities. Semantic Search uses vectors to understand relationships, capturing synonyms and expanding the scope of searchable information.

3. **Grounding and Natural Language Processing (NLP):**
   - Implements grounding, associating words with real-world entities for nuanced understanding.
   - Enhances Copilot's intelligence in understanding user intent and connecting inputs to broader meanings. Grounding is a common approach in NLP systems that associates words and phrases with real-world entities that the AI understands.

### Semantic Relationships

Microsoft's Semantic Index enables grounding through its predefined knowledge graph that contains billions of concepts interconnected by semantic relationships. A semantic relationship refers to a typed connection between two entities or concepts that encodes some meaningful association between them. The graph contains semantic data on people, places, organizations, products, concepts, and the relationships between them all. This graph provides the semantic "understanding" of words, phrases, and entities that Microsoft products use.

The Semantic Index relies on a predefined knowledge graph that features various semantic relationships, such as "is-a," "part-of," "works-for," etc. These relationships enable Copilot to infer new knowledge, enriching language grounding and contextual understanding.

- **"is-a":** Used for categorization or inheritance (e.g., "dog is-a mammal").
- **"part-of":** Describes composition or properties of an entity (e.g., "wheel part-of car").
- **"works-for":** Associates an employee with an employer (e.g., "John works-for Microsoft").
- **"located-in":** Relates an entity to its geographic location (e.g., "Paris located-in France").
- **"causes":** Connects a cause to an effect (e.g., "rain causes wet").

Semantic Index uses billions of these structured relationships between entities, concepts, and data to encode human-like understanding of the connections between things. This web of semantic relationships is what enables context and language grounding.

### Customer Data and Security

Semantic Index doesn't change a customer's data. It simply indexes an organization's Microsoft 365 data across Microsoft 365 apps. The permissions model within your Microsoft 365 tenant can help ensure that data doesn't unintentionally leak between users, groups, and tenants. The Semantic Index only presents data that each individual can access using the same underlying controls for data access used in other Microsoft 365 services. Semantic Index honors the user identity-based access boundary so that the grounding process only accesses content that the current user is authorized to access. Data generated by the Semantic Index remains within your company’s tenant, and complies with your security, compliance, identity, and privacy policies and processes. The Semantic Index works only with content to which your users already have permission and doesn't affect storage quotas.

### Benefits for Users

1. **Deeper Contextual Understanding:**
   - Parses intent beyond literal words, comprehending organizational jargon and language nuances.
   - Contextualizes broad queries, interprets ambiguous instructions, and links concepts across domains.

2. **Continuous Improvement:**
   - New content is continually indexed. This action constantly expands the Semantic Index knowledge graph, which increases its ability to understand an ever growing number of objects, concepts, and the relationships between them. In doing so, Copilot for Microsoft 365's contextual comprehension continues to grow more powerful over time.

### Incorporating Third-Party Information

Graph connectors empower the integration of external data, enriching Copilot with a diverse range of content. Microsoft ensures that the indexing of Graph connectors' data maintains access controls, providing an expanded and searchable content landscape.

## Exercise 3.1: Administering M365 Copilot

This exercise is designed to provide a comprehensive understanding of how to effectively administer and manage the AI-powered **Microsoft Copilot** in a **Microsoft 365** environment through the **Microsoft 365 Admin Center**. Understanding these operations is crucial for the efficient utilization and management of Copilot in your organization. You will delve into the administrative side of **Microsoft Copilot**, exploring how to configure, manage, and optimize it for an organization's specific needs, equipping you with the knowledge and skills needed to maximize the benefits of this powerful tool in your organization.

### Managing Microsoft 365 Copilot Licenses in Admin Center (Read Only)

This exercise guides you through the process of managing **Microsoft 365 Copilot** licenses for users in your tenant through the **Microsoft 365 Admin Center**. You'll learn how to assign and remove licenses, manage Microsoft 365 Copilot services, and configure public web content access. Understanding these operations is crucial for the efficient utilization and management of **Copilot** in your organization.

>**Note:** Your access has been set to Global Reader, meaning you won't be able to make changes. These instructions are for viewing only, reflecting the read-only access granted in your environment.

### Task 1: Assign Copilot licenses to the user

Follow these steps to assign a Copilot license for an existing user from the admin center:

1. Go to [Microsoft 365 Admin Center](https://admin.microsoft.com/) and sign in with your admin credentials.

1. From the left side navigation pane, click on **Users (1)** and then choose **Active users (2)**.

    ![](../labguide/media/M8.png)

1.  In the Active Users page, search or find the user you want to manage the Copilot license. Click on the user.

    ![](../labguide/media/active-users.png)

1. On the user's profile page, on the right side click on **Licenses and apps** to go to their license details.

    ![](../labguide/media/user-licenses.png)

1. To assign, expand the **Licenses (1)** section, select the boxes for the licenses that you want to assign, then select **Save changes (3)**.

   >**Note:** In this case, we have already assigned the licences to the account.

    ![](../labguide/media/M11.png)

 All license changes are saved automatically after you make an assignment change.

### Task 2: Remove a Copilot licenses

To remove an already assigned Copilot license:

1. Follow the steps above to open the user's **Licenses and apps**.

    ![](../labguide/media/user-licenses.png)

1. Uncheck the **Microsoft Copilot for Microsoft 365** under the licenses section.

    ![](../labguide/media/M18.png)

    >**Note:** In this case, you don't need to remove the licenses.

1. Changes apply automatically after saving.

Now the user's Copilot license assignment status will be updated.

## Exercise 3.2: Administering M365 Copilot

This exercise is designed to provide a comprehensive understanding of how to effectively administer and manage the AI-powered **Microsoft Copilot** in a **Microsoft 365** environment through the **Microsoft 365 Admin Center**. Understanding these operations is crucial for the efficient utilization and management of Copilot in your organization. You will delve into the administrative side of **Microsoft Copilot**, exploring how to configure, manage, and optimize it for an organization's specific needs, equipping you with the knowledge and skills needed to maximize the benefits of this powerful tool in your organization.

### Task 1: Manage Microsoft 365 Copilot Services

**Microsoft 365 Copilot** comes with different services that can be enabled or disabled as per your preferences. This can be configured from the **Microsoft 365 Admin Center**.

>**Note:** Your access has been set to Global Reader, meaning you won't be able to make changes. These instructions are for viewing only, reflecting the read-only access granted in your environment.

1. log in to [Microsoft 365 Admin Center](admin.microsoft.com).

1. Go to **Users (1)** > **Active Users (2)**.

    ![](../labguide/media/microsoft.1.png)

1. Select the user for which **Microsoft 365 Copilot** license has been assigned.

    ![](../labguide/media/microsoft.2.png)

1. On the user pane navigate to **Licenses and apps.** 

   ![](../labguide/media/microsoft.2.1.png)

1. Scroll down to Apps section, you will see a detailed list of enabled services tied to the Microsoft 365 Copilot license. 
 
   ![](../labguide/media/microsoft.3.png)
   
   Given below are the features of each of the following services of **Microsoft 365 Copilot**:

    - **Copilot Studio in Copilot for Microsoft 365:** Copilot Studio in Copilot for Microsoft 365 enables users and administrators to customize and extend the functionality of Copilot across Microsoft 365 applications. This feature allows organizations to tailor Copilot's behavior by creating custom workflows, integrating third-party apps or internal tools, and managing specific skills or actions. It also provides insights into usage patterns and supports no-code/low-code customization, making it accessible for all users.
      
    - **Graph Connectors in Microsoft 365 Copilot:** These connectors enable Copilot to access data from **Microsoft Graph**, a cloud-based service that provides a unified programmability model to access data in Microsoft 365. This feature allows Copilot to source information from a wide range of Microsoft services and apps, enriching its responses with contextually relevant data.

    - **Intelligent Search:** This feature uses AI technology to streamline the process of searching for information across Microsoft 365 apps. Instead of merely returning results based on keywords, Intelligent Search understands the context of the search query, providing more relevant results. It can also suggest answers to questions or direct users to specific documents or data points.

    - **Microsoft 365 Copilot for SharePoint:** Microsoft 365 Copilot for SharePoint enhances productivity by assisting with content creation and management. It can generate and refine content for pages and news posts, optimize search results using AI, and suggest metadata for better organization. Additionally, it streamlines workflows, improves collaboration by summarizing discussions, and ensures content adheres to governance and compliance policies.

    - **Microsoft 365 Copilot in Microsoft Teams:** In Teams, Copilot can help summarize key points in a conversation, suggest next steps, and even help with meeting notes. This feature can keep you updated and organized, and enhance the efficiency of teamwork by turning conversations into actions.

    - **Microsoft 365 Copilot in Productivity Apps:** Copilot is integrated with productivity apps like Word, Excel, PowerPoint, and more. It can provide suggestions, automate tasks, and even generate content based on user input. In PowerPoint, for example, it can help design slides, while in Word it can help draft and edit documents.
  
    - **Microsoft Copilot with Graph-Grounded Chat:** Microsoft Copilot with Graph-Grounded Chat uses the power of Microsoft Graph to provide a highly contextual and intelligent chat experience. This service enables Copilot to access and understand organizational data such as files, meetings, emails, and more from Microsoft Graph, ensuring responses are grounded in real-time, relevant information. It can assist with answering complex queries, providing actionable insights, and automating tasks, all while maintaining data security and compliance.

    - **Power Platform Connectors in Microsoft 365 Copilot:** These connectors allow Copilot to interact with the **Power Platform**, a suite of tools including Power Apps, Power Automate, Power BI, and Power Virtual Agents. This enables the AI to access data, perform operations, or trigger workflows within these tools, further enhancing its capabilities and the range of tasks it can help automate.

    Together, these features make **Microsoft 365 Copilot** a powerful tool that can significantly enhance productivity and simplify workflows in an organization.

## Exercise 3.3: Administering M365 Copilot (Read Only)

This exercise is designed to provide a comprehensive understanding of how to effectively administer and manage the AI-powered **Microsoft Copilot** in a **Microsoft 365** environment through the **Microsoft 365 Admin Center**. Understanding these operations is crucial for the efficient utilization and management of Copilot in your organization. You will delve into the administrative side of **Microsoft Copilot**, exploring how to configure, manage, and optimize it for an organization's specific needs, equipping you with the knowledge and skills needed to maximize the benefits of this powerful tool in your organization.

### Task 1: Managing Public web content access 

**Microsoft Copilot for Microsoft 365** chat experiences in Bing, Microsoft Edge, and the Microsoft Teams app have a feature that allows Copilot to reference web content when responding to user prompts. Allowing **Copilot for Microsoft 365** to reference web content enhances the end-user experience and productivity with Copilot. The feature is automatically turned on when you first start using Copilot. You can turn off this feature by following these steps:

>**Note:** Your access has been set to Global Reader, meaning you won't be able to make changes. These instructions are for viewing only, reflecting the read-only access granted in your environment.

1. In the Microsoft 365 admin center, go to **Settings (1)** > **Search & intelligence (2)**.

    ![](../labguide/media/M19.png)

1. On the **Configurations** page, select **Improved responses with web content in Copilot for Microsoft 365**.

    ![](../labguide/media/M20.png)

1. Select **Change**.

1. Uncheck the checkbox for **Allow Copilot to reference web content**.

    ![](../labguide/media/m21.png)

    >**Note:** In this case, you don't need to uncheck this option.

1. Select **Save**.

All admin setting updates may take up to 24 hours to reflect any changes.

### Task 2: End-user Action Required

Once the admin provides access to let **M365 Copilot** access content from the web, the user need to manually turn it on as well. Follow the given steps below to allow the access to the web content for the Copilot:

1. Navigate to `https://www.office.com` and sign in using the **CloudLabs provided credentials**. Select **Copilot** icon from the left pane.

    ![](../labguide/media/office-page.png)

1. On the page of **M365 Copilot Chat**, select the icon for **Plugins**.

    ![](../labguide/media/copilot-plugins.png)

1. You will see a toggle for the plugin **Web Content** which is set off by default. Turn this toggle **ON**. Once it's ON, it allows Copilot to access web-based resources to improve its functionality and suggestions.

    ![](../labguide/media/web-content-toggle.png)

    Your Microsoft 365 Copilot Chat can, now, utilize web to display the responses to you.

>**Note:** If you turn off web access from the admin center, this control is disabled. However, if you enable web access, you must enable this toggle as well to allow web access for the Copilot. Remember, changes to the admin settings may take up to **24 hours** to reflect.

## Exercise 3.4: Administering M365 Copilot

This exercise is designed to provide a comprehensive understanding of how to effectively administer and manage the AI-powered **Microsoft Copilot** in a **Microsoft 365** environment through the **Microsoft 365 Admin Center**. Understanding these operations is crucial for the efficient utilization and management of Copilot in your organization. You will delve into the administrative side of **Microsoft Copilot**, exploring how to configure, manage, and optimize it for an organization's specific needs, equipping you with the knowledge and skills needed to maximize the benefits of this powerful tool in your organization.

### Change update channel of Microsoft 365 Apps to enable Copilot (Read Only)

One of the benefits of Microsoft 365 Apps is that Microsoft provides new (and updated) features for Office apps, such as Excel and Word, regularly. You can control how often the users in your organization get these new features by specifying the update channel. In addition to new features, update channels provide, as needed, security and non-security updates regularly, every month. Non-security updates provide fixes for known issues and provide stability or performance improvements for Office.

**Contoso Ltd**, a leading IT Consultancy firm, has decided to opt for the Monthly Enterprise Channel for their **Microsoft 365 Apps**. This decision was taken after a thorough assessment of the company’s needs and understanding the benefits of the Monthly Enterprise Channel. **Contoso Ltd.** is a dynamic organization that requires regular updates to keep their operations running smoothly and securely, but also needs stability and predictability in their software environment. The Monthly Enterprise Channel perfectly fits their needs as it provides new features, security and non-security updates on a predictable monthly schedule. Contoso appreciates the fact that these updates occur only once a month, allowing their IT team to plan and manage these updates efficiently. Furthermore, the Monthly Enterprise Channel offers Contoso a good balance between receiving the latest updates and having a stable, secure software environment.

In addition to the Monthly Enterprise Channel, Contoso Ltd has also decided to utilize Cloud updates as its management solution. This strategic decision is aimed at maximizing the benefits of cloud-based technologies in their software management processes. With Cloud updates, Contoso can enjoy a more streamlined, efficient, and automated update process. This solution reduces the manual intervention required from the IT team, freeing them up to focus on more strategic tasks. Cloud updates provide real-time access to the latest updates, ensuring that Contoso's Microsoft 365 Apps are always up-to-date with the latest features and security patches. Moreover, the cloud-based solution allows Contoso to manage updates across multiple devices and locations seamlessly, a feature that is particularly beneficial for a global corporation like Contoso Ltd.

>**Note:** Your access has been set to Global Reader, meaning you won't be able to make changes. These instructions are for viewing only, reflecting the read-only access granted in your environment.

### Task 1: Enable Cloud Update

1. A Microsoft Entra ID security group must be established to enable the channel change feature to target an entire security group. This channel change feature can also target individual devices. In our scenario, we have already established a security group named **Copilot Users**.

1. Log into the **Microsoft 365 Apps admin center**, you should land on the Home page automatically. On the Recommendation based on your tenant card, select Enable cloud.

    ![](../labguide/media/channel1.1.png)

1. Please pause momentarily and refresh the page to ensure that both the Monthly Enterprise entry and the Current entry are listed under the Cloud Update navigation.

    ![](../labguide/media/channel1.2.png)

- **Initiate a Channel change**

1. While staying in the **Microsoft 365 Apps admin center**, navigate to **Inventory**. Select **Show all devices**. 

    ![](../labguide/media/channel1.3.png)

1. Select the **Switch device update channel** button on the top. You can enter device names or Microsoft Entra ID groups, or a mix of both. In this case, we will choose our Security group.

    ![](../labguide/media/channel1.4.png)

1. Select Move devices to initiate the channel change.

    ![](../labguide/media/channel1.5.png)

>**Note:** It might take up to 24 hours for the channel change to be completed by the device, assuming devices are online and can connect to the service.

## Exercise 4.1: Reviewing Security and Compliance in Copilot using Sensitivity Labels

### Introduction

**Microsoft Copilot** is designed with security and compliance in mind. It does not store or share any of the user's data. It only uses the data or information that the user explicitly provides as input or context. It also respects the user's privacy and preferences, and does not collect any personal or sensitive information by itself.

Given below are the capabilities from Microsoft Purview which strengthen your data security and compliance for **Microsoft Copilot for Microsoft 365**:

### Task 1: Implementing Sensitivity Labels with Purview 

Sensitivity labels are a way of categorizing and protecting your data based on its level of confidentiality and the impact to your business if it is leaked or misused. You can use sensitivity labels to apply metadata tags and encryption settings to your data sources, columns, tables, and files. Purview is a service that helps you manage and govern your data across your organization.

CoPilot is a system that aids in the management and control of data within an organization. It can work in conjunction with Sensitivity Labels to classify and protect sensitive information. Sensitivity Labels are attributes that can be applied to documents and emails to classify them based on the content sensitivity. These labels can trigger protective actions like encryption or visual markings. Once a sensitivity label is applied to content, it stays with the content regardless of where it's stored or with whom it's shared.

#### Understanding Sensitivity labels

Sensitivity labels in Microsoft 365 allow organizations to classify and protect their sensitive content. Here's some information on what these labels represent in Contoso Ltd:

- **Confidential:**
The **Confidential** sensitivity label is used when information is meant to be restricted to a specific group of people within an organization. This label is typically used for data such as employee records, internal policies, or strategic plans. Unauthorized disclosure of this information can lead to potential damage to the organization, but not to the same extent as that classified as **Highly Confidential**.

- **Highly Confidential:**
The **Highly Confidential** sensitivity label is assigned to the most sensitive information that, if disclosed, could result in severe harm to the organization. This might include trade secrets, legal documents, or personally identifiable information (PII) such as social security numbers, credit card information, or health records. Extra security measures, like encryption, are often applied to these documents to prevent unauthorized access or sharing.

- **Internal:**
The **Internal** sensitivity label is used for information that is not intended for public view but doesn't necessarily contain sensitive data. This could include internal newsletters, meeting minutes, or project plans. This label serves as a reminder to employees that the information should not be shared outside the organization, though its disclosure wouldn't cause significant harm.

- **Public**
The **Public** sensitivity label is applied to information that can be freely shared both inside and outside the organization. This information poses no risk if disclosed and is often intended for public consumption. Examples could include press releases, marketing materials, or public-facing reports.

   >**Note:** Remember, sensitivity labels are a tool for managing and protecting data, but they are most effective when combined with user education about data handling and security best practices.

   >**Note:** Your access has been set to Global Reader, meaning you won't be able to make changes. These instructions are for viewing only, reflecting the read-only access granted in your environment.


### Task 1.1: How are sensitivity labels created in Microsoft Purview (Read Only)

In this task, you will learn how Purview is used to implement sensitivity labels for your data assets.

>**Note:** You are not expected to perform the following steps. This information is provided solely to give you an understanding of the process of creating and publishing Sensitivity Labels in the Purview portal.


- Navigate to the [Microsoft Purview](https://compliance.microsoft.com/homepage) portal and from the left menu select **labels (1)** and in the yellow information box, indicate that Your organization has not turned on the ability to process content in Office online files that have encrypted sensitivity labels applied and are stored in OneDrive and SharePoint. Select **Turn on now (2)**. Once you do this, there can be a delay for the setting to propagate through the system.

   ![](./media/exercise3(2.1).png)

- On **Labels (1)** page, select **+ Create a label (2)**.

   ![](./media/exercise3(2.2).png)

- Provide a name and description for your label. Select **Next (4)** at the bottom of the page.

    | Setting | Action |
    | -- | -- |
    | **Name** | Enter **Confidential-Finance (1)** |
    | **Display name** | Enter **Confidential-Finance (2)** |
    | **Description for users** | Enter **Confidential-Finance Demo (3)** | 

   ![](./media/exercise3(2.3).png)

- Note the scope for this label. The scope is set to Items. Read the description but don’t change anything. Select **Next** at the bottom of the page.

   ![](./media/exercise3(2.4).png)

- On the **Choose protection settings for labeled items** select **Apply or remove encryption (1)** and **Apply content marking (2)**, then select **Next (3)**.

   ![](./media/exercise3(2.5).png)   

- The Encryption window shows the configuration for the encryption settings. Review the information box under Configure encryption settings and review the configured settings. Notice how the user access to content is set to never expire. You can also assign permissions to specific users and groups By clicking on the **Assign permissions (1)**. On the Assign permissions blade, click on **+ Add users or groups (2)**.

   ![](./media/exercise3(2.6).png)

-  On the **Add users or groups** window, select the user name and click on **Add (2)**.

   ![](./media/exercise3(2.7).png)

- You will be redirected to the **Assign Permission** page. Verify that the user is selected and click on **Save (2)**.

   ![](./media/exercise3(2.8).png)

   >**Note:** Only selected users can interact with content that has this label applied. Under users and groups, the tenant is defined so all users in your tenant can view content that has this label.

- Click Next on Encryption window.

   ![](./media/exercise3(2.9).png)

- On the content markings page, take note of the information box at the top of the page. Turn on the **Content Making (1)** and select the check box for **Add a watermark (2)**, **Add a header (3)** and **Add a footer (4)**.

   ![](./media/exercise3(2.10).png)

- Under **Add a watermark**, click on **Customize text (1)**. Under Watermark text, type **Confidential watermark text (2)** and click on **Save (3)**.

   ![](./media/exercise3(2.11).png)

- Under **Add a header**, click on **Customize text (1)**. Under Header text, type **Confidential Document (2)** and click on **Save (3)**.

   ![](./media/exercise3(2.12).png)

- Under **Add a footer**, click on **Customize text (1)**. Under Footer text, type **Confidential Document (2)** and click on **Save (3)**.

   ![](./media/exercise3(2.13).png)

   >**Note**: Content markings will be applied to documents but only headers and footers will be applied to email messages. In other words, watermarks are not applied to emails.

- The content marking associated with this label is a watermark. Select Next at the bottom of the page.

   ![](./media/exercise3(2.14).png)

- You are now in the Auto-labeling for files and emails window. Turn on the **Auto-labeling for files and emails (1)** and Read the description of auto-labelling on the top of the page and the information box below it and under Detect content that matches these conditions click on **+ Add condition (2)** from the drop-down select **Content contains (3)** then under Group name select **Add (4)** drop-down, select Sensitive info type and in Sensitive info type (5) window search for **Credit (6)** and select the **Credit card number (7)**, select **Add (8)** from the button, select **Next (9)** on the bottom of the page.

   ![](./media/exercise3(2.15).png)
  
   ![](./media/exercise3(2.16).png)
  
   ![](./media/exercise3(2.17).png)
  
   ![](./media/exercise3(2.18).png)

- This next window defines protection settings for groups and sites that have this label applied. If this is not enabled, select Next at the bottom of the page.

   ![](./media/exercise3(2.19).png)

- Review the settings and click on Create label.

   ![](./media/exercise3(2.20).png)

### Task 1.3: Publish sensitivity label (Read Only)

The task aims to provide a streamlined method for publishing sensitivity labels to users. Users are guided through a series of steps within Microsoft Purview, specifically under Label policies. The objective is to make the selected labels, such as Confidential-Finance and Highly-Confidential, available to all users, ensuring consistent and standardized data protection measures.

- In the Microsoft Purview. portal, under Solutions, expand Information protection and in the drop-down select **Label policies (1)** and click on **Publish label (2)**.

   ![](./media/exercise3(2.21).png)

- Select **Choose sensitivity labels to publish (1)**. A window opens that provides information about the policy. Select **Confidential-Finance (2)** from the label and select **Add (3)**.

   ![](./media/exercise3(2.22).png)

- Back on **Choose sensitivity labels to publish** blade, click on **Next**.

   ![](./media/exercise3(2.23).png)

- Click on **Next** on the **Assign Admin Units** page.

   ![](./media/exercise3(2.24).png)

- Read the description under **Publish to users and groups**. Notice that this label is available to all users. Don’t change any settings. Select **Next** at the bottom of the page.

   ![](./media/exercise3(2.25).png)

- Under the policy settings, don’t change any settings. Select **Next** at the bottom of the page.

   ![](./media/exercise3(2.26).png)

- Under the **Apply a Default label to documents**, don’t change any settings. Select **Next** at the bottom of the page.

   ![](./media/exercise3(2.27).png)

- Under the **Apply a Default label to emails**, don’t change any settings. Select **Next** at the bottom of the page.

   ![](./media/exercise3(2.28).png)

- Under the **Apply a default label to meetings and calendar events**, don’t change any settings. Select **Next** at the bottom of the page.

   ![](./media/exercise3(2.29).png)

- Under the **Apply a default label to Fabric and Power BI content**, don’t change any settings. Select **Next** at the bottom of the page.

   ![](./media/exercise3(2.30).png)

- The last configuration option is to name your policy. Enter the policy name as **Confidential-Policy (1)**. Select **Next (2)** on the bottom of the page to exit the policy configuration and return to the **Information Protection** page.

   ![](./media/exercise3(2.31).png)

- Review the settings and click on **Submit** and then select **Done**.

   ![](./media/exercise3(2.32).png)
  
   ![](./media/exercise3(2.33).png)

- Back to **Label policies** blade and notice the newly published label.

   ![](./media/exercise3(2.34).png)


This task has provided a clear walkthrough for implementing sensitivity labels in Microsoft Purview, enabling users to categorize and safeguard data based on confidentiality. The guided steps cover label creation, encryption configuration, content marking, and automated labeling, fostering a strong understanding of data protection. Customization options for watermarks, headers, and footers enhance security measures. Demonstrating practical application, the task integrates sensitivity labels seamlessly into Word documents, emphasizing their importance in real-world scenarios. The subsequent label publishing and application steps ensure consistent and standardized data protection, contributing to a robust organizational data governance framework.


### Using Sensitivity Labels in Microsoft 365 Copilot

**Sensitivity labels** from Microsoft Purview Information Protection let you classify and protect your organization's data, while making sure that user productivity and their ability to collaborate isn't hindered.

Sensitivity labels offer the following capabilities:

1. **Customiable:** Specific to your organization and business needs, you can create categories for different levels of sensitive content in your organization. For example, Personal, Public, General, Confidential, and Highly Confidential.

1. **Clear Text:** Because a label is stored in clear text in the metadata for files and emails, third-party apps and services can read it and then apply their own protective actions, if required.

1. **Persistent**: Because the label is stored in metadata for files and emails, the label stays with the content, no matter where it's saved or stored. The label identification that's unique to your organization becomes the basis for applying and enforcing policies that you configure.

The sensitivity labels that you use to protect your organization's data are recognized and used by **Microsoft Copilot for Microsoft 365** to provide an extra layer of protection. For example, in Microsoft Copilot Graph-grounded chat conversations that can reference data from different types of items, the sensitivity label with the highest priority (typically, the most restrictive label) is visible to users. Similarly, when sensitivity label inheritance is supported by Copilot, the sensitivity label with the highest priority is selected.

If the labels applied encryption from Microsoft Purview Information Protection, Copilot checks the usage rights for the user. Only if the user is granted permissions to copy (the **EXTRACT** usage right) from an item, is data from that item returned by Copilot.

In short, the user that uses **Microsoft Copilot**, cannot access labeled documents where he/she has not been added to the permissions for the label. When the user has been added to the permissions, with either Reviewer or Viewer permission, then the document can also not be accessed.

In summary, **Microsoft 365 Copilot** is more stringent when handling encrypted documents with a sensitivity label. As you will need either custom permissions or at least the Co-author role, sensitive information is safeguarded. Provided, of course, that:

1. you have sensitivity labels employed within the enterprise;
1. you have set the right level of permissions to the labels;
1. you are protecting your most sensitive information using labels.

## Exercise 4.2: Reviewing Security and Compliance in Copilot Using Data Classification (Read Only)

### Introduction

**Microsoft Copilot** is designed with security and compliance in mind. It does not store or share any of the user's data. It only uses the data or information that the user explicitly provides as input or context. It also respects the user's privacy and preferences, and does not collect any personal or sensitive information by itself.

Given below are the capabilities from Microsoft Purview whcih strengthen your data security and compliance for Microsoft Copilot for Microsoft 365:

### Using Data Classification in Microsoft 365 Copilot

**Data classification** plays a critical role in helping businesses organize and safeguard their data. Sorting information by its level of sensitivity — like personally identifiable information or confidential records — lets organizations put in place tailored security measures against unauthorized intrusion and data leaks. Additionally, data classification enables businesses to comply with industry regulations and legal requirements by helping ensure that sensitive information is handled appropriately.

**Data classification** forms the foundation needed for Copilot to function efficiently. By accurately categorizing data, Copilot can provide more precise recommendations, making the classification process faster and more reliable. **Copilot** uses AI and ML technologies to make the categorization of data automated and more efficient. By integrating with existing data management systems, such as SharePoint or OneDrive, Copilot analyses the content of documents and automatically assigns appropriate classification labels. This automation eliminates the need for manual classification, saving time and reducing the risk of human error.

One of the key benefits of Copilot is its ability to learn from user interactions. As users review and validate the classification suggestions Copilot provides, the system becomes more accurate over time, resulting in improved classification outcomes. This iterative learning process ensures that the system aligns with each organization's specific needs and requirements, making it an asset for data management.

#### Preparing your data for Copilot

Before deploying Copilot, it is essential to prepare your data to maximize its effectiveness. Consider the following guidelines for effective preparation:

- **Data inventory and analysis:** Conduct a comprehensive inventory of your data and analyze its content to identify patterns and commonalities. This step will help in defining appropriate classification categories and labels.

- **Data cleansing and normalization:** Cleanse and normalize your data by removing duplicates, standardizing formats, removing old or legacy versions and ensuring consistency. This process will improve classification accuracy and optimize Copilot's performance by enabling it to surface accurate data.

- **Engage stakeholders:** Involve key stakeholders, such as legal, compliance and IT teams, in the data preparation process. Their input will ensure the classification process aligns with regulatory requirements and organizational policies.

- **Training and awareness:** Provide training and awareness sessions to users and administrators about the importance of data classification and how to effectively use Copilot. This approach will facilitate a smooth transition and increase user adoption. In addition, utilize organizational change management strategies to champion the process and educate the workforce on how data classification and sanitization can expedite Copilot’s ingestion of the data.

>**Note:** You are not expected to perform the following steps. This information is provided solely to give you an understanding of the process of Data Classification in the Purview portal. Your access has been set to Global Reader, meaning you won't be able to make changes. These instructions are for viewing only, reflecting the read-only access granted in your environment.

### Task 1: Using the Microsoft data classification dashboard

The **data classification page** provides visibility into that body of content, specifically:

- the number items that have been classified as a sensitive information type and what those classifications are

- the top applied sensitivity labels in both Microsoft 365 and Azure Information Protection

- the top applied retention labels

- a summary of activities that users are taking on your sensitive content

- the locations of your sensitive and retained data

Follow the given steps to access the **Microsoft data classification dashboard**:

1. Navigate to `https://compliance.microsoft.com/` and sign in using the **CloudLabs provided credentials**.

1. In the left navigation pane of the compliance portal, select **Data classification** and then, select **Overview**.

1. Data classification will scan your sensitive content and labeled content before you create any policies. This is called **zero change management**. This lets you see the impact that all the retention and sensitivity labels are having in your environment and empower you to start assessing your protection and governance policy needs.

1. The **Top sensitive information type** card shows the top sensitive information types that have been found and labeled across your organization.

1. To find out how many items are in any given classification category, hover over the bar for the category.

    >**Note:** If the card displays the message "**No data found with sensitive information**", it means that there are no items in your organization that have been classified as being a sensitive information type or no items that have been crawled.

1. The **Top sensitivity labels applied to content** card shows the number of items (email or document) by sensitivity level.

    >**Note:** If you haven't created or published any sensitivity labels or no content has had a sensitivity label applied, this card will display the message **"No sensitivity labels detected"**.

1. The **Top retention labels applied to content** card shows you how many items have a given retention label. Retention labels are used to manage the retention and disposition of content in your organization. When applied, they can be used to control how long an item will be kept before deletion, whether it should be reviewed prior to deletion, when its retention period expires, and whether it should be marked as a record.

    >**Note:** If this card displays the message,**"No retention labels detected"**, it means you haven't created or published any retention labels or no content has had a retention label applied.

1. The **Top activities detected** card provides a quick summary of the most common actions that users are taking on the sensitivity labeled items.

    >**Note:** If this card displays the message, **"No activity detected"** it means that there's been no activity on the files or that user and admin auditing isn't turned on.

1. The **Sensitivity and retention labeled data by location** cards provide visibility into the number of items that have which label as well as their location.

    >**Note:** If this card displays the message, **"No locations detected"**, it means you haven't created or published any sensitivity labels or no content has had a retention label applied.

### Task 2: Using Content Explorer for Data Classification

**Content explorer** allows you to natively view the items that were summarized on the **Overview** page. It shows a current snapshot of the items that have a sensitivity label, a retention label or have been classified as a sensitive information type in your organization.

Follow the given steps to use the content explorer for data classification:

1. Navigate to `https://compliance.microsoft.com/` and sign in using the **CloudLabs provided credentials**.

1. In the left navigation pane of the compliance portal, select **Data classification** and then, select **Content explorer**.

1. If you know the name of the label, or the sensitive information type, you can type that into the filter box.

1. Alternately, you can browse for the item by expanding the label type and selecting the label from the list.

1. Select a location under **All locations** and drill down the folder structure to the item and double-click to open the item natively in content explorer.

1. To create a .csv file that contains a listing of whatever the focus of the pane is, select **export**.

>**Note:** It can take up to **seven days** for counts to be updated in content explorer.

### Task 3: Using Activity Explorer

**Activity explorer** allows you to monitor what's being done with your labeled content. It provides a historical view of activities on your labeled content. The activity information is collected from the Microsoft 365 unified audit logs, transformed, and then made available in the Activity explorer UI. Activity explorer reports on up to 30 days worth of data. There are more than 30 different filters available for use, like Data range, Activity type, Location, User, Sensitivity label, Retention label etc.

>**Note:** Make sure **Audit** is turned on before using this in your account. If it's not, select **Turn Audit ON** from the activity explorer page.

To go to the **Activity Explorer**, follow the given steps:

1. Navigate to `https://compliance.microsoft.com/` and sign in using the **CloudLabs provided credentials**.

1. In the left navigation pane of the compliance portal, select **Data classification** and then, select **Activity explorer**.

Activity explorer gathers information from the audit logs of multiple sources of activities. Some examples of the **Sensitivity label activities** and **Retention labeling activities** from applications native to Microsoft Office, the Azure Information Protection (AIP) unified labeling client and scanner, SharePoint, Exchange (sensitivity labels only), and OneDrive include:

- Labels applied
- Labels changed (upgraded, downgraded, or removed)
- Autolabeling simulation
- File read

In addition, using Endpoint data loss prevention (DLP), Activity explorer gathers DLP policy matches events from Exchange, SharePoint, OneDrive, Teams Chat and Channel, on-premises SharePoint folders and libraries and more.

## Exercise 4.3: Reviewing Security and Compliance in Copilot Using Customer Keys (Read Only)

### Introduction

**Microsoft Copilot** is designed with security and compliance in mind. It does not store or share any of the user's data. It only uses the data or information that the user explicitly provides as input or context. It also respects the user's privacy and preferences, and does not collect any personal or sensitive information by itself.

Given below are the capabilities from Microsoft Purview whcih strengthen your data security and compliance for Microsoft Copilot for Microsoft 365:

## Using Customer Keys in Microsoft 365 Copilot

A **Customer Key** provides extra protection against viewing of data by unauthorized systems or personnel, and complements BitLocker disk encryption and SSE in Microsoft data centers. It helps you meet regulatory or compliance obligations for controlling root keys. You explicitly authorize Microsoft 365 services to use your encryption keys to provide value added cloud services, such as eDiscovery, anti-malware, anti-spam, search indexing, and so on.

Customer Key is built on service encryption and lets you provide and control encryption keys. Microsoft 365 then uses these keys to encrypt your data at rest and helps you meet compliance obligations because you control the encryption keys that Microsoft 365 uses to encrypt and decrypt data.

When you revoke access to your keys as part of leaving the service, the availability key is deleted, resulting in cryptographic deletion of your data. Cryptographic deletion mitigates the risk of data remanence, which is important for meeting both security and compliance obligations.

As with other Microsoft 365 services, such as eDiscovery and search, items encrypted with Microsoft Purview Customer Key are supported and eligible to be returned by **Copilot for Microsoft 365**.

#### Encryption Ciphers used by Customer Key

Customer Key uses various encryption ciphers to encrypt keys as shown in the following figure:

![](./media/customer-key-encryption.png)

## Exercise 4.4: Reviewing Security and Compliance in Copilot Using Communication Compliance (Read Only)

### Introduction

**Microsoft Copilot** is designed with security and compliance in mind. It does not store or share any of the user's data. It only uses the data or information that the user explicitly provides as input or context. It also respects the user's privacy and preferences, and does not collect any personal or sensitive information by itself.

Given below are the capabilities from Microsoft Purview whcih strengthen your data security and compliance for Microsoft Copilot for Microsoft 365:

### Communication Compliance in Microsoft 365 Copilot

**Communication Compliance** is an insider risk solution that helps minimize communication risks by helping you detect, capture, and act on potentially inappropriate messages in your organization. Pre-defined and custom policies allow you to check internal and external communications for policy matches so they can be examined by designated reviewers. Reviewers can investigate email, Microsoft Teams, Microsoft Copilot for Microsoft 365, Viva Engage, or third-party communications in your organization and take appropriate actions to make sure they're compliant with your organization's message standards.

**Communication compliance policies in Microsoft 365** help you overcome many modern challenges associated with compliance and internal and external communications, including:

- Checking increasing types of communication channels
- The increasing volume of message data
- Regulatory enforcement and the risk of fines

#### Scenarios for Communication Compliance

**Communication compliance policies** can assist with reviewing messages in your organization in several important compliance areas:

- **Corporate policies**: Users must comply with acceptable use, ethical standards, and other corporate policies in all their business-related communications. Communication compliance policies can detect policy matches and help you take corrective actions to help mitigate these types of incidents. For example, you could check user communications in your organization for human resources concerns such as harassment or the use of potentially inappropriate or offensive language.

- **Risk Management**: Organizations are responsible to all communications distributed throughout their infrastructure and corporate network systems. Using communication compliance policies to help identify and manage potential legal exposure and risk can help minimize risks before they can damage corporate operations. For example, you could check messages in your organization for unauthorized communications and conflicts of interest about confidential projects such as upcoming acquisitions, mergers, earnings disclosures, reorganizations, or leadership team changes.

- **Regulatory compliance**: Most organizations must comply with some type of regulatory compliance standards as part of their normal operating procedures. These regulations often require organizations to implement some type of scoping or oversight process for messaging that is appropriate for their industry. For example:

    - **The Financial Industry Regulatory Authority (FINRA) Rule 3110** is a requirement for organizations to have scoping procedures in place to check user communications and the types of businesses in which it engages.
    - Another example may be a need to review broker-dealer communications in your organization to safeguard against potential insider trading, collusion, or bribery activities.

Communication compliance policies can help your organization meet these requirements by providing a process to both analyze and report on corporate communications.

#### Microsoft Copilot for Microsoft 365

Communication compliance provides support for **Microsoft Copilot for Microsoft 365**. You can use communication compliance to analyze interactions (prompts and responses) entered into Copilot to detect for inappropriate or risky interactions or sharing of confidential information.

The following **Copilot apps** are supported by communication compliance:

- Teams (chats/channels/meetings) Copilot
- Word Copilot
- PowerPoint Copilot
- Excel Copilot
- OneNote Copilot
- Loop Copilot
- Whiteboard Copilot
- Microsoft 365 Chat in Teams
- Microsoft 365 Chat in Bing

Any prompt or response entered into a supported Copilot app that matches a communication compliance policy is displayed as a policy match on the Policies page on the Pending tab, with separate entries for prompts and responses. If only the prompt or only the response matches a policy, an item is created on the Pending tab just for that policy match. You can remediate policy matches for Copilot in the same way that you remediate any other policy match.

![](./media/communication-compliance.png)

The following information is displayed for each item on the **Pending** tab for Copilot policy matches:

- **Copilot icon:** The Copilot icon identifies the policy match as a Copilot interaction.
- **Subject column:** The value in this column identifies the policy match as a Copilot interaction and lists the name of the app that was used. For example: "Copilot in Excel".
- **Sender column:** Sender of the message. If the policy match is a response from Copilot, the value is "Copilot".
- **Recipient column:** Recipients included in the message. If the policy match is a prompt to Copilot, the value is "Copilot".
- **Message text:** The message text that the user entered (the text that caused the policy match) is shown on the right side of the screen in its entirety.

### Task 1: Using Communication Compliance in Microsoft 365 Copilot

>**Note:** You are not expected to perform the following steps. This information is provided solely to give you an understanding of the process of creating and using Communication Compliance policies in the Purview portal. Your access has been set to Global Reader, meaning you won't be able to make changes. These instructions are for viewing only, reflecting the read-only access granted in your environment.

To use Communication compliance in Microsoft 365 Copilot, follow the below steps:

1. Navigate to `https://compliance.microsoft.com/` and sign in using the **CloudLabs provided credentials**.

1. In the left navigation pane of the compliance portal, select **Communication compliance**. You will land on the **Overview** page of the **Communication compliance** portal.

    ![](./media/communication-compliance-overview.png)

1. Select the **Policies** tab and select **Create policy** to create and configure a new policy from a template or to create and configure a custom policy.

    ![](./media/communication-compliance-createpolicy.png)

1. To use communication compliance on Microsoft 365 Copilot, choose **Detect Copilot for Microsoft 365 interactions**, and a flyout page containing the required details will appear.

    ![](./media/communication-compliance-copilot.png)

1. You can see the name of the policy in the **Policy name** section, which is already populated. Here you can configure the following settings:

    ![](./media/compliance-policy-config.png)
    
    - **Users or groups in scope:** Choose the users or groups to apply the policy to, including the users or groups you'd like to exclude. When using the conflict of interest template, you'll select two groups or two users to detect internal communications. You can select **All users** here.

    - **Reviewers:** Reviewers added here are the reviewers that you can choose from when escalating an alert in the investigation and remediation workflow. When reviewers are added to a policy, they automatically receive an email message that notifies them of the assignment to the policy and provides links to information about the review process. You can select your own user here.

    - **Sensitive data to collect:** This step is where you can select default and custom sensitive info types. Pick from existing custom sensitive information types or custom keyword dictionaries in the communication compliance policy wizard. You can create these items before running the wizard if needed. You can also create new sensitive information types from within the communication compliance policy wizard.

        Select **Add trainable classifiers** to choose classifiers which can detect potentially inappropriate language and images sent or received in the body of email messages or other types of text. You can also select all the classifiers as per your choice and click **Add**.

        ![](./media/policy-trainable-classifiers.png)

1. Select **Create policy**.

1. Within sometime, your policy will be created and select **Close** to close the flyout page.

    ![](./media/compliance-policy-created.png)

    >**Note:** It might take upto 1 hour to activate your policy.

1. To test the proper functioning of your policy, select the **More actions** icon on your recently created policy and select **Test policy conditions**.

    ![](./media/compliance-policy-test.png)

1. In the flyout page:

    ![](./media/compliance-policy-tested.png)

    - Select the **Enter messages to test** option, and then enter some messages that you expect would be detected by the policy. Separate messages with a comma.

    - If you have a .txt file that includes a list of messages to detect, select **Upload a file containing messages to test** option, and then select **Upload file** to upload your text file.

1. Select **Test** to see a list of test results.

## Exercise 4.5: Reviewing Security and Compliance in Copilot Using Audit (Read Only)

### Introduction

**Microsoft Copilot** is designed with security and compliance in mind. It does not store or share any of the user's data. It only uses the data or information that the user explicitly provides as input or context. It also respects the user's privacy and preferences, and does not collect any personal or sensitive information by itself.

Given below are the capabilities from Microsoft Purview which strengthen your data security and compliance for Microsoft Copilot for Microsoft 365:

## Auditing in Microsoft 365 Copilot

Microsoft Purview auditing solutions provide an integrated solution to help organizations effectively respond to security events, forensic investigations, internal investigations, and compliance obligations. Thousands of user and admin operations performed in dozens of Microsoft 365 services including **M365 Copilot** and solutions are captured, recorded, and retained in your organization's unified audit log. Audit records for these events are searchable by security ops, IT admins, insider risk teams, and compliance and legal investigators in your organization. This capability provides visibility into the activities performed across your **Microsoft 365 organization**.

For **Auditing in M365 Copilot**, details are captured when users interact with Copilot. Events include how and when users interact with Copilot, in which Microsoft 365 service the activity took place, and references to the files stored in Microsoft 365 that were accessed during the interaction. If these files have a sensitivity label applied, that's also captured.

### Task 1: Accessing the M365 Copilot Logs

>**Note:** You are not expected to perform the following steps. This information is provided solely to give you an understanding of the process of auditing logs in the Purview portal.

Copilot events can be accessed in the **Audit** solution from the **Microsoft Purview compliance portal**.

1. Navigate to `https://compliance.microsoft.com/` and sign in using the CloudLabs provided credentials.

1. In the left navigation pane of the compliance portal, select **Show all** and then select **Audit**.

1. Select **Start recording user and admin activity** to configure the Audit logging activities, and grant confirmation, if required.

    ![](./media/audit-page.png)

1. On the **Audit** page, configure the search using the following conditions on the **New Search** tab.

    - **Date and time range:** Select a date and time range to display the activities that occurred within that period. The date and time are presented in Coordinated Universal Time (UTC). The last seven days are selected by default.
    
        ![](./media/audit-page-2.png)

    - **Activities:** Select the activities to search for. Use the search box to search for activities to add to the list. Leave this box blank to return entries for all audited activities. To search for **Copilot events**, select **Copilot activities** and **Interacted with Copilot**.

        ![](./media/audit-activity-names.png)

        You can also select Copilot as a workload.

        ![](./media/audit-workload.png)

    - **Users:** Select this box and start typing the name of users to display search results for. The audit log entries for the selected activities performed by the users you select in this box are displayed in the list of results. Leave this box blank to return entries for all users (and service accounts) in your organization.

1. Select **Search** to run the search.

1. The audit log search starts running. When the search is completed, audit records are displayed on the page. Select a record to display a flyout page with detailed properties.

    ![](./media/audit-search.png)

1. The screen gets displayed showing all the record entries of the required type.

1. Click on any entry to see it in more details.

    ![](./media/audit-details.png)

1. If you want to download the results as a report to your local system, select **Export** on the top of the Audit search results page and choose **Downloads file**.

    ![](./media/audit-search-export.png)

## Exercise 4.6: Reviewing Security and Compliance in Copilot Using Content Search (Read Only)

### Introduction

**Microsoft Copilot** is designed with security and compliance in mind. It does not store or share any of the user's data. It only uses the data or information that the user explicitly provides as input or context. It also respects the user's privacy and preferences, and does not collect any personal or sensitive information by itself.

Given below are the capabilities from Microsoft Purview which strengthen your data security and compliance for Microsoft Copilot for Microsoft 365:

### Using Content Search in Microsoft 365 Copilot

You can use the Content search eDiscovery tool in the **Microsoft Purview compliance portal** to search for in-place content such as email, documents, and instant messaging conversations including the responses with **M365 Copilot** in your organization.

After you run a search, the number of content locations and an estimated number of search results are displayed on the search flyout page. You can quickly view statistics, such as the content locations that have the most items that match the search query. After you run a search, you can preview the results or export them to a local computer.

When a user interacts with **Microsoft Copilot for Microsoft 365** apps (such as Word, PowerPoint, Excel, OneNote, Loop, or Whiteboard), data about these interactions is stored. The stored data includes the user's prompt, how Copilot responded, and information used to ground Copilot's response. **For example**, this stored data provides users with Copilot interaction history in Microsoft Copilot with Graph-grounded chat and meetings in Microsoft Teams. This data is processed and stored in alignment with contractual commitments with your organization’s other content in Microsoft 365. The data is encrypted while it's stored and isn't used to train foundation LLMs, including those used by **Microsoft Copilot for Microsoft 365**.

>**Note:** You are not expected to perform the following steps. This information is provided solely to give you an understanding of the process of creating and using Content Search in the Purview portal. Your access has been set to Global Reader, meaning you won't be able to make changes. These instructions are for viewing only, reflecting the read-only access granted in your environment.

### Task 1: Creating and running a Search

1. Navigate to `https://compliance.microsoft.com/` and sign in using the **CloudLabs provided credentials**.

1. In the left navigation pane of the compliance portal, select **Content search**.

1. On the **Content search** page, select **New search**.

    ![](./media/content-search-page.png)

1. On the **Name and description** page, enter a name for the search, an optional description that helps identify the search. The name of the search must be unique in your organization. Select **Next**.

    ![](./media/content-search-name.png)

1. On the **Locations** page, choose the content locations that you want to search. You can search mailboxes, sites, and public folders. Select **Next**.

    ![](./media/content-search-locations.png)

    - **Exchange mailboxes:** Set the toggle to **On**. The option to search all Exchange mailboxes is automatically selected. If needed, select **Choose users, groups, or teams** to specify the mailboxes to search. Use the search box to find user mailboxes and distribution groups. You can also search the mailbox associated with a Microsoft Team (for channel messages), Microsoft 365 Group, and Viva Engage Group. All Microsoft Copilot for Microsoft 365 activity data (user prompts and Copilot responses) generated in supported Microsoft 365 apps and services is stored in custodian mailboxes.

    - **SharePoint sites:** Set the toggle to **On**. The option to search all SharePoint sites is automatically selected. Select **Choose sites** to specify SharePoint sites and OneDrive sites to search. Enter the URL for each site that you want to search. You can also add the URL for the SharePoint site for a Microsoft Team, Microsoft 365 Group, or Viva Engage Group.

    - **Exchange public folders:** Set the toggle to **On**. The option to search all Exchange public folders is automatically selected to search all public folders in your Exchange Online organization. You can't choose specific public folders to search. Leave the toggle switch off if you don't want search all public folders.

    - **Add App Content for On-Premises Users:** Keep this checkbox selected to search for Teams content for on-premises users. For example, if you search all Exchange mailboxes in the organization and this checkbox is selected, the cloud-based storage used to store Teams chat data for on-premises users will be included in the scope of the search.

1. On the **Conditions** page, enter a keyword query and add conditions to the search query if necessary.

    - Specify keywords, message properties such as sent and received dates, or document properties such as file names or the date that a document was last changed. You can use more complex queries that use a Boolean operator, such as **AND, OR, NOT**, and **NEAR**. If you leave the keyword box empty, all content located in the specified content locations is included in the search results.

    - Alternatively, you can select the **Show keyword list** checkbox and the enter a keyword in each row. If you do this, the keywords on each row are connected by a logical operator (c:s) that is similar in functionality to the OR operator in the search query that's created.

    - You can add search conditions by selecting **Add condition** to narrow a search and return a more refined set of results. Each condition adds a clause to the search query that is created and run when you start the search. A condition is logically connected to the keyword query (specified in the keyword box) by a logical operator (c:c) that is similar in functionality to the AND operator. That means that items have to satisfy both the keyword query and one or more conditions to be included in the results. This is how conditions help to narrow your results.

    For **content search**, because user prompts to **Copilot** and responses from **Copilot** are stored in a user's mailbox, they can be searched and retrieved when the user's mailbox is selected as the source for a search query. Select and retrieve this data from the source mailbox by selecting **Add condition > Type > Copilot interactions**.

    ![](./media/content-search-conditions.png)
    
    Select **Next**.

1. Review the search settings, and then select **Submit** to start the search.

    ![](./media/content-search-review.png)

1. After some time, your Content search will be created. Click on **Done** and return to the **Content search** page.

    ![](./media/content-search-created.png)

1. Select the newly created content search to see more details about it.

    ![](./media/content-search-details.png)

### Task 2: Exporting the report

After a **Content search** is successfully run, you can export the search report to your local computer. When you export a report, the report files are downloaded to a folder on your local computer that has the same name as the **Content Search**, but that's appended with **_ReportsOnly**. For example, if the Content Search is named **ContosoCase0815**, then the report is downloaded to a folder named **ContosoCase0815_ReportsOnly**.

Follow the given steps to download the content search report of your recently generated content search:

1. On the **Actions** menu at the bottom of the search flyout page of your Content search, select **Export report**.

    ![](./media/content-search-export-report.png)

1. Under **Output** options, choose one of the following options:

    - **All items, excluding ones that have unrecognized format, are encrypted, or weren't indexed for other reasons:** This option only exports information about indexed items.

    - **All items, including ones that have unrecognized format, are encrypted, or weren't indexed for other reasons:** This option exports information about indexed and unindexed items.

    - **Only items that have an unrecognized format, are encrypted, or weren't indexed for other reasons.** This option only exports information about unindexed items.

    Select **Option 2** to include all the items.

    ![](./media/content-search-report-options.png)

1. Select **Generate report**.

    The search reports are prepared for downloading, which means the report documents are uploaded to an Azure Storage location in the Microsoft cloud. This may take several minutes.

    ![](./media/content-search-generate-report.png)

1. Click **Ok** when prompted.

    ![](./media/content-search-report-ok.png)

### Task 3: Downloading the report

Now, you need to download the report from the Azure Storage area to your local computer.

1. On the **Content search** page in the compliance portal, select the **Exports** tab.

    ![](./media/content-search-export-tab.png)

1. Select the export job that you created earlier, ending with **_ReportsOnly**.

    ![](./media/content-search-report-created.png)

1. Under **Export Key** section, select **Copy to clipboard**. You will need this key to download the search report.

    ![](./media/content-search-report-key.png)

1. At the top of the flyout page, select **Download report**.

    ![](./media/content-search-download-report.png)

1. If you're prompted to install the **eDiscovery Export Tool**, select **Install**.

1. In the eDiscovery Export Tool, do the following:

    ![](./media/ediscoveryexporttool.png)

    - Paste the export key that you copied in the appropriate box.

    - Select **Browse** to specify the location where you want to download the search report files.

1. Select **Start** to download the search results to your computer.

1. Once the report gets downloaded, goto the location of the downloaded folder and open it.

    ![](./media/content-search-downloaded-report.png)

1. Open the **Results.csv** file and go through the report.

## Exercise 4.7: Reviewing Security and Compliance in Copilot Using eDiscovery (Read Only)

### Introduction

**Microsoft Copilot** is designed with security and compliance in mind. It does not store or share any of the user's data. It only uses the data or information that the user explicitly provides as input or context. It also respects the user's privacy and preferences, and does not collect any personal or sensitive information by itself.

Given below are the capabilities from Microsoft Purview which strengthen your data security and compliance for Microsoft Copilot for Microsoft 365:

### Using eDiscovery in M365 Copilot

**Microsoft Purview eDiscovery (Standard)** provides a basic eDiscovery tool that organizations can use to search and export content in Microsoft 365 and Office 365, including **M365 Copilot**. You can also use eDiscovery (Standard) to place an eDiscovery hold on content locations, such as Exchange mailboxes, SharePoint sites, OneDrive accounts, and Microsoft Teams.

When users within an organization leverage **Microsoft Copilot** to create prompt and response data, it may contain sensitive or confidential information, or evidence of intellectual property. Organizations need to have visibility and control over this data and be able to identify, preserve, collect, review and export it for legal, regulatory or data security investigation. That's why **Microsoft Purview eDiscovery** provides support for **Microsoft 365 Copilot interactions.**

**eDiscovery** has the ability to help with search, discovery, preservation, review and export of Copilot interactions in Microsoft 365 across Word, Excel, PowerPoint, Teams to name a few. It ensures these Copilot conversations are discoverable and actionable through the regular eDiscovery process. It also provides the ability to filter for specific Copilot interactions in the query building experience to make it easier to scope the searches.

>**Note:** You are not expected to perform the following steps. This information is provided solely to give you an understanding of the process of creating and using eDiscovery Cases in the Purview portal. Your access has been set to Global Reader, meaning you won't be able to make changes. These instructions are for viewing only, reflecting the read-only access granted in your environment.

### Task 1: Creating an eDiscovery Case

 Here are the steps to create a case on eDiscovery page in the **Microsoft Compliance portal**.

 1. Navigate to `https://compliance.microsoft.com/` and sign in using the **CloudLabs provided credentials**.

1. In the left navigation pane of the compliance portal, select **eDiscovery** and then, **Standard**.

    ![](./media/ediscovery-standard.png)

1. On the **eDiscovery (Standard)** page, select **Create a case**.

    ![](./media/ediscovery-create-case.png)

1. On the **New case** flyout page, give the case a name (required) and then type an optional description. The case name must be unique in your organization.

    ![](./media/ediscovery-case-name.png)

1. Select **Save** to create the case.

#### Optional Task: Creating an eDiscovery hold

After creating an eDiscovery case, you can place a hold (also called an **eDiscovery hold**) on the content locations of the people of interest in your investigation. Content locations include Exchange mailboxes, SharePoint sites, OneDrive accounts, and the mailboxes and sites associated with Microsoft Teams and Microsoft 365 Groups, along with **Microsoft 365 Copilot**. While this step is optional, creating an eDiscovery hold preserves content that may be relevant to the case during the investigation. When you create an **eDiscovery hold** you can preserve all content in specific content locations or you can create a query-based hold to preserve only the content that matches a hold query.

In addition to preserving content, another good reason to create **eDiscovery holds** is to quickly search the content locations on hold (instead of having to select each location to search) when you create and run searches in the next step. After you complete your investigation, you can release any hold that you created.

>**Note:** After you create an eDiscovery hold, it may take up to 24 hours for the hold to take effect.

To create an **eDiscovery hold** that's associated with a **eDiscovery (Standard) case**, follow the given steps:

1. Select the **eDiscovery case** that you created in the previous steps.

1. On the **Home** page for the case, select the **Hold** tab, and then select **Create**.

1. On the **Name your hold** wizard page, give the hold a name and add an optional description, and then select Next. The name of the hold must be unique in your organization.

1. On the **Choose locations** wizard page, choose the content locations that you want to place on hold. You can place mailboxes, sites, and public folders on hold.

    - **Exchange mailboxes:** Set the toggle to **On** and then select Choose users, groups, or teams to specify the mailboxes to place on hold. Use the search box to find user mailboxes and distribution groups (to place a hold on the mailboxes of group members) to place on hold. You can also place a hold on the associated mailbox for a Microsoft Team, Microsoft 365 group, and Viva Engage Group.

    - **SharePoint sites:** Set the toggle to **On** and then select Choose sites to specify SharePoint sites and OneDrive accounts to place on hold. Type the URL for each site that you want to place on hold. You can also add the URL for the SharePoint site for a Microsoft Team, Microsoft 365 group or a Yammer Group.

    - **Exchange public folders:** You can keep this toggle **Off**. You can't choose specific public folders to put on hold. Leave the toggle switch off if you don't want to put a hold on public folders.

    >**Note:** When adding **Exchange mailboxes** or **SharePoint sites** to a hold, you must explicitly add **at least one** content location to the hold. In other words, if you set the toggle to **On** for mailboxes or sites, you must select specific mailboxes or sites to add to the hold. **Otherwise**, the eDiscovery hold will be created but no mailboxes or sites will be added to the hold.

    Select **Next**.

1. To create a query-based hold using keywords or conditions, specifically for **Microsoft 365 Copilot** complete the following steps:

    - In the box under **Keywords**, type a query to preserve only the content that matches the query criteria. You can specify keywords, email message properties, or site properties, such as file names. You can also use more complex queries that use a Boolean operator, such as **AND**, **OR**, or **NOT**.

    - Select **Add condition** to add one or more conditions to narrow the query for the hold. Each condition adds a clause to the KQL search query that is created and run when you create the hold. For example, you can specify a date range so that email or site documents that were created within the date ranged are preserved. A condition is logically connected to the keyword query (specified in the **Keywords** box) and other conditions by the **AND** operator. That means items have to satisfy both the keyword query and the condition to be preserved.

    For creating a hold, because user prompts to **Copilot** and responses from **Copilot** are stored in a user's mailbox, they can be searched and retrieved when the user's mailbox is selected as the source for a search query. Select and retrieve this data from the source mailbox by selecting **Add condition > Type > Copilot interactions**.

    Select **Next**.

1. Review your settings, and then select **Submit**.

1. After some time, your **eDsiscovery hold** will be created. Click on **Done** and return to the **Hold** page.

1. Select your newly created hold and check it got created properly.

### Task 2: Creating a search in eDiscovery

After a **Microsoft Purview eDiscovery (Standard)** case is created, you can create and run one or more searches for content relevant to the case. Searches associated with a **eDiscovery (Standard)** case aren't listed on the Content search page in the **Microsoft Purview compliance portal**. These searches are listed on the **Searches** page of the **eDiscovery (Standard)** case the searches are associated with. This also means that searches associated with a case can only be accessed by case members.

To create a **eDiscovery (Standard)** search, follow the given steps:

1. Select the **eDiscovery case** that you created in the previous steps.

1. On the **Home** page for the case, select the **Searches** tab, and then select **New search**.

    ![](./media/ediscovery-search-create.png)

1. In the **New search** wizard, type a name for the search, and an optional description that helps identify the search. The name of the search must be unique in your organization. Select **Next**.

    ![](./media/ediscovery-search-name.png)

1. On the **Locations** page, choose the content locations that you want to search. You can search mailboxes, sites, and public folders.

    ![](./media/ediscovery-search-locations.png)

    - **Exchange mailboxes:** Set the toggle to **On**. The option to put all Exchange mailboxes on hold is automatically selected. If you need to specify specific mailboxes to place on hold, **Choose users, groups, or teams**. Use the search box to find user mailboxes and distribution groups (to place a hold on the mailboxes of group members) to place on hold. You can also search the mailbox associated with a Microsoft Team (for channel messages), Office 365 Group, and Viva Engage Group. All Copilot activity data (user prompts and Copilot responses) generated in supported Microsoft 365 apps and services is stored in custodian mailboxes.

    - **SharePoint sites:** Set the toggle to **On**. The option to put all SharePoint sites on hold is automatically selected. If you need to specify specific SharePoint sites and OneDrive accounts to place on hold,  **Choose sites**. Type the URL for each site that you want to place on hold. You can also add the URL for the SharePoint site for a Microsoft Team, Office 365 Group, or Viva Engage Group.

    - **Exchange public folders:** Set the toggle to **On** to put all public folders in your Exchange Online organization on hold. You can't choose specific public folders to put on hold. Leave the toggle switch off if you don't want to put a hold on public folders.

    - **Add App Content for On-Premises Users:** Keep this checkbox selected to search for Teams content for on-premises users. For example, if you search all Exchange mailboxes in the organization and this checkbox is selected, the cloud-based storage used to store Teams chat data for on-premises users will be included in the scope of the search.

    >**Note:** Select the **Locations on hold** option ONLY if you have previously created any hold, to search all the content locations that have been placed on hold. If the case contains multiple eDiscovery holds, the content locations from all holds are searched when you select this option. Additionally, if a content location was placed on a query-based hold, only the items that match the hold query are searched when you run the search. In other words, only the content that matches both the hold criteria and the search criteria is returned with the search results.

    Select **Next**.

1. On the **Conditions** page, enter a keyword query and add conditions to the search query if necessary.

    - Specify keywords, message properties such as sent and received dates, or document properties such as file names or the date that a document was last changed. You can use more complex queries that use a Boolean operator, such as **AND, OR, NOT**, and **NEAR**. If you leave the keyword box empty, all content located in the specified content locations is included in the search results.

    - Alternatively, you can select the **Show keyword list** checkbox and the enter a keyword in each row. If you do this, the keywords on each row are connected by a logical operator (c:s) that is similar in functionality to the OR operator in the search query that's created.

    - You can add search conditions by selecting **Add condition** to narrow a search and return a more refined set of results. Each condition adds a clause to the search query that is created and run when you start the search. A condition is logically connected to the keyword query (specified in the keyword box) by a logical operator (c:c) that is similar in functionality to the AND operator. That means that items have to satisfy both the keyword query and one or more conditions to be included in the results. This is how conditions help to narrow your results.

    For **content search**, because user prompts to **Copilot** and responses from **Copilot** are stored in a user's mailbox, they can be searched and retrieved when the user's mailbox is selected as the source for a search query. Select and retrieve this data from the source mailbox by selecting **Add condition > Type > Copilot interactions**.

    ![](./media/content-search-conditions.png)
    
    Select **Next**.

1. Review the search settings, and then select **Submit** to start the search.

    ![](./media/ediscovery-search-review.png)

1. After some time, your Content search will be created. Click on **Done** and return to the **Content search** page.

1. Select the newly created content search to see more details about it.

    ![](./media/ediscovery-search-details.png)

### Task 3: Exporting the report

After a **Content search** is successfully run, you can export the search report to your local computer. When you export a report, the report files are downloaded to a folder on your local computer that has the same name as the **Content Search**, but that's appended with **_ReportsOnly**. For example, if the Content Search is named **ContosoCase0815**, then the report is downloaded to a folder named **ContosoCase0815_ReportsOnly**.

Follow the given steps to download the content search report of your recently generated content search:

1. On the **Actions** menu at the bottom of the search flyout page of your Content search, select **Export report**.

    ![](./media/content-search-export-report.png)

1. Under **Output** options, choose one of the following options:

    ![](./media/content-search-report-options.png)

    - **All items, excluding ones that have unrecognized format, are encrypted, or weren't indexed for other reasons:** This option only exports information about indexed items.

    - **All items, including ones that have unrecognized format, are encrypted, or weren't indexed for other reasons:** This option exports information about indexed and unindexed items.

    - **Only items that have an unrecognized format, are encrypted, or weren't indexed for other reasons.** This option only exports information about unindexed items.

    Select **Option 2** to include all the items.

1. Select **Generate report**.

    ![](./media/content-search-generate-report.png)

    The search reports are prepared for downloading, which means the report documents are uploaded to an Azure Storage location in the Microsoft cloud. This may take several minutes.

1. Click **Ok** when prompted.

    ![](./media/content-search-report-ok.png)

### Task 4: Downloading the report

Now, you need to download the report from the Azure Storage area to your local computer.

1. On the **eDiscovery** page in the compliance portal, select your case, and select the **Exports** tab.

1. Select the export job that you created earlier, ending with **_ReportsOnly**.

    ![](./media/ediscovery-report.png)

1. Under **Export Key** section, select **Copy to clipboard**. You will need this key to download the search report.

    ![](./media/content-search-report-key.png)

1. At the top of the flyout page, select **Download report**.

    ![](./media/content-search-download-report.png)

1. If you're prompted to install the **eDiscovery Export Tool**, select **Install**.

1. In the eDiscovery Export Tool, do the following:

    ![](./media/ediscoveryexporttool.png)

    - Paste the export key that you copied in the appropriate box.

    - Select **Browse** to specify the location where you want to download the search report files.

1. Select **Start** to download the search results to your computer.

1. Once the report gets downloaded, goto the location of the downloaded folder and open it.

    ![](./media/content-search-downloaded-report.png)

1. Open the **Results.csv** file and go through the report.

## Exercise 4.8: Reviewing Security and Compliance in Copilot using Retention Policies (Read Only)

### Introduction

**Microsoft Copilot** is designed with security and compliance in mind. It does not store or share any of the user's data. It only uses the data or information that the user explicitly provides as input or context. It also respects the user's privacy and preferences, and does not collect any personal or sensitive information by itself.

Given below are the capabilities from Microsoft Purview which strengthen your data security and compliance for Microsoft Copilot for Microsoft 365:

### Retention and Deletion in Microsoft 365 Copilot

You can use a retention policy to retain data from messages in **Microsoft Copilot for Microsoft 365**, and delete those messages. Behind the scenes, Exchange mailboxes are used to store data copied from these messages. Data from **Copilot** messages is stored in a hidden folder in the mailbox of the user who runs **Copilot**. This hidden folder isn't designed to be directly accessible to users or administrators, but instead, store data that compliance administrators can search with **eDiscovery tools**.

The Exchange mailbox for retaining **Microsoft Copilot for Microsoft 365** messages has the RecipientTypeDetails attribute of **UserMailbox**, which also stores message data for **Teams** private channels and cloud-based **Teams** users. The copy is retained in a hidden folder named **SubstrateHolds** as a subfolder in the Exchange **Recoverable Items** folder.

After a retention policy is configured for **Microsoft Copilot for Microsoft 365** interactions, a timer job from the Exchange service periodically evaluates items in the hidden mailbox folder where these messages are stored. The timer job typically takes **1-7 days** to run. When these items have expired their retention period, they're moved to the SubstrateHolds folder—another hidden folder that's in every user mailbox to store "soft-deleted" items before they're permanently deleted. After a **retention policy** is configured for **Microsoft Copilot for Microsoft 365**, the paths the content takes depend on whether the retention policy is to retain and then delete, to retain only, or delete only.

The following diagram represents the flow in details:

![](./media/copilotretentionlifecycle.png)

For the two paths in the diagram:

1. **If messages are removed from Copilot**, the message is moved to the SubstrateHolds folder where it remains for at least 1 day. When the retention period expires, the message is permanently deleted the next time the timer job runs (typically between 1-7 days).

1. **If messages remain in Copilot** after the retention period expires, the message is copied to the SubstrateHolds folder. This action typically takes between 1-7 days from the expiry date. When the message is in the SubstrateHolds folder, it's stored there for at least 1 day, and then the message is permanently deleted the next time the timer job runs (typically between 1-7 days).

>**Note:** Messages stored in mailboxes, including the hidden folders, are searchable by **eDiscovery tools**. Until messages are permanently deleted from the SubstrateHolds folder, they remain searchable by **eDiscovery tools**.

When the retention period expires and copies a message to the SubstrateHolds folder, a delete operation is communicated to the backend service for Copilot, that then relays the same operation to the user app with Copilot. Delays in this communication or caching can explain why, for a short period of time, users continue to see these messages in Copilot.

#### Content paths for retain-only retention policy

1. **If messages are removed from Copilot** the message is moved to the SubstrateHolds folder after the retention period expires. This action typically takes between 1-7 days from the expiry date. If the retention policy is configured to retain forever, the item remains there. If the retention policy has an end date for the retention period and it expires, the message is permanently deleted the next time the timer job runs (typically between 1-7 days).

1. **If messages remain in Copilot** after the retention period expires, nothing happens before and after the retention period; the message remains in its original location.

#### Content paths for delete-only retention policy

1. **If messages are removed from Copilot** during the retention period, the message is moved to the SubstrateHolds folder. The message is stored in the SubstrateHolds folder for at least 1 day and permanently deleted the next time the timer job runs (typically between 1-7 days).

1. **If messages remain in Copilot** after the retention period expires, the message is copied to the SubstrateHolds folder. This action typically takes between 1-7 days from the expiry date. The message is retained there for at least 1 day and then permanently deleted the next time the timer job runs (typically between 1-7 days).

### Task 1: Creating and Configuring Retenetion Policies

>**Note:** You are not expected to perform the following steps. This information is provided solely to give you an understanding of the process of creating and using Retention Policies in the Purview portal.  Your access has been set to Global Reader, meaning you won't be able to make changes. These instructions are for viewing only, reflecting the read-only access granted in your environment.

A **retention policy** lets you manage the data for your organization by deciding proactively whether to retain content, delete content, or retain and then delete the content very efficiently by assigning the same retention settings at the container level to be automatically inherited by content in that container. For example, retention policies for the location **Teams chats and Copilot interactions** include user prompts to **Microsoft Copilot for Microsoft 365**, and the Copilot responses to users. These messages can be retained and deleted for compliance reasons.

To create a retention policy to for all the interactions with **Microsoft 365 Copilot**, follow the given steps:

1. Navigate to `https://compliance.microsoft.com/` and sign in using the **CloudLabs provided credentials**.

1. In the left navigation pane of the compliance portal, select **Data lifecycle management** and then, **Microsoft 365**.

    ![](./media/retention-overview.png)

1. Under **Retention policies** tab, select **New retention policy** to start creating a new retention policy.

    ![](./media/retention-policy-new.png)

1. Provide the name and description of your retention policy in the appropriate boxes, and select **Next**.

    ![](./media/retention-policy-name.png)

1. On the **Administrative Units** page, click **Next** by keeping the default of **Full directory**.

1. For the **Choose the type of retention policy to create** page, select **Static** and then, **Next** to select the locations (**Microsoft 365 Copilot**) manually, for which you want the retention policy to be applied.

    ![](./media/retention-policy-static.png)

    Deselect all the locations and select **Teams chats and Copilot interactions** ONLY to apply the policy on **Copilot for Microsoft 365**, and its all user prompts to Copilot and all Copilot responses. Select **Next**.

    ![](./media/retention-policy-locations.png)

    >**Note:** By default, all teams and all users are selected, but you can refine this by selecting the **Choose** and **Exclude** options.

1. For **Decide if you want to retain content, delete it, or both** page, specify the configuration options for retaining and deleting content. You can also provide your custom period by choosing **Custom** from the drop-down menu and specifying the period after that.

    ![](./media/retention-policy-configurations.png)

    You can create a retention policy that just retains content without deleting, retains and then deletes after a specified period of time, or just deletes content after a specified period of time. Select **Next**.

1. On the **Review and Finish** page, review your settings and select **Submit**. Select **Done** when required.

    ![](./media/retention-policy-review.png)

1. Select your recently created policy to see it in details and also check its status.

    ![](./media/retention-policy-created.png)

    >**Note:** When you create and submit a retention policy, it can take up to seven days for the retention policy to be applied.

![](./media/retention-policy-timings.png)

If a user leaves your organization and their **Microsoft 365 account** is deleted, their **Copilot** messages that are subject to retention are stored in an inactive mailbox. The Copilot messages remain subject to any retention policy that was placed on the user before their mailbox was made inactive, and the contents are available to an **eDiscovery search**.

### **Conclusion**

In conclusion, this lab series has provided a comprehensive understanding of **Microsoft Copilot for Microsoft 365**, encompassing its architecture, capabilities, and administrative features. You explored how Copilot integrates AI to enhance productivity through intelligent suggestions and tailored responses, grounded in data from Microsoft Graph and external sources.

You learned how to **set up and manage Copilot licenses** and configure services via the **Microsoft 365 Admin Center**, including enabling access to public web content, and managing features across productivity apps like Teams, SharePoint, and Power Platform. Advanced administrative skills, such as configuring **Graph Connectors**, **sensitivity labels**, **customer keys**, and **communication compliance policies**, were developed to strengthen security, ensure compliance, and safeguard organizational data.

Additionally, you gained insights into Microsoft Purview capabilities such as **auditing**, **eDiscovery**, **content search**, and **retention policies**, all of which empower organizations to meet legal, regulatory, and internal governance requirements while using Copilot. The integration of these compliance features with Copilot ensures that organizations can maintain transparency, control, and accountability across their Microsoft 365 ecosystem.

Overall, this lab series has equipped you with the skills needed to effectively deploy, configure, manage, and secure **Microsoft Copilot**, enabling you to unlock its full potential while maintaining a robust and compliant digital workplace.

## **Congratulations! you have successfully completed Lab**