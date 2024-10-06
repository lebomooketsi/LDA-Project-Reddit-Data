# LDA-Project-Reddit-Data

Welcome to my project exploring sentiment analysis and topic modeling on Reddit posts! The primary goal of this project is to analyze user discussions related to Commbank to identify common topics and sentiment trends. Through this analysis, I aim to uncover areas of concern and strength from the perspective of users, as well as gain insights into overall customer sentiment.

## Project Goals
1. **Identify Key Topics**: Using Latent Dirichlet Allocation (LDA), I’ve categorized posts into distinct topics to understand the main themes of discussion.
2. **Sentiment Analysis**: By analyzing both posts and comments, I aim to determine the general sentiment toward different banking topics.
3. **Highlight Areas for Improvement**: Based on sentiment scores, I will identify topics that generate negative sentiments, which may indicate customer dissatisfaction.
4. **Recognize Strengths**: Similarly, I aim to highlight areas with positive sentiments, revealing topics where customer experience or perceptions are favorable.

## Key Findings

### Topics Identified:
These are shown in the table below:

| Topic Number | Associated Words                                                                                   | Suggested Topic                          |
|--------------|----------------------------------------------------------------------------------------------------|------------------------------------------|
| 0            | transactions, interest, transaction, fees, code, happened, take, transfer, pay, free               | Transaction Details and Transfer Issues  |
| 1            | pay, fees, online, take, transaction, interest, transactions, loan, change, every                  | Online Transactions and Loan Services    |
| 2            | points, optus, way, qantas, using, point, pay, award, awards, data                                 | Loyalty Programs and Rewards             |
| 3            | loan, well, fees, rate, take, interest, every, customers, change, ago                              | Loan Interest Rates and Customer Impact  |
| 4            | interest, email, branch, online, change, ago, anz, take, best, transfer                            | Online and Branch Banking Services       |
| 5            | interest, online, way, fees, pay, using, may, transaction, might, payment                          | Online Payment Methods and Options       |
| 6            | interest, pay, fa, fees, business, using, best, free, password, change                             | Business Accounts and Payment Security   |
| 7            | interest, optus, rate, change, nab, better, fees, data, pay, take                                  | Bank Rates and Competitive Positioning   |



### Potential Area for Improvement Topic:

**Topic 5**: The topic identified as "Online Payment Methods and Options" received the most posts and comments. This topic shows an overall negative sentiment, as it has the lowest average post sentiment and a negative median post sentiment. The data suggests a trend of dissatisfaction or concerns among users regarding online payment options.

### Area of Strength Topic:
**Topic 7**: The topic focusing on "Bank Rates and Competitive Positioning" shows the highest positive sentiment scores, with an average post sentiment of 0.86. This suggests that users generally view the bank’s competitive positioning favorably. Other positively scored topics include "Loyalty Programs and Rewards" and "Loan Interest & Customer Impact," highlighting that competitive rates and customer loyalty are areas of strength.

## Visualizations
### Showing Post Sentiment by Topic

![plot2](https://github.com/user-attachments/assets/1988af8d-cd34-4d24-8069-048e2008ee95)

![plot3](https://github.com/user-attachments/assets/633b45a7-3e8f-46ac-9d79-4767ab23c3d6)


### Showing Comment Sentiment by Topic
![plot5](https://github.com/user-attachments/assets/91d6319b-eda6-4d60-b047-9f5669084991)

![plot6](https://github.com/user-attachments/assets/e2d2dac4-d2e0-40b2-9e50-be5d922645ac)

## Conclusion
This project provides valuable insights into user sentiments and highlights both strengths and opportunities for improvement in the bank’s services. I hope this analysis can be a useful resource for understanding customer perceptions and enhancing customer satisfaction.
