# ALIE (Intelligent Language Assistant for Education - Asistente de Lenguaje Inteligente para la Educación)

![AlieBanner](https://github.com/user-attachments/assets/3e4be967-8bb6-43ef-bf94-fe5e49cab722)

ALIE is a comprehensive solution developed to improve the management of academic queries at Pontificia Universidad Javeriana, Bogotá campus. Using artificial intelligence and natural language processing, ALIE enables students to obtain quick and accurate answers to their academic questions, thus optimizing their educational experience and access to important resources, while reducing the administrative burden. This organization contains repositories dedicated to the development, deployment, and management of ALIE, organized into several key areas.

## Repositories

- [**ALIE_IA**](https://github.com/ALIE-PUJ/ALIE_IA): Contains the logic of the ALIE conversational agent, including natural language processing and large language models (LLMs) adapted to educational needs.

- [**ALIE_BD**](https://github.com/ALIE-PUJ/ALIE_BD): Manages all logic related to relational, document, and vector databases, supporting the storage and retrieval of academic information.

- [**ALIE_Frontend**](https://github.com/ALIE-PUJ/ALIE_Frontend): Develops the project’s presentation layer (front-end), providing an intuitive interface for student interaction with the agent.

- [**ALIE_BaseDespliegueK8s**](https://github.com/ALIE-PUJ/ALIE_BaseDespliegueK8s): Configures deployment in Kubernetes clusters, facilitating the management and scalability of the ALIE platform.

- [**ALIE_LMSRunner**](https://github.com/ALIE-PUJ/ALIE_LMSRunner): Contains the containerized utility to run the language model used, optimizing the agent’s execution and response.

- [**ALIE_DinD**](https://github.com/ALIE-PUJ/ALIE_DinD): Stores certificates and security configurations required for deploying the application in controlled environments.

Each repository is designed to contribute integrally to the functionality, efficiency, and scalability of ALIE.

Likewise, you can find the refined language model (ALIE-model), based on *Mistral-7B-Instruct-v0.3* on Hugging Face:
- **Full model**: [ALIE_Model](https://huggingface.co/luisalejandrobf/ALIE_Model)  
- **Quantized version**: [ALIE_Model-Q4_K_M-GGUF](https://huggingface.co/luisalejandrobf/ALIE_Model-Q4_K_M-GGUF)
