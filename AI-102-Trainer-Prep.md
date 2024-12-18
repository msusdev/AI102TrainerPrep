# AI-102 Trainer Preparation Guide

## Introduction

This guide is designed to help you prepare the Microsoft Azure AI Engineer AI-102 curriculum and its associated labs. It provides essential information you need to effectively deliver the content and assist learners in preparing for the Microsoft Certified: Azure AI Engineer Associate certification exam.

## Section 1: Trainer Foundations

This section focuses on components you must internalize and accomplish to be prepared for delivering the training.

### Major focus areas

The training will cover the following focus areas:

- Plan and manage an Azure AI solution
- Implement decision-support solutions
- Implement computer vision solutions
- Implement natural language processing solutions
- Implement knowledge mining and document intelligence solutions
- Implement generative AI solutions

### Audience profile

As an Azure AI Engineer, you will build, manage, and deploy Azure AI solutions leveraging the Microsoft Azure Cognitive Services and Azure Applied AI services. Your role involves participating in all phases of AI solutions projects from requirements gathering through design, development, deployment, maintenance, performance optimization, and continuous monitoring of Azure AI solutions. You will typically collaborate with solution architects, data scientists, data engineers, IoT specialists, and AI developers to build complete, end-to-end AI solutions.

### Instructor prerequisite knowledge

To effectively teach AI-102 content, you must have the following prerequisite knowledge:

- Proficiency with Microsoft Azure and navigating the Azure portal
- Knowledge of either C# or Python
- Familiarity with JSON and REST programming semantics
- Experience with Azure Cognitive Services, Azure Bot Service, and Azure Cognitive Search

### Resources for instructor preparation

You can leverage the following resources to prepare for teaching the Azure AI-102 certification content.

#### Azure administrator training

While AI-102 does not cover Azure administration tasks, you must be able to navigate the Azure portal, create services and resources in the portal, and configure those resources. Familiarity with PowerShell or Bash and Azure Resource Manager (ARM) templates is also useful to help demonstrate the automation of provisioning of services.

To guide participants on navigating the portal and creating and configuring services, you can build your expertise using the following targeted training resources:

- [Microsoft Azure Fundamentals](https://learn.microsoft.com/en-us/training/courses/az-900t00)
- [Microsoft Azure Administrator](https://learn.microsoft.com/en-us/training/courses/az-104t00)
- [PowerShell Training](https://learn.microsoft.com/en-us/training/paths/powershell/)

#### Programming language training

Accessing the services and resources for AI-102 requires an understanding of REST API and SDK access to these services. The most commonly used languages when accessing the services are C# and Python. While the knowledge of both languages is not required, it is imperative that you be very familiar with at least one of these two languages and be able to guide participants in its application.

As REST APIs require uploading of JSON formatted input and also return results in JSON format, you must know how to read JSON files to be able to help participants understand how to use the REST APIs correctly. 

The following resources can be used to learn the programming languages:

- [C# Training](https://dotnet.microsoft.com/en-us/learn/csharp)
- [Python](https://www.udemy.com/course/complete-python-bootcamp/?utm_source=bing&utm_medium=udemyads&utm_campaign=BG-Search_Keyword_Alpha_Prof_la.EN_cc.US&campaigntype=Search&portfolio=Bing-USA&language=EN&product=Course&test=&audience=Keyword&topic=Python&priority=Alpha&utm_content=deal4584&utm_term=_._ag_1324913889653675_._ad__._kw_free+python+course_._de_c_._dm__._pl__._ti_kwd-82808213013652%3Aloc-190_._li_111485_._pd__._&matchtype=e&msclkid=0346a014e1421114b0bfc743868e7057&couponCode=NVD20PMUS)
- [JSON](https://www.w3schools.com/js/js_json_intro.asp)

#### Azure AI-102 specific preparation materials

To effectively prepare for teaching AI-102, explore key resources that build your understanding of Azure AI Services and the AI Engineer role. The following materials will help you strengthen your familiarity with the course content and technologies:

- [Prepare to Teach AI-102](https://learn.microsoft.com/en-us/training/paths/prepare-teach-ai-102-microsoft-design-implement-azure/) Access targeted training and resources designed to enhance your teaching readiness for AI-10
  
- [AI-102 Training](https://learn.microsoft.com/en-us/training/courses/ai-102t00) Dive into specialized training sessions and materials to deepen your understanding of the curriculum and its delivery

While completing these learning paths, you should take notes for areas you are not confident with and use the additional documentation and examples found on the Microsoft documentation sites at the following URL:

- [Azure AI Services Documentation](https://learn.microsoft.com/en-us/azure/ai-services/)

##### Required materials to teach this course

Microsoft PowerPoint files and change log are available to Microsoft Certified Trainers and can be accessed by signing into the [MCT technology hub](https://techcommunity.microsoft.com/) and search for the MCT files download post.

The lab instructions and the lab files are also available for download from the Microsoft Learn GitHub repos. The links are provided in the Lab Trainer Prep Guide.

## Section 2: Training Session Execution

This section outlines the actions and steps you need to perform before, during, and after each training session.

### Pre-class activities

#### License requirements

Participants will require an Azure account (Free trial or paid). Sign up for a [free account](https://azure.microsoft.com/en-in/pricing/purchase-options/azure-account). You must have the necessary Azure account and credits or billing information to create the necessary services. You must also ensure they have requested, and been granted, access to Azure OpenAI.

#### Environment setup

There are various ways to enable participants to perform hands-on exercises. Lab hosting partners such as [Skillable](https://www.skillable.com/virtual-it-labs-skills-validation-hands-on-learning/?nab=1) and [GoDeploy](https://godeploy.com/) offer lab environments for a fee. These lab environments do not require participants to have their own accounts. The account information is included in the lab cost. You must ensure that a lab environment is provisioned and ready for participants on Day One.

Many hands-on exercises can be completed without a lab hosting environment. This will require the participant to have an Azure account and access to the Azure portal to perform the tasks associated with the hands-on exercises. For an environment that does not use a hosted lab, you must provide participants with environment prerequisites for local computers such as Azure CLI, Visual Studio Code, and necessary SDKs if a lab environment is not being used.

#### Pre-reading materials

Share the following materials with participants before the session to help them build a foundational understanding of Azure AI concepts and prepare for the training:

- [Azure AI Services Reference](https://learn.microsoft.com/en-us/azure/ai-services/)
- [Glossary of AI Terms](https://fastbots.ai/ai-glossary)
- [AI-102 study guide](https://learn.microsoft.com/en-us/credentials/certifications/resources/study-guides/ai-102)

### In-class activities

#### Course timing

The following table outlines the course timing for the training sessions, providing a detailed schedule to help participants stay organized and prepared throughout the program:

| Day | Estimated time | Classroom activity|
|-----|----------------|-------------------|
|1 | 20 minutes | Course introduction and participant introductions (time may vary due to the number of participant introductions in a given course)|
| | 130 total minutes | 1: Introduction to AI and Azure AI Services |
| | 30 minutes | Lab: Get started with Azure AI services |
| | 20 minutes | Demo: Secure AI services |
| | 20 minutes | Demo: Monitor AI services |
| | 50 minutes | Lecture |
| | 220 total minutes | 2: Develop computer vision solutions with Azure AI Vision |
| | 40 minutes | Lab: Analyze images with Azure AI Vision|
| | 40 minutes | Lab: Read text in images |
| | 40 minutes | Lab: Classify images with a custom Azure AI Vision model|
| | 20 minutes | Demo: Detect faces |
| | 20 minutes | Demo: Analyze video |
| | 60 minutes | Lecture |
| 2 | | Day 1 review Finish up anything not completed |
| | 270 total minutes | 3: Develop natural language processing solutions|
| | 20 minutes | Lab: Analyze text |
| | 40 minutes | Lab: Create question answering solution |
| | 50 minutes | Lab: Create a language understanding model |
| | 20 minutes | Demo: Custom named entity extraction |
| | 20 minutes | Demo: Translate text |
| | 90 minutes | Lecture |
| 3 |  | Day 2 review Finish up anything not completed|
| | 210 total minutes | 4: Develop Generative AI solutions with Azure OpenAI Service |
| | 40 minutes | Lab: Integrate Azure OpenAI into your app |
| | 40 minutes | Lab: Utilize prompt engineering in your app |
| | 40 minutes | Lab: Use your own data with Azure OpenAI |
| | 20 minutes | Demo: Get started with Azure OpenAI |
| | 70 minutes | Lecture|
| 4 |  | Day 3 review Finish up anything not completed |
| | 120 total minutes | 5: Create knowledge mining solutions Develop solutions with Azure AI Document Intelligence|
| | 20 minutes | Demo: Create an Azure Cognitive Search solution |
| | 45 minutes | Lab: Create a custom skill for Azure AI Search |
| | 45 minutes | Lecture |
| | 120 total minutes | 6: Develop solutions with Azure AI Document Intelligence|
| | 30 minutes | Demo: Prebuilt models |
| | 45 minutes | Lab: Custom document intelligence models|
| | 45 minutes | Lecture|

#### Core concepts

Use the following guidelines to focus on the foundational elements of the course and enhance participant understanding of core AI-102 concepts:

- Use [Microsoft Learn modules for AI-102](https://learn.microsoft.com/en-us/training/courses/ai-102t00) as a base curriculum.
- Emphasize hands-on demos for each Azure Cognitive Service.
- Utilize Azure AI documentation for deep dives into specific services.

#### Lab guidance

Follow these recommendations to guide participants effectively through lab sessions:

- Follow Microsoft Official Courseware (MOC) for AI-102, if available.
- Implement pair programming for complex labs.
- If using a lab environment, walk participants through the process of signing in, setting up, and navigating the lab environment, at least for the first lab session.

#### Best practices

Apply these best practices to deliver engaging, efficient, and effective training sessions:

- Begin with topic overviews and objectives.
- Demonstrations should be clear and rehearsed. You must be thoroughly familiar with the demonstrations and be able to perform them without relying on written instructions during the demo.
- Pause and ask participants if they have questions.
- Create and use polls to gauge participants’ understanding of theoretical concepts.
- Dedicate time for lab guidance and troubleshooting.

#### Tips and tricks

Leverage these tips and tricks to enhance delivery and ensure participants gain the most from the training:

- Stick to the demonstration, content, and lab materials to ensure a consistent delivery and alignment to Microsoft standards.
- Research frequently asked questions for Azure AI services to have answers readily available.
- Summarize key learnings at regular intervals.

### Post-class activities

#### Continuous learning

Encourage participants to expand their knowledge and skills after the session by utilizing the following resources:

- Provide a curated list of additional Azure AI documentation from the trainer preparation section above.
- Provide a curated list of additional hands-on activities. Point participants to the [MS Learn eLearning courses](https://learn.microsoft.com/en-us/training/courses/ai-102t00) for additional hands-on exercises.
- Share upcoming [Azure AI webinars and events](https://azure.microsoft.com/en-in/resources/events/).

#### Exam preparation

Support participants in preparing for the certification exam with these targeted resources and strategies:

- Point to [official preparation materials](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-engineer/?practice-assessment-type=certification).
- Give an overview of the Microsoft certification preparation pages and the resources provided there.
- Demonstrate the use of the [Microsoft practice test](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-engineer/practice/assessment?assessment-type=practice&assessmentId=61&practice-assessment-type=certification) on the exam landing page.
- Showcase the [exam sandbox](https://go.microsoft.com/fwlink/?linkid=2226877) to help participants understand how a Microsoft exam is constructed.
- Review the [exam study guide](https://aka.ms/ai102-StudyGuide) and instruct participants on how to use it effectively for exam preparation.

#### Real-world application

Inspire participants to extend their learning through practical projects and active community involvement:

- Suggest AI hackathon ideas using Azure services.
- Encourage participation in [Azure AI community forums](https://techcommunity.microsoft.com/category/Azure).
