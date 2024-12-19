# AI-102 Lab Trainer Prep Guide

This guide is intended to help you prepare to deliver the labs associated with the AI-102 curriculum. The labs recommended here are those included as part of the AI-102 official training. You must ensure the participants have completed the labs and are familiar with the content prior to delivering the labs. This preparation is essential to ensuring a good experience for the participants. You need to anticipate common problems and be able to assist the participants with any issues or errors arising from the lab steps, changes in the Azure UI, and any hosted lab environments.

## Pre-class activities

### License requirements

Participants will require an Azure account (Free trial or paid). Sign up for a [free account](https://azure.microsoft.com/en-in/pricing/purchase-options/azure-account). You must have the necessary Azure account and credits or billing information to create the necessary services. You must also ensure the participants have requested, and been granted, access to Azure OpenAI.

### Environment setup

There are various ways to enable participants to perform hands-on exercises. Lab hosting partners such as [Skillable](https://www.skillable.com/virtual-it-labs-skills-validation-hands-on-learning/?nab=1) and [GoDeploy](https://godeploy.com/) offer lab environments for a fee. These lab environments do not require participants to have their own accounts. The account information is included in the cost. You must ensure that a environment is provisioned and ready for participants on Day One.

Many hands-on exercises can be completed without a lab hosting environment. This will require the participants to have an Azure account and access to the Azure portal to perform the tasks associated with the hands-on exercises. For an environment that does not use a hosted lab, you must provide participants with environment prerequisites for local computers such as Azure CLI, Visual Studio Code, and necessary SDKs if a lab environment is not being used.

### Lab familiarization

You must complete all the labs from beginning to end. If you are using a hosted lab environment, perform the labs in that environment as there may be subtle differences or nuances in the hosted environments that cause the labs to behave differently.

When setting up a local computer to perform the labs, ensure you follow the setup instructions and document any variations that participants may need to be aware of.

Use the lab instructions, labfiles, and required software listed at the following links:

- Labs for core AI Services, [AI Services](https://github.com/MicrosoftLearning/mslearn-ai-services). These labs are designed to cover the basic aspects of Azure AI Services. More information on creating Azure AI Services can be found on the [AI Services web page](https://learn.microsoft.com/en-us/azure/ai-services/what-are-ai-services). Follow the Quickstarts and How-to guides on this page to practice.

- Azure [AI Vision](https://github.com/MicrosoftLearning/mslearn-ai-vision) is a service that provides services for processing images. The services support Optical Character Recognition (OCR), image analysis, face detection and feature recognition, and video analysis. Further documentation and support for learning about Azure AI Vision can be found on the [computer vision](https://learn.microsoft.com/en-us/azure/ai-services/computer-vision/overview) page. Use this resource to understand how to effectively use the services in the labs.

- The Azure [AI Language](https://github.com/MicrosoftLearning/mslearn-ai-language) service provides Natural Language Processing (NLP) features for understanding and analyzing text. Explore the capabilities and gain access to quickstarts and how-tos on the [Azure AI language page](https://learn.microsoft.com/en-us/azure/ai-services/language-service/overview).

- Azure AI [Document Intelligence](https://github.com/MicrosoftLearning/mslearn-ai-document-intelligence) is a cloud-based Azure AI service that uses machine-learning models to automate your data processing in applications and workflows. In this lab, participants will practice setting up an Azure AI document intelligence resource and manage the service in the Document Intelligence Studio as well as through the APIs using C# and Python.

- Ensure you understand the various types of documents supported and how to work with pre-built forms and custom forms for data extraction in the forms' recognizer capabilities. Further information is available on the [document intelligence](https://learn.microsoft.com/en-us/azure/ai-services/document-intelligence/overview?view=doc-intel-4.0.0) page.

- [Knowledge Mining](https://github.com/MicrosoftLearning/mslearn-knowledge-mining) uses a combination of intelligent services to quickly learn from vast amounts of information. It allows organizations to deeply understand and easily explore information, uncover hidden insights, and find relationships and patterns at scale. These labs explore setting up an Azure search resource to be used in the knowledge mining tasks and then moves on to help participants learn how to add skills to the search, add their own data, and add skill enrichments through connections to other AI services such as sentiment analysis, language detection, etc.

- There are many exercises in these labs so completion of each lab and gaining a thorough understanding of the concepts being covered is crucial to support participants as they complete these exercises. Additional information can be found on the [knowledge mining](https://azure.microsoft.com/en-us/solutions/knowledge-mining/#:~:text=By%20orchestrating%20various%20AI%20capabilities%2C%20knowledge%20mining%20delivers,phases%20to%20knowledge%20mining%3A%20ingest%2C%20enrich%2C%20and%20explore.) page.

- These labs cover exercises on using the Azure OpenAI models for generative AI. This will help participants learn how to use the Azure OpenAI and Azure AI Studio portals. The labs also teach how to access the services over REST APIs.  [OpenAI](https://github.com/MicrosoftLearning/mslearn-openai). Complete these labs to understand how to use the various facilities that participants will use. For added information, familiarize yourself with the reference materials found on the [Azure OpenAI](https://learn.microsoft.com/en-us/azure/ai-services/openai/overview) page.

## In-class activities

### Lab guidance

Follow these recommendations to guide participants effectively through the lab sessions:

- Ensure participants understand how to sign in, set up, and navigate the lab environment.
- Follow Microsoft Official Courseware (MOC) for AI-102, if available.
- Implement pair programming for complex labs.
- Create a troubleshooting guide for common issues participants might face.
- Adjust pacing if participants are progressing faster or slower than expected.

### Lab estimated durations

The following table lists the labs along with their durations, providing a clear schedule to help participants manage their time effectively during the training:

| Lab | Estimated Duration |
| --- | --- |
| Lab: Get Started with Azure AI Services | 30 minutes |
| Lab: Analyze Images with Azure AI Vision| 40 minutes |
| Lab: Read Text in Images  |40 minutes |
| Lab: Classify images with a custom Azure AI Vision model | 40 minutes |
| Lab: Analyze text | 40 minutes |
| Lab: Create question answering solution | 50 minutes  |
| Lab: Create a language understanding model | 50 minutes  |
| Lab: Integrate Azure OpenAI into your app  | 40 minutes |
| Lab: Utilize prompt engineering in your app | 40 minutes |
| Lab: Use your own data with Azure OpenAI | 40 minutes |
| Lab: Create a Custom Skill for Azure AI Search | 45 minutes |
| Lab: Custom document intelligence models| 45 minutes |

### Best Practices

- If you are not using a hosted lab environment, ensure that all participants receive communication prior to class, on required hardware and software components they should have.
- Stress the importance of being ready to start on Day One. Any delays caused by installing and configuring software can disrupt the class flow and lead to significant timing challenges in delivering the content effectively.
  
### Tips and Tricks

- As you complete the labs yourself, take note of any challenges you encounter and document them for future reference. If you had an issue, participants will likely experience the same thing.
- Verify the timing of the labs to ensure you know how long it takes you to complete them. If possible, have someone who is not an expert in the technology, complete the labs and time them. This will give you an idea of how long participants, who are learning, could take to complete the labs.
- Have a plan to manage timelines for the range of participants that will attend. Some will take longer than others to complete the labs. Have additional reading or some other resource to pass on to the participants who complete the labs early.
- If using a hosted lab environment, familiarize yourself with how to use the administrative tools that are provided, such as the ability to monitor the lab progress or to take control of a lab VM to assist.

## Post-class activities

### Continuous learning

Encourage participants to expand their knowledge and skills after the lab sessions by utilizing the following resources:

- Provide a curated list of additional Azure AI documentation from the trainer preparation section above.
- Provide a curated list of additional hands-on activities. Point participants to the [MS Learn eLearning courses](https://learn.microsoft.com/en-us/training/courses/ai-102t00) for additional hands-on exercises.
- Share upcoming [Azure AI webinars and events](https://azure.microsoft.com/en-in/resources/events/).

### Exam preparation

Support participants in preparing for the certification exam with these targeted resources and strategies:

- Point to [official preparation materials](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-engineer/?practice-assessment-type=certification).
- Give an overview of the Microsoft certification preparation pages and the resources provided there.
- Demonstrate the use of the [Microsoft practice test](https://learn.microsoft.com/en-us/credentials/certifications/azure-ai-engineer/practice/assessment?assessment-type=practice&assessmentId=61&practice-assessment-type=certification) on the exam landing page.
- Showcase the [exam sandbox](https://go.microsoft.com/fwlink/?linkid=2226877) to help participants understand how a Microsoft exam is constructed.
- Review the [exam study guide](https://aka.ms/ai102-StudyGuide) and instruct participants on how to use it effectively for exam preparation.

### Real-world application

Inspire participants to extend their learning through practical projects and active community involvement:

- Suggest AI hackathon ideas using Azure services.
- Encourage participation in [Azure AI community forums](https://techcommunity.microsoft.com/category/Azure).
