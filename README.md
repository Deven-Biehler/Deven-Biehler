## My Personal Projects


### Interpretable Flood Prediction using Sentinel-1 SAR Data

This project leverages Sentinel-1 Synthetic Aperture Radar (SAR) data for flood prediction using a ResNet-34-based deep learning model. The approach incorporates Monte Carlo Dropout (MC Dropout) to estimate predictive uncertainty and saliency maps to improve interpretability by highlighting key regions influencing flood classification.
Key Features

- Flood Prediction with SAR Data – Utilizes Sentinel-1 imagery from the SEN12FLOODS dataset.
- ResNet-34 with Uncertainty Estimation – Employs MC Dropout to provide confidence scores for flood detection.
- Explainability with Saliency Maps – Identifies critical flood-prone areas in SAR images.
- Robust Model Training – Includes data preprocessing, augmentation, and hyperparameter tuning with Optuna.
- Comprehensive Evaluation – Uses accuracy, F1-score, confusion matrices, and uncertainty quantification.

This project enhances flood monitoring and disaster response efforts by delivering interpretable, confidence-aware predictions. Future improvements include multimodal learning with Sentinel-2 data, advanced architectures like U-Net, and interactive model deployment.


### Distribution Disaster Net (D-DNet)

Overview
Distribution Disaster Net (D-DNet) is a dynamic resource allocation (DRA) system designed to optimize evacuation and resource distribution in disaster-affected cities. The framework models real-world constraints such as stockpile capacities, household demand, road network safety, and equitable resource distribution. Inspired by the 2023 paper Safety Map Disaster Management Road Network, D-DNet expands disaster relief logistics to multiple disaster types, evolving risk levels, and dynamic traffic patterns.

Key Features
- Optimized Resource Allocation – Uses an adaptive model to distribute food supplies efficiently.
- Disaster-Aware Routing – Accounts for road closures, flood risks, and infrastructure safety.
- Equity-Based Planning – Ensures fair access to resources across affected communities.
- Cost-Effective Delivery – Minimizes travel time and fuel consumption while maximizing aid coverage.
- Scalable & Modular – Designed for integration with real-time GIS data and disaster monitoring systems.


### Autonomous Orchard Navigation
This project focuses on developing and implementing algorithms and models for Autonomous Orchard Navigation. The goal is to enable a rover to accurately detect and avoid obstacles while maintaining its path within an orchard. The following tasks are being worked on:

- Utilizing 3D stereo imaging and LiDAR scanning to gather comprehensive data for obstacle detection and path planning.
- Developing advanced algorithms to fuse the data from different sensors and improve the accuracy of obstacle detection.
- Implementing machine learning techniques to enhance the robot's ability to navigate safely and efficiently in dynamic farm environments.
- Annotating large datasets and training the machine learning models to fine-tune their performance.
- Ensuring the robot's robustness and adaptability to different orchard conditions.
- Feel free to explore the code and contribute to this project. Together, we can revolutionize farming with AI!

### [Media Bias Prediction Model](https://github.com/WSUCapstoneS2023/Media-Bias-Prediction-Model)
Thi project aims to address the limitations of current methods for characterizing media bias. The existing approaches are often subjective and lack the level of detail required for an accurate assessment. This project intends to create a purely empirically driven model that characterizes media sources in a probabilistic way, eliminating the need for human subjective judgments. The goal is to provide a comprehensive tool that can assess media bias in a more nuanced and context-aware manner. The following tasks are being worked on:

- Develop a model that probabilistically characterizes media bias using empirical data and advanced research techniques.
- Avoid biases inherent in current bias assignment methods by removing the reliance on human judgments.
- Incorporate sentiment analysis and fact selection as primary drivers for determining bias.
- Utilize natural language processing, topic modeling, sentiment analysis, and data management tools to build the model.
- Create a media landscape assessment tool that can be used to combat information warfare.
- Ensure the model is flexible enough to adapt to different media landscapes, both within the United States and globally.

### [Autonomous PDF Ingestion](https://github.com/Deven-Biehler/Cosmos)
The objective of this project is to enhance an open-source project called COSMOS to cater specifically to our chemistry research papers. The focus is on autonomous ingestion of PDF files and extraction of relevant information, which will be stored in an online database. The key tasks include:

- Collaborating with the COSMOS community to integrate the necessary improvements for handling chemistry research papers.
- Utilizing Docker to create an isolated environment for running the ingestion process.
- Implementing Dask to distribute the processing load across multiple machines, ensuring efficient ingestion of a large number of PDFs.
- Utilizing XGBoost, a powerful machine learning library, to extract valuable information from the research papers.
- Storing the extracted information in an online database for further analysis and retrieval.
- Feel free to contribute to this project by suggesting improvements, reporting issues, or submitting pull requests. Your input is highly appreciated!

### Anomalous User Detection on Reddit
This project explores the detection of scams and malicious users on Reddit by leveraging Hypergraph Neural Networks (HGNNs) and Bag-of-Words (BoW) models. Traditional text classification methods often fail to capture intricate user interactions, making them ineffective against sophisticated scams and coordinated bot activities. Our approach models Reddit users, subreddits, and their interactions as a hypergraph, integrating textual features via BoW representations.

Key contributions:
- Hypergraph-based framework for capturing complex relationships in user interactions.
- HGNN architecture that integrates text and structural features for anomaly detection.
- Evaluation on a large Reddit dataset, demonstrating competitive performance against traditional classifiers.

This research aims to advance anomaly detection in online communities while providing insights into evolving malicious behaviors.

### Q-learning for Optimal Stock Trading Strategy
This project applies Q-learning and Deep Q-Networks (DQN) to develop an autonomous stock trading strategy. We explore reinforcement learning (RL) techniques, including Double DQN (DDQN) and Dueling DDQN, to optimize trading decisions based on historical stock data. Our simulation environment models real-world trading dynamics, allowing an agent to learn buy, sell, or hold strategies to maximize profits.
Key Contributions:

- Reinforcement learning framework for stock trading using DQN, DDQN, and Dueling DDQN.
- Trading environment simulation incorporating historical market data.
- Performance evaluation of different Q-learning architectures, showcasing improved decision-making and risk management.
- Insights into trading behavior in various market conditions, including trends and volatility.

### Steam Review Sentiment Analysis

This project explores natural language processing (NLP) techniques to classify Steam game reviews as positive or negative, with a focus on detecting sarcasm—a major challenge in sentiment analysis. Using a dataset of 6.4 million Steam reviews, we developed multiple machine learning models to improve sentiment classification.
Key Features

- Deep Learning Approach – Implemented a GRU-based neural network with softmax activation.
- Naive Bayes Classifiers – Compared Gaussian, Multinomial, and Bernoulli Naive Bayes models.
- Preprocessing Pipeline – Removed stopwords, special characters, and short reviews (<100 characters).
- Sarcasm Detection – Focused on nuanced text structures that indicate sarcasm.
- Model Performance – Achieved up to 86.5% accuracy with the Multinomial Naive Bayes model.

## Contributions and Contact
If you're interested in any of the projects mentioned above or have any questions, suggestions, or ideas, I would love to hear from you. Contributions are always welcome! You can reach out to me via email at deven.biehler@wsu.edu.

Thank you for your support and interest in my projects!
