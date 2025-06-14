# RAG-to-manage-policy-enquiries
A technology firm intended to develop an internal assistant designed to manage complex inquiries pertaining to their various policy documents. These documents may include tables, graphs, and images. The assistant is expected to operate in a manner akin to systems that parse and respond based on specific policy documents. The task involves creating a Retrieval-Augmented Generation (RAG) model. 

This model must efficiently retrieve and apply relevant policy data to deliver accurate and contextually appropriate responses. A critical performance metric for the system is its reliability; providing no response is more acceptable than offering an incorrect one, as the latter could mislead the user regarding their query.

Key Considerations:
Given that we are publishing a small subset of the problem and solution for contributiong to the overall community, the initial dataset is comprising a few examples of the company's policies. The solution in this repo includes:

1. Framework Development: 
A comprehensive roadmap to guide the development of the Retrieval-Augmented Generation (RAG) model. This roadmap  clearly indicate each phase of development, from exploratory data analysis (EDA) to high-level design and technology stack selection. Specifying what additional data actually enhanced the analysis and detail the specific concepts and tools to be employed at each stage. The framework outlines various methodologies for constructing the RAG, ensuring flexibility in approach and adaptability in implementation. Bear in mind propietary insights gained that directly contribute to the design of the specific RAG model are not included due to NDA restrictions. 
    
2. RAG implementation:
Develop the RAG model by applying the methods identified in the framework. The pipeline is depcited in a jupyter notebook for readibilty purposes, final implementation required OOP among other ML ops processes and applications. The notebook explain the setting up of the necessary infrastructure, selecting the appropriate algorithms, the steps for implementing, including data preprocessing, integration of retrieval mechanisms, open-source libraries where applicable and document the process for replicating the setup and results.

3. Evaluation:
Establish robust evaluation criteria and methods to assess the performance of the RAG model. Implement a testing protocol that covers various scenarios and edge cases to ensure the model’s efficacy across different types of policy queries. Outline the tools and techniques for continuous monitoring and evaluation of the model’s performance post-deployment.


