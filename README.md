# Smart Litter System Event Classification

## Background

The client is a global company in the Pet Care and pet food space. They own a range of smart pet products aiming to improve the health of pets by monitoring their activities and generating portfolios for pet owners to consume.

The Smart Litter System is a smart cat litter system equipped with four load sensors to capture any load disturbance happening in the litter box. Operating at a frequency rate of 40 Hz, it records 40 samples per second. Multiple devices are used in the client's facility to capture all activities in the form of load signals on a day-to-day basis. Additionally, the facility is equipped with cameras that capture photo and video feeds, enabling manual tagging of various cat and human interaction events with the litter system.

### Cat Interaction Events

- **Elimination**
  - Defecation
  - Urination
- **Non-Elimination**

## Objective

The objective of this project is to develop a solution approach to correctly classify events as elimination or non-elimination, and further classify elimination events into urination and defecation.

## Import Components

To achieve the project objectives, the following components will be utilized:

- **Machine Learning Algorithms**: Various machine learning algorithms will be employed to train models for event classification based on the collected data.
  
- **Feature Engineering**: Feature engineering techniques will be applied to extract relevant features from the sensor data.
  
- **Data Visualization**: Data visualization tools and libraries will be utilized to analyze and visualize the data, aiding in understanding patterns and trends.
  
- **Model Evaluation Metrics**: Metrics such as accuracy, precision, recall, and F1-score will be used to evaluate the performance of the trained models.

## Steps for enabling pre-commit

pip install pre-commit
Install pre-commit hooks.

pre-commit install
Done, after this each commit will be verified based on pre-commit configurations. The configurations can be disabled in commit stage by adding --no-verify argument to the commit.

Example: git commit -a --no-verify -m "Commit without pre-commit verification"
  
## Requirements

The following packages are required to run the project:

- scikit-learn
- numpy
- pandas
- matplotlib
- python
