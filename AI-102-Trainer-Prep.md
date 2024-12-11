# AI-102 Trainer Preparation Guide

This document is intended to help trainers prepare to teach content and lab resources related to the Microsoft Azure AI Engineer AI-102 curriculum. The document presents information relative to preparing to teach the content and to prepare to take the certification exam, Microsoft Certified: Azure AI Engineer Associate.

## Major Focus Areas

- Plan and manage an Azure AI solution
- Implement decision support solutions
- Implement computer vision solutions
- Implement natural language processing solutions
- Implement knowledge mining and document intelligence solutions
- Implement generative AI solutions

## Role Definition for Azure AI Engineer

The Azure AI Engineer is has the responsibility to build, manage, and deploy Azure AI solutions leveraging the Microsoft Azure Cognitive Services and Azure Applied AI services. They participate in all phases of AI solutions projects from defining requirements, to the design and development, deployment, maintenance, performance tuning, and monitoring of Azure AI solutions. They will typically collaborate with solution architects, data scientists, data engineers, IoT specialists, and AI developers to build complete end-to-end AI solutions.

## Instructor Prerequisite Knowledge

To effectively teach content on AI-102, an instructor must meet this prereqeuisite knowledge:

- Knowledge of Microsoft Azure and ability to navigate the Azure portal
- Knowledge of either C# or Python
- Familiarity with JSON and REST programming semantics
- Experience with Azure Cognitive Services, Azure Bot Service, and Azure Cognitive Search

## Course Timing

| Day | Estimated Time | Classroom activity|
|-----|----------------|-------------------|
|1 | 20 minutes | Course Introduction slide deck (time may vary due to the number of student introductions in a given course)|
| | 130 total minutes | 1: Introduction to AI and Azure AI Services |
| | 30 minutes | Lab: Get Started with Azure AI Services |
| | 40 minutes | Demo: Secure AI Services |
| | | Demo: Monitor AI Services |
| | 50 minutes | Lecture |
| | 220 total minutes | 2: Develop computer vision solutions with Azure AI Vision |
| | 120 minutes | Lab: Analyze Images with Azure AI Vision|
| | | Lab: Read Text in Images |
| | | Lab: Classify images with a custom Azure AI Vision model|
| | 40 minutes | Demo: Detect faces |
| | | Demo: Analyze video |
| | 60 minutes | Lecture |
| 2 | -- minutes | Day 1 review Finish up anything not completed |
| | 270 total minutes | 3: Develop natural language processing solutions|
| | 140 minutes | Lab: Analyze text |
| | | Lab: Create question answering solution |
| | | Lab: Create a language understanding model |
| | 40 minutes | Demo: Custom named entity extraction |
| | | Demo: Translate text |
| | 90 minutes | Lecture |
| 3 | -- minutes | Day 2 review Finish up anything not completed|
| | 210 total minutes | 4: Develop Generative AI Solutions with Azure OpenAI Service |
| | 120 minutes | Lab: Integrate Azure OpenAI into your app |
| | | Lab: Utilize prompt engineering in your app |
| | | Lab: Use your own data with Azure OpenAI |
| | 20 minutes | Demo: Get started with Azure OpenAI |
| | 70 minutes | Lecture|
| 4 | -- minutes | Day 3 review Finish up anything not completed |
| | 120 total minutes | 5: Create knowledge mining solutions Develop solutions with Azure AI Document Intelligence|
| | 20 minutes | Demo: Create an Azure Cognitive Search solution |
| | 45 minutes | Lab: Create a Custom Skill for Azure AI Search |
| | 45 minutes | Lecture |
| | 120 total minutes | 6: Develop solutions with Azure AI Document Intelligence|
| | 30 minutes | Demo: Prebuilt models |
| | 45 minutes | Lab: Custom document intelligence models|
| | 45 minutes | Lecture|

## Resources for Instructor Preparation

The following list of resources are recommended for an instructor looking to teach content on the Azure AI-102 content.

### Azure Administrator Training

While AI-102 does not cover Azure administration tasks, the instructor needs to be able to navigate the Azure portal, create services and resources in the portal, and configure those resources. Familiarity with PowerShell or Bash and Azure Resource Manager (ARM) templates are also recommended to help demonstrate automation of provisioning of services.

Students will need guidance on navigatin the portal and creating and configuring services. Instructors can gain the necessary experience by completing the followign training.

- [Microsoft Azure Fundamentals](https://learn.microsoft.com/en-us/training/courses/az-900t00)
- [Microsoft Azure Administrator](https://learn.microsoft.com/en-us/training/courses/az-104t00)
- [PowerShell Training](https://learn.microsoft.com/en-us/training/paths/powershell/)

### Programming Language Training

Accessing the services and resources for AI-102 requires an understanding of REST API and SDK access to these services. The most commonly used languages when accessing the services are C# and Python. While not every instructor will know multiple programming languages, it is imperative that they instructor be very familiar with at least one of these two languages and be able to assist students in understanding how to effectively use them to access the AI services.

Instructors will also need to know how to read JSON files to be able to help students understand how to use the REST APIs correctly. REST APIs require uploading of JSON formatted input and will return results in JSON format.

The following are recommended resources for learning the above programming languages.

- [C# Training](https://dotnet.microsoft.com/en-us/learn/csharp)
- [Python](https://www.udemy.com/course/complete-python-bootcamp/?utm_source=bing&utm_medium=udemyads&utm_campaign=BG-Search_Keyword_Alpha_Prof_la.EN_cc.US&campaigntype=Search&portfolio=Bing-USA&language=EN&product=Course&test=&audience=Keyword&topic=Python&priority=Alpha&utm_content=deal4584&utm_term=_._ag_1324913889653675_._ad__._kw_free+python+course_._de_c_._dm__._pl__._ti_kwd-82808213013652%3Aloc-190_._li_111485_._pd__._&matchtype=e&msclkid=0346a014e1421114b0bfc743868e7057&couponCode=NVD20PMUS)
- [JSON](https://www.w3schools.com/js/js_json_intro.asp)

### Pre-class Activities

#### License Requirements

Particpants will require an Azure account (Free trial or paid). Sign up for a [free account](https://azure.microsoft.com/en-in/pricing/purchase-options/azure-account). The instructor must have the necessary Azure account and credits or billing information to create the necessary services. The instructor should also ensure they have requested, and been granted, access to Azure OpenAI.

#### Environment Setup

There are various ways to enable students to perform hands-on exercises. Lab hosting partners such as [Skillable](https://www.skillable.com/virtual-it-labs-skills-validation-hands-on-learning/?nab=1) and [GoDeploy](https://godeploy.com/) offer lab environments for a fee. These lab environments do not require students to have their own accounts. The account information is included in the lab cost. The instructor must ensure that a lab environment is provisioned and ready for students on day one.

Many hands-on exercises can be completed without a lab hosting environment. This will require the student to have an Azure account and access to the Azure portal to perform the tasks associated with the hands-on exercises. For an environment that does not use a hosted lab, the instructor must provide participants with environment prerequisites for local computers such as Azure CLI, Visual Studio Code, and necessary SDKs if a lab environment is not being used.


#### Pre-reading Materials

- Share Azure [AI documentation links](https://learn.microsoft.com/en-us/azure/ai-services/)
- Distribute a glossary of key AI and Azure terms
- Provide link to the [AI-102 study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-102)

### In-class Activities

#### Core Concepts

- Use [Microsoft Learn modules for AI-102](https://learn.microsoft.com/en-us/training/courses/ai-102t00) as a base curriculum
- Emphasize hands-on demos for each Azure Cognitive Service
- Utilize Azure AI documentation for deep dives into specific services

#### Lab Guidance

- Follow Microsoft Official Courseware (MOC) for AI-102 if available
- Implement pair programming for complex labs
- If using a lab environment, walk participants through the sign in, starting, and using the lab environment for the first lab at a minimum

#### Best Practices

- Demonstrations should be clear and rehearsed. Instructor must know the demonstrations and be able to perform them without reading from a set of instructions during the demo
- Pause and ask participants if they have questions
- Create and use polls to gauge participants’ understanding of theory

#### Tips and Tricks

- Stick to the demonstration, content, and lab material to ensure a consistent delivery and that the session conforms to Microsoft standards
- Research common questions for Azure AI services to have answers readily available.

### Azure AI-102 Specific Preparation Materials

The following learning paths are specifically oriented toward the Azure AI Services and the AI Engineer role. Completing these learning paths will help prepare the instructor in the actualy content that is covered in the AI-102 exam and training. The instructor should complete all the modules and hands-on exercises to gain experience with the technologies used in the course content.

- [Prepare to Teach AI-102](https://learn.microsoft.com/en-us/training/paths/prepare-teach-ai-102-microsoft-design-implement-azure/)
- [AI-102 Training](https://learn.microsoft.com/en-us/training/courses/ai-102t00)

While completing these learning paths, the instructor should take notes for areas they are not confident with and use the additional documentation and examples found on the Microsoft documentation sites found at the following URL.

- [Azure AI Services Documentation](https://learn.microsoft.com/en-us/azure/ai-services/)