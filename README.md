# Heart-disease-detction-system
This project aims to predict the likelihood of heart disease in a patient using machine learning models, while preserving data privacy by employing Federated Learning (FL) — a decentralized AI training approach.

In a traditional ML setup, data from all hospitals or medical centers would be collected in one place to train a single model.
But due to privacy regulations (like HIPAA, GDPR) and ethical reasons, medical data cannot be shared.

To overcome that, Federated Learning allows multiple hospitals (clients) to train models locally on their own data, and only share the learned parameters (weights) with a central server, which then aggregates them to create a global model — without ever accessing the raw patient data.
