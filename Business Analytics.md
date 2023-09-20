# Introduction to Business Analytics

- Analytics is a process that requires collaboration across a team of data scientists, data engineers, business analysts, and business leaders. 
- The power of analytics is in collaboration that focuses on defining and solving business problems.
- There is no debate that existing business leaders are facing new and unanticipated competitors. 
- These business leaders are looking at new strategies that can prepare them for the future.

_The goal of any analytics solution is to provide the organization with actionable insights for smarter decisions and better business outcomes.

- Analytics can help technical and business leaders to know how to anticipate and predict the future. 
- With the appropriate analytics, organizations can continually predict changes in the business so that they can have a competitive advantage.

Analytics follows a process that is like the data scientific method :-
__STEP 1:__ The analytics process always starts with a business process as the first step to identify a business problem. 
__STEP2:__ The next step is to plan the work, including analyzing the problem and building a business case. 
In summary, the analytics process uses tools and techniques to turn data into meaningful business insights.

![[Pasted image 20230602214221.png]]

# Approaches of Advanced Analytics

## Descriptive Analytics

Descriptive analytics is the analytical models that uses data mining and business intelligence to provide trending information about the historical events that can help the business analysts understand the context of the current business and evaluate the current state. 

*Descriptive Analytics provides insights into the past and answers the question of “What has happened?”

- Descriptive analytics drills down into data and uses key performance indicators (KPIs), such as frequency of events, cost of operations, and the root cause of failures. 
- All these KPIs help in measuring the business growth.
- Descriptive analytics is the most commonly adopted model by companies and organizations. It helps them to visualize the results as reports and dashboards. 
- It can discover data patterns that indicate that a problem might arise and automatically issue alarms.

## Predictive Analytics

Predictive Analytics applies advanced statistical analysis and data mining to validate assumptions and test hypothesis.

- This approach provides a solid, data-based foundation that can raise the business owners’ confidence regarding conclusions.
- It helps business owners to anticipate likely scenarios so that they can plan rather than react to what has happened.
-  A predictive analytics tool requires constantly feeding the model with new data that reflects business changes to provide the business with actionable insights based on data.
- The foundation of predictive analytics is based on statistics and probability.

*Predictive Analytics is about understanding the future and answers the question of “What could happen?”*

- Predictive analytics combines historical data from different sources to identify patterns in the data and apply statistical models and algorithms to fill in the missing data with best guesses. 
- It also helps in predicting the missing information.
- Data scientists and business analysts are constrained to make predictions that are based on analytical models that are based on historical data.
- However, there are always unknown factors that can have a significant impact on future outcomes. 
- Companies must build predictive models that can react and change when there are changes to the business environment.
- Good examples of predictive analytics include predicting which customers are likely to terminate their contract with their current business provider (churn analysis), which customers are likely to buy a new product or service from their current service provider (cross-sell analysis), or predicting the future prices of assets such as real estate or commodities.

## Prescriptive Analytics

Prescriptive analytics is mainly about providing advice regarding the possible outcomes to solve complex optimization problems involving tradeoffs between business goals and constraints.

- Prescriptive analytics goes beyond descriptive and predictive analytics by recommending one or more possible actions. 
- Prescriptive analytics predicts what will happen and why by providing recommendations regarding actions that take advantage of the predictions.

*Prescriptive analytics answer the question of “What should we do?”*

- Prescriptive analytics use a combination of techniques and tools that are applied against input from many different data sets, including historical and transactional data, real-time data feeds, and big data. 
- Prescriptive analytics are relatively complex to administer, and most companies are not yet using them daily.
- Large companies use prescriptive analytics to make sure that they are delivering the correct products at the correct time and optimizing the customer experience.
- Good examples of prescriptive analytics include optimizing the maintenance of production line equipment to reduce the costs of downtime and planning effective marketing campaigns by distributing resources across multiple channels to target as many customers as possible to maximize the revenue.

![[Pasted image 20230602221956.png]]

# Deploying the appropriate Analytics Approach

Different types of analytics to provide different types of insights.
- It is important for business analysts and data scientists to understand what each analytics type delivers and to match analytics functions to the organization’s operational capabilities.
- Analytics maturity levels are increasing for businesses, progressing from descriptive to predictive and prescriptive analytics.
-  Companies have been successful at using analytics to understand both where they have been and how they can learn from the past to anticipate the future.
- They can describe how various actions and events will impact outcomes. 
- Although the knowledge from this analysis can be used to make predictions, typically these predictions are made through a lens of preconceived expectations.

__To apply analytics techniques__ : Data scientists and Business analysts must understand the business problem and goals. Must determine what data sources and types are best suited to solve the business problem.

- Most companies have important data that is stored across different business units, some of which might be found in social media sources and other unstructured data sources, such as documents that are related to new research findings. 
- Data is also found in semi-structured sources such as sensor and IoT-based systems.
- Data scientists and business analysts must understand the data and search for opportunities and threats in the data. 
- They must make sure that the data that is available is ready to perform analytics by using the most recent data from the correct sources. 
- They must use all the sources of data because most of the time the data that is required to assess the future exists but was never used to make sense of the business.
- An effective strategy must be in place to select a meaningful problem that has an impact on the business. The problem must be tackled on a small scale to deliver rapid results.
- Organizations should match their infrastructure, technologies, and processes to the level of analytics maturity that they can perform and the goals that they want to accomplish. 
- In parallel, the organization should put in place advanced technologies and processes to support more complex analytics later.

There are different architectural examples of advanced analytics, according to the type of data.

**Traditional Analytics** : This architecture is rigid, so getting responses quickly can be difficult. The data should be guaranteed to have quality and be secure. There should be some sort of control and governance in place to make sure that the data is seen only by the people that are authorized to access the data.

In this architecture, data is pulled from transactional systems, such as a supply chain, points of sale, or finance systems. The data is extracted, transformed, and loaded (by using ETL tools) into a data warehouse, where the reporting data is stored. Then, reporting and analytics tools point to the reporting data to visualize the data through dashboards and graphs.

![[Pasted image 20230605132437.png]]



**Big Data Analytics** : In this example, the data is pulled from Twitter, Facebook, messaging applications, and websites, and then the data is pulled into a Hadoop cluster. Hadoop can ingest large volumes of unstructured data. A subset of the data (after cleaning) which now might be structured, is pulled into a data warehouse that is like the one that is described in Example 1. The reporting data that is stored in the data warehouse is accessed by the reporting tools to visualize the data through dashboards and graphs.

![[Pasted image 20230605132543.png]]