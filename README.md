# Objective

To identify potential leads from multi-dimensional data sets in a user-friendly and intuitive way.

# Background

During drug development, compounds are screened against assays to look at how compounds react. Leads are commonly defined as compounds that have selective activity against assays. These compounds can be identified by through hierarchical clustering where compounds with similar activities are grouped into a cluster. 

![Problem](./images/problem.png)

# Discovering Data

![Data](./images/data.png)

Sample data set can be found in ./data/data.csv. It is obtained from HMS LINCS database, www.lincs.hms.harvard.edu/db

# Developing Solution

![Solution](./images/solution.png)

![Solution2](./images/solution2.png)

# Deploying Solution

KNIME is an open-source data analytics platform that allows users to drag and drop nodes that perform certain functions, https://www.knime.com/. The solution is deployed in KNIME for 2 reasons:

1. Low-cost, scalable, flexible, and quick deployment
	- Changes can be made by modifying a node in the workflow and deploying it on the server instantly
	- This is a priority for the business as the company does not have a dedicated data science and engineering team to manage deployment

2. User-friendly and intuitive interface
	- Users can upload any data and customize analysis through a web interface and visualization is output in an interactive manner that is easy to get insights from

*Workflow can be downloaded from ./solution/viz_hts.kwf but KNIME needs to be installed in order to run the workflow*

![Deploy](./images/deploy.png)

# Improving Solution

![Improve](./images/improvement.png)

# Future Work

![Future](./images/future.png)

![Future2](./images/future2.png)

![Future3](./images/future3.png)

# Conclusion

![Conclusion](./images/conclusion.png)


