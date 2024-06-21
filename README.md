# Fraud-Detection-in-E-commerce-Transactions
## Project Background
With the internet's growing accessibility and the increasing ease of online shopping, many people are turning to digital platforms for their buying needs. This shift in consumer behavior, driven by the convenience of purchasing from home, comes with challenges, including rising fraud activity such as payment scams  in e-commerce transactions

## About Dataset 
The dataset comprises 1,472,952 transactions with 16 collected features from January 2024 to April 2024, with two target values (fraud and not fraud). The impact of this fraudulent activity resulted in a total loss of $40,449,950. Feature details:
- Transaction ID: A unique identifier for each transaction.
- Customer ID: A unique identifier for each customer.
- Transaction Amount: The total amount of money exchanged in the transaction.
- Transaction Date: The date and time when the transaction took place.
- Payment Method: The method used to complete the transaction (e.g., credit card, PayPal, etc.).
- Product Category: The category of the product involved in the transaction.
- Quantity: The number of products involved in the transaction.
- Customer Age: The age of the customer making the transaction.
- Customer Location: The geographical location of the customer.
- Device Used: The type of device used to make the transaction (e.g., mobile, desktop).
- IP Address: The IP address of the device used for the transaction.
- Shipping Address: The address where the product was shipped.
- Billing Address: The address associated with the payment method.
- Is Fraudulent: A binary indicator of whether the transaction is fraudulent (1 for fraudulent, 0 for legitimate).
- Account Age Days: The age of the customer's account in days at the time of the transaction.
- Transaction Hour: The hour of the day when the transaction occurred.

**Data source : https://www.kaggle.com/datasets/shriyashjagtap/fraudulent-e-commerce-transactions/data**

## Conclusion
In conclusion, the fraud detection model shows strong performance with an accuracy of 79% and a recall of 65%. While accuracy reflects the model's overall capability to classify transactions correctly, recall emphasizes its effectiveness in detecting a significant portion of actual fraudulent activities. This balance of high accuracy and decent recall underscores the model's reliability in flagging fraudulent transactions while reducing the risk of missing genuine fraud cases. However, there's room for further optimizations to potentially improve the model's performance, especially in enhancing its F1 score—a composite metric that balances precision and recall—thus strengthening its overall efficacy in combating fraudulent activities.
