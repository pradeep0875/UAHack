# Enhancing Call Center Efficiency at United Airlines

## Project Overview
This project aims to optimize the efficiency of United Airlines' call center operations by reducing the Average Handle Time (AHT) and Average Speed to Answer (AST), thereby enhancing customer satisfaction and operational performance. By leveraging data analysis and machine learning techniques, this project identifies areas of improvement, offers actionable insights, and provides recommendations to optimize call center performance.

## Problem Statement
United Airlines' call center plays a critical role in ensuring customer satisfaction. However, challenges such as high AHT and AST impact efficiency and customer experience. The goal of this project is to identify inefficiencies in call handling, streamline processes, and improve the customer experience through data-driven insights.

## Objectives
- Reduce Average Handle Time (AHT) without sacrificing service quality.
- Decrease Average Speed to Answer (AST) to minimize customer wait times.
- Identify recurring low-complexity issues that can be addressed through IVR self-service options.
- Improve customer satisfaction by understanding customer sentiment and optimizing call routing.

## Methodology
1. **Data Collection**: Multiple datasets were collected, including call details, sentiment analysis, call reasons, and customer information.
2. **Data Preprocessing**: Handling missing values, converting date columns to datetime, and setting customer weights based on loyalty.
3. **Exploratory Data Analysis (EDA)**: Analyzing distributions of AHT and AST, clustering call data, and identifying high-impact factors.
4. **Machine Learning**:
   - **K-Means Clustering**: Grouping customers based on AHT, AST, and other features to identify service needs.
   - **Random Forest Model**: Predicting primary call reasons and identifying the key drivers of long AHT and AST.
5. **Self-Service Implementation**: Identifying common low-complexity issues that can be resolved without agent intervention.
6. **Recommendations**: Actionable insights were provided to enhance agent performance, optimize IVR, and improve customer satisfaction.

## Tools and Frameworks Used
- **Python**: Used for data analysis and preprocessing.
- **Pandas**: For data manipulation and analysis.
- **Matplotlib & Seaborn**: For visualizing data and generating insightful plots.
- **Natural Language Processing (NLP)**: For sentiment analysis of customer conversations.
- **K-Means Clustering**: To segment customers based on interaction features.
- **CountVectorizer & WordCloud**: For analyzing frequently occurring words in call transcripts and visualizing key phrases.

## Key Findings
- **High AHT Reasons**: Top 5 reasons for prolonged handling times were identified, indicating areas for focused agent training.
- **IVR Optimization**: Long AST reasons were flagged as opportunities for optimizing IVR options to reduce wait times.
- **Sentiment Trends**: Analysis of sentiment trends revealed declining satisfaction during specific periods, indicating the need for proactive measures.
- **Self-Solvable Issues**: Identified common, low-complexity issues that could be addressed through IVR or other self-service options, freeing up agents for more complex issues.

## Recommendations
1. **Targeted Agent Training**: Focus on the top call reasons contributing to high AHT to improve efficiency.
2. **IVR Optimization**: Update IVR options to handle frequent call reasons and reduce customer wait times.
3. **Self-Service Implementation**: Implement self-service options for low-complexity issues, such as status checks or information updates.
4. **Sentiment Monitoring**: Set up real-time sentiment analysis and alerts for proactive response to declining satisfaction.
5. **Future Work**: Due to time constraints, predictive modeling was not fully completed; further exploration is recommended to improve call routing and efficiency.

## Future Enhancements
- **Advanced Call Routing**: Use AI to predict customer needs and route calls accordingly.
- **Real-Time Sentiment Analysis**: Provide immediate feedback to agents based on customer sentiment.
- **AI Chatbots**: Integrate AI chatbots for handling low-complexity customer queries to further enhance call center efficiency.

## Contact
For any questions or inquiries, feel free to contact: pradeepmsc23@cs.du.ac.in

## License
This project is licensed under the MIT License. See the LICENSE file for more details.
