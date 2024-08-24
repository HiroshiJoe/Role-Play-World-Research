# Sentiment Analysis of the Role Play World (RPW) Community

### A Comprehensive Study on User Sentiments, Anonymity, and Social Interactions

## Description
This project focuses on the sentiment analysis of the Role Play World (RPW) community, a unique online space where users assume different identities, often of idols or fictional characters, to interact anonymously on social media platforms like Facebook. The study aims to understand user sentiments, explore the impact of anonymity on user experiences, and investigate how the RPW community fosters social interaction and personal expression.

## Features
- **Sentiment Analysis:** Analyzes the overall sentiment of users in the RPW community, with sentiment scores ranging from negative to very positive.
- **User Experience Analysis:** Investigates how different respondent types and interview sections influence sentiment.
- **Impact of Anonymity:** Explores how anonymity in RPW allows for open communication, self-expression, and the development of a supportive community.
- **Correlation Studies:** Examines the relationship between user experience (years of RPW use) and sentiment.

## Table of Contents
1. [Introduction](#introduction)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Data](#data)
5. [Methodology](#methodology)
6. [Results](#results)
7. [Conclusion](#conclusion)
8. [Future Work](#future-work)
9. [Contributing](#contributing)
10. [License](#license)
11. [Acknowledgements](#acknowledgements)

## Introduction
The RPW community is a fascinating blend of online personas and anonymity, allowing users to take on roles distinct from their real-life identities. This study delves into the sentiments of RPW users, examining how anonymity affects their interactions and the overall experience within this digital space.

## Installation
To run this project locally, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/RPW-Sentiment-Analysis.git
   ```
2. Navigate to the project directory:
   ```bash
   cd RPW-Sentiment-Analysis
   ```
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
To perform sentiment analysis on your RPW dataset:
1. Ensure your dataset is in the correct format (e.g., CSV, JSON).
2. Run the analysis script:
   ```bash
   python analyze_sentiments.py --input data/rpw_dataset.csv
   ```
3. View the results in the output directory, where sentiment scores, visualizations, and summary statistics will be stored.

## Data
The dataset used in this study contains the following columns:

- **InterviewSection:** The section of the interview (e.g., first interview, second interview).
- **RespondentType:** The type of respondent (e.g., new user, veteran user).
- **RespondentName:** The pseudonym or identifier of the respondent.
- **RPWUserSince:** The year the respondent started using RPW.
- **Question:** The questions asked during the interview.
- **Answer:** The responses given by the respondents.
- **YearsInRPW:** The number of years the respondent has been a part of RPW.
- **Sentiment:** The sentiment score of the respondent's answer, ranging from negative to positive.
- **Emotion:** The emotion detected in the respondent's answer.

**Please note that the data is private and not available for public use due to confidentiality and privacy concerns.** Only authorized researchers with specific access permissions may use this dataset.

## Methodology
The study employs a combination of qualitative and quantitative methods to analyze user sentiments. Sentiment analysis techniques, including natural language processing (NLP) and machine learning models, are used to assess the overall sentiment of RPW users.

## Results
The analysis reveals a generally positive sentiment within the RPW community, with variations across different user groups and interview sections. The findings suggest that anonymity plays a crucial role in facilitating open communication and positive interactions.

## Conclusion
The RPW community offers a unique platform for users to express themselves freely, often leading to positive social interactions and personal growth. This study highlights the importance of anonymity in creating a supportive online environment.

## Future Work
Further research could explore the long-term effects of RPW participation on user behavior, the impact of anonymity on mental health, and the potential for using sentiment analysis to improve online community experiences.

## Contributing
Contributions are welcome! Please fork this repository and submit a pull request if you'd like to contribute to this project.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgements
Special thanks to the RPW community members for participating in this study and to all contributors who helped make this project possible.
