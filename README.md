# A Retail Analysis
### Capstone Project – Ikram

#### Description

For this project, I looked at customer transactions between 2009-12-01 to 2010-12-09. This data is useful for creating a marketing strategy and better understanding customer behaviour. My goal was to identify the types of customers and create a model predicting the daily number of orders.


#### Results
Customers were divided into three groups based on revenue, number of orders, the average time between orders, and whether they were registered customers or not.

| Cluster            | 0         |  1        | 2           |
| :---               |   :----:  |   :----:  |        ---: |
| Name               | Regular   | One-off   | Low Spender |
| Number of customers| 2741      | 1656      | 1544        |
| Number of orders   | 6.3       | 1         | 1.1         |
| Yearly spend       | £2938     | £703      | £381        |
| Revenue (%)        | 82.12%    | 11.88%    | 6%          |
| Registered         | Yes       | No        | Yes         |

The following image is 5609 customers plotted in their clusters
![image](https://i.ibb.co/cbpLQCN/clusters-3d-plot.png)

---

This repository contains my capstone project notebooks and presentation.

The data can be found here: 
http://archive.ics.uci.edu/ml/datasets/Online+Retail+II
