# Project Title: CNN to Evaluate Social Distancing Measures

## Project Description

This project explores the application of Convolutional Neural Networks (CNNs) to evaluate social distancing measures using surveillance and crowd imagery. By leveraging advanced CNN architectures, students will develop models capable of detecting and assessing adherence to social distancing guidelines in public spaces. This approach can be valuable for public health authorities and policymakers in managing and enforcing social distancing during pandemics. For similar studies, refer to:
https://www.mdpi.com/2076-3417/10/21/7514
https://exposing.ai/oxford_town_centre/

## Project Steps

### Part 1: Data Collection and Preliminary Analysis (10 points)

#### Data Collection
- Gather datasets of surveillance and crowd images from public datasets that capture various scenarios of social distancing compliance and non-compliance. Examples include datasets available from academic or governmental sources.

#### Data Cleaning
- Clean the datasets by removing low-quality images, ensuring consistent resolution and format.

#### Preliminary Data Analysis and Visualization
- Perform preliminary analysis to identify patterns and anomalies in the imagery related to social distancing.
- Visualize the data using heat maps for spatial distribution and statistical charts for compliance rates.

### Part 2: Deep Learning Model (10 points)

#### Build CNN Model
- Develop a CNN model using PyTorch. Incorporate layers suited for image detection and segmentation tasks.
- Provide a detailed walkthrough of the code, which should be well-commented and available in a repository linked in the report.

#### Model Training and Validation
- Train the model on the prepared dataset, using a split of training and validation data to monitor for overfitting.
- Validate the model's performance using appropriate metrics such as accuracy, precision, recall, and F1-score. Adjust hyperparameters as needed to improve outcomes.

#### Deployment and Real-Time Testing
- Deploy the model to perform real-time evaluation of social distancing measures from incoming surveillance footage.
- Reconstruct the distance between people and study its evolution after covid19 restrictions.
- Visualize the results and assess the model's effectiveness in real-world scenarios.

### Part 3: Public Health Impact Analysis (10 points)

#### Analysis Using the Predictive Model
- Analyze the results obtained from the CNN model to understand the effectiveness of social distancing measures in various settings.
- Evaluate the implications of these findings on public health strategies and policies.

#### Presentation and Report
- Summarize the findings and methodologies in a comprehensive report. Reflect on the model's efficacy and areas for improvement.
- Discuss potential societal impacts, including both the benefits and challenges of using AI for public health monitoring.

## Grading Criteria

### Presentation of Data and Preliminary Data Analysis (10 points)
- Proper handling and presentation of the dataset.
- Clarity and relevance of the visualizations.
- Thoroughness of the initial analytical findings.

### Deep Learning Model (10 points)
- Accuracy and robustness of the CNN model.
- Model architecture design and implementation.
- Detailed documentation and reproducibility of the model training process.

### Public Health Impact Analysis (10 points)
- Depth and rigor of the analysis regarding the model's real-world applicability.
- Discussion of ethical considerations and potential biases.
