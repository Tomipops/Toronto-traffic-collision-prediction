# Toronto Traffic Collision Prediction

## I. Introduction
In today’s data-driven landscape, cities are increasingly relying on technology and analytics to improve public safety and operational efficiency. One critical area of focus is traffic accident and collision management. This capstone project addresses the limitations of Toronto’s current accident and collision reporting system by proposing a predictive analytics solution supported by real-time data monitoring tools. 

By analyzing traffic data and integrating machine learning techniques, this project seeks to forecast high-risk areas and future collision trends. Additionally, it proposes the development of interactive dashboards to assist law enforcement and city officials in making timely, data-informed decisions. The ultimate goal is to create safer roads for Toronto residents and enhance the city's ability to manage traffic-related incidents proactively.

## II. Business Problem
The business problem stems from the Toronto Police Services’ current accident and collision reporting system, which provides insights based on descriptive and delayed data. This issue is compounded by the fact that accidents are often reported hours or even days after they occur, making it difficult to identify accident hotspots and respond proactively.

This project aims to address this problem by developing a predictive model to identify high-risk areas and creating real-time tools like dashboards for more efficient decision-making.

## III. Project Importance
The proposed solution is significant for the following reasons:
- **Enhanced Public Safety and Trust**: Proactively predicting and preventing accidents can reduce the frequency and severity of traffic incidents, thereby improving public safety and fostering trust between the Toronto Police Service and the community.
- **Reduction in Traffic Accident Rates**: By preventing accidents, the project contributes to improved quality of life, increased property values, and reduced costs related to investigations.
- **Efficient Resource Allocation**: The predictive model will optimize resource allocation, ensuring police presence is concentrated in areas with higher accident risks.
- **Evidence-Based Policing**: The integration of predictive analytics into decision-making processes will enhance the accuracy and accountability of law enforcement actions.

## IV. Stakeholders
The implementation of this system involves several key stakeholders:
- **Toronto Police Service (TPS)**: The primary users of the system, responsible for applying predictive insights to prevent accidents and allocate resources efficiently.
- **City of Toronto Officials**: Policymakers and funders responsible for supporting the system's development and ensuring its integration into the city's broader safety initiatives.
- **Toronto Residents**: The beneficiaries of this project, whose safety and quality of life will be directly impacted by improved traffic accident prevention strategies.

## V. Analytical Questions
The project addresses the following analytical questions:
1. **What are the key predictors of traffic collisions?**
2. **Where are the high-risk areas or collision hotspots?**
3. **How can machine learning models forecast collision trends?**

## VI. Data and Data Flow
### Data Source
The project uses accident data from the **Traffic Collisions - Killed or Seriously Injured (KSI)** and **Total_Collisions** datasets provided by the Toronto Police Service.

### Data Flow
Data flows from emergency 911 calls, police reports, and traffic surveillance systems to an Enterprise Data Warehouse (EDW), where it is processed and analyzed using tools like Power BI for visualization and prediction.

## VII. Solution Design and Implementation
### Machine Learning Models
1. **Random Forest Classifier**: An ensemble learning method used to predict accident-prone areas.
2. **Multilayer Perceptron (MLP)**: A neural network model that showed the highest accuracy in predicting accident hotspots.
3. **CatBoost**: A gradient boosting model, though less effective in this case due to computational resource limitations.

### Power BI Dashboards
Power BI was used to visualize historic and predicted accident data, including mapping accident hotspots and displaying trends.

## VIII. Outcome Testing and Reviewing
The models were evaluated on accuracy, with the **MLP model** performing the best, achieving an accuracy of **85.31%**, followed by **Random Forest** at **81.67%**, and **CatBoost** at **60.62%**.

## IX. Optimization
Several optimization strategies were applied to improve model performance, including feature selection, hyperparameter tuning, and cloud-based deployment.

## X. Conclusion
This project provides a comprehensive solution to Toronto's traffic collision management challenges by integrating predictive analytics into law enforcement operations. By using machine learning models, real-time dashboards, and evidence-based strategies, the solution helps enhance public safety, optimize resource allocation, and improve decision-making for both law enforcement and city officials.

## XI. References
1. Spinks, R. (2024, June 19). Evidence-based policing. *American Police Beat*. Retrieved January 26, 2025, from [apbweb.com](https://apbweb.com/2024/06/evidence-based-policing/)
2. Toronto Police Service. (n.d.). *Body-worn cameras*. Retrieved February 4, 2025, from [Toronto Police Service](https://www.tps.ca)
3. Toronto Police Service. (n.d.). *Next Generation 911*. Retrieved February 4, 2025, from [Toronto Police Service](https://www.tps.ca)
4. Toronto Police Service. (2022, October). *Artificial intelligence* -Toronto Police Service.
5. Romeo-Beehler, B. (2022, June 14). *Toronto Police Service - Audit of 9-1-1 Public Safety Answering Point operations*. Office of the Auditor General of Toronto.
