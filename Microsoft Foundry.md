## What is an AI application?
**Artificial Intelligence** (AI) refers to systems designed to perform tasks that typically require human intelligence, such as reasoning, problem-solving, perception, and language understanding.  
**Responsible AI:** Emphasizes fairness, transparency, and ethical use of AI technologies.

Key AI workloads:
- Generative AI
- Agents and automation
- Speech
- Text analysis
- Computer Vision
- Information Extraction  

All these workloads are built on the foundation of machine learning.  

AI is the broader goal, creating systems that mimic human intelligence. **Machine learning** (ML) is the primary method we use to reach AI and is made possible by data-driven algorithms. In general, ML enables machines to learn patterns from data and improve performance without explicit programming.

### Types of ML:
- **Supervised and Unsupervised Learning:** such as regression (supervised) for predicting prices, classification (supervised) for spam detection, and clustering (unsupervised) for customer segmentation.
- **Deep Learning:** A specialized branch of ML using neural networks with multiple layers for tasks like image recognition and speech synthesis. Deep learning provides the foundation through neural networks that learn complex patterns from massive datasets.
- **Generative AI:** uses deep learning capabilities to create new content—text, images, audio, code—rather than just classify or predict outcomes.

### AI Applications
An AI application is a software solution that uses AI techniques such as computer vision, speech, and information extraction, to perform tasks that typically require human-like intelligence. These applications can understand, reason, learn, and respond to inputs in a way that feels more adaptive and intelligent than traditional software.

AI applications are:
- **Model-powered:** They use trained models to process inputs and generate outputs, such as text, images, or decisions.
- **Dynamic:** Unlike static programs, AI apps can improve over time through retraining or fine-tuning.

Some of the typical ways people interact with AI applications include:
- **Conversational Interfaces:** Users interact via chatbots or voice assistants (such as: asking questions, getting recommendations).
- **Embedded Features:** AI is integrated into apps for tasks like autocomplete, image recognition, or fraud detection.
- **Decision Support:** AI applications provide insights or predictions to help users make informed choices (such as: personalized shopping, medical diagnostics).
- **Automation:** They handle repetitive tasks, such as document processing or customer service, reducing manual effort.

Some examples of AI applications for different industries include:
- **Healthcare:** AI-powered diagnostic tools that analyze medical images (such as X-rays or MRIs) to help doctors detect diseases more accurately and quickly.
- **Finance:** Fraud detection systems that use AI to monitor transactions in real time and identify suspicious activity, helping prevent financial crimes.
- **Retail:** Personalized recommendation engines that analyze customer behavior and preferences to suggest products, improving the shopping experience.
- **Manufacturing:** Predictive maintenance solutions that use AI to monitor equipment and forecast when machines are likely to fail, reducing downtime and maintenance costs.
- **Education:** Intelligent tutoring systems that adapt to each student’s learning style and pace, providing customized feedback and support to enhance learning outcomes.

## Components of an AI application
Microsoft supports each layer of an AI application: the data layer, model layer, compute layer, and orchestration layer.

### Data Layer
The data layer is the foundation of any AI application. It includes the collection, storage, and management of data used for training, inference, and decision-making. Common data sources include structured databases such as Azure SQL and PostgreSQL, unstructured data, such as documents and images, and real-time streams. Azure services like Cosmos DB and Azure Data Lake are often used to store and manage large-scale datasets efficiently.

Microsoft offers databases as a Platform-as-a-Service (PaaS). Platform services are managed cloud services that provide the foundational building blocks for developing, deploying, and running applications without requiring users to manage the underlying infrastructure. PaaS sits between Infrastructure-as-a-Service (IaaS) and Software-as-a-Service (SaaS) in the cloud service model.

### Model Layer
The model layer involves the selection, training, and deployment of machine learning or AI models. Models can be pretrained (for example: Azure OpenAI in Foundry Models) or custom-built using platforms like Azure Machine Learning. This layer also includes tools for fine-tuning, evaluating, and versioning models to ensure they meet performance and accuracy requirements. Microsoft Foundry, a unified Azure platform-as-a-service for enterprise AI operations, provides a comprehensive model catalog for application developers.

### Compute Layer
AI applications require compute resources to train and run models. Microsoft provides several platform options:
- Azure App Service for hosting web apps and APIs.
- Azure Functions for serverless, event-driven execution of AI tasks.
- Containers for scalable and portable deployment of AI models and services. Azure Container Instances (ACI) offers lightweight, serverless container execution, perfect for AI workloads needing rapid deployment and simple scaling. Azure Kubernetes Service (AKS) is a fully managed Kubernetes service that provides enterprise-level orchestration for AI workloads.

**Note:**  
**Application programming interfaces (APIs)** define the information that is required for one component to use the services of the other. APIs enable software components to communicate securely.

### Integration & Orchestration Layer
The integration and orchestration layer connects models and data with business logic and user interfaces. Foundry plays a key role here by offering:
- An agent Service for building intelligent agents that can reason and act.
- AI Tools like speech, vision, and language APIs.
- Software Development Kits (SDKs) and APIs for integrating AI capabilities into applications.
- Portal tools for managing models, agents, and workflows.

By using Foundry to build their applications, developers can embed intelligence directly within the data layer for smarter, more responsive applications.

## Microsoft Foundry for AI
**Microsoft Foundry** is a unified, enterprise-grade platform for building, deploying, and managing AI applications and agents. It consolidates models, agent orchestration, monitoring, and governance tools in one platform, offering production-grade infrastructure and security. With Foundry, developers can seamlessly design, customize, and scale generative AI applications using a rich portal experience or integrated SDKs, without worrying about underlying infrastructure complexities.

Within Foundry's portal, you can work with:
- **Foundry Models:** Access to foundation and partner models (Azure OpenAI in Foundry Models, Anthropic, Cohere, etc.).
- **Agent Service:** Build and orchestrate multi-step AI workflows.
- **Foundry Tools:** Prebuilt Azure services (Vision, Language, Search, Document Intelligence).
- **Governance & Observability capabilities:** Centralized identity, policy, and monitoring for AI workloads.
