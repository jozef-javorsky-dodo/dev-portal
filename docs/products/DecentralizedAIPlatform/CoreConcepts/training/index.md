# Understanding Training on the Platform

## What is Training?

Training in the context of AI refers to the process of feeding data into a model to refine its performance and improve its ability to make predictions or generate insights. Instead of relying solely on pre-built models, [users now have the ability to train AI models themselves](/docs/products/DecentralizedAIPlatform/DevelopersTutorials/IntegrationTrainingService/), tailoring them to their specific needs. This means that an AI model can be customized with domain-specific knowledge, creating a unique tool designed for particular use cases. By allowing training, the platform empowers users to develop AI solutions that align closely with their requirements, enhancing the effectiveness and precision of AI-driven decisions.

Training involves multiple iterations where an AI model continuously learns from the provided data, adjusting its parameters to optimize accuracy. The process may include supervised learning, where labeled data is used to guide the model, or unsupervised learning, where the model identifies patterns within unstructured data. Reinforcement learning can also be employed, allowing AI to improve based on feedback from its environment. These varied approaches ensure that AI can be fine-tuned for a vast array of applications, from medical imaging to financial forecasting.

## Why is Training Important?

AI models are only as good as the data they are trained on. By enabling training, we offer flexibility and control to AI consumers, allowing them to enhance existing models or create entirely new ones suited to their needs. This is particularly useful for industries requiring specialized models, such as healthcare, finance, or engineering. A medical institution, for example, might need a model trained specifically on dental x-rays rather than general radiographic images. By offering training capabilities, we make AI more precise, adaptable, and valuable to a wider range of users.

In a rapidly evolving technological landscape, pre-trained models may not always address the nuanced demands of specific domains. Training allows businesses and researchers to refine AI to their niche, ensuring higher accuracy and reliability. Moreover, the ability to train models ensures that AI can keep up with shifting trends and emerging data patterns, making it a sustainable and future-proof solution for many sectors.

## Who Can Use Training?

Training is available to AI consumers who require personalized models. Whether you are an AI researcher, a developer, or a business looking to improve automation, training allows you to mold an AI model according to your requirements. The training process is facilitated through our AI Marketplace, ensuring that models remain secure while allowing AI developers to manage metadata.

## How Training Works

When a user decides to train a model, [they must first create a project within the AI Marketplace](/docs/products/DecentralizedAIPlatform/SDK/PythonSDK/training/#create-model). This serves as the foundation for building a new model. Once the project is set up, users can request a new model and define key attributes, including whether the model is publicly accessible or restricted to certain addresses. Upon request, the user receives a unique model ID, which is required for all subsequent training interactions.

[Training methods are invoked using this model ID](/docs/products/DecentralizedAIPlatform/DevelopersTutorials/IntegrationTrainingService), and the data provided can vary depending on the model type. Some models may require images, others may use text or audio datasets. The responsibility of storing and managing the training data rests with the AI developer, who also defines the methods through which training data is received. [The AI Marketplace provides a seamless way to initiate, monitor, and manage training sessions](/docs/products/DecentralizedAIPlatform/SDK/PythonSDK/training/#base-pipeline), ensuring that users have full control over their AI development process.


## AI Marketplace Integration

All training operations are managed through the AI Marketplace, which acts as the hub for creating, updating, and managing AI models. [Users can edit existing models, modify access permissions](/docs/products/DecentralizedAIPlatform/SDK/PythonSDK/training/#update-model), or even delete models they no longer need. The AI Marketplace ensures that [metadata about models is easily accessible](/docs/products/DecentralizedAIPlatform/SDK/PythonSDK/training/#get-model) while keeping the underlying AI model secure with the original developer.

## Related Resources

- [**Integration guide for training.proto**](/docs/products/DecentralizedAIPlatform/DevelopersTutorials/IntegrationTrainingService/)

- [**Python SDK — Training Guide**](/docs/products/DecentralizedAIPlatform/SDK/PythonSDK/training/)

- [**GitHub: snet-sdk-python (Official Python SDK)**](https://github.com/singnet/snet-sdk-python)

- [**GitHub: snet-sdk-js (Official JavaScript SDK)**](https://github.com/singnet/snet-sdk-js)