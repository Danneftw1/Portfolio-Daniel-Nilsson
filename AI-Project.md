# Workflow of an AI/ML-project 

When it comes to finding data specifically for the task of house pricing projections, we can go a few ways. First, I'd check if there was any [open source data sets][data1] available for the task. This way we can possibly get a massive amount of data, however, we'll most likely have to clean it up and adapt it for our goal. If we can't find a reliable open source database, then we can use a web-scraping tool to help us collect data from websites. We could also use synthetic databases and manual data generation if we absolutely had to.

[data1]:https://medium.com/codex/how-to-collect-data-for-a-machine-learning-model-2b152752a15b (open source data, web-scraping, synthetic database & manual data generation)

Once we have our data, we'd need a place to save it and figure out what format to use. Alot of the worlds data uses format that isn't usable for machine learning. Luckily we can utilize programs like [Hopswork][data2] in order to format it to our liking. We could use a format like [CSV][data3] which is a useful text file that fits well for spreadsheets. When it comes to storage, we'd almost certainly use a cloud service, more specifically a data base. Luckily for us there is plenty out there to choose from. When we've found a database we don't need to worry about local storage.

[data2]: https://towardsdatascience.com/guide-to-file-formats-for-machine-learning-columnar-training-inferencing-and-the-feature-store-2e0c3d18d4f9 ("Guide to File Formats for Machine Learning: Columnar, Training, Inferencing, and the Feature Store")
[data3]: https://www.howtogeek.com/348960/what-is-a-csv-file-and-how-do-i-open-it/

Since we're going to use alot of data, then a table of the contents won't be enough to reasonably be able to read and understand the data. Now we can start coding in order to help us set up [data ploting][data4]. Using python for the task is a good idea since we can use **Matplotlib** within python for graphs and data ploting. Viewing data this way will be way easier and understandable if we have a large amount of information.

[data4]: https://towardsdatascience.com/data-visualization-for-machine-learning-and-data-science-a45178970be7 ("Why Visualization?")

Models that are used for AI/ML-projects could differ, however, when it comes to predictive analysis we could use the concept of [linear regression][data5]. For linear regression we would need a couple of variables in order to check if these variables are good at predicting a specific outcome. For the case of housing predictions we could as an example use linear regression in order to see if a certain feature of the house was predictive of its future pricing.

[data5]: https://www.statisticssolutions.com/free-resources/directory-of-statistical-analyses/what-is-linear-regression/ ("What is Linear Regression?")

The deployment-phase like any other part in this chain has different roads you can go down. Most AI/ML projects use [on-demand prediction service][data6] or batch prediction mode. However when deploying to a mobile phone or in edge, the embedded models could be used. Depending on what model you would use, they do some things well and other things badly. If computing cost is a concern, then you might wanna look in to batch scenarios for example.

[data6]:https://towardsdatascience.com/3-ways-to-deploy-machine-learning-models-in-production-cdba15b00e ("How to deploy a machine learning model in production?")

Machine learning is mainly based on [four big types of usage][data7]: Supervised learning, unsupervised learning, semi-supervised learning & reinforcement learning. Supervised learning is when the algorithm is given labeled training data to classify data or foresee certain outcomes correctly. When it comes to unsupervised learning, the data is instead unlabled. The algorithm instead search the data to check for connections and/or correlations. Semi-supervised just means that you can use a mix of former methods, i.e both use labled data and unlabled data. Reinforcement learning takes inspiration from behaviourism, which punishes and rewards in order to get a wanted outcome.

This document is not supposed to viewed as an exhaustive list when it comes to any of paragraphs above. It is mainly text which can help you get on the right track and look into the mentioned contents more thoroughly.

[data7]: https://www.techtarget.com/searchenterpriseai/definition/machine-learning-ML ("What are the different types of machine learning?")