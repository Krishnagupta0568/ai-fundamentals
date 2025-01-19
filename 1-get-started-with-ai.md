# Get Started with AI

[Learning Path](https://learn.microsoft.com/training/paths/get-started-with-artificial-intelligence-on-azure/?WT.mc_id=academic-0000-alfredodeza)

## Get Started with AI on Azure

[Learn Module](https://learn.microsoft.com/training/modules/get-started-ai-fundamentals/?WT.mc_id=academic-0000-alfredodeza)

### Introduction to AI

- **Machine Learning**: Foundation of AI. Teaches a machine to learn based on data
- **Anomaly Detection**: Automatic error detection based on anomaly
- **Computer Vision**: Interpretation of images and video
- **Natural Language Processing (NLP)**: Interpret written or spoken language
- **Document Intelligence**: Manging, Processing, and using high volume of data found in forms and documents.
- **Knowledge mining**: Information extraction from unstructured data
- **Generative AI**: Create orginal content in a variety of formats including Natural Language, image, code and more.

### Machine Learning

Definition: The foundation for most AI solutions

How does it work:

- Machines (computers) learn from data
- Data Scientists use data to train machine learning models to make predicitons and inferences based on the relationships in the data.

### Machine Learning on Azure

A cloud based platform for creating, managing, and publishing machine learning models.

- **Automated ML (AutoML)**: Create effective ML models with no expertise needed
- **Azure ML Designer**: A GUI for no-code development of ML models
- **Data and Compute**: Cloud-based resources for data scientists tu run experiments
- **Pipelines**: A way to orchestrate tasks like training, validation, and deployment
- **Notebooks**: Write and run your own code in managed Jupyter Notebook servers that are directly integrated in the studio.

### Anomaly Detection

Definition: Analyzing data over time to identify unusual changes

**Anomaly Detector**: An Azure service with an API to create anomaly detection solutions

### Computer Vision

Definition: Area of AI for visual processing based on interpretation of images and video

The Seeing AI app is a great example of the power of computer vision. Designed for the blind and low vision community, the Seeing AI app harnesses the power of AI to open up the visual world and describe nearby people, text and objects.

**Models and capabilities**

| Task | Description |
| -    | -           |
| Image Classification | Classify images based on content. For example _is this a car or a bike?_ |
| Object Detection | Classify individual objects and location within an image using a box |
| Semantic Segmentation | Similar to object detection that uses an overlay to color-code distinct objects|
| Image Analysis | Extract information from images including tags for easier cataloging|
| Face detection, analysis, and recognition | Finds human faces in an image. Can be used with facial geometry to recognize individuals|
| Optical Character Recognition (OCR) | Detect and extract text in images, like a road sign or building number|

Azure Services

- **Computer Vision**: Analyse images and videos to extract descriptions, tags, objects and text
- **Custom Vision**: Customized image classification with your own images
- **Face**: Face detection and facial recognition solutions
- **Form Recognizer**: Information extraction from scanned documents

Computer vision services in Microsoft Azure

Use Microsoft's Azure AI Vision to develop computer vision solutions. The service features are available for use and testing in the Azure Vision Studio and other programming languages. Some features of Azure AI Vision include:

- **Image Analysis**: capabilities for analyzing images and video, and extracting descriptions, tags, objects, and text.
- **Face**: capabilities that enable you to build face detection and facial recognition solutions.
- **Optical Character Recognition (OCR)**: capabilities for extracting printed or handwritten text from images, enabling access to a digital version of the scanned text.


### Natural Language Processing

Definition: Area of AI that understands written and spoken language

Uses:

- Analyze and interpret text in documents, email messages, and other sources.
- Interpret spoken language, and synthesize speech responses.
- Automatically translate spoken or written phrases between languages.
- Interpret commands and determine appropriate actions.

Natural language processing in Microsoft Azure Services

- **Language**:  Analyze text or spoken language to build smart applications
- **Translator**: Translation service for more than 60 languages
- **Speech**:  Recognize and synthesize speech and translate to other languages
- **Azure Bot**: Conversational AI with the ability to connect to channels like email, Teams, and web chat


### Document Intelligence and Knowledge Mining

Document Intelligence: Document Intelligence is the area of AI that deals with managing, processing, and using high volumes of a variety of data found in forms and documents. Document intelligence enables you to create software that can automate processing for contracts, health documents, financial forms and more

- Document Intelligence to build solutions that manage and accelerate data collection from scanned documents.
- Document Intelligence help automate document processing in applications and workflows, enhance data-driven strategies, and enrich document search capabilities.

Knowledge Mining: Describe solutions about extracting information from large volume of unstructured data to create a searchable one

Azure Service: Azure Cognitive Search, and enterprise solution for building searchable indexes from private or public assets including image processing, document intelligence, and natural language processing to extract data, enabling quick insights from large datasets and indexing previously unsearchable content.

### Challenges and Risks

Challenges or risks:

- **Bias**: Trained data might rely heavily on specific race, or geography
- **Errors**: Mistakes can cause harm (e.g. autonomus vehicles)
- **Exposing data**: Non-compliant solutions that don't remove Personal Identifiable Information (PII)
- **Accessibility**: A solution might not work with individuals with disabilities
- **Complex systems**: Users must trust how solutions are generated (e.g. from what data)
- **Liability**:  Who/what is liable for decisions?

### Generative AI

Defination: describes a category of capabilities within AI that create original content.

## Generative AI in Azure
 
Azure OpenAI Service: deploying, customizing, and hosting generative AI models. It combines OpenAI's advanced models with Azure's security and scalability. supports various foundation models for different use cases and is accessible via Azure AI Foundry, a platform for managing and developing enterprise-grade AI solutions.

## Challenges and risks with AI

| Challenge or Risk |	Example |
| Bias can affect results |	A loan-approval model discriminates by gender due to bias in the data with which it was trained |
| Errors may cause harm	| An autonomous vehicle experiences a system failure and causes a collision |
| Data could be exposed |	A medical diagnostic bot is trained using sensitive patient data, which is stored insecurely |
| Solutions may not work for everyone |	A home automation assistant provides no audio output for visually impaired users |
| Users must trust a complex system |	An AI-based financial tool makes investment recommendations - what are they based on? |
| Who's liable for AI-driven decisions? |	An innocent person is convicted of a crime based on evidence from facial recognition – who's responsible? |


### Responsible AI

AI development at Microsoft uses 6 principles:

- **Fairness**: AI systems should treat all people fairly

- **Reliability & Safety**: AI systems should work reliably and safely

- **Privacy & Security**: Respect privacy and consider security at all times, even after deployment

- **Inclusiveness**: Empower everyone regardless of ability, gender, and other factors

- **Transparency**: Systems shouold be understandable

- **Accountability**: People should be accountable. Engineers and designers should work with a governance framework
