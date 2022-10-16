# Project Description

**As an analyst at a big online store and working with the marketing department, we’ve compiled a list of hypotheses that may help boost revenue. We need to prioritize these hypotheses, launch an A/B test, and analyze the results.** 

### Description of the data:
 Data used in the first part of the project and has the following fields:
 
* Hypotheses — brief descriptions of the hypotheses
* Reach — user reach, on a scale of one to ten
* Impact — impact on users, on a scale of one to ten 
* Confidence — confidence in the hypothesis, on a scale of one to ten 
* Effort — the resources required to test a hypothesis, on a scale of one to ten. The higher the Effort value, the more resource-intensive the test.

Data used in the second part of the project has two tables: Orders and Visits

Orders table has the following fields:
transactionId — order identifier 
* visitorId — identifier of the user who placed the order
* date — of the order
* revenue — from the order
* group — the A/B test group that the user belongs to

Visits table has the following fields: 
* date — date
* group — A/B test group
* visits — the number of visits on the date specified in the A/B test group specified

#### Python libraries used: Pandas, Matplotlib, Seaborn, Scipy


