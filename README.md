# Minimizing-Churn-of-subscription-product-through-usage-analysis
Build a model predicting which customers are likely to cancel subscription by analyzing the use of the application and their habbits.

This project illustrates how machine learning can optimize digital app's revenues. It can be looked at in parallel of [Directing customers to subscription and identify most important drivers](https://github.com/LaurentVeyssier/App-Directing-customers-to-subscription), which I covered separately.

# Problem statement

The main source of revenues for many digital applications comes from subscription. Subscriptions provide a continuous flow of revenues making it possible to finance growth and new developments. Subscription-based companies want to reduce customer churn as much as possible and retain customers life-time value. Customer acquisition is far more expensive than keeping existing customers, being able to keep the customer is extremely valuable.

To retain customers, companies must identify behavorial patterns giving early warnings of customer disengagement (such as customers starting to lose interest in the service). Being able to identify early signs and catalyst to disengagement represents a tremendous opportunity to re-engage these customers with the product or service.

This business case proposes to build a model predicting which customers are likely to churn so that the company can focus on retaining them. For example, the company can develop new features that customers would be interested in or provide information on value-added services the user did not realize or has forgotten about.

This situation can apply to a wide variety of business cases and subscription services. It assumes the company has data available from the user on the use of the service: What functionalities he uses, how the customer interacts with the various services, etc...

# Business case
In this project, the business case involves a digital app offering financial / banking services such as loans, credit cards, purchases and deposits to name a few.
We assume that, by subscribing, customers have provided data on their financial situation and how they use the service. Demographic information is also likely to be available as it is acquired during the sign-up process.

# Behavioral data (usage log)
Information available are not time-bound. This includes a log of activity. It combines usage data (number of deposits made, number of purchases made, credit card offer accepted,...) and customer specific information (income and revenues, referrals, mobile platform...).

