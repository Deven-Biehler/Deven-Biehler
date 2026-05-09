# My Personal Projects

### [STAAR-FM: Scalable Terrain-Aware Adaptive Resolution Framework for Flow Modeling](https://github.com/Deven-Biehler/STAAR-FM)

This project aims to produce a terrain-aware framework that dynamically adjusts grid resolutions based on local complexity. The framework is tested by predicting stream accumulation in watershed digital elevation models; all while utilizing significantly less data than what is provided.

Key contributions
- Developed a spatially adaptive framework that utilizes terrain complexity analysis to guide the creation of multi-resolution rasterized datasets for analysis by geospatial algorithms
- Integrated a preprocessing method that applies user-defined heuristics to DEM data, creating an optimal spatial resolution map for STAAR-FM.
- The core of STAAR-FM can enhance methods like the traditional D8 flow direction algorithm by utilizing dynamically sized kernels based on the values of \textit{ARM}.

### [Interpretable Flood Prediction using Sentinel-1 SAR Data](https://github.com/Deven-Biehler/interpretable-flood-prediction)

This project leverages Sentinel-1 Synthetic Aperture Radar (SAR) data for flood prediction using a ResNet-34-based deep learning model. The approach incorporates Monte Carlo Dropout (MC Dropout) to estimate predictive uncertainty and saliency maps to improve interpretability by highlighting key regions influencing flood classification.
Key Features

- Flood Prediction with SAR Data – Utilizes Sentinel-1 imagery from the SEN12FLOODS dataset.
- ResNet-34 with Uncertainty Estimation – Employs MC Dropout to provide confidence scores for flood detection.
- Explainability with Saliency Maps – Identifies critical flood-prone areas in SAR images.
- Robust Model Training – Includes data preprocessing, augmentation, and hyperparameter tuning with Optuna.
- Comprehensive Evaluation – Uses accuracy, F1-score, confusion matrices, and uncertainty quantification.

This project enhances flood monitoring and disaster response efforts by delivering interpretable, confidence-aware predictions. Future improvements include multimodal learning with Sentinel-2 data, advanced architectures like U-Net, and interactive model deployment.

### [Media Bias Prediction Model](https://github.com/WSUCapstoneS2023/Media-Bias-Prediction-Model)
Thi project aims to address the limitations of current methods for characterizing media bias. The existing approaches are often subjective and lack the level of detail required for an accurate assessment. This project intends to create a purely empirically driven model that characterizes media sources in a probabilistic way, eliminating the need for human subjective judgments. The goal is to provide a comprehensive tool that can assess media bias in a more nuanced and context-aware manner.

Key contributions:
- Developed a model that probabilistically characterizes media bias using empirical data and advanced research techniques.
- Model avoids biases inherent in current bias assignment methods by removing the reliance on human judgments.
- Incorporate sentiment analysis and fact selection as primary drivers for determining bias.
- Utilize natural language processing, topic modeling, sentiment analysis, and data management tools to build the model.
- Create a media landscape assessment tool that can be used to combat information warfare.

### [Anomalous User Detection on Reddit](https://github.com/Deven-Biehler/hypergraph-anomaly-detection)
This project explores the detection of scams and malicious users on Reddit by leveraging Hypergraph Neural Networks (HGNNs) and Bag-of-Words (BoW) models. Traditional text classification methods often fail to capture intricate user interactions, making them ineffective against sophisticated scams and coordinated bot activities. Our approach models Reddit users, subreddits, and their interactions as a hypergraph, integrating textual features via BoW representations.

Key contributions:
- Hypergraph-based framework for capturing complex relationships in user interactions.
- HGNN architecture that integrates text and structural features for anomaly detection.
- Evaluation on a large Reddit dataset, demonstrating competitive performance against traditional classifiers.

This research aims to advance anomaly detection in online communities while providing insights into evolving malicious behaviors.

### [Q-learning for Optimal Stock Trading Strategy](https://github.com/Deven-Biehler/wsu-reinforcement-learning/blob/main/Homework/Final%20Project/deep-reinforcement-learning-on-stock-data.ipynb)
This project applies Q-learning and Deep Q-Networks (DQN) to develop an autonomous stock trading strategy. We explore reinforcement learning (RL) techniques, including Double DQN (DDQN) and Dueling DDQN, to optimize trading decisions based on historical stock data. Our simulation environment models real-world trading dynamics, allowing an agent to learn buy, sell, or hold strategies to maximize profits.
Key Contributions:

- Reinforcement learning framework for stock trading using DQN, DDQN, and Dueling DDQN.
- Trading environment simulation incorporating historical market data.
- Performance evaluation of different Q-learning architectures, showcasing improved decision-making and risk management.
- Insights into trading behavior in various market conditions, including trends and volatility.

### [Time-Series COVID-19 Geospatial Visualization](https://github.com/Deven-Biehler/us-covid-visualization)

This project utilizes a dynamic Tableau dashboard to analyze and visualize COVID-19 time-series data, focusing on geospatial trends, case fatality rates (CFR), and temporal case dynamics. The visualization enhances pandemic analysis by integrating geo-tagged COVID-19 statistics, allowing for an intuitive exploration of the virus’s spread and impact.
Key Features

- Geospatial Visualization – Interactive bubble maps and heatmaps display the spread of COVID-19 across U.S. states.
- Time-Series Analysis – Tracks case and mortality trends over time with delta cases and deaths metrics.
- Case Fatality Rate (CFR) Mapping – Evaluates the lethality of the virus across different regions.
- Pandemic Impact Assessment – Analyzes the effects of lockdowns on public health and infection rates.
- Data Processing & Integration – Utilizes Pandas, GeoJSON, and Tableau for real-time insights.

## Contributions and Contact
If you're interested in any of the projects mentioned above or have any questions, suggestions, or ideas, I would love to hear from you. You can reach out to me via email at deven.biehler@gmail.com.

Thank you for your support and interest in my projects!
