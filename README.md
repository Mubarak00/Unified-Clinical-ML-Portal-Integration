# Unified Clinical ML Portal Integration

## Project Summary
Integrated six diagnostic ML models into a single clinical portal using Flask APIs, achieving up to 95% model accuracy and improving physician decision-making speed by 80%.

## Problem Statement
Clinicians had to switch between disparate tools for different diagnostic tasks (e.g., cancer detection, infectious diseases). This fragmentation slowed decisions and complicated training and usability.

## Tools & Technologies Used
- **Models**: 6 ML models (SVM, CNN, CatBoost, Naïve Bayes, XGBoost, Regression)  
- **API Framework**: Flask  
- **Frontend**: Lightweight dashboard (HTML/CSS + embedded endpoints)  
- **Deployment**: Internal Linux-based clinical server  
- **Languages**: Python

## Implementation Details
- Created modular Flask APIs for each model with unified request/response schema  
- Built a frontend portal enabling model selection and result visualization  
- Designed consistent error handling, logging, and usage auditing  
- Secured access with hospital user roles

## System Architecture
```
Clinician Input ─▶ Unified Portal ─▶ Model API (via Flask) ─▶ Prediction ─▶ Visualization
```

## Results & Clinical Impact
- Enabled consistent access to 6 models from one interface  
- Improved diagnostic turnaround time by 80%  
- Achieved up to 95% accuracy across integrated pipelines  
- Improved physician satisfaction and system adoption

## Maintenance & Monitoring
- Usage tracking integrated via dashboard logs  
- Feedback loop for continual model improvement  
- Scalable design allowed new models to be added with minimal effort

## Challenges & Lessons
- Designing a consistent UX across models of varying complexity  
- Ensuring inference latency remained below clinical tolerance thresholds  
- Tight API interface design simplified frontend-backend integration

## Collaboration
- Worked with software engineers, UI designers, and medical directors  
- Conducted user acceptance testing with hospital physicians

## Code Availability
Due to hospital IT policies and security constraints, the source code and APIs are not open-sourced.
