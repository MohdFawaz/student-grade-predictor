# student-grade-predictor

## Project Overview
This project implements multiple supervised learning models to predict students' final grades in an online machine learning course at my university. The analysis is based on data collected from a nine-week course from online platform, including various student activities and intermediate assessments.

## Dataset Description
The dataset contains information from 107 enrolled students, including:
- Course activity logs (Status0-3)
- 9 intermediate grades (mini projects, quizzes, peer reviews)
- 36 weekly activity logs across 9 weeks

### Features Include:
1. **Status0**: Course/lecture related activities
   - Course module views
   - Content page views
   - Lesson interactions
   
2. **Status1**: Assignment related activities
   - Quiz attempts
   - Submission handling
   
3. **Status2**: Grade related activities
   - Grade report views
   - User profile activities
   
4. **Status3**: Forum related activities
   - Post creation/updates
   - Discussion participation

## Implementation Steps

### 1. Data Processing
- Missing value analysis
- Feature selection and engineering
- Data cleaning and preparation

### 2. Data Split
- Training and test set division
- Validation strategy

### 3. Model Training
- Implementation of two different supervised learning approaches
- Model comparison and evaluation
- Performance optimization

### 4. Performance Evaluation
- Model accuracy assessment
- Visualization of results
- Comparative analysis

### 5. Feature Importance
- Identification of top predictive features
- Feature impact analysis

## Technical Requirements
- Python 3.x
- Google Colab environment
- Required packages (specified in code)

## Project Structure
```
project/
│
├── code/
│   └── code (ipynb)                 # Main Colab notebook
│
└── README.md                        # Project documentation
```

## Results
- Model performance metrics
- Comparison between different approaches
- Key findings about predictive features

## Future Improvements
- Feature engineering refinements
- Additional model architectures
- Hyperparameter optimization

## Requirements
The code runs in Google Colab environment. Required packages are listed in the notebook.

## Acknowledgments
Data collected from a Moodle-based online learning environment.
